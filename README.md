# BetaPixel — Next-Level Interactive Portfolio (Concept)

A complete, responsive, dependency-free frontend concept. Original CSS-based interactive 3D scene, cursor, navigation, portfolio filters, responsive project artwork, scroll animation, and working mailto enquiry flow.

## Run locally

1. Open `index.html` in a modern browser. For best results, use a local server:
2. `python -m http.server 8080` in this directory
3. Visit http://localhost:8080

No npm install or API key required.

## Content & production notes

- BetaPixel's public company description, contact email/phone, founder, published project names and headline metrics are based on the existing BetaPixel website as inspected October 9, 2026.
- Art on portfolio cards is **original concept artwork**, not client-provided media or a representation of published campaign deliverables.
- Work cards link to existing BetaPixel portfolio category pages. This avoids inventing unverified individual project URLs or results.
- The enquiry form opens the visitor's email client, pre-filled. Connect a real backend/API before deploying if in-page submissions are required.
- Pure CSS 3D depth offers a fast, interactive concept; a production-level WebGL engine can replace it if desired.
- External Google Fonts improve typography but local system font fallbacks exist.
- This is a standalone prototype, not a direct modification of the live WordPress site. Nothing on the live website, database, or hosting has been changed.
