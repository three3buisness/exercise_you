## 2026-08-14 - HTML CRLF handling during automated diffs
**Learning:** Editing files with CRLF line endings using standard Unix line-based tools or git merge patches can generate major diff noise or fail completely due to carriage return (\r) mismatch.
**Action:** Always convert line endings from CRLF to LF (`python3 -c "import sys; content = open('filename', 'rb').read().replace(b'\r\n', b'\n'); open('filename', 'wb').write(content)"`) before performing precise code edits, and restore CRLF prior to final submission to keep git history clean.
