## 2026-10-26 - CRLF Line Endings in HTML Source Files
**Learning:** `exercise.html` uses CRLF line endings and long single lines, which can cause diff match tools to fail or produce bloated git diffs if line endings are unintentionally normalized to LF.
**Action:** When editing HTML files in this repository, explicitly convert CRLF to LF prior to editing, apply changes, and convert back to CRLF before committing.
