# CHANGELOG

### 1.3.0

- Added sorting to the installed vehicles list for required equipment to pick from (currently sorted by nation, type, level and name in ascending order)

### 1.2.0

- Added ability to quickly demount ANY equipment to save it later for auto return (auto return doesn't work for deluxe and enhanced equipment) (original idea: panikaxa, enhancements: poliroid)
- Added ability to one-click demount ALL equipment from vehicle in carousel context menu
- **WARNING: BOTH FEATURES MAY ASK YOU TO SPEND CURRENCY (BONDS or SCRAP) IF YOU ARE TRYING TO DEMOUNT NON SUBCRIPTION-SUPPORTED EQUIPMENT WHEN DIRECTLY TRY TO DEMOUNT ALL EQUIPMENT OR SINGLE ONE FROM OTHER VEHICLE USING RIGHT MOUSE BUTTON IN TANK SETUP**
- Enhanced system messages with detailed information about what mod did or what happened
- Fixed issue with cache saving on game exit
- Fixed auto return toggle logic, now it will remove any saved data about devices instead of keeping unsynchronized (possibly) devices state in cache
- Fixed cases when equipment layout wouldn't update when same equipment in slot was installed in other setup
- Removed logic that automatically disabled auto return when WoT Plus subscription was cancelled or not active due to cancellation. This should also fix some issues when saved devices were desynchronized
- Refactored codebase

### 1.1.6

- Minor fix for renamed attribute

### 1.1.5

- Fixed accidentally removed critical line

### 1.1.4

- Fixed issue where wrong cache path was used

### 1.1.3

- Minor update

### 1.1.2

- Localization implementation update

### 1.1.1

- Removed obsolete info logs on mod start

### 1.1.0

- Migrate localization system from JSON to YAML

### 1.0.4

- Sync shared codebase

### 1.0.3

- Fixed broken hooks due to New Year 2024 patch

### 1.0.2

- Added German localization - (c) OldSkool aka @deadhat
- Fixed IndexError or hanged 'Completing the operation' process when trying to get merged layout
- Minor changes for equipment setup index swap method 

### 1.0.1

- Added Polish translation - (c) Aslain

### 1.0.0

- Initial release

