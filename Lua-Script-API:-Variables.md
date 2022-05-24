## Lua/Unique variables
### Note: Those are the only variables that can be changed by using `= true` or `= false` for now, you will have to use [setProperty()](https://github.com/ShadowMario/FNF-PsychEngine/wiki/Lua-Script-API:-Value-Setting-and-Getting-Functions#setpropertyvariablestring-valuedynamic) if you want to change the rest of them
* `luaDebugMode` - Enables debug mode, use `luaDebugMode = true` to enable it. Default value: `false`
* `luaDeprecatedWarnings` - Tells you if a function/variable is deprecated (shouldn't be used anymore), only works when Debug mode is on, use `luaDeprecatedWarnings = false` to disable it. Default value: `true`
* `inChartEditor` - Tells you if your script is running on Chart Editor's chart playtest.

____
## Song/Week Variables
* `curBpm` - Current BPM of the Song, shortcut to `getPropertyFromClass('Conductor', 'bpm')`
* `bpm` - Starting BPM of the Song, shortcut to `getProperty('SONG.bpm')`
* `scrollSpeed` - Starting Scroll speed of the Song, shortcut to `getProperty('SONG.speed')`
* `crochet` - Interval between Beat hits
* `stepCrochet` - Interval between Step hits
* `songLength` - Song duration in milliseconds
* `songName` - Shortcut to `getProperty('SONG.song')`
* `isStoryMode` - Shortcut to `getProperty('isStoryMode')`
* `difficulty` - Returns the difficulty ID (Easy = 0, Normal = 1, Hard = 2), Shortcut to `getProperty('storyDifficulty')`
* `weekRaw` - Returns the raw current week number. I doubt you will ever use this, but hey, just in case you do, it's here.
* `week` - Returns the properly formatted current week file name.

____
## Camera Variables
* `cameraX` - Shortcut to `getProperty('camFollowPos.x')`
* `cameraY` - Shortcut to `getProperty('camFollowPos.y')`

____
## Screen variables
* `screenWidth` -  Shortcut to `getPropertyFromClass('FlxG', width)`
* `screenHeight` -  Shortcut to `getPropertyFromClass('FlxG', heigth)`

____
## Gameplay Variables
* `startedCountdown` - Tells you if the countdown already started
* `seenCutscene` - Is set to `true` after `onCreate()` function, Shortcut to `getProperty('seenCutscene')`

* `curBeat` - Current beat number
* `curStep` - Current step number

* `score` - Current score, Shortcut to `getProperty('songScore')`
* `misses` - Current total number of notes missed, Shortcut to `getProperty('songMisses')`
* `ghostMisses` - Current number of Key press misses, Shortcut to `getProperty('ghostMisses')`
* `hits` - Current number of notes hit, Shortcut to `getProperty('songHits')`

* `rating` - Current rating percentage, goes from `0` to `1`. Shortcut to `getProperty('ratingPercent')`
* `ratingName` - Current rating's name. Shortcut to `getProperty('ratingString')`

* `inGameOver` - Player is Dead
* `mustHitSection` - Tells if the current section is a `Must Hit Section` (from Chart Editor)
* `altAnim` - Tells if the current section is a `Alt Animation`Section (from Chart Editor)
* `gfSection` - Tells if the current section is a `GF Section` (from Chart Editor)
* `botPlay` - Tells if Botplay is enabled. Shortcut to `getProperty('cpuControlled')`

____
## Strum/Receptor Variables
* `defaultPlayerStrumX0` - Player's default left arrow X
* `defaultPlayerStrumY0` - Player's default left arrow Y
* `defaultOpponentStrumX0` - Opponent's default left arrow X
* `defaultOpponentStrumY0` - Opponent's default left arrow Y
* `defaultPlayerStrumX1` - Player's default down arrow X
* `defaultPlayerStrumY1` - Player's default down arrow Y
* `defaultOpponentStrumX1` - Opponent's default down arrow X
* `defaultOpponentStrumY1` - Opponent's default down arrow Y
* `defaultPlayerStrumX2` - Player's default up arrow X
* `defaultPlayerStrumY2` - Player's default up arrow Y
* `defaultOpponentStrumX2` - Opponent's default up arrow X
* `defaultOpponentStrumY2` - Opponent's default up arrow Y
* `defaultPlayerStrumX3` - Player's default right arrow X
* `defaultPlayerStrumY3` - Player's default right arrow Y
* `defaultOpponentStrumX3` - Opponent's default right arrow X
* `defaultOpponentStrumY3` - Opponent's default right arrow Y

____
* `defaultBoyfriendX` -  Player's Default X position, defined by the Stage's JSON file.
* `defaultBoyfriendY` -  Player's Default Y position, defined by the Stage's JSON file.
* `defaultOpponentX` -  Opponent's Default X position, defined by the Stage's JSON file.
* `defaultOpponentY` -  Opponent's Default Y position, defined by the Stage's JSON file.
* `defaultGirlfriendX` - Girlfriend's Default X position, defined by the Stage's JSON file.
* `defaultGirlfriendY` - Girlfriend's Default Y position, defined by the Stage's JSON file.

____
## Preferences Variables
* `downscroll` - Downscroll is enabled. Shortcut to `getPropertyFromClass('ClientPrefs', 'downScroll')`
* `middlescroll` - Middlescroll is enabled. Shortcut to `getPropertyFromClass('ClientPrefs', 'middleScroll')`
* `framerate` - Current framerate limit. Shortcut to `getPropertyFromClass('ClientPrefs', 'framerate')`
* `ghostTapping` - Ghost tapping is enabled. Shortcut to `getPropertyFromClass('ClientPrefs', 'ghostTapping')`
* `hideHud` - "Hide HUD" is enabled. Shortcut to `getPropertyFromClass('ClientPrefs', 'hideHud')`
* `hideTime` - "Hide Song Length" is enabled. Shortcut to `getPropertyFromClass('ClientPrefs', 'hideTime')`
* `cameraZoomOnBeat` - Shortcut to `getPropertyFromClass('ClientPrefs', 'camZooms')`
* `flashingLights` - Shortcut to `getPropertyFromClass('ClientPrefs', 'flashing')`
* `noteOffset` - Represents the note delay in milliseconds (Goes from `0` to `500`). Shortcut to `getPropertyFromClass('ClientPrefs', 'noteOffset')`
* `lowQuality` - Shortcut to `getPropertyFromClass('ClientPrefs', 'lowQuality')`