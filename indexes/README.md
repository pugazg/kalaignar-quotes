# Indexes

This directory contains **derived** discovery indexes across quote collections.

Available indexes:

- [`source-page.md`](source-page.md) — source-level and page-map discovery across collections
- [`opening-word.md`](opening-word.md) — complete consolidated opening-word discovery for `KQ-CCM-0001`–`KQ-CCM-0497` (**497 / 497 quotes**). Final collation review preserves Tamil initial-letter group order and deterministic literal-Unicode ordering within each group.
- [`theme-taxonomy.md`](theme-taxonomy.md) — controlled theme vocabulary and assignment rules for the derived theme index. Taxonomy version **1.0** defines 16 stable theme keys.
- [`theme.md`](theme.md) — complete consolidated theme discovery index for `KQ-CCM-0001`–`KQ-CCM-0497` (**497 / 497 quotes**), incorporating the completed consistency pass.
- [`theme-consistency-review.md`](theme-consistency-review.md) — completed full consistency pass across all 497 quote-level theme assignments, including the 13 corrections required before consolidated publication.
- [`theme-0001-0025.md`](theme-0001-0025.md) — first theme-classification batch for `KQ-CCM-0001`–`KQ-CCM-0025`.
- [`theme-0026-0050.md`](theme-0026-0050.md) — second theme-classification batch for `KQ-CCM-0026`–`KQ-CCM-0050`.
- [`theme-0051-0075.md`](theme-0051-0075.md) — third theme-classification batch for `KQ-CCM-0051`–`KQ-CCM-0075`.
- [`theme-0076-0100.md`](theme-0076-0100.md) — fourth theme-classification batch for `KQ-CCM-0076`–`KQ-CCM-0100`.
- [`theme-0101-0125.md`](theme-0101-0125.md) — fifth theme-classification batch for `KQ-CCM-0101`–`KQ-CCM-0125`.
- [`theme-0126-0150.md`](theme-0126-0150.md) — sixth theme-classification batch for `KQ-CCM-0126`–`KQ-CCM-0150`.
- [`theme-0151-0175.md`](theme-0151-0175.md) — seventh theme-classification batch for `KQ-CCM-0151`–`KQ-CCM-0175`.
- [`theme-0176-0200.md`](theme-0176-0200.md) — eighth theme-classification batch for `KQ-CCM-0176`–`KQ-CCM-0200`.
- [`theme-0201-0225.md`](theme-0201-0225.md) — ninth theme-classification batch for `KQ-CCM-0201`–`KQ-CCM-0225`.
- [`theme-0226-0250.md`](theme-0226-0250.md) — tenth theme-classification batch for `KQ-CCM-0226`–`KQ-CCM-0250`.
- [`theme-0251-0275.md`](theme-0251-0275.md) — eleventh theme-classification batch for `KQ-CCM-0251`–`KQ-CCM-0275`.
- [`theme-0276-0300.md`](theme-0276-0300.md) — twelfth theme-classification batch for `KQ-CCM-0276`–`KQ-CCM-0300`.
- [`theme-0301-0325.md`](theme-0301-0325.md) — thirteenth theme-classification batch for `KQ-CCM-0301`–`KQ-CCM-0325`.
- [`theme-0326-0350.md`](theme-0326-0350.md) — fourteenth theme-classification batch for `KQ-CCM-0326`–`KQ-CCM-0350`.
- [`theme-0351-0375.md`](theme-0351-0375.md) — fifteenth theme-classification batch for `KQ-CCM-0351`–`KQ-CCM-0375`.
- [`theme-0376-0400.md`](theme-0376-0400.md) — sixteenth theme-classification batch for `KQ-CCM-0376`–`KQ-CCM-0400`.
- [`theme-0401-0425.md`](theme-0401-0425.md) — seventeenth theme-classification batch for `KQ-CCM-0401`–`KQ-CCM-0425`.
- [`theme-0426-0450.md`](theme-0426-0450.md) — eighteenth theme-classification batch for `KQ-CCM-0426`–`KQ-CCM-0450`.
- [`theme-0451-0475.md`](theme-0451-0475.md) — nineteenth theme-classification batch for `KQ-CCM-0451`–`KQ-CCM-0475`.
- [`theme-0476-0497.md`](theme-0476-0497.md) — twentieth and final quote-level theme-classification batch for `KQ-CCM-0476`–`KQ-CCM-0497`; overall theme-classification coverage is **497 / 497 quotes**.

Construction/audit shards retained for opening-word traceability:

- [`opening-word-0101-0125.md`](opening-word-0101-0125.md)
- [`opening-word-0126-0150.md`](opening-word-0126-0150.md)
- [`opening-word-0151-0175.md`](opening-word-0151-0175.md)
- [`opening-word-0176-0200.md`](opening-word-0176-0200.md)
- [`opening-word-0201-0225.md`](opening-word-0201-0225.md)
- [`opening-word-0226-0250.md`](opening-word-0226-0250.md)
- [`opening-word-0251-0275.md`](opening-word-0251-0275.md)
- [`opening-word-0276-0300.md`](opening-word-0276-0300.md)
- [`opening-word-0301-0325.md`](opening-word-0301-0325.md)
- [`opening-word-0326-0350.md`](opening-word-0326-0350.md)
- [`opening-word-0351-0375.md`](opening-word-0351-0375.md)
- [`opening-word-0376-0400.md`](opening-word-0376-0400.md)
- [`opening-word-0401-0425.md`](opening-word-0401-0425.md)
- [`opening-word-0426-0450.md`](opening-word-0426-0450.md)
- [`opening-word-0451-0475.md`](opening-word-0451-0475.md)
- [`opening-word-0476-0497.md`](opening-word-0476-0497.md)

The consolidated opening-word index was validated for **497 unique quote IDs with no gaps from `KQ-CCM-0001` through `KQ-CCM-0497`**. It represents the canonical verification states without changing them: **496 quotes are `verified_from_scan` and `KQ-CCM-0391` remains `needs_review`** because of the documented physical source blemish. Its unaffected opening word is indexed, but the unresolved source reading is not promoted or inferred.

Quote-level theme classification is complete under taxonomy version 1.0. All twenty batches cover **497 / 497 quotes** and preserve their canonical verification states: **496 `verified_from_scan` and 1 `needs_review` (`KQ-CCM-0391`)**. Classification is based only on canonical quote text, assigns exactly one primary theme and at most two secondary themes, and does not edit source transcriptions.

The full consistency pass is complete. It confirmed **497 unique theme rows with no gaps or duplicates**, valid controlled keys, valid primary/secondary cardinality, and preservation of all verification states. The three `other-unclear` assignments (`KQ-CCM-0306`, `KQ-CCM-0343`, `KQ-CCM-0403`) were re-read and retained. The pass applied **13 assignment corrections across 10 batch files** to align general character, cause-oriented struggle and no-inference cases with taxonomy version 1.0; details are recorded in [`theme-consistency-review.md`](theme-consistency-review.md).

The consolidated theme index is now published in [`theme.md`](theme.md). It contains all **497 / 497** assignments in quote-ID order, incorporates the completed consistency corrections, and continues to preserve `KQ-CCM-0391` as `needs_review`.

Theme-index publication under taxonomy version 1.0 is complete. The next planned derived-discovery activity is **keyword-index design and construction**.

Canonical source transcriptions remain in `collections/<collection-id>/quotes/`. Derived indexes must never replace or override canonical quote files.
