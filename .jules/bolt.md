## 2026-08-08 - CRLF Line Endings in Static HTML Files
**Learning:** Editing files with CRLF line endings (Windows style) can cause issues with git patch applications and lead to unintended diff noise (such as displaying the whole file as modified) when not converted properly during modification.
**Action:** Always convert files with CRLF line endings to LF before making edits with `replace_with_git_merge_diff` or other diff tools, and restore them back to CRLF before committing to maintain codebase style consistency.
