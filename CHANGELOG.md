# Changelog

# Changelog

## [1.0.2] - 2026-08-01

### Added
- Player-owned teleport points, stored separately by player identity
- Branded `/tphelp` menu header:
  `===== [ CHAOS RELICS | ADVANCED TELEPORT ] =====`
- Help-menu header entries for all supported localization files
- Built-in localization fallback for missing language keys

### Changed
- Improved teleport execution on dedicated and community servers
- Teleports now synchronize the player's server position and client position
- Teleport cost is checked before the teleport delay begins
- Teleport currency is only deducted after a successful teleport execution
- Improved Linux and dedicated-server mod path resolution
- Renamed the release assembly to `ChaosRelics-AdvancedTeleport.dll`
- Improved configuration and localization reload behavior

### Fixed
- Fixed teleport points being shared globally between players
- Fixed successful server-side teleports not visibly moving the client
- Fixed `SafeTeleport: false` still forcing safe-destination validation
- Fixed duplicate chat command responses caused by overlapping handlers
- Fixed missing localization keys appearing as raw key names in chat
- Fixed nullable-path compiler warnings in `FileSystemPaths`


## [1.0.1] - 2026-07-27

### Added
- Initial public release of the Advanced Teleport mod
- Configurable teleport delay and cooldown support
- Optional teleport cost handling
- Safety checks and movement cancellation during teleport delay
- Permission-based command access
- Localization support via language files
- Optional Discord webhook logging

### Changed
- Standardized mod metadata and project documentation
