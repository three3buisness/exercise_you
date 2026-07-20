## 2025-01-22 - CRLF Line Endings and Git Merge Diffs
**Learning:** The file `exercise.html` is configured with CRLF line terminators, which can cause search-and-replace failures when applying Git merge diffs.
**Action:** Always convert CRLF line endings to LF before attempting file modifications, perform the replacement, and restore CRLF afterwards to maintain consistency without causing unexpected diff noise.
