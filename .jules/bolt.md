## 2026-07-13 - CRLF handling in automated diffs
**Learning:** The `exercise.html` file uses CRLF line endings, which can cause `replace_with_git_merge_diff` to fail or produce unexpected results if not handled correctly.
**Action:** Always convert CRLF files to LF before applying automated diffs, and restore CRLF afterwards to maintain repository consistency.
