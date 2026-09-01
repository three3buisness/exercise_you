## 2026-09-01 - CRLF Line Endings in HTML Source Files
**Learning:** `exercise.html` uses CRLF line endings which causes standard search-and-replace tools to fail when matching multi-line patterns.
**Action:** Always convert CRLF files to LF before applying git merge diffs, then convert back to CRLF after modification.
