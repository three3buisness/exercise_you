## 2026-10-15 - Explicit Meta Charset and Clean Test Artifact Management
**Learning:** Adding `<meta charset="UTF-8">` as early as possible in `<head>` prevents browser charset sniffing and potential re-parsing overhead. When testing static servers locally, server logs (e.g. `server.log`) can easily be staged if created in the repo root directory.
**Action:** Always convert files with CRLF line endings to LF before using diff operations, restore original line endings afterward, and ensure temporary log files are deleted before committing.
