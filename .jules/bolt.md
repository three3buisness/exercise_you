## 2025-05-14 - CRLF Line Endings in HTML
**Learning:** The `exercise.html` file uses CRLF line endings and contains very long lines. This can cause `replace_with_git_merge_diff` to fail if the diff doesn't match perfectly, and it can introduce noise in the git history if not handled carefully.
**Action:** Always convert CRLF to LF before using automated edit tools, and restore CRLF before submitting to maintain consistency.
