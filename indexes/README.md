# Indexes

This directory contains **derived** discovery indexes across quote collections.

Available indexes:

- [`source-page.md`](source-page.md) — source-level and page-map discovery across collections
- [`opening-word.md`](opening-word.md) — complete consolidated opening-word discovery for `KQ-CCM-0001`–`KQ-CCM-0497` (**497 / 497 quotes**). Final collation review preserves Tamil initial-letter group order and deterministic literal-Unicode ordering within each group.

Construction/audit shards retained for traceability:

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

Planned derived discovery work may include:

- theme index
- keyword index

Canonical source transcriptions remain in `collections/<collection-id>/quotes/`. Derived indexes must never replace or override canonical quote files.
