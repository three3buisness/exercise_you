## 2026-09-07 - CRLF Line Ending Handling for HTML Modifications
**Learning:** `exercise.html` uses CRLF line terminators and contains very long lines (886 characters), which can cause git merge diff search failures or diff noise when using search-and-replace tools.
**Action:** Convert CRLF to LF prior to applying string replacements, then restore CRLF line endings after modifications are complete.
