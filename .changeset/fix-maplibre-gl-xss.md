---
'@watergis/maplibre-gl-legend': minor
---

fix: upgrade maplibre-gl to ^6.4.1 to address the XSS sanitizer bypass in `DOM.sanitize()` (GHSA-jrc7-96c5-q579 / CVE-2026-85061), which affects maplibre-gl 6.4.0 and earlier. No patched 5.x release exists, so this moves the dependency to the 6.x major.
