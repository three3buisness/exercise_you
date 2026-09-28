## 2026-09-28 - CRLF Line Endings in HTML Source Files
**Learning:** `exercise.html` uses CRLF line endings, which can cause git merge diff edits to fail or create diff noise if not handled cleanly. Converting to LF prior to diff application and restoring CRLF afterwards ensures reliable file edits.
**Action:** Always convert CRLF files to LF before applying git merge diffs and restore CRLF prior to finalizing changes.
