## 2026-10-13 - CRLF Line Endings in HTML Source
**Learning:** `exercise.html` uses CRLF line endings and contains very long lines, which can cause git merge diff search tools to fail or produce unwanted line ending diff noise if modified directly without normalization.
**Action:** Always convert CRLF to LF prior to applying string replacements, then restore CRLF line endings before committing.
