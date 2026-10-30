## 2026-10-30 - CRLF Line Ending Handling in exercise.html
**Learning:** `exercise.html` uses CRLF line endings and long lines, which can cause `replace_with_git_merge_diff` to fail or create diff noise if not handled cleanly.
**Action:** Always convert CRLF to LF prior to applying string search-and-replace, apply modifications, and then restore CRLF line endings.
