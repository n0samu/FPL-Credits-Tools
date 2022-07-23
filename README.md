# FPL Credits Tools
Tools for working with [Flashpoint Launcher](https://github.com/flashpointproject/launcher) [Credits files](https://github.com/FlashpointProject/launcher_DiscordCredits) (`credits.json`).

## csvExport.py
Export credits to a CSV spreadsheet, including each contributor's Discord ID, username, and description.
Usage: `python csvExport.py credits.json credits.csv`

## csvImport.py
Import contributors' descriptions and preferred names from a CSV spreadsheet into an existing credits file.
Usage: `python csvImport.py credits.json credits.csv`

## createProfile.py
Manually add a contributor profile to the credits file. Useful for adding contributors who aren't in the Discord server.
Usage: `python createProfile.py credits.json name role1,role2`
