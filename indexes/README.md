# Indexes

This directory contains **derived** discovery indexes across quote collections.

Available indexes:

- [`source-page.md`](source-page.md) — source-level and page-map discovery across collections
- [`opening-word.md`](opening-word.md) — consolidated alphabetical/opening-word discovery through `KQ-CCM-0100` (**100 / 497 quotes**)
- [`opening-word-0101-0125.md`](opening-word-0101-0125.md) — continuation batch for `KQ-CCM-0101`–`KQ-CCM-0125`; overall opening-word coverage is now **125 / 497 quotes**

The next opening-word construction batch is `KQ-CCM-0126`–`KQ-CCM-0150`. The continuation batch is kept separate so the established consolidated master index is not rewritten or risked during incremental construction; final Tamil-collation consolidation can be performed after full coverage.

Planned indexes may include:

- theme index
- keyword index

Canonical source transcriptions remain in `collections/<collection-id>/quotes/`. Derived indexes must never replace or override canonical quote files.
