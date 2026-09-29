## 2026-09-29 - CRLF Line Endings in HTML Optimization

**Learning:** `exercise.html` uses CRLF line endings and long lines. Direct line-diff search operations can fail unless converted to LF before edits and converted back to CRLF afterwards.
**Action:** Always convert CRLF files to LF before applying changes with `replace_with_git_merge_diff`, then restore CRLF line endings.
