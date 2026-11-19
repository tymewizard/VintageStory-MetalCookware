## 1.0.5 — Vintage Story 1.22.7

- Updated mod metadata to version 1.0.5.
- Consolidated legacy metal addon assets under the `mc` namespace.
- Removed obsolete recipe patches that referenced missing candle recipes or invalid `allowedVariants` paths.
- Preserved forging, cookware capacities, and texture corrections from 1.0.4.

## 1.0.4 standalone consolidation (release candidate)
- Consolidated legacy metal variant patches, shapes and translations into the Metal Cookware (`mc`) asset domain.
- Removed obsolete recipe patches referencing missing candelabra/candlelamp recipe files and unsupported `allowedVariants` targets.
- Preserved the current `mc` block/item codes and existing forging and texture fixes.
- Retained Expanded Matter as a required dependency and Vanilla rod extension patches where supported.
- In-game testing still required.

# Metal Cookware — Changelog

## 1.0.4 — Vintage Story 1.22.7 (release candidate)

### Added
- Anvil smithing recipes for iron, meteoric iron, steel, and titanium bowls, crocks, crock components, cooking pots, jugs, and watering cans.
- One-ingot smithing recipe yielding two finished forged crocks (50 metal units per crock).
- Metal-specific variants and expanded vessel capacities for high-tier cookware.
- Optional A Culinary Artillery saucepan and cauldron compatibility content.

### Fixed
- Incorrect copper fallback textures on iron, meteoric iron, steel and titanium bowls.
- Missing forged watering can and spout texture assignments.
- Incorrect bismuth watering can, spout and cooking pot textures.
- Smithing patterns for crock lids, jugs, watering cans and cooking pots.
- Missing or raw `mc:block-*` item names across forged cookware variants.
- Incomplete handbook capacity descriptions for forged crocks, pots, jugs, bowls and watering cans.

### Preserved / compatibility
- Existing recipes, crock component assembly, and mold-based systems.
- Expanded Matter (`em`) 3.8.3 required; A Culinary Artillery optional.
- No automatic legacy ID remapping.

**Verification:** Archive and JSON checks completed during patch iteration. Final live in-game and multiplayer checks are still recommended before publishing as stable.

## 1.0.3 — 2026-11-18
- Removed Pewter as a playable metal and its related registrations.
- Required Expanded Matter (`em`) 3.8.3.
- Retained pit-kiln mold-firing correction.
- No remapping rules included.

## 1.0.2
- Fixed mold pit-kiln firing behavior.

## 1.0.1 — 2026-11-18
- Removed temporary Pewter-to-`mc` migration configuration and empty remapping patches.
- Documented migration as separate from normal installation.

## 1.0.0 — 2026-11-18
- Initial Metal Cookware release for Vintage Story 1.22.7 under mod ID `mc`.
- Added metal tableware, cookware, molds, watering cans and multiple metal variants.
