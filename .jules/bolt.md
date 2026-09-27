## 2026-09-27 - CRLF Line Endings in HTML Source File
**Learning:** `exercise.html` uses CRLF line endings. Editing it directly without converting line endings can cause diff errors or unnecessary whitespace churn in Git.
**Action:** Always convert CRLF to LF prior to applying diffs, and restore CRLF afterwards to maintain formatting consistency.
