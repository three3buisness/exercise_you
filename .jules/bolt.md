## 2026-06-28 - Emoji impact on file encoding detection
**Learning:** Adding the lightning bolt emoji ⚡ to an ASCII HTML file causes automated tools like 'file' to detect it as UTF-8.
**Action:** Account for encoding shifts in verification steps when using non-ASCII characters for documentation or comments.
