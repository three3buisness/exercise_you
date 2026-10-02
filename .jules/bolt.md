## 2026-10-02 - CRLF Line Endings in HTML Source Files
**Learning:** `exercise.html` uses CRLF line endings and long single-line blocks, which can cause diff tools to fail or generate dirty diffs if edited directly without line ending normalization.
**Action:** Always convert CRLF to LF prior to applying diff edits, and restore CRLF afterwards to maintain file formatting consistency.
