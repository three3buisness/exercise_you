## 2026-08-31 - CRLF Line Endings in HTML Source Files
**Learning:** Editing CRLF files directly with diff tools can cause search failures or git diff noise. Converting CRLF to LF before modification and restoring CRLF afterwards preserves formatting without diff corruption.
**Action:** Always follow the convert-edit-restore sequence for CRLF files in this repository.
