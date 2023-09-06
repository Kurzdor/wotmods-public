# CHANGELOG

### 2.0.4

- Added `Story Mode` and `Versus AI (Lesta only)` AI game modes to exclusion
- Added support for separated game modes exclusion for Lesta

### 2.0.3

- Fix for client CTD when missing IO permissions on config folder

### v2.0.2

- Cleanup after Cosmic Event

### v2.0.1

- Added Cosmic Event to excluded gamemodes 

### v2.0.0

- Major update
- Dependency gambiter.guiflash removed in favor of self-written solution (thx - poliroid)
- Added minimizer instead of hotkey
- Added specialization icon for slot type
- Moved to enhanced and more stable way to get data about current equipment
- Added posibility to anchor panel on the left or right side from panel
- Added garage/hangar settings
- Added possibility to change show on key hotkey (single key only!)
- Temporarily removed drag option

### v1.15.0

- Reworked file and config loader
- Reworked alt mode
- Deprecated own logging solution in favor of native logging module
- Fixed issue when player vehicle was destroyed and panel was visible in alt mode
- Fixed an issue when config couldn't automatically be saved after battle or on game exit
- Renamed config folder to lowercase

### v1.14.0

- Refactored old parts of mod to new standards as a preparation for removing GUIFlash as dependency

### v1.13.0

- Migrate duplicate self-written code solution to built-in WG solution
- Minor changes

### v1.12.1

- Removed tutorial battles from excluded types as it's removed in 1.20 CT

### v1.12.0

- UI components cleanup rework

### v1.11.0

- Fixed a bug when in case of missing gambiter.guiflash mod would still try to create mod's UI in battle
- Rework import of gambiter.guiflash to handle case when it's missing
- Small cleanup

### v1.10.0

- Added modernized equipment support from 1.19 CT (backwards compatible)
- Changed paths where mod related assets stored inside package

### v1.9.0

- Minor changes and fixes

### v1.8.6

- Fixed a bug when in case of missing or impossibility of getting optional device info in one of slots next slots didn't read

### v1.8.5

- Updated dependency gambiter.guiflash to 0.5.1
- Minor code changes

### v1.8.4

- Fixed a bug when vehicle had basic trophy equipment and the type icon was missing

### v1.8.3

- Config path has changed and now it's located on `mods/kurzdor/battleEquipment` path
- Fixed bug when mod was working in "Steel Hunter" mode

### v1.8.1

- Dependency gambiter.guiflash updated to 0.4.4
- Minor improvements

### v1.7.2

- Fixed panel position reset in battle
- Minor fixes

### v1.7.2

- Fixed panel position in battle saving
- Fixed minor issues

### v1.7.1

- Fixed a crash when field modifcation was leveled up for alternate equipment setup but not for optional devices and directives(thx @Scharfhobel с Korean Random)

### v1.7.0

- Added mode when modifcation only visible by pressing and holding Alt button (`"mode": "alt"` in config)
- Added hotkey to reset modification position in battle to default one
- Configuration file is moved and now located in `mods/configs/battleEquipment`
- Refactoring

### v1.6.0

- Added hotkey Ctrl + H to hide mod in battle
- Added small margins between optional devices slots (thx @pe3pa for idea)

### v1.5.0

- Fixed a bug when second preset is used and player doesn't have any battle boosters in any presets
