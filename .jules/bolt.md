## 2026-06-04 - CRLF line endings break `replace_with_git_merge_diff`
**Learning:** `exercise.html` uses CRLF line endings, which causes `replace_with_git_merge_diff` to fail because it expects LF.
**Action:** Always check file line endings using `file` command and convert to LF before using targeted replacement tools, then restore to CRLF if necessary.
