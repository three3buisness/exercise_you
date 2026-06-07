## 2026-06-07 - Handling CRLF in Static HTML Files
**Learning:** The 'exercise.html' file uses CRLF line endings, which can cause 'replace_with_git_merge_diff' to fail or produce noisy diffs if not handled correctly.
**Action:** Always check for line endings using the 'file' command and convert CRLF to LF using a Python script before editing, then restore CRLF after modifications to maintain repository consistency.
