## 2025-05-18 - CRLF Line Endings in HTML Files
**Learning:** `exercise.html` uses CRLF line endings, which can cause automated search-and-replace or diff tools (`replace_with_git_merge_diff`) to fail if line endings are not handled or standardized to LF before applying changes.
**Action:** Convert files with CRLF to LF line endings before modifying them, apply edits, and restore CRLF prior to verification and commit.
