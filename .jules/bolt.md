## 2026-09-21 - CRLF Handling in Static HTML Diffs
**Learning:** Files with CRLF line endings cause targeted search-and-replace tools (`replace_with_git_merge_diff`) to fail when search blocks use standard LF line breaks.
**Action:** Convert CRLF files to LF before applying git merge diffs, then restore CRLF line endings afterwards to avoid unintended diff noise.
