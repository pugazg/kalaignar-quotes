# Indexes

This directory contains **derived** discovery indexes across quote collections.

Available indexes:

- [`source-page.md`](source-page.md) — source-level and page-map discovery across collections
- [`opening-word.md`](opening-word.md) — consolidated alphabetical/opening-word discovery through `KQ-CCM-0100` (**100 / 497 quotes**)
- [`opening-word-0101-0125.md`](opening-word-0101-0125.md) — continuation batch for `KQ-CCM-0101`–`KQ-CCM-0125`
- [`opening-word-0126-0150.md`](opening-word-0126-0150.md) — continuation batch for `KQ-CCM-0126`–`KQ-CCM-0150`
- [`opening-word-0151-0175.md`](opening-word-0151-0175.md) — continuation batch for `KQ-CCM-0151`–`KQ-CCM-0175`
- [`opening-word-0176-0200.md`](opening-word-0176-0200.md) — continuation batch for `KQ-CCM-0176`–`KQ-CCM-0200`
- [`opening-word-0201-0225.md`](opening-word-0201-0225.md) — continuation batch for `KQ-CCM-0201`–`KQ-CCM-0225`; overall opening-word coverage is now **225 / 497 quotes**

The next opening-word construction batch is `KQ-CCM-0226`–`KQ-CCM-0250`. Continuation batches are kept separate so the established consolidated master index is not rewritten or risked during incremental construction; final Tamil-collation consolidation can be performed after full coverage.

Planned indexes may include:

- theme index
- keyword index

Canonical source transcriptions remain in `collections/<collection-id>/quotes/`. Derived indexes must never replace or override canonical quote files.
