## 2024-08-03 - Resource hints for YouTube origins
**Learning:** Adding preconnect resource hints for YouTube origins (`https://youtube.com` and `https://youtu.be`) in static HTML pages significantly reduces the latency to load the external video clips (especially on high-latency/mobile connections). It avoids DNS lookup, TCP handshake, and TLS negotiation overhead at click/load time, saving ~100-125ms of connection latency.
**Action:** Use preconnect links in the `<head>` of HTML documents containing multiple outbound links to the same external domains.
