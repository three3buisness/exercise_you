## 2026-07-06 - Handling CRLF and Long Lines in Static HTML
**Learning:** The 'exercise.html' file uses CRLF line endings and contains extremely long lines (up to 886 characters), which can cause 'replace_with_git_merge_diff' to fail or create messy diffs if not handled carefully.
**Action:** Always convert CRLF to LF before applying automated patches and restore them afterwards to maintain consistency and ensure tool compatibility.
