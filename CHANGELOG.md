# Changelog

## Dev
### Changes
- Optionally added seed to permalink

## 1.0.5
### Options
- Added option to randomize dungeon entrances
- Added option to add rupoors into the junk item pool
- Added bulk and json options (for mass testing seeds)
### Changes
- Verify ISO checksum
- Item after LMF is given before exiting out of the back
- Treasure and Rupee dowsing are now obtainable after getting the Goddess Whitesword
- Shorten timeshift stone cutscenes
- Make it possible to not get pumpkin soup when doing lumpy pumpkin quest with spiral charge

## 1.0.4
### Options
- Add option to not generate a spoiler log
- Add option to start with Adventure pouch
- Changed Batreaux type to a specific max count
- Add option to skip imp 2
- Add permalink to options that can be specified on the command line
### Changes
- Songs give a hint if the item their trial has is potentially useful
- Eldin Entrance statue is always checked, prevents softlocks if BiTsaving out of an area without checking a statue first
### Bugfixes
- Fix Bomb Bag having a wrong text sometimes
- Fix potential softlock in the Skyview Beetle room
- Fix potential softlock when getting Spiral Charge in the Lumpy Pumpkin

## 1.0.3
### Options
- Change tablet rando option to select amount of tablets to randomize
- More types and Area types
### Changes
- Removed more text triggers and cutscenes
- Show a hash on the file select screen to make it easier to verify that everyone has the same seed
- Make Fun Fun island quest be startable immediately
- Always skip opening the inventory screen after treasures/bug/crystals
### Bugfixes
- Fix double increasing pouch counter
- Fixed a shared storyflag, causing levias to sometimes not give an item
- Fixed layers in Volcano Summit
- Fix some NPCs holding items in their hands

## 1.0.2
### Options
- add hero mode option
- add scrapper quests/peatrice types
- add permalink to share settings more easily
### Changes
- GUI only asks for ISO once
- progress bars for WIT and copy commands in GUI
- remove even more unnecessary text triggers
- all skippable cutscenes can always be skipped
- add logic for normal mode
- make pouch and pouch expansion progressive
- added spiral charge as an obtainable item
- levias item is randomized after calming him
- increase max loftwing speed from 80 to 350
- ancient sea chart now gives ship dowsing instead of immediately opening sandship
### Bugfixes
- fix required dungeon text not being readable with 4+ dungeons
- fix being able to buy a pouch upgrade from beetle before having the adventure pouch
- fix CS in Fire Sanctuary setting Sealed Grounds intro storyflag, causing sceneflags to not be set
- fix various doubled NPCs
- fix crash when recieving a sword upgrade in ghirahims room by delaying the visual sword upgrade until the next reload

## 1.0.2-rc1
### Options
- checks can be filtered by types
- add option to make sure unrequired dungeons are useless
- add option to skip skykeep
- make number of required dungeons dynamic
### Gameplay
- remove various unnecessary text triggers
### Misc
- gui
- custom title screen logo
### Bugfixes
- fix soil items being indefinetly reobtainable
- fix a softlock in fire sanctuary, related to the mogma near the second key

## 1.0.0
- Initial Randomization of Items
- Option to start with open/closed thunderhead
- Option to start with light pillars open/closed
- Option to start with/without a sword
- Option to specify a seed
