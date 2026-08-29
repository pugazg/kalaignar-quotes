# Keyword index design

This document defines the construction protocol for the repository's **derived keyword index**. It is a discovery aid only. Canonical transcription authority remains in `collections/<collection-id>/quotes/`.

## Status

- Design version: **0.1**
- Scope: `chinna-chinna-malargal`
- Canonical quote range available: `KQ-CCM-0001`–`KQ-CCM-0497`
- Keyword assignment: **in progress — indexed through `KQ-CCM-0275` (275 / 497)**
- Construction cadence: **25 quotes per sequential batch**, with a shorter final batch when needed
- Vocabulary state: **working — [`keyword-vocabulary.md`](keyword-vocabulary.md), version 0.5 with 167 keys**
- Next keyword-index activity: **construct `KQ-CCM-0276`–`KQ-CCM-0300`, reusing or extending the working vocabulary only when the canonical text requires it**
- Source verification states remain authoritative and unchanged: **496 `verified_from_scan`**, **1 `needs_review` (`KQ-CCM-0391`)**

## Purpose

The keyword index should provide **finer-grained discovery than the theme index** without becoming a second transcription, a modernized paraphrase, or an interpretation layer.

A theme answers a broad question such as "what general subject does this quote concern?" A keyword should identify a narrower, reusable concept that is materially present in the quote itself, for example a named social issue, institution, practice, relationship, value, political concept, language issue, literary form, natural image, or other directly supported subject.

The keyword index must complement, not duplicate or override:

- the canonical quote files;
- the opening-word index;
- the theme taxonomy and consolidated theme index.

## Evidence rule

Every keyword must be supported by the **canonical quote text itself**.

Do not use:

- outside biography or historical context;
- inferred authorial intent;
- OCR-only readings;
- modern political interpretation;
- facts known from another source;
- a theme assignment as a substitute for reading the quote.

A keyword may represent an explicit concept expressed by the quote even when the exact surface word is inflected or phrased differently, but the concept must be directly recoverable from the canonical wording without outside knowledge.

If a candidate keyword would require explanation beginning with "this probably refers to...", do not assign it.

## Keyword model

1. Every quote receives **one to five keyword keys**.
2. Keywords are **unranked**. There is no primary/secondary distinction.
3. Keywords must be narrower than the 16 broad theme categories and useful for cross-quote discovery.
4. Do not index function words, generic connective language, or incidental wording merely because it appears in the quote.
5. Do not create a keyword for every noun in a quote. Index materially significant subjects or concepts only.
6. A person, party, institution, religion, language, place, literary form or named object may be a keyword only when it is material to the proposition, not merely mentioned in passing.
7. Metaphorical objects or natural images may be indexed when the image is materially used in the quote; omit decorative or incidental imagery.
8. Reuse an existing stable keyword whenever the same concept is already represented. Do not create near-duplicate keys solely because of spelling, inflection or grammatical form.
9. Do not merge genuinely different concepts merely to reduce vocabulary size.
10. Keyword assignment must never modify canonical wording, punctuation, spelling, source provenance, quote ID or verification status.

## Controlled vocabulary

Keyword construction maintains a separate `keyword-vocabulary.md`.

Each vocabulary entry must contain:

- a stable machine-readable key;
- a Tamil display label;
- a short scope definition;
- optional boundary guidance when confusion with another keyword is likely.

Stable keys should be concise lowercase ASCII kebab-case. Tamil display labels may preserve the natural concept label used for discovery; they are derived metadata and do not rewrite the canonical source text.

### Vocabulary lifecycle

- During sequential construction, the vocabulary remains a **0.x working vocabulary**.
- New keys may be added when a later quote introduces a genuinely new concept.
- Existing keys may be clarified when necessary, but changes must not silently change the meaning of previously assigned rows.
- If a key must be renamed, split or merged during construction, record the migration in the vocabulary file and update all affected batch rows in the same commit.
- After all 497 quotes are assigned and a full consistency pass is complete, freeze the controlled vocabulary as **version 1.0** before publishing the consolidated keyword index.

## Batch construction format

Use sequential batch files:

`indexes/keyword-NNNN-NNNN.md`

Each batch begins with:

- design/vocabulary version used;
- quote range;
- number of quotes indexed;
- verification states represented;
- statement that canonical quote files were not changed.

Use one row per quote with this exact column structure:

```text
Quote ID | Keyword key(s) | PDF | Printed | Verification status | Assignment note
```

Rules:

- list one to five stable keyword keys, separated by semicolons;
- preserve PDF, printed-page and verification values from the canonical quote file;
- normally leave `Assignment note` blank;
- use the note only for a difficult boundary decision, a vocabulary migration, or a `needs_review` limitation that affects indexing.

## Construction cadence

Proceed in the same sequential 25-quote cadence used successfully for prior derived-index work:

1. read all 25 canonical quote files completely;
2. assign one to five text-supported keyword keys to each quote;
3. add any genuinely new concepts to `keyword-vocabulary.md`;
4. validate the batch;
5. update `indexes/README.md` with coverage and the next batch;
6. commit the derived files without modifying canonical quote files.

The final batch may contain fewer than 25 quotes.

## Batch validation

Before each batch commit, confirm:

- every quote ID in the batch appears exactly once;
- every row has one to five keyword keys;
- every key exists in the current vocabulary;
- no duplicate keyword appears within one quote row;
- PDF and printed-page values match the canonical quote file;
- verification status matches the canonical quote file;
- no keyword depends on outside context or OCR inference;
- no canonical quote file was changed.

## `KQ-CCM-0391`

`KQ-CCM-0391` remains `needs_review` because of the documented physical source blemish.

When its keyword batch is reached:

- assign keywords only from the readable canonical content;
- do not infer a keyword from the obscured terminal glyph;
- keep the verification status `needs_review`;
- add a short assignment note only if the unresolved glyph prevents an otherwise plausible keyword from being assigned.

Keyword indexing must not be treated as resolution of the source uncertainty.

## Full consistency pass

After all 497 quote rows are constructed, perform a repository-wide consistency pass before consolidation. Check:

- exactly 497 unique quote IDs, with no gaps or duplicates;
- all keys valid under the working vocabulary;
- one to five keywords per quote;
- consistent reuse of equivalent concepts;
- accidental near-duplicate vocabulary keys;
- over-broad keywords that merely repeat theme categories;
- over-specific one-off keywords that are not useful for discovery;
- unsupported inference or person/organization keywords based only on incidental mentions;
- preserved source verification states, including `KQ-CCM-0391`;
- unchanged canonical quote files.

Record any corrections in a dedicated keyword consistency-review file.

## Consolidated publication

Only after the full consistency pass:

1. freeze `keyword-vocabulary.md` as version **1.0**;
2. publish `indexes/keyword.md` as the consolidated keyword discovery index;
3. retain sequential batch files as construction/audit shards;
4. document final coverage and consistency status in `indexes/README.md`.

The consolidated index should remain quote-ID addressable and link every entry back to its canonical quote file.
