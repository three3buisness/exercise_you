## 2025-01-24 - [Add resource hints for YouTube links]
**Learning:** Adding `preconnect` and `dns-prefetch` for external domains like YouTube can significantly reduce the latency of navigating to those links by pre-resolving DNS and pre-establishing TCP/TLS connections.
**Action:** Always check for external links in static HTML files and consider adding resource hints for the most frequent ones.
