# English translation — கலைஞரின் சின்னச் சின்ன மலர்கள்

This directory contains the derived English translation layer for the canonical Tamil quotations in `collections/chinna-chinna-malargal/quotes/`.

The audited Tamil quote files remain authoritative. English files must never silently correct, normalize or replace the Tamil source layer.

## Current status

- Canonical quote range: `KQ-CCM-0001`–`KQ-CCM-0497`
- English first-pass coverage: **497 / 497 — COMPLETE**
- Completed batches:
  - [`batches/translation-0001-0025.md`](batches/translation-0001-0025.md) — pilot, 25 quotes
  - [`batches/translation-0026-0050.md`](batches/translation-0026-0050.md) — Batch 2, 25 quotes
  - [`batches/translation-0051-0075.md`](batches/translation-0051-0075.md) — Batch 3, 25 quotes
  - [`batches/translation-0076-0100.md`](batches/translation-0076-0100.md) — Batch 4, 25 quotes
  - [`batches/translation-0101-0125.md`](batches/translation-0101-0125.md) — Batch 5, 25 quotes
  - [`batches/translation-0126-0150.md`](batches/translation-0126-0150.md) — Batch 6, 25 quotes
  - [`batches/translation-0151-0175.md`](batches/translation-0151-0175.md) — Batch 7, 25 quotes
  - [`batches/translation-0176-0200.md`](batches/translation-0176-0200.md) — Batch 8, 25 quotes
  - [`batches/translation-0201-0225.md`](batches/translation-0201-0225.md) — Batch 9, 25 quotes
  - [`batches/translation-0226-0250.md`](batches/translation-0226-0250.md) — Batch 10, 25 quotes
  - [`batches/translation-0251-0275.md`](batches/translation-0251-0275.md) — Batch 11, 25 quotes
  - [`batches/translation-0276-0300.md`](batches/translation-0276-0300.md) — Batch 12, 25 quotes
  - [`batches/translation-0301-0325.md`](batches/translation-0301-0325.md) — Batch 13, 25 quotes
  - [`batches/translation-0326-0350.md`](batches/translation-0326-0350.md) — Batch 14, 25 quotes
  - [`batches/translation-0351-0375.md`](batches/translation-0351-0375.md) — Batch 15, 25 quotes
  - [`batches/translation-0376-0400.md`](batches/translation-0376-0400.md) — Batch 16, 25 quotes; `KQ-CCM-0391` source-limited
  - [`batches/translation-0401-0425.md`](batches/translation-0401-0425.md) — Batch 17, 25 quotes
  - [`batches/translation-0426-0450.md`](batches/translation-0426-0450.md) — Batch 18, 25 quotes
  - [`batches/translation-0451-0475.md`](batches/translation-0451-0475.md) — Batch 19, 25 quotes
  - [`batches/translation-0476-0497.md`](batches/translation-0476-0497.md) — Batch 20, final 22 quotes
- Source states represented: **496 `verified_from_scan`, 1 `needs_review` (`KQ-CCM-0391`)**
- Pilot fidelity/style review: [`PILOT_REVIEW.md`](PILOT_REVIEW.md) — **complete**
- Glossary: [`GLOSSARY.md`](GLOSSARY.md), version **1.3** — pilot conventions locked; Batch-2 through Batch-4 terminology added; Batches 5–20 required no glossary revision
- Translation protocol: [`TRANSLATION_PLAN.md`](TRANSLATION_PLAN.md)
- Progress ledger: [`PROGRESS.md`](PROGRESS.md)
- Next activity: **full quote-by-quote English fidelity/consistency review across `KQ-CCM-0001`–`KQ-CCM-0497`**

## Translation principles

The English aims to be readable while remaining source-bound. It preserves substantive meaning, rhetorical force, metaphor, satire and explicit political/social language without modernizing the Tamil or adding historical interpretation not present in the canonical text.

Tamil wordplay that cannot survive directly in English is kept visible through a retained source term or a short translation note. Culturally specific terms are transliterated when a supposedly smoother English substitute would introduce unsupported interpretation.

The mandatory pilot review rechecked all 25 first-batch translations against their canonical Tamil and refined four English renderings (`KQ-CCM-0004`, `0016`, `0020`, `0025`). Those conventions remain locked. Batches 2 and 3 added source-facing political, social, literary and culturally specific terminology. Batch 4 added source-bound handling for **Vamana avatar / King Mahabali**, mirror-context **reflective coating**, **the Last Seven Great Patrons**, **panneer flowers**, **vaguppuvaadam**, **kalli plant**, and related domination/fanaticism vocabulary. Batches 5–20 retained glossary version 1.3 and documented one-off source-specific language, scan-confirmed irregular forms and wordplay locally without changing earlier conventions.

## Construction model

Translation proceeded in sequential 25-quote batches, with the final 22-quote batch `0476`–`0497`. All twenty batch files are retained as construction/audit history.

The first-pass construction stage is now **complete at 497 / 497**. A full consistency/fidelity review must now be performed before publication of consolidated `quotes.md`.

`KQ-CCM-0391` remains source-limited: its obscured terminal glyph is not to be guessed or reconstructed in English. The first-pass English entry does not resolve the canonical `needs_review` state.

## Publication gate

Do **not** publish consolidated `translations/en/quotes.md` merely because first-pass coverage has reached 497 / 497. The required next gate is:

1. full quote-by-quote fidelity review against the canonical Tamil files;
2. consistency review of recurring terminology, names, transliterations and wordplay handling across all twenty batches;
3. explicit confirmation that `KQ-CCM-0391` remains source-limited unless the controlling source itself has been genuinely resolved;
4. creation of `TRANSLATION_REVIEW.md` recording review results and corrections;
5. only after that review, publication of consolidated `quotes.md`.
