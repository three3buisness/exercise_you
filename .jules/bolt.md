## 2026-08-12 - CRLF Handling in Automated Diffs for exercise.html
**Learning:** The source file `exercise.html` uses CRLF line terminators and contains very long lines (up to 886 characters), which can cause git merge diff search-and-replace block failures when editing the file directly with tools like `replace_with_git_merge_diff`.
**Action:** Before applying modifications, convert `exercise.html` line endings to LF, perform the search-and-replace, and restore CRLF line endings prior to committing to maintain repository consistency and avoid unexpected diff failures.
