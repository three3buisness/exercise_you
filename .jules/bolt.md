## 2026-06-23 - CRLF and Encoding Handling in Static HTML
**Learning:** Modifying files with CRLF line endings using `replace_with_git_merge_diff` can fail or produce noisy diffs if not handled correctly. Additionally, inserting non-ASCII characters (like ⚡) into an ASCII HTML file shifts its encoding to UTF-8, which should be explicitly declared and verified.
**Action:** Always follow the three-step sequence for CRLF files: (1) convert to LF, (2) apply changes, (3) restore CRLF. When adding UTF-8 characters, ensure `<meta charset="UTF-8">` is present and verified via `document.characterSet`.
