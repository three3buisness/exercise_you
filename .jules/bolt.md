## 2026-05-26 - [Handling CRLF Line Endings]
**Learning:** CRLF line endings in source files can cause issues with line-based modification tools like `replace_with_git_merge_diff` and create unnecessary noise in diffs.
**Action:** Identify line endings using `file` and convert to LF for processing. Restore original CRLF line endings before submission using a Python one-liner to ensure repository consistency.
