# CHANGELOG

### v1.4.2

- Sync up shared codebase and fixes

### v1.4.1

- Fixed wrong or missing localization in some cases

### v1.4.0

- Reworked file and config loader
- Fixed issue when mod couldn't restore WG original colors when it was disabled after modifying colors
- Renamed config folder to lowercase

### v1.3.0

- GUI Settings refactored to ModSettings' Templates API
- Updated localization
- Updated config and l10n loader
- Refactoring done as for preparation for big changes

### v1.2.1

- Config path has changed and now it's located on `mods/kurzdor/outliningColors` path
- Updated dependency izeberg.modsettingsapi to v1.5.4

### v1.2.0

- Added vehicle outlining and obtacle areas transparency settings - using RGBA alpha channel, acceptable values from 0 to 1
- Added ability to change outlining color for player vehicle when it's behind invisible obstacle (bushes, ally or enemy vehicles, etc.) - thx AssMonk3y from NA region
- Added ability to apply outlining to squad members (it's neccessary to also check checkbox in "Additional settings" section) - thanks @ktulho from XVM developers team
- Tweaked colors to be more WG like
- Drastically changed mod configurator in better way
- Disabling mod in it's configurator now properly reverts all changes with game reload need
- Configuration and l10n (localization) files are changed, don't forget to update them + waiting for Polish l10n
- Mod refactoring done

### v1.1.0

- Fixed found issues with fill and pattern transparency

### v1.0.0

- Initial public release
