## 2026-10-28 - CRLF Line Endings and Automated Diffs
**Learning:** `exercise.html` uses CRLF line terminators, which can cause multi-line pattern matching and Git diff tools to fail if line endings mismatch.
**Action:** Convert CRLF files to LF before applying search-and-replace modifications, then restore CRLF line endings afterwards to preserve original line formatting.
