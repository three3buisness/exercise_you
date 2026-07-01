## 2026-07-01 - Optimizing Link-Heavy Static HTML
**Learning:** Adding non-ASCII characters (like ⚡) to an ASCII HTML file triggers a charset shift. Without a meta charset tag, browsers may incur a slight delay or re-parsing overhead when detecting the encoding.
**Action:** Always include `<meta charset="UTF-8">` as one of the first tags in the `<head>` when introducing UTF-8 characters to maintain optimal parsing speed.
