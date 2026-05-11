## 2025-05-14 - [Optimize YouTube Link Performance in Static HTML]
**Learning:** In projects consisting primarily of external links (e.g., YouTube), `preconnect` resource hints can significantly improve perceived performance by front-loading DNS/TCP/TLS negotiations. Additionally, removing tracking parameters (`?si=...`) from many URLs can provide a non-trivial reduction in HTML payload size (~7%).
**Action:** Always check for repeated external domains and consider `preconnect`. Audit link parameters for bloat.
