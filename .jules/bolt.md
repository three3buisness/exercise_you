## 2026-08-23 - Character Set Declaration in HTML Head
**Learning:** Adding `<meta charset="UTF-8">` as the first tag in `<head>` avoids encoding detection/sniffing and re-parsing delays in HTML documents. When modifying files with CRLF line endings, converting to LF before editing and restoring CRLF afterward prevents merge diff failures.
**Action:** Always check file line endings with `file` before editing HTML files in static repositories, and insert character set declarations near the top of `<head>`.
