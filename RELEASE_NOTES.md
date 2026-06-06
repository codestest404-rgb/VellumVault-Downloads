# VellumVault 0.1.9 Public Alpha

This public alpha expands the built-in Character Creator data with SRD 5.2.1 / Creative Commons-compatible spell and feat references.

## Download

- `VellumVault_0.1.9_x64-setup.exe`
- `VellumVault_0.1.9_x64_en-US.msi`

## SHA-256

- `VellumVault_0.1.9_x64-setup.exe`: `94A7FA8914FD39694B7830A7CA9553D6FD60B435A19B87905DC67B345AE33BFE`
- `VellumVault_0.1.9_x64_en-US.msi`: `F3C06357B8D2AE48952DE904816CFE7123EBB7E1282EABCB66A55B8A6946B714`

## Added

- 339 SRD spell references with level, class availability, school, casting metadata, components, duration, concentration, and ritual flags where available.
- 17 SRD feat references across Origin, General, Fighting Style, and Epic Boon categories.
- Version-aligned frontend, Tauri, Cargo, and package metadata.

## Notes

- Built-in spell and feat data remains metadata-focused and does not bundle copied spell or feat rules text.
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
