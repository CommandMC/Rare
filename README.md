# Rare
## A frontend for legendary, the open source Epic Games Launcher alternative

Rare is currently considered beta software and in no way feature-complete. You **will** run into issues, so make backups first!

### Disclaimer
I'm in no way experienced in Python or PyQt5 (this project originally was a "Let's learn Python", then became a "Let's learn Qt"), so the code will be messy. If you have suggestions to improve it, please issue a pull request or message me on Discord (CommandMC#7964).

### Requirements
 - requests, pillow and pyqt5 installed via PyPI
 - Legendary installed somewhere in your $PATH
 
 ### Usage
 When you run Rare, it'll check if you're currently logged in and walk you through logging in if you aren't.
 Once you're logged in, it will pull game covers from the "metadata" folder in Legedary's config folder, join logo and background together and then display a list of games you have in your account. Installed games will appear in full color while not installed ones will appear in black and white.
 Left-clicking a game will install / launch it, right clicking it will bring up the settings for that game.
