# CHANGELOG

### v1.10.3

- Upstream to 1.21.1.0 codebase
- Temporarily removed gamemode exclusion

### v1.10.2

- Added cosmic event to excluded game modes from mod processing

### v1.10.1

- Added compatibility with Onslaught gamemode (1.20.1 CT)
- Fixed issue when player re-entered battle which already started (after timer)

### v1.10.0

- Added config versioning and enhanced config migration
- Added comments for macroses and other important things in default config
- Added health percentage macros to health info
- Renamed aiming info to aiming timer
- Added more settings for aiming timer to GUI settings and config (c) Arni Ex from Korean Random
- Added aiming timer progress calculator in percents
- Added color settings for aiming timer
- Added "almost ready" threshold option for aiming timer
- Added text alignment options for panel
- Added gun elevation and gun depression macros (c) Scharfhobel from Korean Random
- Marked ability to make text bigger in template (c) Kaeptn and Arni Ex from Korean Random
- Marked ability to change font in template
- Enabled aiming timer by default now
- Reworked file/config loader
- Reworked logging
- Fixed `'AccountInputHandler' object has no attribute 'onCameraChanged'` (c) Scharfhobel from Korean Random
- Fixed empty space before battle starts when aiming timer was enabled
- Now tip uses localization from l10n file as expected

### v1.9.0

- Added shellSpeed macros to shell info

### v1.8.1

- Added memoization for localization strings calls - (с) poliroid
- Minor changes

### v1.8.0

- Fix for missing shell info on battle start
- Refactor for health info module
- Minor changes

### v1.7.0

- Added aiming timer, disabled by default. Available in mod settings in garage.
- Added support for color blind
- Added Ukranian localization
- Updated localizations

### v1.6.0

- Added shell damage macroses incl. shell damage dispersion
- Updated locale files

### v1.5.2

- Fix for forcing wrong language

### v1.5.1

- Added support for respawn mechanic in battles

### v1.5.0

- Changed path where l10n files are stored in VFS
- Minor changes

### v1.4.0

- Added Polish translation - (c) Aslain
- Updated way of loading locales for mod. They aren't located in mods/configs folder now.

### v1.3.0

- Added new `visible` property to config (to save state between game relaunch)
- Added config migrations for new config property visible
- Fixed a bug when showing/hiding panel in battle didn't work as it should
- Fixed a bug when l10n loader tried to load and apply empty l10n data

### v1.2.0

- Added health info and shell info templates to GUI configurator and config file
- Added text shadow settings to config file (not present in GUI configurator!)
- Added macros `%(shellKind)s` that outputs current shell kind (normal, premium or stun)
- Macros `%(c:shellType)s` renamed to `%(c:shellKind)s`
- Added l10n loader
- Moved l10ns to separate files instead storing it in mod
- Added config migration because of templates and text shadow settings were added. Your config will be automatically updated if it doesn't have templates or shadow field
- Fixed bug when settings applied via GUI configurator didn't save

### v1.0.0

- Initial release