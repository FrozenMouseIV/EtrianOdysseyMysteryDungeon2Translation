# EtrianMysteryDungeon2Translation
A tool to translate Etrian Mystery Dungeon 2

## Guide to use
Extract the romfs folder of the release in a modded 3DS or an emulator with mod support.

## Instructions
* Install Python 3.12
* Run main.py or translate.py

## Guide to make a mod
* You need a legal copy of Etrian Mystery Dungeon 2.
* Dump the RomFS
* Use main.py to max export the folder of "message"
* Edit the csv files with a compatible editor.
* Put a copy of the original .bin files in a folder with the edited .csv
* Use main.py to max import the csv files to the .bin
* Load the mod with a modded 3DS or an emulator with the path "romfs/message/*.bin".


## Credits
Based in the work from Evan Dixon (https://github.com/evandixon/SkyEditor.ROMEditor)