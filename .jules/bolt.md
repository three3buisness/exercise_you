## 2026-08-16 - Preconnect on External Anchors Anti-pattern
**Learning:** Using `<link rel="preconnect">` for domain origins used only in standard outbound anchor links (`<a href="...">`) without embedded subresources (like `<iframe>` or images) is a performance anti-pattern. The browser opens idle sockets that time out after ~10 seconds, incurring unnecessary TLS handshake overhead during page load.
**Action:** Only use `preconnect` when the origin serves subresources loaded during page render, or use `<meta charset="UTF-8">` to avoid parsing delays.
