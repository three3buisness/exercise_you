## 2026-08-01 - Handling CRLF line endings in Static HTML files during search/replace modifications
**Learning:** Found that `exercise.html` has CRLF (`\r\n`) line endings. This often causes tools like `replace_with_git_merge_diff` to fail because standard search patterns or block matches assume LF (`\n`) line endings.
**Action:** Always inspect line endings first using `file <filename>`. If the file uses CRLF, convert it temporarily to LF before applying changes with `replace_with_git_merge_diff`, then restore CRLF to match the repository's original format and preserve clean diffs.
