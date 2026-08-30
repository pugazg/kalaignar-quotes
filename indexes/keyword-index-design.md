# Keyword index design

This document defines the construction protocol for the repository's **derived keyword index**. It is a discovery aid only. Canonical transcription authority remains in `collections/<collection-id>/quotes/`.

## Status

- Design version: **0.1**
- Scope: `chinna-chinna-malargal`
- Canonical quote range available: `KQ-CCM-0001`–`KQ-CCM-0497`
- Keyword assignment: **complete — indexed through `KQ-CCM-0497` (497 / 497)**
- Construction cadence: **25 quotes per sequential batch**, with a shorter final batch when needed
- Vocabulary state: **frozen / published — [`keyword-vocabulary.md`](keyword-vocabulary.md), version 1.0 with 182 keys**
- Full consistency pass: **complete — 497 / 497 rows reviewed; 21 quote-row corrections across 12 batch files; 1 added key and 1 vocabulary migration with no net key-count change**
- Consistency record: [`keyword-consistency-review.md`](keyword-consistency-review.md)
- Consolidated publication: **complete — [`keyword.md`](keyword.md), 497 / 497 quote assignments**
- Keyword-index lifecycle: **complete under controlled vocabulary version 1.0**
- Source verification states remain authoritative and unchanged: **496 `verified_from_scan`**, **1 `needs_review` (`KQ-CCM-0391`)**

## Purpose

The keyword index provides **finer-grained discovery than the theme index** without becoming a second transcription, a modernized paraphrase, or an interpretation layer.

A theme answers a broad question such as "what general subject does this quote concern?" A keyword identifies a narrower, reusable concept that is materially present in the quote itself, for example a named social issue, institution, practice, relationship, value, political concept, language issue, literary form, natural image, or other directly supported subject.

The keyword index complements, and never overrides:

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

The controlled vocabulary is maintained in [`keyword-vocabulary.md`](keyword-vocabulary.md).

Each vocabulary entry contains:

- a stable machine-readable key;
- a Tamil display label;
- a short scope definition;
- optional boundary guidance when confusion with another keyword is likely.

Stable keys are concise lowercase ASCII kebab-case. Tamil display labels are derived metadata and do not rewrite canonical source text.

### Vocabulary lifecycle

During sequential construction the vocabulary remained a **0.x working vocabulary**. New keys could be added when later quotes introduced genuinely new concepts, and migrations had to be recorded whenever a key was renamed, split or merged.

Sequential construction and the full consistency pass are complete. The consistency-reviewed working vocabulary 0.9 was frozen as **version 1.0** during consolidated publication, with **182 stable keys**. The freeze itself introduced no additional key change.

Any future controlled-vocabulary change must:

1. increment the vocabulary version beyond 1.0;
2. document the change and its evidence boundary;
3. record and apply any migration to affected assignments;
4. republish affected derived index data without modifying canonical quote text.

## Batch construction format

Construction used sequential batch files:

`indexes/keyword-NNNN-NNNN.md`

Each batch records:

- design/vocabulary version used;
- quote range;
- number of quotes indexed;
- verification states represented;
- statement that canonical quote files were not changed.

Each batch uses one row per quote with this column structure:

```text
Quote ID | Keyword key(s) | PDF | Printed | Verification status | Assignment note
```

Rules:

- list one to five stable keyword keys, separated by semicolons;
- preserve PDF, printed-page and verification values from the canonical quote file;
- normally leave `Assignment note` blank;
- use the note only for a difficult boundary decision, a vocabulary migration, a consistency correction, or a `needs_review` limitation that affects indexing.

## Construction cadence

Sequential construction used the same 25-quote cadence as prior derived-index work:

1. read all canonical quote files in the batch completely;
2. assign one to five text-supported keyword keys to each quote;
3. add genuinely new concepts to the working vocabulary when needed;
4. validate the batch;
5. update `indexes/README.md` with coverage;
6. commit only derived files without modifying canonical quote files.

The final batch contained 22 quotes. Sequential construction is complete for all **497 / 497** quotes.

## Batch validation

Each batch was validated for:

- every quote ID appearing exactly once;
- one to five keyword keys per row;
- every key existing in the current vocabulary;
- no duplicate keyword within one row;
- PDF and printed-page values matching the canonical quote file;
- verification status matching the canonical quote file;
- no keyword depending on outside context or OCR inference;
- no canonical quote file changes.

## `KQ-CCM-0391`

`KQ-CCM-0391` remains `needs_review` because of the documented physical source blemish.

Its keyword assignment:

- uses only readable canonical content;
- does not infer a keyword from the obscured terminal glyph;
- keeps the verification status `needs_review`;
- remains `arrogance`; `speech` under the frozen vocabulary.

Keyword indexing and consolidated publication do not resolve the source uncertainty.

## Full consistency pass

The required full consistency pass is complete and documented in [`keyword-consistency-review.md`](keyword-consistency-review.md).

The pass checked:

- exactly **497 unique quote IDs**, with no gaps or duplicates;
- all keys valid under the controlled vocabulary;
- one to five keywords per quote;
- consistent reuse of equivalent concepts;
- accidental near-duplicate vocabulary keys;
- over-broad keywords that merely repeat theme categories;
- over-specific one-off keywords that are not useful for discovery;
- unsupported inference or person/organization keywords based only on incidental mentions;
- preserved source verification states, including `KQ-CCM-0391`;
- unchanged canonical quote files.

It applied **21 quote-row corrections across 12 batch files**, added the reusable `patience` key, and migrated the one-off `hindikkara-state` key into `hindi-state`. The reviewed vocabulary remained at **182 stable keys** because the added and retired keys offset one another.

## Consolidated publication

Publication is complete.

- [`keyword-vocabulary.md`](keyword-vocabulary.md) is frozen as controlled vocabulary version **1.0** with **182 stable keys**.
- [`keyword.md`](keyword.md) publishes all **497 / 497** consistency-reviewed quote assignments.
- All twenty sequential batch files and [`keyword-consistency-review.md`](keyword-consistency-review.md) remain as construction and audit history.
- `KQ-CCM-0391` remains `needs_review` and its obscured terminal glyph remains unresolved.
- Canonical quote files were not modified by construction, consistency review, vocabulary freeze, or consolidated publication.

Future controlled-vocabulary changes require a version increment and an explicit migration record where existing assignments are affected.
