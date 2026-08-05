## 2026-08-05 - Managing CRLF Line Endings in HTML
**Learning:** Editing static HTML files with CRLF line endings via standard diffing tools can lead to syntax issues or search failure unless they are first converted to LF, and then restored to CRLF post-optimization.
**Action:** Always follow the three-step sequence: (1) convert file to LF, (2) apply merge diff modifications, (3) restore CRLF line endings.
