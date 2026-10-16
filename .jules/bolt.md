## 2026-10-16 - CRLF Line Endings in HTML Performance Optimization
**Learning:** `exercise.html` uses CRLF line endings and long lines (886+ chars). Direct string replacement without converting line endings to LF first can cause tool diff failures or subtle syntax issues. Adding `<meta charset="UTF-8">` prevents browser charset sniffing delays.
**Action:** Always convert CRLF files to LF before applying git merge diffs, then restore CRLF afterwards to maintain clean git diffs.
