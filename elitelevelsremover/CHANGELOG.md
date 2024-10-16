# CHANGELOG

### 1.5.2

- Localization implementation update

### 1.5.1

- Removed obsolete info logs on mod start

### 1.5.0

- Migrate localization system from JSON to YAML

### 1.4.4

- Sync up shared codebase and fixes

### 1.4.3

- Added settings migration support
- Renamed `disablePrestigeRewardWindow` to `hidePrestigeRewardWindow` setting to keep consistency

### 1.4.2

- Added fool protection that prevents from modification loading on non-original clients
- Removed obsolete tooltips

### 1.4.1

- Added Polish translation - (c) Aslain

### 1.4.0

- Added localization and settings support
- Added ModsSettings API support
- Added English, Ukranian and Russian localizations
- Added ability to prevent showing elite levels (i.e. prestige) windows in future by forcing `viewed` flag even when player never viewed them after mod installation
- Now mod also prevents from showing Onboarding window (when entering hangar for a first time)
- Changing settings in ModsSettings now dynamically applies to some lobby settings (i.e. hangar widget)

### 1.3.0

- Added ability to remove elite levels (i.e. prestige) in elite vehicle acquire window (after researching all modules)
- Added ability to remove elite levels (i.e. prestige) in squad (i.e. platoon) window

### 1.2.0

- Added ability to remove elite levels (i.e. prestige) in battle results
- Added ability to disable elite levels (i.e. prestige) level up views 
- Added ability to remove elite levels (i.e. prestige) in system messages (first entry or level up)
- Minor rework to support future updates
- Initialized as separate mod

### 1.1.0

- Added ability to remove elite levels (i.e. prestige) widget in lobby
- Added ability to remove elite levels (i.e. prestige) widget in vehicle statistics in profile

### 1.0.0

- Initial release
- Mod removes elite levels (i.e. prestige) icons in battle (on battleLoading, player panels and fullStats on Tab key)
