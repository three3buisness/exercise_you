## 2025-03-04 - Static HTML Optimization with Resource Hints
**Learning:** Adding preconnect links to external resource origins (like YouTube) can reduce DNS lookup and TLS handshake latency by ~100-125ms per click for external navigation in a static web page.
**Action:** Identify all external domains using grep and add preconnect resource hints with explanatory comments directly inside the HTML head.
