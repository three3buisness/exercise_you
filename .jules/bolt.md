## 2025-05-15 - CRLF Line Endings and Git Merge Diff
**Learning:** `exercise.html` uses CRLF line endings, which causes `replace_with_git_merge_diff` to fail or produce incorrect results when the search block uses LF.
**Action:** Always convert the file to LF line endings before applying modifications and restore CRLF afterwards to maintain consistency and avoid noisy diffs.
