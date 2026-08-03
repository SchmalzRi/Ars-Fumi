# Ars Fumi 0.4.2

- Removed the explanatory paragraphs under the Recipes and People module headers.
- Fixed People actions with robust event delegation.
- Added a Safari/iPhone-safe modal fallback for Add, Open, Edit, and Close profile actions.
- Added explicit button types inside profile dialogs to prevent accidental form submission.
- Preserved the existing storage schema and data key.

## 0.4.2 — People interaction fix
- Fixed People editor crashes caused by CSS selectors being passed to the ID-only lookup helper.
- Restored preference slider synchronization, favorite recipe/flavor fields, and profile-view editing.
- No storage schema changes; existing data remains compatible.
