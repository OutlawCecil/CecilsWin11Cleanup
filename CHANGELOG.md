# Changelog

All notable changes to this project will be documented in this file as versions increase.

## [4.61] - 2026-05-08
- Disable VBS / Core Isolation for more performance gains
- Disable Xbox Game Bar for more performance gains
- Timezone detection and options
- Consistancy fixes

## [4.5] - 2026-03-11
- Found and fixed another elevated permissions issue; hopefully the last of it
- Utilized new policy found on the latest Win11 to remove apps from new profiles
- Consistancy fixes

## [4.43] - 2026-03-02
- More fixes for issue with elevated permissions, which was addressed in 4.42
- Windows 11 Drag Tray was added to latest release. Removed by default
- Added current user and user's SID to top of the script to confirm targeting

## [4.42] - 2026-02-25
- Edge now includes a sidebar, shopping assistants, and heavy telemetry. Added registry edits to help.
- Removed artificial pauses so the script runs faster, but pauses at the end to allow for review
- Fixed issue with elevated permissions making registry edits affect admin instead of current user
- Removed weather widget from taskbar
- Removed chat icon (teams) from taskbar

## [4.35] - 2026-02-04
- Initial public GitHub release.
