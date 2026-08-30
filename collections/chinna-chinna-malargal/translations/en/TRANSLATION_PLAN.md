# English Translation Plan — கலைஞரின் சின்னச் சின்ன மலர்கள்

## Objective

Create a clear, faithful English translation of all canonical quotations in `chinna-chinna-malargal` while preserving Kalaignar's argument, metaphor, satire, wordplay, rhetorical force and political/social vocabulary without turning the material into a modern adaptation.

The English layer is **derived metadata**. Canonical transcription authority remains in `../../quotes/`.

## Status

- Collection: `chinna-chinna-malargal`
- Canonical quote range: `KQ-CCM-0001`–`KQ-CCM-0497`
- Total canonical quotes: **497**
- Source verification states: **496 `verified_from_scan`**, **1 `needs_review` (`KQ-CCM-0391`)**
- Translation cadence used: **25 sequential quote IDs per batch**, with final batch `0476`–`0497`
- Pilot batch: `KQ-CCM-0001`–`KQ-CCM-0025`
- Pilot first-pass translation: **complete**
- Pilot fidelity/style review: **complete** — see [`PILOT_REVIEW.md`](PILOT_REVIEW.md)
- Glossary/style conventions: [`GLOSSARY.md`](GLOSSARY.md), version **1.3** — pilot conventions locked; Batch-2 through Batch-4 terminology added; Batches 5–20 required no glossary revision
- Batches 2–20: **all first-pass complete**
- Current first-pass coverage: **497 / 497 — COMPLETE**
- `KQ-CCM-0391`: **translated source-limited; canonical `needs_review` status remains unresolved**
- Next activity: **full quote-by-quote English fidelity/consistency review before consolidated publication**

## Source-authority hierarchy

Translation and review must follow this order:

1. canonical audited Tamil quote files in `../../quotes/`;
2. collection audit and page-map records when a source-critical note affects interpretation;
3. repository metadata and derived indexes only as navigation/context aids.

Do not translate or review from OCR, memory, internet quotations, modernized spellings or outside retellings.

If a canonical quote remains `needs_review`, translate and review only what the canonical file establishes. Do not reconstruct an obscured or uncertain glyph from context.

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
    translation-0101-0125.md
    translation-0126-0150.md
    translation-0151-0175.md
    translation-0176-0200.md
    translation-0201-0225.md
    translation-0226-0250.md
    translation-0251-0275.md
    translation-0276-0300.md
    translation-0301-0325.md
    translation-0326-0350.md
    translation-0351-0375.md
    translation-0376-0400.md
    translation-0401-0425.md
    translation-0426-0450.md
    translation-0451-0475.md
    translation-0476-0497.md
  TRANSLATION_REVIEW.md       # create during the full consistency/fidelity review
  quotes.md                   # publish only after review is complete
```

Batch files are construction and audit shards. The final consolidated `quotes.md` will provide quote-ID-addressable English discovery only after the complete translation consistency pass.

## Core translation rules

1. **No summarising.** Translate every substantive proposition, contrast, image, list, rhetorical question and repeated phrase.
2. **Natural but source-bound English.** Reorder syntax only when needed for intelligibility; do not add interpretation absent from the Tamil.
3. **Preserve force.** Do not soften accusation, satire, ridicule, irony, anger or political intensity.
4. **Do not intensify.** Do not make a claim broader, harsher, more historically specific or more doctrinal than the canonical Tamil.
5. **Preserve metaphor.** Keep source images even when they sound unusual in English unless literal rendering would become unintelligible.
6. **Preserve wordplay visibly.** Where English cannot reproduce a Tamil pun, retain the key Tamil term or explain the wordplay in a short translation note rather than silently replacing it.
7. **Preserve named-source vocabulary.** Do not silently modernize caste, religious, linguistic, political or literary terminology.
8. **Minimal notes.** Translation notes are allowed only when wordplay, a source-specific term or a source uncertainty materially affects comprehension.
9. **No canonical edits.** Translation work and review must never change Tamil wording, punctuation, provenance, quote IDs or verification states.
10. **Traceability.** Every English entry must link directly to its canonical Tamil quote file.

## Translation-batch format

Each batch file begins with:

- quote range;
- number translated;
- source verification states represented;
- translation status;
- statement that canonical quote files were not changed.

Each quote entry includes:

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

The reviewed decisions were locked in [`GLOSSARY.md`](GLOSSARY.md) version **1.0**. Version **1.1** added terminology required by Batch 2, version **1.2** added Batch-3 terminology, and version **1.3** added Batch-4 source-facing handling for `வாமனாவதாரம்`, mirror-context `ரசம் பூசுதல்`, `கடையேழு வள்ளல்கள்`, `பத்தாம் பசலி`, domination/fanaticism vocabulary, `வகுப்புவாதம்`, `கள்ளிச் செடி` and `பாதரசம்`. Batches 5–20 required no glossary-version change; their one-off source-specific expressions, scan-confirmed irregular forms and wordplay are documented in the batch files. None of these later batches revises the locked pilot conventions.

An established convention should change during full review only where canonical evidence requires an explicit revision recorded in the review history.

## `KQ-CCM-0391` rule

`KQ-CCM-0391` remains `needs_review` because the controlling scan has a physical blemish obscuring its terminal glyph after the readable text recorded by the repository.

Its first-pass English translation is explicitly source-limited. During the full review:

- review only the readable canonical content;
- retain the English entry as source-limited / `needs_review`;
- do not infer or complete the obscured terminal glyph;
- do not treat translation or review as resolution of the source uncertainty.

## Source-critical final-window rules

The final construction batches include scan-confirmed forms that must not be normalized during review without direct source evidence:

- `KQ-CCM-0466`: source-visible `வாணனைகள்`, retained as **vaananaigal**;
- `KQ-CCM-0478`: source-visible `புனிதமோடதை`, retained as **punithamodathai** in the first pass;
- `KQ-CCM-0491`: source-visible `முக்குடைப்பட்டாலும்`, retained as **mukkudaipattaalum**;
- `KQ-CCM-0496`: no punctuation between `புரட்சிக் கவிஞர்` and `அதனால்தான்`, and no terminal punctuation; the first-pass English deliberately preserves that source punctuation state.

These are review checkpoints, not invitations to reconstruct the source from outside editions.

## Full fidelity/consistency review — required next stage

First-pass translation is now complete. Before consolidated publication, perform a full `KQ-CCM-0001`–`KQ-CCM-0497` review and record the work in `TRANSLATION_REVIEW.md`.

For every quote:

1. compare English directly against the canonical Tamil file;
2. verify every substantive proposition, contrast, list, metaphor and rhetorical question;
3. reconcile recurring terms against `GLOSSARY.md` and earlier reviewed conventions;
4. check named people, movements, party references, transliterations and culturally specific terms for consistency;
5. check source-bound wordplay and scan-confirmed irregular forms against their local notes;
6. make English-only corrections where required, recording changed quote IDs and rationales;
7. make **no** canonical Tamil edits as part of translation review;
8. keep `KQ-CCM-0391` source-limited unless the controlling source itself is genuinely resolved.

## Publication gate

After the full review:

1. confirm review coverage **497 / 497**;
2. confirm recurring terminology and wordplay decisions are reconciled;
3. confirm `KQ-CCM-0391` is still source-limited unless source evidence changed;
4. finalize `TRANSLATION_REVIEW.md`;
5. publish consolidated `translations/en/quotes.md` from the reviewed batch content;
6. retain all twenty sequential batch files and review records as audit history.
