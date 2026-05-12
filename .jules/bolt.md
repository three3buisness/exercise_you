## 2026-05-12 - Initial Audit
**Learning:** The project is a minimal static HTML page with many external links to YouTube. The main performance bottleneck for users is the connection latency when clicking exercise links.
**Action:** Use resource hints like `preconnect` and `dns-prefetch` to reduce latency for external navigations. Add `meta charset` to avoid encoding sniffing delays.
