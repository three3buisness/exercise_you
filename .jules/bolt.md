## 2026-09-30 - CRLF Line Endings in HTML files
**Learning:** HTML files in this project use Windows CRLF (`\r\n`) line endings. Modifying line endings or performing multi-line replacements without normalized LF line endings during edit operations can introduce unwanted diff noise or result in search-and-replace failures.
**Action:** When modifying files with CRLF line endings, convert them to LF line endings first, apply modifications, and restore CRLF line endings prior to committing.
