## 5.9.1

#### 🚨 Bugfixes

 - Addresses legacy configuration descriptors

#### 👷 Internals

 - Upgrades Electron to v1.6.7
 - Upgrades `utils`
 - Upgrades dependencies

## 5.8.1

#### 🐰 Features

 - Adds updated system tray icons (Linux)
 - Adds custom branded title bar (macOS)
 - Optimizes title bar size (macOS)
 - Optimizes external url presentation

#### 🐰 Bugfixes

 - Fixes interface redraws on window resize
 - Fixes missing icons symbols

#### 🐰 Internals

 - Adds system tray icon sources
 - Adds runtime CSS injection module
 - Upgrades cross-platform build & deployment system

## 5.6.1

#### 🐰 Features

 - Adds platform-specific native system fonts
 - Reduced webview repaints on resize

#### 🐰 Bugfixes

 - Improves UI responsiveness

#### 🐰 Internals

 - Upgrades live reload infrastructure
 - Upgrades dependencies

## 5.6.0

#### 🍾 Features

 - Adds SMS Mirroring configuration option
 - Adds notification count icon badge

#### 🚨 Bugfixes

 - Fixes outgoing / pending SMS pushes (#43)

#### 👷 Internals

 - Upgrades dependencies

## 5.5.1

#### 🍾 Features

 - Increases frequency of auto update server checks
 - Adds persistency to icon badge count calculation (macOS) (#41)
 - Adds notification count icon badge
 - Adds configuration for badge counters
 - Adds updated menu icons

#### 🚨 Bugfixes

 - Fixes regression of ui enhancements application (#45)
 - Addresses `pending` item regression  (#43)
 - Improves live updates of badge count (macOS) (#41)
 - Fixes first-time login issue (#42)
 - Fixes global font size control (#34)
 - Fixes resetting of current location hash
 - Fixes file transfer description text
 - Fixes SMS description text

## 5.3.1

#### 🍾 Features

 - Adds 'always-on-top' window setting
 - Adds video thumbnails to YouTube urls
 - Adds display of release notes after automated updates
 - Adds improved connectivity user interface (#26)
 - Adds SMS mirroring (Android) (#24) (#38)
 - Adds rich application pushes (Android) (#38)
 - Adds interface font size control (#34)
 - Adds bootstrapping phase for global module (#33)
 - Adds automatic reconnect (#27)
 - Adds connectivity handling (#27)
 - Adds 'offline' state tray icon (#26)
 - Improves resource usage (#31)
 - Reduces download and application size by 1/3
 - Adds tag-based (`[]`) url title detection
 - Removes ARM package (Linux)

#### 🚨 Bugfixes

 - Fixes updater progress bar display (Windows)
 - Addressed websocket-related stability issues on pushbullet.com
 - Adds disk persistence of logging messages in verbose mode
 - Fixes path detection in global module bootstrap (#33)
 - Fixes configuration initialisation (#40)
 - Fixes window initialisation loop (#39)
 - Fixes title and body for API url pushes (#37)
 - Fixes global npm module usage (#33)
 - Fixes application name and title of mirrored pushes (#32)
 - Fixes guards to Pushbullet API hooks
 - Fixes an issue related to snooze mode

#### 📒 Documentation

 - Updated screenshots

#### 👷 Internals

 - Automates change log generation
 - Upgrades Electron to v1.6.6
 - Upgrades build system
 - Upgrades dependencies

## 4.3.0

#### 🍾 Features

 - Adds filtering of dismissed pushes to `self` (#29)
 - Adds dismissal of pushes to `self` through Pushbullet API (#29)
 - Adds network reconnect UI (#21)
 - Adds account logout UI (#21)
 - Adds coloured tray icon (Linux) (#20)
 - Adds `--debug` command line argument
 - Adds `nsis` package and assets (Windows)
 - Removes `squirrel` package (Windows)

#### 🚨 Bugfixes

 - Improves resource usage (#25)
 - Improves network performance (#25)
 - Improves i/o performance (#25)
 - Improves ui responsiveness (#23)
 - Fixes connection issue (#22)
 - Fixes auto update (Windows)
 - Fixes AppImage dependencies (Linux)
 - Fixes auto-launch

#### 📒 Documentation

 - Augments readme.md
 - Adds contributing.md
 - Adds issue template
 - Adds pull request template

#### 👷 Internals

 - Upgrades Electron to 1.6.2
 - Upgrades dependencies
 - Upgrades build & deployment system

## 3.9.0

#### 🍾 Features

 - Add [Slack](http:slack.com) notification sounds

#### 🚨 Bugfixes

 - Disable Clipboard syncing if no Pushbullet Pro account is available
 - Fix configuration persistency

#### 📒 Documentation

 - Augments readme.md
 - Adds contributing.md
 - Adds issue template
 - Adds pull request template

#### 👷 Internals

 - Dependencies upgrade

## 3.8.0

#### 🍾 Features

 - Improve connection stability
 - Enforce usage of passive graphics adapter

#### 🚨 Bugfixes

 - Fix configuration persistency

#### 👷 Internals

 - Dependencies upgrade

## 3.6.0

#### 🍾 Features

 - Improved connectivity detection
 - Further reduced CPU usage
 - Further decreased memory footprint

## 3.5.3

#### 🚨 Bugfixes

 - Settings persistence
 - Image asset lookup (fixes #17)

#### 👷 Internals

 - Dependencies upgrade

## 3.5.0

#### 🍾 Features

 - Integration of Pushbullet End-to-End encrypted messaging -  (🙏🏽 @andrebeat)
 - End-to-End encryption setup workflow
 - Dependency installation enforcement for Linux-based platforms

#### 🚨 Bugfixes

 - Many, many bugfixes and performance enhancements

#### 👷 Internals

 - Main & support components modularized
 - JSDoc coverage increased
 - Dependencies upgrade

## 3.3.0

#### 👷 Internals

 - Dependencies upgrade

## 3.2.1

#### 🍾 Features

 - #14

#### 👷 Internals

 - Dependencies upgrade

## 3.2.0

#### 🍾 Features

 - Native titlebars
 - Native translucent menu sidebars (macOS)

#### 🚨 Bugfixes

 - #13

#### 👷 Internals

 - Dependencies upgrade

## 3.1.0

#### 🍾 Features

 - Automatic deployment of latest versions to [https://sidneys.github.io/pb-for-desktop](https://sidneys.github.io/pb-for-desktop)

#### 🚨 Bugfixes

 - Fixes for auto updating
 - Multiple user interface fixes
 - Delivery of ghost pushes upon device usage

#### 📒 Documentation

 - Augments readme.md
 - Adds contributing.md
 - Adds issue template
 - Adds pull request template

#### 👷 Internals

 - Dependencies upgrade
 - Buildsystem upgrade

## 2.9.978

#### 🍾 Features

 - Additional tray Icons
 - Realtime connectivity monitoring

#### 👷 Internals

 - Electron 1.4.14
 - Dependencies upgrade

## 2.9.976

#### 🍾 Features

 - Automatic in-app updates (macOS)
 - Improved offline handling

#### 🚨 Bugfixes

 - Run as CLI module

#### 👷 Internals

 - Size optimisation (25%)
 - Electron 1.4.13
 - Dependencies upgrade
 - Buildsystem upgrade
