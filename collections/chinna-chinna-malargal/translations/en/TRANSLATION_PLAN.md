# English Translation Plan — கலைஞரின் சின்னச் சின்ன மலர்கள்

## Objective

Create a clear, faithful English translation of all canonical quotations in `chinna-chinna-malargal` while preserving Kalaignar's argument, metaphor, satire, wordplay, rhetorical force and political/social vocabulary without turning the material into a modern adaptation.

The English layer is **derived metadata**. Canonical transcription authority remains in `../../quotes/`.

## Status

- Collection: `chinna-chinna-malargal`
- Canonical quote range: `KQ-CCM-0001`–`KQ-CCM-0497`
- Total canonical quotes: **497**
- Source verification states: **496 `verified_from_scan`**, **1 `needs_review` (`KQ-CCM-0391`)**
- Translation cadence: **25 sequential quote IDs per batch**, with the shorter final batch `0476`–`0497`
- Pilot batch: `KQ-CCM-0001`–`KQ-CCM-0025`
- Pilot first-pass translation: **complete**
- Pilot fidelity/style review: **complete** — see [`PILOT_REVIEW.md`](PILOT_REVIEW.md)
- Glossary/style conventions: [`GLOSSARY.md`](GLOSSARY.md), version **1.2** — pilot conventions locked; Batch-2 and Batch-3 terminology added
- Batch 2: `KQ-CCM-0026`–`KQ-CCM-0050` — **first pass complete**
- Batch 3: `KQ-CCM-0051`–`KQ-CCM-0075` — **first pass complete**
- Current first-pass coverage: **75 / 497**
- Next activity: **translate `KQ-CCM-0076`–`KQ-CCM-0100`**

## Source-authority hierarchy

Translation must follow this order:

1. canonical audited Tamil quote files in `../../quotes/`;
2. collection audit and page-map records when a source-critical note affects interpretation;
3. repository metadata and derived indexes only as navigation/context aids.

Do not translate from OCR, memory, internet quotations, modernized spellings or outside retellings.

If a canonical quote remains `needs_review`, translate only what the canonical file establishes. Do not reconstruct an obscured or uncertain glyph from context.

## File structure

```text
translations/en/
  README.md
  TRANSLATION_PLAN.md
  PROGRESS.md
  GLOSSARY.md
  PILOT_REVIEW.md
  batches/
    translation-0001-0025.md
    translation-0026-0050.md
    translation-0051-0075.md
    translation-0076-0100.md
    ...
    translation-0476-0497.md
  TRANSLATION_REVIEW.md       # create for full consistency/fidelity review
  quotes.md                   # publish only after all batches and review are complete
```

Batch files are construction and audit shards. The final consolidated `quotes.md` will provide quote-ID-addressable English discovery after the complete translation consistency pass.

## Core translation rules

1. **No summarising.** Translate every substantive proposition, contrast, image, list, rhetorical question and repeated phrase.
2. **Natural but source-bound English.** Reorder syntax only when needed for intelligibility; do not add interpretation absent from the Tamil.
3. **Preserve force.** Do not soften accusation, satire, ridicule, irony, anger or political intensity.
4. **Do not intensify.** Do not make a claim broader, harsher, more historically specific or more doctrinal than the canonical Tamil.
5. **Preserve metaphor.** Keep source images even when they sound unusual in English unless literal rendering would become unintelligible.
6. **Preserve wordplay visibly.** Where English cannot reproduce a Tamil pun, retain the key Tamil term or explain the wordplay in a short translation note rather than silently replacing it.
7. **Preserve named-source vocabulary.** Do not silently modernize caste, religious, linguistic, political or literary terminology.
8. **Minimal notes.** Translation notes are allowed only when wordplay, a source-specific term or a source uncertainty materially affects comprehension.
9. **No canonical edits.** Translation work must never change Tamil wording, punctuation, provenance, quote IDs or verification states.
10. **Traceability.** Every English entry must link directly to its canonical Tamil quote file.

## Translation-batch format

Each batch file must begin with:

- quote range;
- number translated;
- source verification states represented;
- translation status;
- statement that canonical quote files were not changed.

Each quote entry must include:

- quote ID;
- link to canonical Tamil;
- canonical verification status;
- English translation;
- translation note only when necessary.

## Pilot style lock

`KQ-CCM-0001`–`KQ-CCM-0025` was the mandatory pilot. Its fidelity/style review is complete and recorded in [`PILOT_REVIEW.md`](PILOT_REVIEW.md).

The review covered:

- treatment of `இலட்சியம்`, `கொள்கை`, `அதிகாரம்`, `நீதி`, `அநீதி`, `பொதுவாழ்வு`, `பொதுத் தொண்டு`, `இயக்கம்` and recurring political/social vocabulary;
- culturally specific terms such as `மோட்சம்`, `அஷ்டமா சித்து`, `புனுகு`, `ஜவ்வாது` and `எருக்கம்`;
- Tamil wordplay that cannot be reproduced directly in English (`KQ-CCM-0004`, `0005`, `0011`, `0014`, `0025`);
- rhetorical punctuation and exclamation density;
- idiomatic force such as `சூடு சொரணை`;
- consistency of `Anna` / `Arignar Anna` and other named references.

The reviewed decisions were locked in [`GLOSSARY.md`](GLOSSARY.md) version **1.0**. Version **1.1** added terminology required by Batch 2, including source-facing handling of `திராவிட இயக்கம்`, `சுயமரியாதை மாநாடு`, `கழக ஆட்சி`, `பேரறிஞர் அண்ணா` and `அறிவியக்கம்`. Version **1.2** adds terminology required by Batch 3, including `சாதி மல்லிகை`, `பக்த சிகாமணி`, `அன்னம்`, `கெண்டை மீன்` and `இந்து ராஜ்யம் / இந்தி ராஜ்யம்`. Neither extension revises the locked pilot conventions.

Later batches may add new terminology, but an established convention should change only where later canonical evidence requires an explicit revision recorded in the translation history.

## `KQ-CCM-0391` rule

`KQ-CCM-0391` remains `needs_review` because the controlling scan has a physical blemish obscuring its terminal glyph after the readable text recorded by the repository.

When the translation reaches that quote:

- translate only the readable canonical content;
- mark the English entry as source-limited / `needs_review`;
- do not infer or complete the obscured terminal glyph;
- do not treat translation as resolution of the source uncertainty.

## Batch validation

Before each translation-batch commit, confirm:

- every quote ID in the batch appears exactly once;
- every English entry links to the correct canonical quote file;
- source verification status matches the canonical file;
- every substantive Tamil proposition is represented;
- no unsupported historical/contextual detail has been inserted;
- named terms and glossary decisions are used consistently;
- wordplay limitations are noted where necessary;
- canonical quote files remain unchanged.

## Final review and publication

After all 497 quotes have first-pass English translations:

1. perform a full quote-by-quote fidelity and consistency review;
2. reconcile recurring terminology and wordplay decisions across all batches;
3. preserve `KQ-CCM-0391` as source-limited unless the controlling source is genuinely resolved;
4. publish the consolidated `translations/en/quotes.md`;
5. retain all sequential batch files and review records as audit history.