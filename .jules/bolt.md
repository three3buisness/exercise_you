## 2025-02-02 - CRLF and Git Merge Diffs on Long Lines
**Learning:** Working with CRLF files can cause replace_with_git_merge_diff to fail silently or loudly if the search block is not matched precisely.
**Action:** Always convert CRLF to LF before applying changes, then restore CRLF afterwards to keep the repository's native line endings without introducing noise.
