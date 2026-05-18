## 2026-05-18 - [Resource Hints for YouTube]
**Learning:** For a static site with many external links to a specific domain (e.g., YouTube), using `preconnect` and `dns-prefetch` reduces the perceived latency for the user when clicking those links by resolving DNS and establishing connections early.
**Action:** Always check for external domains and consider adding resource hints for the most frequent ones.
