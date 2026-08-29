## 2026-08-29 - CRLF Line Endings & HTML Encoding Declaration
**Learning:** Editing CRLF files with diff tools can result in unreadable diffs or search block mismatch failures unless normalized. Additionally, omitting `<meta charset="UTF-8">` forces browsers into encoding detection overhead or re-parsing delays.
**Action:** Always convert CRLF to LF before applying git merge diffs, insert `<meta charset="UTF-8">` within the first 1024 bytes of `<head>`, and restore CRLF before committing.
