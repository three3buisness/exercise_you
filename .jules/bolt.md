## 2026-09-25 - Explicit UTF-8 Encoding in Static HTML
**Learning:** Lacking `<meta charset="UTF-8">` in HTML causes modern browser parsers to pause rendering and perform character sniffing or fallback parsing.
**Action:** Always declare explicit `<meta charset="UTF-8">` as early as possible within the `<head>` tag in static HTML files.
