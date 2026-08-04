## 0.6.3 — People Edit Hotfix

- Fixed the Edit button on People cards being covered by the card’s decorative overlay.
- Decorative card graphics now ignore pointer input.
- Profile action buttons now sit in an explicit interactive layer and use `type="button"`.
- No schema or archive-data changes.

# Changelog


## 0.6.3 — Friendly Flavor Separators

- Changed tobacco examples to the keyboard-friendly `Brand: Flavor` format.
- Accepted both `:` and a normal spaced ` - ` as brand/flavor separators.
- Treated colon, normal hyphen, en dash, and em dash forms as equivalent for matching and duplicate prevention.
- Canonicalized manually typed Science and People flavor entries against the existing catalogue before saving.
- Preserved the display spelling of existing canonical entries and kept Schema 2 unchanged.

## 0.6.1 — Data Stewardship

- Completed the dedicated Settings and data-management pass.
- Formally locked the current persistent structure as Schema 2.
- Added full backup metadata and archive summaries.
- Added pre-import validation, Merge/Replace choices, and automatic pre-import recovery snapshots.
- Added visible archive-health, storage-size, and persistence checks.
- Added canonical tobacco/flavor catalogue management with reference-safe renaming and autocomplete-only removal.
- Added conservative duplicate-flavor consolidation.
- Added typed confirmation for complete archive reset.
- Kept the existing storage key and data compatibility.
