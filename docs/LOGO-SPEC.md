# Pay24.now — Logo specification

## Scope
This specification documents the images tracked in this repository, not an original trademark master file. Prefer the latest complete `v2` asset for a given use. The earlier `v1` family remains available separately for traceability and compatibility.

## Brand identity
- Brand spelling: **Pay24.now** (capital P, lower-case ay, numerals 24, period, lower-case now).
- Referenced visual geometry: a circular arrangement with 22 off-white radial segments and a distinct green, two-pronged accent featuring a V-shaped notch.
- Brand colors: charcoal `#121212`, near-white `#FAFAFA` and emerald `#3ECF8E`.
- Preserving the identity does not require treating brand green as a transaction-status semantic token.

## Asset architecture
- `assets/v2/svg/` contains vector paths for the newer custom-lettering generation. Example: [horizontal on dark](../assets/v2/svg/pay24-horizontal-on-dark.svg).
- `assets/v2/png/` and `assets/v2/webp/` contain the corresponding available raster editions. The catalog, rather than a filename guess, defines which exports exist.
- `assets/v2/favicon/` contains SVG, PNG and ICO favicon resources.
- `assets/v1/` contains an earlier rendering generation; it is not interchangeable with `v2` by assumption.
- `assets/reference/pay24-reference-400.png` preserves a referenced original raster. The selected lettering screenshot mentioned in earlier metadata is **not present** in this repository.
- `assets/previews/` and `assets/reference/concepts/` are for reference; do not substitute them for production masters without review.

## Practical use rules
Keep the aspect ratio unchanged. Prefer the foreground specifically designed for the chosen light/dark surface. Avoid stretching, mirroring, cropping, unauthorized recoloring and destructive recompression of the master SVG. Reserve provisional clear space at least 15% of emblem width; this is a usage guideline, not a certification. Verify final legibility in the actual browser and at the intended display size.

## QA and unresolved verification
Source SVGs are path-based assets in inspected samples; all assets are preserved byte-for-byte at their Git object IDs during repository relocation. A complete per-file rendering comparison, at-size browser validation, contrast/accessibility assessment and trademark clearance are **not evidenced by this structural migration**.
