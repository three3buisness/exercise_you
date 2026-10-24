## 2026-10-24 - CRLF Line Ending Preserved HTML Editing
**Learning:** `exercise.html` uses CRLF line endings and contains very long lines (up to 886 characters), which can cause string matching and diff application tools to fail or introduce unintended diff noise.
**Action:** Convert CRLF to LF using Python prior to applying edits with git merge diffs, and restore CRLF afterwards to maintain exact line ending compatibility across the repository.
