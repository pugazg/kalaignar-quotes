# Audit — கலைஞரின் சின்னச் சின்ன மலர்கள்

## Current state

- The source scan remains the controlling textual authority.
- The materialized controlling PDF has **249 physical PDF pages**.
- The quotation section runs from PDF **10-249** / printed **9-248**.
- **First-pass source capture is complete through the physical end of the PDF.**
- Fully verified canonical range now reaches PDF **10-131** / printed **9-130**.
- Fully verified quote IDs now reach `KQ-CCM-0001` through `KQ-CCM-0245`.
- Stored quote range reaches `KQ-CCM-0497`.
- Every quote from `KQ-CCM-0246` onward remains `needs_review` until the mandatory formal high-resolution second visual comparison is completed.

## Counts

- Verified quote files: **245**
- `needs_review` quote files: **252**
- Stored quote files: **497**
- Source pages captured: PDF **10-249**
- Fully verified source pages: PDF **10-131**
- Physical source PDF pages: **249**

## Completed first-pass source-capture windows

- PDF 82-106 / printed 81-105 → `KQ-CCM-0142`-`0191` → 50 quotes
- PDF 107-131 / printed 106-130 → `KQ-CCM-0192`-`0245` → 54 quotes
- PDF 132-156 / printed 131-155 → `KQ-CCM-0246`-`0296` → 51 quotes
- PDF 157-181 / printed 156-180 → `KQ-CCM-0297`-`0346` → 50 quotes
- PDF 182-206 / printed 181-205 → `KQ-CCM-0347`-`0398` → 52 quotes
- PDF 207-231 / printed 206-230 → `KQ-CCM-0399`-`0457` → 59 quotes
- PDF 232-249 / printed 231-248 → `KQ-CCM-0458`-`0497` → 40 quotes

The final window is shorter because PDF 249 is the physical end of the source.

## Completed high-resolution second-pass windows

### PDF 82-106 / printed 81-105

- Quote IDs: `KQ-CCM-0142` through `KQ-CCM-0191`
- Quote count: **50**
- Status: **verified_from_scan**
- PDF 94 / printed 93 confirmed as a one-quote page.
- PDF 100 / printed 99 confirmed as a three-quote page.
- The previously incomplete `KQ-CCM-0179` was fully recovered from the source scan.

This second pass produced numerous substantive corrections, including `பஞ்சை, பராரி`, `விபச்சாரதளங்கள்`, `பிர்மஹத்தி`, `பச்சைக் கொடியல்ல; பச்சைப் பாம்பு`, `விரசம்`, and `நவநாகரீக காலம்`.

### PDF 107-131 / printed 106-130

- Quote IDs: `KQ-CCM-0192` through `KQ-CCM-0245`
- Quote count: **54**
- Status: **verified_from_scan**
- PDF 108 / printed 107 confirmed as a three-quote page.
- PDF 113 / printed 112 confirmed as a three-quote page.
- PDF 128 / printed 127 confirmed as a three-quote page.
- PDF 131 / printed 130 confirmed as a three-quote page.

Corrections and source-sensitive readings from this window include:

- `KQ-CCM-0194`: source punctuation `ஈ, எறும்பு, புழு பூச்சிகளின்`.
- `KQ-CCM-0200`: source form `பாப விமோசனத்துக்கான`.
- `KQ-CCM-0214`: unusual source form `தவடையில்` retained without normalization.
- `KQ-CCM-0219`: joined source form `அளிக்கப்படவேண்டிய`.
- `KQ-CCM-0230`: unusual printed form `தாமம்` retained.
- `KQ-CCM-0240`: corrected preliminary `தங்கத்துண்டுகள்` to source `தங்கத்துகள்கள்`.
- `KQ-CCM-0241`: unusual source form `கனிவர்க்கமாகும்` retained.
- `KQ-CCM-0243`: corrected preliminary `அம்பனைத்` to source `அற்பனைத்`.

No source spelling, spacing, punctuation, or unusual lexical form was silently modernized.

## Structural observations remaining in the review range

One-quote pages still awaiting formal second-pass verification:

- PDF 179 / printed 178
- PDF 243 / printed 242

Three-quote pages still awaiting formal second-pass verification:

- PDF 141, 164, 203, 205
- PDF 207, 208, 209, 212, 220, 222, 226, 230, 231
- PDF 232, 234, 235, 242, 244

## Priority second-pass review queue

Priority items still ahead include:

- `KQ-CCM-0274` and `KQ-CCM-0279` — especially uncertain preliminary wording
- `KQ-CCM-0302`, `0304`, `0309`, `0331`, `0342` — source-sensitive or long passages requiring close comparison
- `KQ-CCM-0416` — long poetic `தமிழே!` passage; multiple uncommon forms require glyph-by-glyph comparison
- `KQ-CCM-0421` — source-visible `தேவையில்லைபென்று` retained provisionally
- `KQ-CCM-0431` — source-visible reading provisionally captured as `ஏசறணைகளைப்`
- `KQ-CCM-0440` — long embedded poetic quotation; wording and punctuation require close review
- `KQ-CCM-0466` — `வாணனைகள்` reading requires second-pass check
- `KQ-CCM-0478` — embedded poetic quotation requires close source comparison
- `KQ-CCM-0491` — `முக்குடைப்பட்டாலும்` retained provisionally pending glyph audit
- `KQ-CCM-0496` — final-page punctuation and lineation require formal visual audit

## Why `needs_review` remains mandatory

`docs/QUOTE_PROCESSING_GUIDE.md` requires a high-resolution visual second pass before `verified_from_scan` can be assigned.

- Never silently normalize source spelling, punctuation, spacing, joined forms, quotation marks, numerals, or anomalies.
- OCR, outside quotations, and contextual inference are aids only.
- A difficult source reading remains visible as `needs_review`; it is never promoted merely because a plausible modern reading exists.
- Quote boundaries are determined from the source page and decorative separators, not from assumptions about a fixed number of quotes per page.

## Important historical corrections

### KQ-CCM-0010 — substantive lexical correction

A user review caught a serious earlier transcription error. High-resolution inspection confirmed the source reading `புனுகு, ஜவ்வாது தடவி`, replacing the incorrect earlier reading.

### KQ-CCM-0018 — punctuation correction

The retrospective high-resolution audit found that the source reads `வாய்க்கால் அமைத்து; வயல்`, with a semicolon rather than the earlier comma.

The complete detailed audit history through `KQ-CCM-0141` remains preserved in `AUDIT_HISTORY_THROUGH_0141.md`. `HIGH_RES_REAUDIT_0001_0024.md` contains the dedicated retrospective re-audit triggered by the KQ-CCM-0010 correction.

## Next activity

Proceed with the next **25-page high-resolution second-pass verification iteration**:

- PDF pages **132-156**
- printed pages **131-155**
- quote IDs `KQ-CCM-0246` through `KQ-CCM-0296`

Only after direct visual comparison should corrected entries be promoted from `needs_review` to `verified_from_scan`.
