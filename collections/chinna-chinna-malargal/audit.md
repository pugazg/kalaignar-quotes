# Audit — கலைஞரின் சின்னச் சின்ன மலர்கள்

## Current state

- The attached source scan remains the controlling textual authority.
- Quote section begins at PDF page 10 / printed page 9.
- The materialized controlling PDF has **249 physical PDF pages**.
- The earlier values `150` and `>300` were not raw-PDF page counts and must not be reused.
- Fully verified canonical range remains PDF pages 10-81 / printed pages 9-80.
- Fully verified quote IDs remain `KQ-CCM-0001` through `KQ-CCM-0141`.
- Source capture now reaches PDF page **181** / printed page **180**.
- Stored quote range now reaches `KQ-CCM-0346`.
- All quote files from `KQ-CCM-0142` onward remain `needs_review` until the mandatory formal high-resolution second visual comparison is completed.

## Counts

- Verified quote files: **141**
- `needs_review` quote files: **205**
- Stored quote files: **346**
- Source pages captured: PDF **10-181**
- Fully verified source pages: PDF **10-81**
- Physical source PDF pages: **249**

## Source-capture windows completed

### PDF 82-106 / printed 81-105

- Quote IDs: `KQ-CCM-0142` to `KQ-CCM-0191`
- Quote count: 50
- Status: `needs_review`
- PDF 94 / printed 93 contains one quote.
- PDF 100 / printed 99 contains three quotes.
- `KQ-CCM-0179` remains an intentionally incomplete preliminary transcription and requires priority review.

### PDF 107-131 / printed 106-130

- Quote IDs: `KQ-CCM-0192` to `KQ-CCM-0245`
- Quote count: 54
- Status: `needs_review`
- Three-quote pages observed at PDF 108, 113, 128, and 131.
- Source-sensitive readings and difficult wording remain explicitly marked in individual files.

### PDF 132-156 / printed 131-155

- Quote IDs: `KQ-CCM-0246` to `KQ-CCM-0296`
- Quote count: 51
- Status: `needs_review`
- PDF 141 / printed 140 contains three quotes.
- PDF pages 132-150 were inspected from the controlling scan; PDF pages 151-156 were also rendered directly from the materialized raw PDF.
- No quote in this window has been promoted to `verified_from_scan`.

### PDF 157-181 / printed 156-180

- Quote IDs: `KQ-CCM-0297` to `KQ-CCM-0346`
- Quote count: **50**
- Status: `needs_review`
- The embedded source image for every page was extracted directly from the materialized raw 249-page PDF and visually inspected for first-pass source capture.
- PDF 164 / printed 163 contains three quotes.
- PDF 179 / printed 178 contains one long quote; the historical anecdote is one source unit because no decorative quote separator divides its paragraphs.
- No quote in this window has been promoted to `verified_from_scan`.

### Focused review items in PDF 132-156

The entire window still needs the standard formal second pass. The following files additionally contain especially uncertain preliminary wording and should receive priority:

- `KQ-CCM-0247` — quoted epithet, middle clause, closing wording
- `KQ-CCM-0249` — middle wording before `ஆணவத்தின் உச்சக்கட்டம்`
- `KQ-CCM-0251` / `0253` — second-sentence / closing wording
- `KQ-CCM-0256` — full quote requires a clean re-read
- `KQ-CCM-0259` — first sentence
- `KQ-CCM-0261` — full quote requires a clean re-read
- `KQ-CCM-0262` — `வயிற்றுக் கனம்` clause
- `KQ-CCM-0265` / `0266` — middle/opening wording
- `KQ-CCM-0267` / `0268` — closing verb and second sentence
- `KQ-CCM-0271` — full quote requires a clean re-read
- `KQ-CCM-0274` — full quote is especially uncertain and must not be cited as canonical
- `KQ-CCM-0275` / `0276` — middle/opening wording
- `KQ-CCM-0279` — complete wording requires priority re-verification
- `KQ-CCM-0281` / `0282` — first two sentences / middle wording
- `KQ-CCM-0289` — punctuation and final clause

### Focused review items in PDF 157-181

The entire window requires the normal formal second visual pass. Priority items are:

- `KQ-CCM-0302` — opening word provisionally read as `விலைகளால்`
- `KQ-CCM-0304` — source form provisionally read as `இரணமான`
- `KQ-CCM-0309` — opening word provisionally read as `பாதிரியாருக்கு`
- `KQ-CCM-0331` — unusual source-visible spacing `கண்ணாடி யாகவும்` retained provisionally
- `KQ-CCM-0342` — long Warren Hastings / Edmund Burke anecdote; historical names and punctuation need especially careful second-pass comparison

## Why `needs_review` remains mandatory

`docs/QUOTE_PROCESSING_GUIDE.md` requires a high-resolution visual second pass before `verified_from_scan` can be assigned. Source capture and final verification are therefore intentionally separated.

- Never silently normalize source spelling, punctuation, spacing, joined forms, quotation marks, numerals, or anomalies.
- OCR, outside quotations, and contextual inference are aids only.
- A difficult source reading remains visible as `needs_review`; it is never promoted merely because a plausible modern reading exists.

## Important historical corrections

### KQ-CCM-0010 — substantive lexical correction

A user review caught a serious earlier transcription error. High-resolution inspection confirmed the source reading `புனுகு, ஜவ்வாது தடவி`, replacing the incorrect `பஞ்சு, ஒவ்வொரு தடவி`.

### KQ-CCM-0018 — punctuation correction

The retrospective high-resolution audit found that the source reads `வாய்க்கால் அமைத்து; வயல்`, with a semicolon rather than the earlier comma.

The complete detailed audit history through `KQ-CCM-0141` is preserved in `AUDIT_HISTORY_THROUGH_0141.md`. `HIGH_RES_REAUDIT_0001_0024.md` contains the dedicated retrospective re-audit that followed the KQ-CCM-0010 correction.

## Verified structural exceptions

- PDF page 22 / printed page 21 contains one quote.
- PDF page 41 / printed page 40 contains one quote.
- PDF page 81 / printed page 80 contains one quote.

Observed structures in later `needs_review` ranges are recorded in `page-map.md` but remain subject to final visual verification.

## Iteration rule

New source capture proceeds in **25 PDF pages per iteration**.

- Uncertainty does not stop capture of the rest of the same 25-page window.
- Uncertainty must remain explicit as `needs_review`.
- Final verification continues to require the high-resolution protocol.

## Next activity

Proceed with the next 25-page source-capture iteration:

- PDF pages **182-206**
- printed pages **181-205**
- next stable ID begins with `KQ-CCM-0347`

The physical PDF contains 249 pages, so source capture continues after PDF 206 until the actual end of the scan.
