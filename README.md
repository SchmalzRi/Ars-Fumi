# Ars Fumi 0.6.2 — Friendly Flavor Separators

This build completes the Settings and data-management pass before the first genuine-session beta.

## Data stewardship

- Schema 2 is treated as the fixed persistent format.
- Full JSON exports contain sessions, recipe families and versions, People profiles, photos, equipment, canonical flavors, defaults, UI settings, and export metadata.
- Imports are parsed and validated before they can change active data.
- Import supports **Merge** and **Replace**.
- An automatic pre-import snapshot can be restored from Settings.
- Archive health shows record counts, approximate storage size, storage persistence, broken references, invalid ratings, duplicate IDs, and conservative flavor-duplicate warnings.
- Reset requires typing `ERASE`.

## Catalogue management

Settings now manages equipment and canonical tobacco/flavor names. Renaming a flavor updates matching Science records, People favorites, and the current draft. Removing a flavor only removes it from autocomplete; historical records remain intact.

## Upgrade compatibility

The storage key remains `arsFumi.v0.1.data`, and Schema 2 remains unchanged. Updating at the same GitHub Pages address preserves existing 0.6.0 data. Export a backup before replacing files.


## 0.6.2 separator handling

Tobacco names can now use `Brand: Flavor`, `Brand - Flavor`, or the older long-dash form. Ars Fumi treats these separators as equivalent for autocomplete, duplicate detection, People favorites, Science records, imports, and catalogue management. The visible spelling of an existing canonical entry is preserved.
