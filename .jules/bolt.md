## 2026-08-15 - CRLF File Line Endings in Static HTML Projects
**Learning:** Editing CRLF files directly using `replace_with_git_merge_diff` can cause diff matching failures or introduce mixed line endings unless converted to LF before editing and restored to CRLF afterwards.
**Action:** Always convert files with CRLF line endings to LF before making structural or code modifications, and restore CRLF afterwards to maintain repo consistency.
