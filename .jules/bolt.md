## 2026-09-22 - HTML CRLF Line Endings and Meta Charset Optimization
**Learning:** `exercise.html` uses CRLF line endings which require converting to LF before automated search-and-replace modifications and restoring CRLF afterwards to maintain format integrity. Additionally, static HTML files without `<meta charset="UTF-8">` in `<head>` risk character set sniffing overhead and potential encoding fallback issues in modern web browsers.
**Action:** Always handle CRLF conversions when editing `exercise.html` and declare `<meta charset="UTF-8">` as early as possible in `<head>`.
