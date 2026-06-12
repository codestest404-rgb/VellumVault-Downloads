# VellumVault 0.1.10 Public Alpha

This public alpha expands table-running tools with dedicated Locations, Loot & Items, faster Encounter Tracker setup, and calmer spell selection.

## Download

- `VellumVault_0.1.10_x64-setup.exe`
- `VellumVault_0.1.10_x64_en-US.msi`

## SHA-256

- `VellumVault_0.1.10_x64-setup.exe`: `5BC4E2B6BD5F69FB28059CF5A16EE5B8F01E1FC15FD6A500FA37824254F799FC`
- `VellumVault_0.1.10_x64_en-US.msi`: `5F082C9184CD87E5C447066D4DD166921C42468A5ABA3193EB8EA49E31666314`

## Added

- Dedicated Locations tab with plane/world/region/settlement/point-of-interest layering, parent locations, map pins, and nearby/contained location panels.
- Dedicated Loot & Items tab for prepping SRD-safe equipment, Creator Forge gear, treasure, clue items, and assigning items to player sheet inventories.
- Encounter Tracker preloaded Red Vellum-original enemy templates and minimize/expand controls for long initiative lists.
- Character Creator spell lists now collapse by spell level.
- Version-aligned frontend, Tauri, Cargo, and package metadata.

## Notes

- Built-in combat templates are original Red Vellum quick-start enemies, not copied monster stat blocks.
- D&D Beyond import remains user-supplied and local-only.

## Verification

- `npm run build` passed.
- Native Tauri packaging generated both Windows installer bundles.

## Notes

VellumVault is a local-first desktop campaign manager for long-form homebrew and 5e-style tabletop campaigns. It includes campaign dashboards, NPCs, factions, locations, sessions, quest and hook tracking, party sheets, local D&D Beyond PDF import, DM Screen, Session Prep, Encounter Tracker, backups, restore points, and local SQLite storage.

Privacy posture:

- No account required.
- No cloud sync or telemetry.
- No hosted generation or model-provider integration.
- Installer builds contain the app only, not private campaign databases, backups, restore points, or notes.

Windows SmartScreen may warn on early unsigned builds because the installer is new. Verify downloads come from this repository and match the hash above.
