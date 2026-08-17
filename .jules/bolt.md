## 2026-08-17 - CRLF Line Endings in Static HTML File Modifications
**Learning:** `exercise.html` uses CRLF line endings and long lines, which can cause diff/search tool failures or line ending diff noise during automated modifications.
**Action:** Always convert CRLF to LF before applying git merge diff modifications, and restore CRLF afterwards to maintain file line ending consistency.
