## 2026-10-25 - CRLF Line Endings in HTML Source Files
**Learning:** `exercise.html` uses CRLF line terminators, which can cause git merge diff search-and-replace failures if line endings are not normalized during modification.
**Action:** Always convert files with CRLF to LF line endings before applying targeted search-and-replace edits, then restore CRLF line endings afterward.
