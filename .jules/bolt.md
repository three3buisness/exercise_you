## 2025-05-18 - Line Endings in HTML Optimization

**Learning:** `exercise.html` uses CRLF line endings, which can cause diff matching failures when applying automated diffs if not converted to LF first.
**Action:** Convert `exercise.html` from CRLF to LF before applying changes, then restore CRLF line endings after editing.
