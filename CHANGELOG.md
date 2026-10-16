# Changelog

## 2026-10-16 — Asset repository structure and access overhaul
- Organized the asset library into distinct `assets/v2` (newer custom-lettering) and `assets/v1` (earlier) generations, each grouped by available format.
- Replaced compressed and ambiguous filenames with descriptive, lowercase kebab-case names; preserved original Git blob identifiers and bytes for every asset.
- Moved reference originals, generated concepts and previews out of production logo directories.
- Preserved earlier manifests and superseded documentation under `docs/archive/` without treating obsolete Gist paths as the current API.
- Added a comprehensive `assets/CATALOG.md` with individually linked GitHub file, GitHub raw and jsDelivr URLs, plus `assets/manifest.json` with old-to-new path mapping.
- Rebuilt root documentation around real repository paths, CDN patterns, selection guidance and limitations.

**Compatibility note:** Existing old `assets/brand/logo/...` paths are renamed and therefore must be migrated. Old binaries remain available in Git history. Neither the default `main` branch nor external Gist content is modified by this branch.
