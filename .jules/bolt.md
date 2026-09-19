## 2026-09-19 - CRLF Line Endings in HTML Source Files
**Learning:** `replace_with_git_merge_diff` fails or produces inconsistent diffs when targeting files with CRLF line endings on Linux sandbox environments.
**Action:** Convert target files from CRLF to LF (`replace(b'\r\n', b'\n')`) before applying merge diffs, then convert back to CRLF (`replace(b'\n', b'\r\n')`).
