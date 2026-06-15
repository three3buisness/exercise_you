## 2026-06-15 - [Resource Hint Optimization for Static Exercise Table]
**Learning:** Adding `preconnect` resource hints to external video origins (youtube.com, youtu.be) in a link-heavy static HTML file can reduce link-click latency by ~100-125ms (covering DNS, TCP, and TLS handshakes). This is a safe and effective optimization for perceived performance in static sites.
**Action:** Always identify external origins in static sites with many outbound links and consider `preconnect` for frequently used domains.

## 2026-06-15 - [CRLF Handling and Encoding Shift]
**Learning:** The `exercise.html` file uses CRLF line endings and ASCII encoding. Using `replace_with_git_merge_diff` works best with LF endings. Restoring CRLF is necessary for consistency. Additionally, adding UTF-8 characters (like the ⚡ emoji) shifts the file's detected encoding from ASCII to UTF-8.
**Action:** Use a three-step process for CRLF files: (1) convert to LF, (2) apply changes, (3) restore CRLF. Verify encoding shifts during frontend verification.
