## 2026-07-28 - preconnect resource hints for external link-heavy HTML pages
**Learning:** Adding preconnect resource hints is highly effective for reducing link-click latency in a static HTML project with many external links. In this case, pre-connecting to YouTube origins saves ~100-125ms per video click by performing DNS, TCP, and TLS handshakes beforehand.
**Action:** Identify external domains linked on heavy traffic static pages and add `<link rel="preconnect" href="...">` in the HTML head.

## 2026-07-28 - CRLF line endings on git merge diffs
**Learning:** Codebases containing CRLF line endings can cause standard git merge diff tools to fail because of carriage return mismatches.
**Action:** For modifying CRLF files, convert to LF using a python script, apply changes, and then restore line endings back to CRLF before committing.
