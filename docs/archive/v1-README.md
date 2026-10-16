# Pay24.now — Brand Logo Asset Library

**Status:** PROPOSED brand asset kit, pending owner visual approval. Do not imply formally approved/registered trademark execution.

## Authoritative identity

- Original owner-supplied raster: `original/pay24-reference-400.png` (preserved, unmodified).
- Vector source of truth for icon: `svg/pay24-mark-master.svg` (precision-inspired geometric reconstruction, NOT a mathematically exact trace of the raster antialiasing).
- Horizontal/stacked/wordmark are the proposed Pay24.now typographic extensions, not source-provided wordmarks.
- Other SVG files inherit shared fixed RGB identity; PNG/WebP/ICO are exports rather than independent sources.

## Original logo fidelity

The reference shows a 22-segment off-white circular ring, with a **two-pronged green accent** aligned at the top. Unlike a simple wedge, the original accent includes a narrow V-shaped negative-space notch. This geometric invariant must remain in Pay24's new designs. The ring fills are `#FAFAFA`, green is `#3ECF8E`, and original background is `#121212` (sampled exact from source). SVG reconstruction simplifies antialiased raster edges and slightly regularizes ring-segment curvature and spacing; original raster is retained for comparison.

## Wordmark and typography

The proposed wordmark is `Pay24.now`, with `Pay24` in near-black on light backgrounds / off-white on dark, and `.now` in green. It is outlined to SVG paths from **Inter Display Bold**, with manual tracking adjustments; no font is shipped or required to render SVG. This is a vectorized typographic proposal, not a newly commissioned typeface. Inter is licensed under SIL Open Font License 1.1; confirm distribution obligations if modifying or shipping the font itself.

## Selection table

| Context | Recommended file |
| --- | --- |
| Primary dark UI | `svg/pay24-horizontal-on-dark.svg` |
| Primary light UI | `svg/pay24-horizontal-on-light.svg` |
| Compact navigation | `svg/pay24-mark-on-dark.svg` or `svg/pay24-mark-on-light.svg` |
| Vertical / square placements | `svg/pay24-stacked-on-dark.svg` or `svg/pay24-stacked-on-light.svg` |
| Black/white print | `svg/pay24-horizontal-mono-black.svg` or `svg/pay24-horizontal-mono-white.svg` |
| App tile | `svg/pay24-app-icon.svg` |
| Favicon | `favicon/favicon.svg` or `favicon/favicon.ico` |
| Editable vector mark | `svg/pay24-mark-master.svg` |

Avoid using a white-segment icon on a white background; use the explicitly named on-light variant. Do not add glow, gradient, shadows or animate the logo by default. Do not change the two-pronged top accent or rearrange segment counts.

## Size, exclusion zone and accessibility

- Clear space (PROPOSED): at least one inner-ring-radius around logo lockups; never crop the emblem into UI edges.
- Minimum sizes (PROPOSED, subject to real-device testing): full lockup 150 CSS px wide; symbol 24 CSS px; for favicon use packaged 32/16 previews and check legibility.
- Logo itself conveys brand identity, not financial status. Use accessible name `Pay24.now` when the logo is the only label; hide it from screen readers if adjacent visible text already names the brand.
- Monochrome SVGs intentionally remove the green, for reproduction where colors are unavailable.
- PNGs with transparent background should be composited on their intended tone. App icons and favicon include an opaque near-black square.
- For any font, vector or color adaptation, review licensing and accessible contrast in the final use context.

## Formats and source preservation

- `svg/` — genuine scalable path-based vectors. The typography is outlined (no external font dependency).
- `png/` — rendered RGBA assets in named widths; transparent except app tile.
- `webp/` — optimized raster exports.
- `favicon/` — favicon SVG, PNG resolution set, multi-resolution ICO.
- `previews/` — review visuals, not master artwork.
- `original/` — untouched supplied reference raster.

Avoid importing model-generated logo concepts as canonical assets if they changed the green forked top marker, introduced blur/glow, or have baked checkerboard artifacts.

## Source and version notes

Source: the brand logo uploaded by the owner on 2026-10-16. Design expansion is proposed by the documentation workflow and should be accepted or revised by the brand owner before release. The design is independent of unrelated vendor skins. No Pay24 source-code implementation or dependency changes were performed.
