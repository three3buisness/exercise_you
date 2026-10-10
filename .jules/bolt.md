## 2026-10-10 - HTML Charset and CRLF diff handling
**Learning:** Adding `<meta charset="UTF-8">` to static HTML documents prevents browser character set guessing and re-parsing overhead. When modifying files with CRLF line endings, converting to LF prior to diff application prevents merge diff failures.
**Action:** Convert CRLF files to LF before applying git merge diffs, restore CRLF afterwards, and ensure explicit `<meta charset="UTF-8">` is declared early in the HTML `<head>`.
