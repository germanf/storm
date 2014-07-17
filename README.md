# Cuevana Share

Cuevana app to watch movies with friends!

## Current version: V 0.1

- 2 people syncing exchanging keys from PeerJS
- Support for Windows / Linux / Mac(not tested)
- Added voice capabilities
- Sync Pause/Play on movie and Re-sync time when resume
- Enable/Disable voice chat using keyboard key 'V'

##RoadMap:

###V 0.2

- Send data of movie instead of manually choosing each
- Sync movie time every some time
- Add notifications when somebody connected
- Load movie torrent from file

###V 0.3

- Improve start sync

###V 0.4

- Sign-in using facebook (openpeer)

###V 0.5

- Add video capabilities

###V 0.6

- Multiple people syncing

##Build/Run

#### Build

Use this to build the application executable.

`npm install`

`npm run build` will build for your current platform.

`npm run build-all` will build for all platforms.

#### Run

`npm start`

or find the nw executables in build/Cuevana/your-os/

#### Developers

`npm run compile` will compile less and update html references.

`npm run watcher` will automatically watch for file changes and compile when needed.

When the app is launched with `npm start`, it runs in `--debug` mode. Press `F11` to reload or `F12` to open Developers Tools (console).

## Comments

Inspired by Cuevana and Popcorn Time's use of peerflix module. Expanded on their idea.
