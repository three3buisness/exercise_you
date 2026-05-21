## 2026-05-21 - [Handling CRLF in Static HTML]
**Learning:** The `exercise.html` file uses CRLF line endings and contains very long lines. This combination can cause `replace_with_git_merge_diff` to fail or produce messy diffs if the environment defaults to LF.
**Action:** Always convert the file to LF before using diff tools and restore CRLF afterwards to maintain consistency and clean diffs.

## 2026-05-21 - [Resource Hints for Link-Heavy Pages]
**Learning:** For static pages like `exercise.html` that serve as a directory of external links (e.g., YouTube), `preconnect` and `dns-prefetch` provide a significant perceived performance boost by reducing connection setup time on click.
**Action:** Identify primary external domains and add corresponding resource hints to the `<head>`.
