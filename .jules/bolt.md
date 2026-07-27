## 2026-07-27 - CRLF Line Ending and Merge Tool Compatibility
**Learning:** Operating on files with CRLF line endings (common on Windows-based check-ins or static archives) can cause search-and-replace or git-merge-diff tools to fail or produce excessive noise in diffs if line-ending mismatches occur.
**Action:** Always identify line-ending types using the `file` command, temporarily convert to LF before applying edits, apply changes, and restore to CRLF to ensure pristine line-ending consistency and zero-noise diffs.
