## 2026-10-06 - Handling CRLF line endings in static HTML edits
**Learning:** Editing HTML files with CRLF line endings using standard string replacement tools can cause formatting noise or diff failures unless normalized first.
**Action:** Always convert CRLF to LF prior to modification, apply changes, and restore CRLF before staging or committing.
