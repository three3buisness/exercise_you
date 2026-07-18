## 2023-11-23 - CRLF line endings with git merge diff in static HTML files
**Learning:** In static HTML projects like exercise_you, source files can have CRLF line endings, which cause tool compatibility issues and noisy diffs when using tools like replace_with_git_merge_diff.
**Action:** Always convert CRLF line endings to LF before editing, apply the target changes, and restore the original CRLF line endings afterwards to ensure a clean and noiseless diff.
