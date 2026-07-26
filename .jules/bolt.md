## 2026-07-26 - CRLF Line Endings and Diff Tools
**Learning:** Editing files with CRLF line endings on unix environments directly using automated diff tools can fail or result in noisy diffs. Conversions to LF before changes and restoring back to CRLF afterwards is the cleanest, most reliable approach.
**Action:** Convert CRLF files to LF using Python before applying merge diffs, then convert back to CRLF before committing.
