## 2026-10-31 - Line ending preservation during HTML diffing
**Learning:** `exercise.html` is checked into the repository with CRLF terminators and long lines. Direct diff replacements can fail or introduce unwanted line ending churn unless converted to LF for editing and restored to CRLF prior to commit.
**Action:** Always inspect line endings with `file` and perform the 3-step conversion (CRLF -> LF -> edit -> CRLF) to maintain clean diffs and prevent editor/patch failures.
