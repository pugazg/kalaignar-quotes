# Kalaignar Quotes

Source-critical archive of quotations attributed to Kalaignar M. Karunanidhi, transcribed from scanned source publications.

## Principles

- The source scan is the controlling textual authority.
- Preserve the wording, punctuation, spelling, and paragraphing visible in the source.
- Do not silently normalize or modernize Tamil.
- Every quote must carry source-page provenance.
- Uncertain readings must be flagged rather than guessed.
- Derived indexes and translations never override the canonical Tamil source layer.

## Repository layout

```text
README.md
docs/
  QUOTE_PROCESSING_GUIDE.md
collections/
  <collection-id>/
    README.md
    metadata.yaml
    page-map.md
    audit.md
    quotes/
      0001.md
      0002.md
      ...
    translations/
      en/
        README.md
        TRANSLATION_PLAN.md
        PROGRESS.md
        GLOSSARY.md
        PILOT_REVIEW.md
        TRANSLATION_REVIEW.md
        quotes.md
        batches/
indexes/
  README.md
  opening-word.md
  theme.md
  keyword.md
  ...
```

## Current collection

The first collection is [`collections/chinna-chinna-malargal/`](collections/chinna-chinna-malargal/), based on the scanned book **கலைஞரின் சின்னச் சின்ன மலர்கள்**.

Current durable state:

- Canonical Tamil quote records: **497 / 497**
- High-resolution source audit: **complete through the physical end of the 249-page PDF**
- Canonical verification states: **496 `verified_from_scan`, 1 `needs_review` (`KQ-CCM-0391`)**
- Opening-word index: **497 / 497 published**
- Theme index: **497 / 497 consistency-reviewed and published**
- Keyword index: **497 / 497 consistency-reviewed and published** under frozen vocabulary version **1.0**
- English first-pass translation: **497 / 497 complete**
- Full English fidelity/consistency review: **497 / 497 complete**
- Consolidated reviewed English publication: [`collections/chinna-chinna-malargal/translations/en/quotes.md`](collections/chinna-chinna-malargal/translations/en/quotes.md) — **497 / 497 published**

`KQ-CCM-0391` remains unresolved only because a physical blemish in the controlling scan obscures its terminal glyph. No index or translation layer is permitted to infer or repair that source uncertainty.