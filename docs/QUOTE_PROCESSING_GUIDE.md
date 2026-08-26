# Quote Processing Guide

## Purpose

This repository is a source-critical archive of quotations attributed to Kalaignar M. Karunanidhi. The immediate source is the scanned publication itself, not OCR, search results, later quote collections, or modernized reprints.

## Controlling authority

1. The visible scan is the controlling textual authority.
2. OCR or extracted text may be used only for navigation.
3. When OCR and the scan disagree, follow the scan.
4. Do not silently normalize spelling, sandhi, punctuation, quotation marks, or older forms.
5. If a glyph or word cannot be read confidently, mark the quote `needs_review` and record the uncertainty in the quote file.
6. Do not fill missing words from memory, context, another edition, or an online quotation.

## Mandatory visual-verification protocol

A quote must not be marked `verified_from_scan` merely from a reduced page preview.

For every quote:

1. inspect the correct PDF page and printed-page number;
2. inspect the quote area at sufficient resolution to distinguish individual Tamil glyphs and punctuation;
3. read the source itself word by word, not an OCR-derived reconstruction;
4. compare the completed transcription back against the high-resolution source a second time;
5. pay special attention to visually confusable words, joined forms, vowel marks, punctuation, numerals and quotation marks;
6. if any reading remains uncertain, use `needs_review` rather than guessing.

If a user or later audit finds a substantial discrepancy in a quote already marked verified, record the correction in `audit.md` and retrospectively re-audit the affected verification batch before adding new source pages.

## Canonical unit

The canonical archival unit is **one quote per Markdown file** under:

`collections/<collection-id>/quotes/NNNN.md`

Each quote file must contain:

- stable quote ID
- source ID
- collection ID
- PDF page
- printed page, when present
- position on the printed page
- verification status
- Tamil transcription
- source note

Sequential quote IDs are never reused after publication.

## Transcription rules

- Preserve the source wording exactly.
- Preserve meaningful paragraph breaks.
- Preserve visible punctuation, including semicolons, dashes, quotation marks, question marks, and exclamation marks.
- Do not preserve purely typographic line wrapping.
- Do not modernize Tamil.
- Do not add explanatory words inside the transcription.
- Decorative separators and illustrations are not part of the quote text.
- If one quote spans multiple paragraphs on the page, keep it as one quote file.

## Verification statuses

- `verified_from_scan` — read directly from the scan and checked visually under the mandatory high-resolution protocol above.
- `needs_review` — one or more readings remain uncertain.
- `provisional` — entered from a non-controlling aid and not yet visually verified. Provisional entries should be avoided whenever the scan is available.

## Page mapping

Every collection must maintain `page-map.md`, mapping:

- PDF page
- printed page
- first quote ID
- second quote ID
- verification state

Do not assume every source has exactly two quotes per page; record what the scan actually contains.

## Metadata and indexing

Collection metadata belongs in `metadata.yaml`.

Global indexes under `indexes/` are derived discovery aids. They must never replace or override canonical quote files.

Theme classification, translations, keywords, or modernized renderings may be added later as **derived metadata**, clearly separated from the source transcription.

## Audit

Each collection keeps `audit.md` with:

- transcription progress
- verified ranges
- unresolved readings
- structural anomalies
- any corrected quote IDs

The audit must make it possible to resume work without guessing.
