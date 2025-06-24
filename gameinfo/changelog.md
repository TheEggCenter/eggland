# Changelog

All notable changes to the project, [Egg Land](https://github.com/katakatakombe/eggland/blob/main/gameinfo/gamelinks.md)., will be documented in this file.
This changelog does not refer to the actual GitHub repository.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.8.2] - 2025-06-02

### Added

- Added support for forced updates

### Changed

- Changed the update notice background

- Rewrote update detection

- Adjusted descriptions in the Cloud Shop for the Milk, Metal Egg, and Quikswap

### Fixed

- Fixed animations on the Lightgen and Nightgen

## [0.1.8.1] - 2025-05-22

### Added

- (BETA) Added interpolation support (hold "I" until you reach the title screen on startup)

- Added 1 new tip

- Added scrolling clouds to the clicker and kitchen

- Implemented custom item positions to save data

### Changed

- Made the rain more transparent

- Lightgen and Nightgen now both work during Twilight, but they produce 200 eggs

- Changed the Lightgen and the Nightgen Cloud Shop text to include their new functionality

- Updated the Milk, Metal Egg, Egg Generator, Butter, Tomato, Loaf, Carrot, and Clackclock Cloud Shop descriptions

- The Cloud Shop page you were last on now persists after you exit the menu

- Changed the logo sprite in the title menu to have a thicker outline

### Removed

- Removed the Butter's spawning and despawning sounds

- Removed unused sprites, code, and music

- Removed 5 tips, making the tip count 12

### Fixed

- Fixed Jacko not appearing on the submenu screen properly

- Fixed issues with the "functionality" text on the Multiglove in the Cloud Shop

- Fixed the Quikswap being able to be clicked outside of the kitchen

### Security

- Added fallbacks for incorrectly loaded save data and unwritten slots

## [0.1.8] - 2025-05-09

### Added

- Added twilight to the day in the clicker

- Added 5 new items to the Cloud Shop (Lightgen, Clackclock, Devious Panel, Nightgen, Quikswap)

- Added "Night Creatures", creatures that show up at night and steal your eggs if not clicked away

- Added 9 new tips

- Added rain sfx that plays whenever it rains

- (BETA) Added barebones controller support (untested on non-dualshock 4 controllers)

- Added new playtester, Ikeo, to the credits menu

- Added the ability to go forward when changing the game volume in the pause menu by right clicking

- Added new sound button sounds in pause menu

- Added the pause menu's sound button to the title menu

- Added "hover" images to the purchase and "I feel lucky" buttons in the Cloud Shop

- Added the submenu infobox to the pause menu

- Added scrolling support to most menus

### Changed

- Renamed "redpizzalion" to "RedLikesGarlicBread" in the credits menu

- Changed the pause menu song to be a different cut

- Renamed "Jacko Catacomb" to "kataKombe" in the credits menu

- Replaced the scrolling text with a project version number in the submenu

- Swapped heyothefunnier with RedLikesGarlicBread in the credits menu

- Changed info on KataKombe and RedLikesGarlicBread's credit pages

- Rewrote the Metal Egg shop description

- Rewrote the Nultiglove shop description

- Rewrote how the pause menu displays it's options

- Changed how text is displayed in certain menus (like the submenu) to no longer use images

- Changed sound effects in various menus to match the newer sfx

- Changed the rain animation

- Rain can now happen during any time of day

- Changed the submenu intro sound and song

- Updated the nighttime theme

- Updated the daytime theme

- Updated the titlemenu theme

- Redrew RedLikesGarlicBread's credits image

- Changed kataKombe's credits image

- Ported the Cloud Shop to the new shopmenu framework

- Changed the github repo that the update detection system pulls version numbers from

- Nerfed the Multiglove (4 eggs and tomatoes every 5 seconds)

- Changed the pause menu layout

- Changed how "pausing" the game works (you no longer collect currencies and most functions are paused)

### Removed

- Removed the crashbox's active sound

- Removed ConveyorBelt support

### Fixed

- Fixed the logo in title screen being rotated slightly

- Fixed the day counter going up when restarting the game

- Various preformance fixes

## [0.1.7.1] - 2025-03-04

### Added

- Integrated update detection that lets you know when theres a new update available

- Added tips that display every 2 minutes

