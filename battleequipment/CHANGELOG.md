# CHANGELOG

### 3.4.2

- Added Grinch battles to ignore list

### 3.4.1

- Added Project Babylon and Waffentrager battles to ignore list
- Localization implementation update

### 3.4.0

- Added logic for handling vehicle selection in Onslaught
- Fixed logic to detect whether setup selection is available in Onslaught
- Fixed possible TypeError in rare situations (can be unstable, please report any issues if you see `Player vehicle is None, please provide replay for this battle to developer!` in logs!)
- Minor refactor

### 3.3.1

- Add Races gamemode to ignorelist

### 3.3.0

- Fixed crash related to missing battle type in ignorelist
- Fixed battle booster incompatibility logic

### 3.2.2

- Removed obsolete info logs on mod start
- Minor refactor

### 3.2.1

- Fixed desyncing issue in Onslaught when setup index was different from the actual one

### 3.2.0

- Added killcam support
- Added German localization (CHAMPi)
- Enhanced Frontline support
- Migrate localization system from JSON to YAML

### 3.1.0

- Added proper Frontline support

### 3.0.6

- Fixed possible type descriptor related crashes

### 3.0.5

- Added Cosmic Event battle type to ignore list
- Minor exclusion list refactor

### 3.0.4

- Properly handle game finalization event
- Improved error handling when reading JSON file
- Minor refactor

### 3.0.3

- Fixed error in case of missing config file
- Fixed localizations
- Minor cleanup

### 3.0.2

- Improved handling of dynamically added slots before panel enter animation
- Refactored parts of slot dynamic rendering logic
- Refactored animation logic
- Fixed panel position when left or right position options was used (more space as WG's consumables panel has for its items in between)
- Fixed wrong panel position in Onslaught battle type
- Disabled modification in Maps Training battle type
- Update project to Animate 2024

### 3.0.1

- Fixed missing battle booster icon

### 3.0.0

- Added dynamic slot rendering system depending on defined slot counts by game design
- Added ability to drag panel in screen bounds under 'Free' position setting in GUI settings
- Added ability to show current setup index badge with tooltip
- Added ability to instantly show panel when setup selection is not available with Onslaught battle mode respect
- Added battle booster compatibility icon (i.e. shown when wrong battle booster is used, copied directly WG implementation from hangar/garage)
- Added disabled slot when it's empty
- Added memoization for settings entries with invalidation ability for whole or parts of memoized values
- Added initial support for respawns or ability to reset panel in battle (i.e. Frontline mode)
- Added 'showBadge' entry to settings to toggle current setup index badge
- Added 'offset' entry to settings
- Modification will ignore battles when current vehicle has no slots by game design
- Improved panel visibility system
- Updated localizations
- Fixed radial menu child stack issue
- Fixed Polish localization being ignored by modification
- Refactored many parts of modification
- Synced shared codebase

### 2.0.6

- Improved view loading logic
- Remove Versus AI battles from exclusion list (Lesta only)

### 2.0.5

- Added new Halloween (WG) event to exclusion list

### 2.0.4

- Added `Story Mode` and `Versus AI (Lesta only)` AI game modes to exclusion
- Added support for separated game modes exclusion for Lesta

### 2.0.3

- Fix for client CTD when missing IO permissions on config folder

### 2.0.2

- Cleanup after Cosmic Event

### 2.0.1

- Added Cosmic Event to excluded gamemodes 

### 2.0.0

- Major update
- Dependency gambiter.guiflash removed in favor of self-written solution (thx - poliroid)
- Added minimizer instead of hotkey
- Added specialization icon for slot type
- Moved to enhanced and more stable way to get data about current equipment
- Added posibility to anchor panel on the left or right side from panel
- Added garage/hangar settings
- Added possibility to change show on key hotkey (single key only!)
- Temporarily removed drag option

### 1.15.0

- Reworked file and config loader
- Reworked alt mode
- Deprecated own logging solution in favor of native logging module
- Fixed issue when player vehicle was destroyed and panel was visible in alt mode
- Fixed an issue when config couldn't automatically be saved after battle or on game exit
- Renamed config folder to lowercase

### 1.14.0

- Refactored old parts of mod to new standards as a preparation for removing GUIFlash as dependency

### 1.13.0

- Migrate duplicate self-written code solution to built-in WG solution
- Minor changes

### 1.12.1

- Removed tutorial battles from excluded types as it's removed in 1.20 CT

### 1.12.0

- UI components cleanup rework

### 1.11.0

- Fixed a bug when in case of missing gambiter.guiflash mod would still try to create mod's UI in battle
- Rework import of gambiter.guiflash to handle case when it's missing
- Small cleanup

### 1.10.0

- Added modernized equipment support from 1.19 CT (backwards compatible)
- Changed paths where mod related assets stored inside package

### 1.9.0

- Minor changes and fixes

### 1.8.6

- Fixed a bug when in case of missing or impossibility of getting optional device info in one of slots next slots didn't read

### 1.8.5

- Updated dependency gambiter.guiflash to 0.5.1
- Minor code changes

### 1.8.4

- Fixed a bug when vehicle had basic trophy equipment and the type icon was missing

### 1.8.3

- Config path has changed and now it's located on `mods/kurzdor/battleEquipment` path
- Fixed bug when mod was working in "Steel Hunter" mode

### 1.8.1

- Dependency gambiter.guiflash updated to 0.4.4
- Minor improvements

### 1.7.2

- Fixed panel position reset in battle
- Minor fixes

### 1.7.2

- Fixed panel position in battle saving
- Fixed minor issues

### 1.7.1

- Fixed a crash when field modifcation was leveled up for alternate equipment setup but not for optional devices and directives(thx @Scharfhobel с Korean Random)

### 1.7.0

- Added mode when modifcation only visible by pressing and holding Alt button (`"mode": "alt"` in config)
- Added hotkey to reset modification position in battle to default one
- Configuration file is moved and now located in `mods/configs/battleEquipment`
- Refactoring

### 1.6.0

- Added hotkey Ctrl + H to hide mod in battle
- Added small margins between optional devices slots (thx @pe3pa for idea)

### 1.5.0

- Fixed a bug when second preset is used and player doesn't have any battle boosters in any presets
