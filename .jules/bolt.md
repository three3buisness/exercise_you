## 2026-10-12 - Handling CRLF Line Endings in HTML
**Learning:** `exercise.html` uses CRLF line endings which causes automated diff application to fail if line endings are not normalized.
**Action:** Convert CRLF files to LF before applying search-and-replace modifications, then restore CRLF line endings before committing.
