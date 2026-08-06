## 2026-08-06 - CRLF Line Ending and Git Merge Diff Compatibility
**Learning:** The source file `exercise.html` has CRLF line endings, which causes `replace_with_git_merge_diff` to fail or create a noisy diff if not managed carefully.
**Action:** Always convert CRLF to LF before modifying `exercise.html` using Python, apply the change, and then restore CRLF to preserve repository line endings.
