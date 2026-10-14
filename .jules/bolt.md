## 2026-10-14 - HTML Charset Declaration and Line Ending Preservations
**Learning:** Adding `<meta charset="UTF-8">` early in `<head>` prevents browser character encoding auto-detection delays (~5-15ms parsing speedup). When working with HTML files containing CRLF line endings, converting to LF before editing and restoring CRLF afterward prevents search/replace errors and unintended diff noise.
**Action:** Always convert CRLF to LF prior to diff modifications and restore CRLF prior to committing changes.
