# CHANGELOG

### 1.18.0

- Added support for new Arcade night mode maps
- Added Ukranian localization
- Added better handling of clients in future per type and realm
- Minor changes in language getter
- Cleanup after previous game modes

### 1.17.0

- Added support for new Frontline map - Fata Morgana
- Updated support for new Steel Hunter branch
- Cleanup after Cosmic Event
- Minor code cleanup

### v1.16.1

- Hotfix for Cosmic Event
- Fixed wrong vehicle name in Cosmic Event
- Fixed issue when long vehicle name was used instead of short

### v1.16.0

- Added Cosmic Event support (WG only)

### v1.15.0

- Added Winback/Warm-up gamemode support
- Added support for new maps in Recon Mission
- Minor changes

### v1.14.0

- Refactor code to new standards and move to built-in WG helpers instead of self-written where possible
- Cleanup

### v1.13.0

- Added support for new map "Oyster Bay"
- Remove localizations for old tutorial battles removed in 1.20

### v1.12.0

- Cleanup old winter maps from NY events

### v1.11.0

- Enhanced support for Arcade: Cabinet mode

### v1.10.0

- Removed HW22 mode assets
- Better reconnecting support
- Revert way of getting vehicle info in battle
- Small codestyle changes

### v1.9.0

- Added support for battle result in Discord status
- Added better support for respawn mechanic (now it will deny any activity update if battle hasn't started yet)
- Cleanup

### v1.8.1

- Fix for time elapsed in events (previously done for Mirny-13 event)

### v1.8.0

- Added support for "Pumpkin Bash" event
- Cleanup from previous events

### v1.7.0

- Enhanced error handling when connection is lost (due to Discord client close and etc.)
- Small changes done in l10n
- Small refactor and cleanup done to code

### v1.6.0

- Global mod refactoring
- Added support for "Onslaught" mode in 1.18.1 with backwards compatibility in 1.18
- Added support for "The Waffentrager: Legacy" mode
- Fixed a bug when status didn't have vehicle name in battle start (awaiting players status)
- Enhanced error handling if mod can't connect or send data to Discord RPC
- In case of missing battle type in supported list the "Special battle" battle type icon will be used

### v1.5.2

- Added pre-support for new map in 1.18 - Outpost
- Minor cleanup from previous changes

### v1.5.1

- Added support for new gamemode "Arcade"

### v1.5.0

- Added pre-support for new gamemode "Fun Random"
- Minor improvements

### v1.4.1

- Fixed hangar infinite loading during loading

### v1.4.0

- Now forcing english or russian text locale in Discord status if neither of this languages are installed in client. Before this mod received localizations from game client - in case when Polish locale was installed in client then in status we could see both English and Polish locales in Discord status. Now it's fixed.
- Current vehicle status now shows short vehicle name
- When Discord client is missing or not launched mod better handles errors from RPC module
- Minor improvements

### v1.3.0

- Added support for new event "Art of Strategy"
- Fixed bug when wrong battle type icon was shown in status
- Changed main icon in Discord status
- Minor fixes

### v1.2.1

- Fixed spam in logs
- Small improvements

### v1.2.0

- Initial public release