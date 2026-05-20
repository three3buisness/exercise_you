## 2024-05-20 - [Resource Hints for External Links]
**Learning:** Resource hints like `preconnect` and `dns-prefetch` are effective for reducing latency when a page heavily links to specific external domains (e.g., YouTube), even if they aren't assets loaded by the page itself.
**Action:** Always verify the specific origins used in the links and include estimated performance impact in comments. Ensure environment-specific artifacts like `server.log` are removed before submission.