- Added a "day counter" that updates every full day cycle

### Changed

- Changed the pause menu song

- Changed the cloud Shop UI scaling

- Reverted all internal holiday changes from 0.1.6

### Deprecated

- Deprecated ConveyorBelt support

### Fixed

- Fixed a grammar error in the submenu's infobox

- Fixed various preformance and lag issues

- Fixed kitchen lights not properly loading

### Security

- Fixed issues with save data incorrectly loading

## [0.1.7] - 2025-02-18

### Added

- Added page support to the submenu's infobox

- Added ConveyorBelt support

- Added proper backgrounds to the clicker

- Added a return to title prompt when Z is held down in the clicker

### Changed

- Redrew every art asset used

- Remade the day, night, and titlemenu songs

- Changed UI sounds on buttons and other UI elements

### Removed

- Removed Red's Outfit Shop

- Reverted all visual holiday changes from 0.1.6

- Removed 5 items (Yolkbread Man, Berrycane, Ornamegg, Eggnog, Sorrowglobe)

### Fixed

- Various preformance fixes

### Security

- Fixed save data issues

## [0.1.6] - 2024-12-24

### Added

- Added christmas lights to the clicker

- Added 5 new items (Yolkbread Man, Berrycane, Ornamegg, Eggnog, Sorrowglobe)

- Added 10 ornaments and an ornament quest

- Added a boss fight for when all ornaments are collected

- Added an outfit shop with four outfits for purchase (Santa's Hat Present Lid, Snow Shoveler, Tangled Lights)

### Changed

- Changed the rain to be snow

- Redrew the kitchen

- Changed the day and night songs

- Changed the day and night backgrounds

### Fixed

- Various bug fixes

## [0.1.5.1] - 2024-11-29

### Changed

- Animated the startup loading screen

### Fixed

- Fixed eggs not displaying when buying items

- Fixed raining during the day

## [0.1.5] - 2024-11-28

### Added

- Added a credits menu

- Added a submenu before the clicker

- Added logo animations to the title menu

- Added local storage saving

- Added autosaving every 5 minutes

- Added the ability to erase your data

- Added a new titlemenu secret

### Changed

- Changed the currency visuals

- Changed currency-per-click visuals

- Increased rarity of titlemenu secrets

- Changed the egg and tomato sprites

### Removed

- Removed the Network Booster

- Removed startup tutorial

- Removed save codes

- Removed test sprites

### Fixed

- Cleaned up loose variables and code for optimization

- Merged some sprites together for optimization

- Fixed issues with the kitchen assets acting strange when clicked

- Fixed issues with the rain functionality

- Fixed the audio being heavily compressed

- Fixed the Crashbox not working after being bought

- Fixed an issue how your currency would go offscreen and break if it exceeded 1 sextillion

- Fixed audio being too quiet

- Fixed bugs and issues with the new audio system

## [0.1.4.1] - 2024-11-2

### Added

- Added sounds to the Network Booster

### Changed

- Made the network boost show up when the Network Booster is repaired

### Fixed

- Fixed an issue with the Carrot's shop price being incorrect

- Fixed issues with the save button's visibility

- Fixed issues with the savecode system

- Fixed Jacko being slow on the titlemenu

## [0.1.4] - 2024-10-31

### Added

- Added saving and loading via save codes

- Added three new Cloud Shop items (Sheet O' Paper, Multiglove, Crashbox)

- Added a day and night cycle, with rain occasionally happening during night

- Added a egg booster that syncs across the cloud

- Added a 100 tomato conversion limit to the grater

### Changed

- Redid the layout of the title menu

- Added Jacko to the title menu

- Redid all art and music assets

- Redid the kitchen's layout

### Removed

- Removed old assets

### Fixed

- Fixed issues with items not functioning properly

## [0.1.3] - 2023-??-??

### Fixed

- Fixed Demo Egg functionality

- Various preformance fixes

## [0.1.2] - 2023-1-??

### Added

- Added particles when clicking the egg

- Added an easter egg when typing "R-E-D"

- Added a cheese grater that allows you to convert all of your tomatoes into eggs

- Added a display the version number

- Added two new items (Carrot and Loaf)

### Fixed

- Fixed issues with item speed

- Various preformance fixes