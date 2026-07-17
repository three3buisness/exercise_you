# Bolt's Performance Journal

## 2026-07-17 - CRLF Line Endings in Static HTML Projects
**Learning:** Static HTML source files created under Windows-centric environments may contain CRLF line endings, which can cause git-based search-and-replace tools (`replace_with_git_merge_diff`) to fail silently or generate massive diff noise.
**Action:** Always identify line ending formats using `file <filename>`. If CRLF is present, follow the three-step sequence: (1) convert to LF via Python, (2) apply targeted changes, (3) restore CRLF using Python before committing to maintain codebase line ending consistency.
