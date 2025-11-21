# Steam Deck PokeMMO Installer
Easily install PokeMMO on the Steam Deck

This script will allow you to easily install PokeMMO on the Steam Deck. It has been tested with SteamOS as well as Bazzite. It may also work on some other distros as well, though it probably won't be able to add the entry to Steam automatically on them.

# DISCLAIMER!
Install at your own risk. This is a fairly small, simple script, and should not harm your Steam Deck or PC in any way. That being said, shit happens, and I am not responsible for any damages, lost files, or other issues as a result of running this script.

# Installation
Simply download the script from [here](https://github.com/RHOPKINS13/SteamDeckPokeMMOInstaller/raw/refs/heads/main/Install_PokeMMO) and execute it. By default, it will download and install PokeMMO, along with Java, in a Games folder in your Home folder (on SteamOS this will typically be /home/deck/Games/PokeMMO). If you would like to install it somewhere else, feel free to edit the GAMEDIR variable in the script before running it.

Perhaps the easiest way of using this script is to just open up a terminal window and paste the following command:
```
wget https://github.com/RHOPKINS13/SteamDeckPokeMMOInstaller/raw/refs/heads/main/Install_PokeMMO -O - -q | bash
```

After the script is finished, you should have a new entry for PokeMMO.sh in your Steam Library. Feel free to rename it to simply PokeMMO, and I would recommend using [SteamGridDB](https://www.steamgriddb.com/) and [SGDBoop](https://www.steamgriddb.com/boop) in order to add game art to the library entry.

This script does **NOT** include the original Pokémon ROMs required to play the game. These must be **LEGALLY** dumped from your own legally purchased game cartridges. Please do not download pirated or "archived" ROMs of these 15+ year old games online, doing so is stealing from Nintendo's employee's children, you thoughtless brute!

# Why use this script? Why not use the flatpak available on Flathub instead?
Because sometimes when an update is released for PokeMMO, it can be a long time before the flatpak is updated. And lots of these updates tend to be for limited special events. The in-game updater doesn't work with the flatpak version, and this could leave you locked out of the game until the flatpak is updated, potentially missing time to enjoy a special event.

# Special Thanks
Special thanks goes to MajoraAKC from the PokeMMO forums. This script is based on the instructions that they posted [here](https://forums.pokemmo.com/index.php?/topic/149313-pokemmo-on-steamos-steam-deck/).
