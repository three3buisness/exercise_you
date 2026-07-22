## 2024-07-22 - CRLF line endings in exercise.html
**Learning:** The file `exercise.html` uses CRLF line endings, which can cause diff noise or failure when using git merge diff tools or automated scripts if not properly handled.
**Action:** Always convert CRLF to LF before modifying, apply changes, and then convert back to CRLF to ensure clean diffs and compatibility.
