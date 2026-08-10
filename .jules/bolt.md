## 2026-08-10 - CRLF Line Endings in HTML Source
**Learning:** The static HTML source file `exercise.html` has CRLF line endings. Applying modifications directly with `replace_with_git_merge_diff` can fail or introduce unwanted line ending modifications across unchanged lines, causing noisy diffs.
**Action:** For compatibility and cleanliness, always convert CRLF to LF line endings before performing changes, apply the modifications, and restore CRLF line endings prior to committing.
