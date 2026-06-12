## 2026-06-12 - CRLF line endings in exercise.html
**Learning:** The file `exercise.html` uses CRLF line endings, which can cause `replace_with_git_merge_diff` to fail if the diff doesn't account for them.
**Action:** Convert to LF before using `replace_with_git_merge_diff` and restore to CRLF afterwards to maintain consistency.
