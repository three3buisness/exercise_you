## 2026-09-12 - CRLF line endings in exercise.html
**Learning:** `exercise.html` uses CRLF line endings and contains single lines up to 886 characters, which can cause git merge diff search/replace operations to fail or create diff noise.
**Action:** Always convert `exercise.html` to LF before editing with diff tools, then restore CRLF after editing.
