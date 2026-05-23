## 2024-05-16 - [Resource Hint Optimization]
**Learning:** Adding 'preconnect' and 'dns-prefetch' to external domains reduces the perceived latency for users by performing DNS lookups and establishing connections before the user clicks a link. In this repository, YouTube links are the primary external assets.
**Action:** Use 'grep -oP "https?://[^/\"]+" exercise.html | sort | uniq' to identify all external origins accurately before implementing resource hints.

## 2024-05-16 - [Environment Hygiene]
**Learning:** Background processes like 'python3 -m http.server' can generate log files ('server.log') in the project root, which should never be committed.
**Action:** Ensure all temporary files and logs are deleted before running the pre-commit checks and submitting the PR.
