## 2026-07-16 - [Resource Hint Subdomains]
**Learning:** Preconnecting only to the base origin (e.g., `youtube.com`) may not be sufficient if assets or links are on subdomains (e.g., `www.youtube.com`), as the browser may still need new handshakes.
**Action:** Always verify all unique origins used in the application and include `preconnect` hints for each distinct subdomain if applicable.
