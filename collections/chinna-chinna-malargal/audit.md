# Audit — கலைஞரின் சின்னச் சின்ன மலர்கள்

## Current state

- The attached source scan remains the controlling textual authority.
- Quote section begins at PDF page 10 / printed page 9.
- Controlling PDF page count: 150; final printed page: 149.
- Fully verified canonical range remains PDF pages 10-81 / printed pages 9-80.
- Fully verified quote IDs remain `KQ-CCM-0001` through `KQ-CCM-0141`.
- Preliminary source readings have been stored as `needs_review` for `KQ-CCM-0142` through `KQ-CCM-0148`, covering PDF pages 82-85 through the first quote on printed page 84.
- PDF page 85 / printed page 84 contains a second quote, but its complete wording could not be resolved confidently from the available reduced rendering. It has **not** been transcribed or assigned a canonical file yet; the next ID remains `KQ-CCM-0149`.
- Do not continue to PDF page 86 until this review queue is cleared.

## Counts

- Verified quote files: 141
- `needs_review` quote files: 7
- Stored quote files: 148
- Untranscribed source quote currently blocking continuation: PDF 85 / printed 84 / position 2

## Why PDF 82-85 are not marked verified

`docs/QUOTE_PROCESSING_GUIDE.md` requires a high-resolution visual second pass before a quote can receive `verified_from_scan` status. In this batch the controlling scan pages were inspected directly, but the execution environment did not provide a usable high-resolution crop/render despite repeated attempts. The reduced page renderings were adequate for preliminary reading of seven quotes but are not sufficient under the repository's strengthened protocol.

Accordingly:

- `KQ-CCM-0142` through `KQ-CCM-0148` are intentionally marked `needs_review`.
- No source-sensitive spelling or punctuation in those files should be treated as final until the high-resolution pass is completed.
- The second quote on PDF page 85 remains untranscribed rather than being guessed.

## Current review queue

| Quote ID | PDF page | Printed page | Position | Status |
|---|---:|---:|---:|---|
| KQ-CCM-0142 | 82 | 81 | 1 | needs_review |
| KQ-CCM-0143 | 82 | 81 | 2 | needs_review |
| KQ-CCM-0144 | 83 | 82 | 1 | needs_review |
| KQ-CCM-0145 | 83 | 82 | 2 | needs_review |
| KQ-CCM-0146 | 84 | 83 | 1 | needs_review |
| KQ-CCM-0147 | 84 | 83 | 2 | needs_review |
| KQ-CCM-0148 | 85 | 84 | 1 | needs_review |
| KQ-CCM-0149 | 85 | 84 | 2 | not yet transcribed — high-resolution reading required |

## Important historical corrections

### KQ-CCM-0010 — substantive lexical correction

A user review caught a serious earlier transcription error. High-resolution inspection confirmed the source reading `புனுகு, ஜவ்வாது தடவி`, replacing the incorrect `பஞ்சு, ஒவ்வொரு தடவி`.

### KQ-CCM-0018 — punctuation correction

The retrospective high-resolution audit found that the source reads `வாய்க்கால் அமைத்து; வயல்`, with a semicolon rather than the earlier comma.

The complete detailed audit history through `KQ-CCM-0141`, including all preserved source-visible forms and every completed high-resolution batch, is archived in `AUDIT_HISTORY_THROUGH_0141.md`. `HIGH_RES_REAUDIT_0001_0024.md` contains the dedicated retrospective re-audit that followed the KQ-CCM-0010 correction.

## Verified structural exceptions

- PDF page 22 / printed page 21 contains one quote.
- PDF page 41 / printed page 40 contains one quote.
- PDF page 81 / printed page 80 contains one quote.

These exceptions are source-verified and must not be normalized into the usual two-quote layout.

## Next activity

1. Obtain a sufficiently high-resolution rendering of PDF pages 82-85 from the controlling source.
2. Re-read `KQ-CCM-0142` through `KQ-CCM-0148` word by word and correct any discrepancies before promotion to `verified_from_scan`.
3. Read and transcribe the second quote on PDF page 85 / printed page 84 as `KQ-CCM-0149` without guessing.
4. Update `page-map.md`, this audit, and the collection README only after that verification pass.
5. Resume new-source transcription at PDF page 86 / printed page 85 only after the review queue is cleared.
