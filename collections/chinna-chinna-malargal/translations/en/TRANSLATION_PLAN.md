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
- First-pass coverage: **497 / 497 — COMPLETE**
- Full fidelity/consistency review: [`TRANSLATION_REVIEW.md`](TRANSLATION_REVIEW.md) — **497 / 497 COMPLETE**
- Consolidated reviewed publication: [`quotes.md`](quotes.md) — **497 / 497 PUBLISHED**
- `KQ-CCM-0391`: **translated and published source-limited; canonical `needs_review` status remains unresolved**
- Translation/publication plan: **COMPLETE**

## Source-authority hierarchy

Translation, review and any future revision must follow this order:

1. canonical audited Tamil quote files in `../../quotes/`;
2. collection audit and page-map records when a source-critical note affects interpretation;
3. repository metadata and derived indexes only as navigation/context aids.

Do not translate, review or revise from OCR, memory, internet quotations, modernized spellings or outside retellings.

If a canonical quote remains `needs_review`, translate and review only what the canonical file establishes. Do not reconstruct an obscured or uncertain glyph from context.

## File structure

```text
translations/en/
  README.md
  TRANSLATION_PLAN.md
  PROGRESS.md
  GLOSSARY.md
  PILOT_REVIEW.md
  TRANSLATION_REVIEW.md
  quotes.md
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
```

Batch files are retained as construction and audit shards. [`quotes.md`](quotes.md) is the reviewed quote-ID-addressable English publication. [`TRANSLATION_REVIEW.md`](TRANSLATION_REVIEW.md) records the eleven English-only corrections applied at publication.

## Core translation rules

1. **No summarising.** Translate every substantive proposition, contrast, image, list, rhetorical question and repeated phrase.
2. **Natural but source-bound English.** Reorder syntax only when needed for intelligibility; do not add interpretation absent from the Tamil.
3. **Preserve force.** Do not soften accusation, satire, ridicule, irony, anger or political intensity.
4. **Do not intensify.** Do not make a claim broader, harsher, more historically specific or more doctrinal than the canonical Tamil.
5. **Preserve metaphor.** Keep source images even when they sound unusual in English unless literal rendering would become unintelligible.
6. **Preserve wordplay visibly.** Where English cannot reproduce a Tamil pun, retain the key Tamil term or explain the wordplay in a short construction/review note rather than silently replacing it.
7. **Preserve named-source vocabulary.** Do not silently modernize caste, religious, linguistic, political or literary terminology.
8. **Minimal notes.** Notes are allowed only when wordplay, a source-specific term or a source uncertainty materially affects comprehension.
9. **No canonical edits.** Translation work and review must never change Tamil wording, punctuation, provenance, quote IDs or verification states.
10. **Traceability.** Every published English entry links directly to its canonical Tamil quote file.

## Pilot style lock

`KQ-CCM-0001`–`KQ-CCM-0025` was the mandatory pilot. Its fidelity/style review is complete and recorded in [`PILOT_REVIEW.md`](PILOT_REVIEW.md).

The review covered:

- treatment of `இலட்சியம்`, `கொள்கை`, `அதிகாரம்`, `நீதி`, `அநீதி`, `பொதுவாழ்வு`, `பொதுத் தொண்டு`, `இயக்கம்` and recurring political/social vocabulary;
- culturally specific terms such as `மோட்சம்`, `அஷ்டமா சித்து`, `புனுகு`, `ஜவ்வாது` and `எருக்கம்`;
- Tamil wordplay that cannot be reproduced directly in English (`KQ-CCM-0004`, `0005`, `0011`, `0014`, `0025`);
- rhetorical punctuation and exclamation density;
- idiomatic force such as `சூடு சொரணை`;
- consistency of `Anna` / `Arignar Anna` and other named references.

The reviewed decisions were locked in [`GLOSSARY.md`](GLOSSARY.md) version **1.0**. Version **1.1** added terminology required by Batch 2, version **1.2** added Batch-3 terminology, and version **1.3** added Batch-4 source-facing handling for `வாமனாவதாரம்`, mirror-context `ரசம் பூசுதல்`, `கடையேழு வள்ளல்கள்`, `பத்தாம் பசலி`, domination/fanaticism vocabulary, `வகுப்புவாதம்`, `கள்ளிச் செடி` and `பாதரசம்`. Batches 5–20 required no glossary-version change; their one-off source-specific expressions, scan-confirmed irregular forms and wordplay remain documented in the batch files.

The full 497-quote review did not require a glossary-version change. Eleven English-only publication corrections are recorded in `TRANSLATION_REVIEW.md`.

## `KQ-CCM-0391` rule

`KQ-CCM-0391` remains `needs_review` because the controlling scan has a physical blemish obscuring its terminal glyph after the readable text recorded by the repository.

Its English translation and consolidated publication are explicitly source-limited:

- only the readable canonical content is represented;
- the English entry remains identified as source-limited / `needs_review`;
- the obscured terminal glyph is not inferred or completed;
- translation, review and publication do not resolve the source uncertainty.

## Source-critical final-window rules

The final construction batches include scan-confirmed forms that remain unnormalized in review and publication:

- `KQ-CCM-0466`: source-visible `வாணனைகள்`, retained as **vaananaigal**;
- `KQ-CCM-0478`: source-visible `புனிதமோடதை`, retained as **punithamodathai**;
- `KQ-CCM-0491`: source-visible `முக்குடைப்பட்டாலும்`, retained as **mukkudaipattaalum**;
- `KQ-CCM-0496`: no punctuation between `புரட்சிக் கவிஞர்` and `அதனால்தான்`, and no terminal punctuation; the published English deliberately preserves that source punctuation state.

These are source checkpoints, not invitations to reconstruct the text from outside editions.

## Full fidelity/consistency review — completed

The required full `KQ-CCM-0001`–`KQ-CCM-0497` review is complete and recorded in [`TRANSLATION_REVIEW.md`](TRANSLATION_REVIEW.md).

The review:

1. compared the English against canonical Tamil;
2. checked substantive propositions, contrasts, lists, metaphors and rhetorical questions;
3. reconciled recurring terms against `GLOSSARY.md` and earlier conventions;
4. checked names, movements, party references, transliterations and culturally specific terms;
5. checked source-bound wordplay and scan-confirmed irregular forms;
6. recorded eleven English-only corrections and their rationales;
7. made **no** canonical Tamil edits;
8. retained `KQ-CCM-0391` as source-limited.

## Publication gate — passed

- Review coverage **497 / 497** — **PASS**
- Recurring terminology and wordplay reconciled — **PASS**
- `KQ-CCM-0391` source limitation preserved — **PASS**
- [`TRANSLATION_REVIEW.md`](TRANSLATION_REVIEW.md) finalized — **PASS**
- Consolidated [`quotes.md`](quotes.md) published from reviewed content — **PASS**
- All twenty sequential batch files and review records retained as audit history — **PASS**

The planned English translation, full review and consolidated publication are complete. Any future changes require new canonical source evidence or explicit editorial authorization.