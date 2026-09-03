## 2026-09-03 - CRLF Line Endings in HTML Performance Optimization
**Learning:** Editing CRLF files directly with diff tools can result in patch failures or dirty diffs due to line ending mismatches.
**Action:** Convert CRLF files to LF before applying git merge diffs, then convert back to CRLF before verifying and committing.
