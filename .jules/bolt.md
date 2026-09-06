## 2026-09-06 - CRLF Line Ending Handling in HTML Files
**Learning:** `exercise.html` uses CRLF line terminators, which can cause `replace_with_git_merge_diff` to fail or produce noisy diffs if not converted properly.
**Action:** Always convert CRLF to LF prior to applying string replacements/git diffs, apply the edit, and then convert back to CRLF before committing.
