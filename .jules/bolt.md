## 2026-10-18 - CRLF Line Endings in HTML Optimization
**Learning:** Editing CRLF files directly using search-and-replace tools without converting to LF first can lead to tool search failures or line ending diff noise.
**Action:** Always convert CRLF to LF prior to applying diff edits, and convert back to CRLF after editing.
