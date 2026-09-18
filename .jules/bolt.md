## 2026-09-18 - CRLF Line Endings & HTML Encoding Optimization
**Learning:** In static HTML documents with CRLF line endings, editing without converting line endings first can create tool compatibility issues or dirty diffs. Furthermore, specifying `<meta charset="UTF-8">` early in `<head>` prevents browser character encoding detection delays (~10-50ms).
**Action:** Always convert files with CRLF line endings to LF before applying git merge diff edits, restore CRLF after, and ensure static HTML pages declare `<meta charset="UTF-8">` early in `<head>`.
