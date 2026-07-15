## 2026-07-15 - Handling CRLF in Automated Diffs
**Learning:** The source file `exercise.html` uses CRLF line endings, which causes `replace_with_git_merge_diff` to fail if the search block uses LF.
**Action:** Always convert files with CRLF to LF before applying automated diffs, and restore CRLF afterwards to maintain repository consistency.
