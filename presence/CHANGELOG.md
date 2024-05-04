# CHANGELOG

### 3.1.2

- Added support for event lobbies in future
- Now client should raise exception when we can't find Discord client
- Properly handle lobby leave in event lobbies

### 3.1.1

- Implemented event lobby logic
- Fixed issue with cosmic vehicle getter

### 3.1.0

- Added queue support for Cosmic Event on WG
- Improved Cosmic vehicle getter

### 3.0.0

- Added support for Cosmic Event on WG
- Refactored RPC client async way

### 2.8.0

- Added future support for Historical Battles
- Refactored lobby logic

### 2.7.0

- Added support for 'Last Moment' view (i.e. KillCam) for WG client
- Enhanced vehicleDescriptor getter
- Updated localizations

### 2.6.1

- Rework error handling

### 2.6.0

- Added support for Steel Hunter: Shamrock Showdown

### 2.5.0

- Added support for Cosmic Event back
- Cleanup after NY event

### 2.4.0

- Added Hungarian language support (Sanci_Rex with some my changes for new features)
- Added battle loading status support
- Added arena leaving status support
- Updated localizations
- Fixed issue when sometimes inLobby status with arena preview image would fire because of queueing handling rework
- Refactored some parts of controller

### 2.3.0

- Refactored vehicle, queue and arena data providers
- Minor refactor

### 2.2.0

- Added German localization (Flachzange)
- Added better support for Arcade Cabinet
- Added support for Lesta Arcade Cabinet submodes
- Fixed issues with battle queue entering and leaving when player is in squad
- Cleanup

### 2.1.0

- Added enhanced elapsed time handler in specific battle types
- Fixed bug when in arena waiting time would show elapsed time instead of remaining to start the battle
- Fixed bug when elapsed time didn't save when transitioning from battle to killed status in specific battle types (Halloween)
- Minor code refactor with moving code to separate utillity methods

### 2.0.1

- Use elapsed time in status when playing Halloween (WG) battle

### 2.0.0

- Added split support for two clients
- Added TweakVar system (WIP)
- Added Polish localization (Aslain)
- Added localization overrides
- Moved localizations to external YAML files
- Reworked client type getter
- Reworked localization system
- Refactored parts of code to built-in similar helper methods from game
- Fixed obsolete extra l10n getter call in replays
- Fixed bug with Versus AI mode small image in status
- Minor refactor in controller module

### 1.21.0

- Added support Waffentrager event (Wargaming only)

### 1.20.0

- Added support for new map - Stalingrad (Lesta only)
- Support for the `Story Mode` and `Versus AI (Lesta only)` game modes

### 1.19.0

- Support for the Overwhelming Fire Event
- Cleanup after Night battles

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

### 1.16.1

- Hotfix for Cosmic Event
- Fixed wrong vehicle name in Cosmic Event
- Fixed issue when long vehicle name was used instead of short

### 1.16.0

- Added Cosmic Event support (WG only)

### 1.15.0

- Added Winback/Warm-up gamemode support
- Added support for new maps in Recon Mission
- Minor changes

### 1.14.0

- Refactor code to new standards and move to built-in WG helpers instead of self-written where possible
- Cleanup

### 1.13.0

- Added support for new map "Oyster Bay"
- Remove localizations for old tutorial battles removed in 1.20

### 1.12.0

- Cleanup old winter maps from NY events

### 1.11.0

- Enhanced support for Arcade: Cabinet mode

### 1.10.0

- Removed HW22 mode assets
- Better reconnecting support
- Revert way of getting vehicle info in battle
- Small codestyle changes

### 1.9.0

- Added support for battle result in Discord status
- Added better support for respawn mechanic (now it will deny any activity update if battle hasn't started yet)
- Cleanup

### 1.8.1

- Fix for time elapsed in events (previously done for Mirny-13 event)

### 1.8.0

- Added support for "Pumpkin Bash" event
- Cleanup from previous events

### 1.7.0

- Enhanced error handling when connection is lost (due to Discord client close and etc.)
- Small changes done in l10n
- Small refactor and cleanup done to code

### 1.6.0

- Global mod refactoring
- Added support for "Onslaught" mode in 1.18.1 with backwards compatibility in 1.18
- Added support for "The Waffentrager: Legacy" mode
- Fixed a bug when status didn't have vehicle name in battle start (awaiting players status)
- Enhanced error handling if mod can't connect or send data to Discord RPC
- In case of missing battle type in supported list the "Special battle" battle type icon will be used

### 1.5.2

- Added pre-support for new map in 1.18 - Outpost
- Minor cleanup from previous changes

### 1.5.1

- Added support for new gamemode "Arcade"

### 1.5.0

- Added pre-support for new gamemode "Fun Random"
- Minor improvements

### 1.4.1

- Fixed hangar infinite loading during loading

### 1.4.0

- Now forcing english or russian text locale in Discord status if neither of this languages are installed in client. Before this mod received localizations from game client - in case when Polish locale was installed in client then in status we could see both English and Polish locales in Discord status. Now it's fixed.
- Current vehicle status now shows short vehicle name
- When Discord client is missing or not launched mod better handles errors from RPC module
- Minor improvements

### 1.3.0

- Added support for new event "Art of Strategy"
- Fixed bug when wrong battle type icon was shown in status
- Changed main icon in Discord status
- Minor fixes

### 1.2.1

- Fixed spam in logs
- Small improvements

### 1.2.0

- Initial public release

### 1.1.0

- Added Battle Royale, Training, Front Line, Clan Wars, Grand Battle, Training, Fortifications support to Discord RPC (added icon)
- Fixed battle countdown in arena prebattle in Event

### 1.0.0

- First public release