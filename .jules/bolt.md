## 2026-09-14 - Character Encoding Declaration in Static HTML
**Learning:** Adding `<meta charset="UTF-8">` within the first 1024 bytes of `<head>` prevents browsers from buffering HTML bytes to perform charset sniffing, eliminating re-parsing delays. When working with CRLF files, line endings must be converted to LF during modifications and restored to CRLF afterwards to maintain clean diffs and avoid tool failure.
**Action:** Always verify line endings using `file` and declare `<meta charset="UTF-8">` at the start of `<head>` in static HTML pages.
