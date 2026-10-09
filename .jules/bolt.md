## 2026-10-09 - CRLF Line Endings in Static HTML
**Learning:** `exercise.html` uses CRLF line terminators and contains very long lines (up to 886 chars), which causes string replacements and diff applications to fail or introduce diff noise when tools expect LF line endings.
**Action:** Convert CRLF to LF using Python before applying modifications with diff tools, then restore CRLF line endings afterward to preserve original file formatting.
