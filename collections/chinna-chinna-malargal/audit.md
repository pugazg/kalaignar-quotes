# Audit — கலைஞரின் சின்னச் சின்ன மலர்கள்

## Current state

- The attached source scan remains the controlling textual authority.
- Quote section begins at PDF page 10 / printed page 9.
- Controlling PDF page count: 150; final printed page: 149.
- Fully verified canonical range remains PDF pages 10-81 / printed pages 9-80.
- Fully verified quote IDs remain `KQ-CCM-0001` through `KQ-CCM-0141`.
- The latest source-capture iteration covers **25 PDF pages: 82-106 / printed pages 81-105**.
- That 25-page window maps to `KQ-CCM-0142` through `KQ-CCM-0191` — 50 source quotes in total.
- All 50 current-window quote files are deliberately `needs_review`, because the available reduced renderings do not satisfy the repository's mandatory high-resolution second-pass rule.
- Source capture may now advance in 25-page windows while this review queue remains explicit; no `needs_review` text may be treated as final or promoted without the required visual recheck.

## Counts

- Verified quote files: **141**
- `needs_review` quote files: **50**
- Stored quote files: **191**
- Source pages captured: PDF **10-106**
- Fully verified source pages: PDF **10-81**

## Current 25-page iteration — PDF 82-106

- PDF pages: 82-106
- Printed pages: 81-105
- Quote IDs: `KQ-CCM-0142` to `KQ-CCM-0191`
- Quote count: 50
- Status: source captured from controlling scan; high-resolution second pass pending
- No quote in this range is currently asserted to be `verified_from_scan`.

### Structural observations

- PDF page 94 / printed page 93 contains one quote.
- PDF page 100 / printed page 99 contains three quotes (`KQ-CCM-0177`, `KQ-CCM-0178`, `KQ-CCM-0179`).
- These structures are recorded from the controlling scan but remain part of the current review range until high-resolution confirmation.

### Focused review items

The entire range requires the normal high-resolution second pass. The following entries additionally contain wording that was especially difficult in the available rendering and must receive priority during review:

- `KQ-CCM-0149` — dictionary/“ஏழை” wordplay and punctuation
- `KQ-CCM-0153` — opening description of the மடாலயங்கள்
- `KQ-CCM-0158` / `0159` — multi-sentence mythological and metaphorical wording
- `KQ-CCM-0161` — final தாழம்பூ metaphor
- `KQ-CCM-0166` — second sentence on the single-quote page
- `KQ-CCM-0170` / `0172` / `0176` — closing clauses
- `KQ-CCM-0179` — **incomplete transcription**: only the confidently readable opening is stored; the remainder is intentionally withheld rather than guessed
- `KQ-CCM-0181` — especially uncertain preliminary reading; must not be cited as canonical text
- `KQ-CCM-0187` / `0189` — middle clauses require a cleaner source view

## Why these are `needs_review`

`docs/QUOTE_PROCESSING_GUIDE.md` requires a high-resolution visual second pass before `verified_from_scan` can be assigned. The controlling scan pages were inspected directly for this iteration, but the available page renderings are reduced. The repository therefore separates **source capture** from **final verification** rather than weakening the accuracy rule.

This also means that secondary quotations found elsewhere, OCR, context, or modernized versions must not be used to silently repair these files. They may assist review only; the visible scan remains controlling.

## Iteration rule

Per the current project instruction, new source capture proceeds in **25 PDF pages per iteration** (or all remaining pages if fewer than 25 remain).

- Uncertainty does not stop capture of the rest of the same 25-page window.
- Uncertainty must remain visible as `needs_review`.
- Final verification continues to require the high-resolution protocol.

## Important historical corrections

### KQ-CCM-0010 — substantive lexical correction

A user review caught a serious earlier transcription error. High-resolution inspection confirmed the source reading `புனுகு, ஜவ்வாது தடவி`, replacing the incorrect `பஞ்சு, ஒவ்வொரு தடவி`.

### KQ-CCM-0018 — punctuation correction

The retrospective high-resolution audit found that the source reads `வாய்க்கால் அமைத்து; வயல்`, with a semicolon rather than the earlier comma.

The complete detailed audit history through `KQ-CCM-0141`, including all previously preserved source-visible forms and completed high-resolution batches, is archived in `AUDIT_HISTORY_THROUGH_0141.md`. `HIGH_RES_REAUDIT_0001_0024.md` contains the dedicated retrospective re-audit that followed the KQ-CCM-0010 correction.

## Previously verified structural exceptions

- PDF page 22 / printed page 21 contains one quote.
- PDF page 41 / printed page 40 contains one quote.
- PDF page 81 / printed page 80 contains one quote.

## Next activity

Proceed with the next **25-page source-capture iteration**:

- PDF pages **107-131**
- printed pages **106-130**
- next stable ID begins with `KQ-CCM-0192`

Continue to preserve uncertainty explicitly as `needs_review`; do not convert any current or future entry to `verified_from_scan` without the mandatory high-resolution second pass.
