# VellumVault 0.1.8 Public Alpha

This public alpha focuses on first-time tester clarity, safer campaign sharing, and a cleaner guided character-creation path.

## Download

- `VellumVault_0.1.8_x64-setup.exe`
- `VellumVault_0.1.8_x64_en-US.msi`

## SHA-256

- `VellumVault_0.1.8_x64-setup.exe`: `6DC307AF3CA1335811A18476CF8299745DBB771B8C98F814C64E761D1B4DBD07`
- `VellumVault_0.1.8_x64_en-US.msi`: `98CBF2EF6ED21C532CF05AD9E36CEE68DD60A449F9810A289812C1049434BD79`

## Changed

- Added first-run onboarding reassurance for local storage, guided setup, and safe sharing.
- Added Character Creator readiness progress with required fields, optional polish, and next-best-fix actions.
- Improved Settings sharing tools with private/player-safe export counts and restore point visibility.
- Clarified backup import warnings so users know local data will be replaced and restore points are created first.
- Updated About and release metadata to 0.1.8.
- Added a 0.1.8 alpha readiness checklist for installer checks, tester workflows, and public release validation.

## Verification

- `npm run build` passed.
- `verify-desktop.ps1` passed readiness checks for Node, npm, Rust/Cargo, MSVC x64, Windows SDK, and Tauri config.
- Native Tauri packaging generated both Windows installer bundles.

## Notes

VellumVault is a local-first desktop campaign manager for long-form homebrew and 5e-style tabletop campaigns. It includes campaign dashboards, NPCs, factions, locations, sessions, quest and hook tracking, party sheets, local D&D Beyond PDF import, DM Screen, Session Prep, Encounter Tracker, backups, restore points, and local SQLite storage.

Privacy posture:

- No account required.
- No cloud sync or telemetry.
- No hosted generation or model-provider integration.
- Installer builds contain the app only, not private campaign databases, backups, restore points, or notes.

Windows SmartScreen may warn on early unsigned builds because the installer is new. Verify downloads come from this repository and match the hash above.
