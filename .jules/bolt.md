## 2026-07-23 - CRLF line endings compatibility during search-and-replace
**Learning:** Files containing CRLF line endings can lead to search-and-replace block failures when matching multi-line patterns due to carriage returns (`\r`). Converting to LF, applying diff modifications, and then restoring CRLF is a reliable pattern to prevent tool issues and preserve file formats.
**Action:** Always inspect the line ending style using `file` beforehand and handle conversion/restoration steps gracefully.
