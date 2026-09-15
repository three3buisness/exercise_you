## 2026-09-15 - CRLF Line Endings in HTML Source Files
**Learning:** `exercise.html` uses CRLF line endings, which can cause pattern matching failures in diff/editing tools or result in line ending noise across the entire file if modified naively.
**Action:** Convert CRLF to LF prior to applying string replacements, then convert LF back to CRLF to ensure minimal and clean git diffs.
