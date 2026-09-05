## 2026-09-05 - HTML Character Encoding Optimization
**Learning:** HTML documents with mixed line endings (CRLF) can cause git diff failures when using search-and-replace tools unless converted to LF prior to modification.
**Action:** Always convert CRLF line endings to LF before applying git merge diffs and restore CRLF afterwards if original formatting requires it.
