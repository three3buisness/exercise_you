## 2026-09-13 - CRLF Line Endings in HTML Source Files
**Learning:** Editing CRLF files directly with diff tools can result in tool failure or line ending conversion noise.
**Action:** Convert CRLF to LF prior to diff modifications, apply the changes, and convert back to CRLF before committing.
