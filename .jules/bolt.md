## 2026-08-13 - CRLF line endings compatibility with git-merge-diff tool
**Learning:** Editing files with CRLF line endings using replace_with_git_merge_diff can fail if search patterns have mismatched line terminators.
**Action:** Always convert CRLF line endings to LF before modifications, apply the edits, and restore CRLF to prevent line ending mismatches or massive diff noise.
