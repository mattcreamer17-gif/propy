# Propy landing page

Bespoke, single-page site prepared for Propy (booth 1149) ahead of the conference. Headline opens with a read on where AI actually fits in Propy's closing stack. The page carries the full pitch body from `fit-analysis.md` section 7 in Propy's own visual vocabulary: Playfair Display for display type, Space Grotesk for body, the signature `#38A6FB` sky-blue accent against a clean light neutral, and the single-color logomark in the nav. Eduba shows up only in the footer. The CTA routes straight to Matt Creamer's calendar.

Intended URL path: `/for/propy`

## Files
- `index.html` — full page markup
- `styles.css` — brand-token-driven styles (no JS)
- `logo.svg` — Propy logomark copied from the brand pack

## Notes
- All fonts loaded from Google Fonts to match Propy's live site (Playfair Display, Space Grotesk, Roboto Mono).
- Tested at 375px minimum width. Sticky nav collapses its link row on narrow viewports.
- Every outbound URL is a real anchor with `target="_blank" rel="noopener"`.
- Pricing, fees, retainer amounts, and revenue-share terms are stripped from the prospect-facing copy per sprint rules.
- NLP Logix mention includes the mandatory "in machine learning since 2011" and "over 150 data scientists" stats on a single line.
- No mention of Ethics Engine, KPMG, Correlation One, or the 22,000-member community. Those cues do not fit Propy's CTO-peer conversation.
