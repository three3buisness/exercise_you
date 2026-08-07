## 2026-08-07 - CRLF Line Endings and Git Merge Diffs Compatibility
**Learning:** Working with files that use CRLF line endings can cause standard diff-application tools like `replace_with_git_merge_diff` to fail or create messy, noisy diffs with unwanted line-ending changes.
**Action:** Always follow a 3-step lifecycle: (1) check line endings and convert CRLF to LF, (2) perform file modification/patching, (3) restore original CRLF line endings before committing and testing.
