## 2026-08-21 - CRLF Line Endings in exercise.html
**Learning:** `exercise.html` uses CRLF line terminators and contains long lines. Applying git merge diff tools directly without converting CRLF to LF first can lead to diff failures or unintended formatting changes.
**Action:** When modifying `exercise.html`, convert CRLF to LF before applying edits, apply changes, and then restore CRLF line endings.
