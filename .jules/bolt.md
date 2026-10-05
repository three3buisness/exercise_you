## 2026-10-05 - CRLF handling in HTML diff editing
**Learning:** Editing files with CRLF line endings via merge diff tools can fail or create extraneous diff noise if line endings are not converted to LF before editing and restored afterward.
**Action:** Always convert CRLF files to LF before applying git merge diffs, then convert back to CRLF before committing.
