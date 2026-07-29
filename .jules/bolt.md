## 2026-07-29 - Handling CRLF Files in Git Merge Diff Tools
**Learning:** Editing a file with CRLF line endings using standard Python script modifiers or precise git-diff replacement tools can fail or produce excessive whitespace diffs if line ending normalization is not performed first.
**Action:** Always check the file format using the `file` command first, convert CRLF to LF line endings prior to making automated search-and-replace modifications, and restore CRLF afterwards to maintain clean git commits.
