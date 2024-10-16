# CHANGELOG

### 1.7.2

- Localization implementation update

### 1.7.1

- Removed obsolete info logs on mod start

### 1.7.0

- Migrate localization system from JSON to YAML

### 1.6.3

- Hotfix for added localization

### 1.6.2

- Reworked localizations and tooltips in GUI settings configurator
- Sync up shared codebase and fixes

### 1.6.1

- Fixed wrong or missing localization in some cases

### 1.6.0

- Reworked file and config loader
- Renamed config folder to lowercase

### 1.5.3

- Minor changes

### 1.5.2

- Added Polish language - credits to Aslain
- Fix for forcing wrong language

### 1.5.0

- Updated way of loading locales for mod. They aren't located in mods/configs folder now
- Cleanup and minor changes

### 1.4.0

- Added new option lifetimeFragsCount that counts frags count from player vehicle statistics and frags count in battle
- fragsCount option now only counts frags in battle. To use old functionality of fragsCount use lifetimeFragsCount instead
- Code optimizations

### 1.3.1

- Fixed critical bug when vehicle without serial number style updated by mistake
- Small improvements

### 1.3.0

- When replace mode is set to random value mod will replace serials number for other vehicles
- Fixed MoE replace mode
- Small improvements

### 1.2.0

- Mod now updates serial number on different battle events, i.e. damage, assist, frag
- Added new replace modes: random number, damage, total assist, total damage (damage + all assist), total damage for MoE (damage + max assist from two - radio or track assist), battles count, average damage on vehicle and MoE value

### 1.1.0

- Fixed crash issues when graphics in battle was broken
- Fixed crash issues when getting frags count in hangar
- Frag count getter in hangar is enhanced and optimized
- Added note in mod configurator that frag counter is not updating in battle in real-time at the moment
- Mod now properly handles settings changes

### 1.0.0

- Initial public release
