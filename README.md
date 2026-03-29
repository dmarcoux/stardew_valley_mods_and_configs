Mods and their configs when playing Stardew Valley.

# Setup

## Arch Linux

Whenever a mod/config is changed/updated, it happens on this device. Changes are manually pushed
to this Git repository.

1. [Install SMAPI](https://stardewvalleywiki.com/Modding:Installing_SMAPI_on_Linux).
2. Install `stardrop-bin` package from AUR.
3. Start [Stardrop](https://github.com/Floogen/Stardrop) and add my Nexus Mods API key for Stardrop (it's in 1Password).
4. Clone this Git repostiory.
5. Symlink mods from this Git repository to Stardew Valley's directory:

```bash
ln -s "$(pwd)/Stardrop Installed Mods" ~/.steam/steam/steamapps/common/Stardew\ Valley/Mods/Stardrop\ Installed\ Mods
```

## Steam Deck

1. [Install SMAPI](https://stardewvalleywiki.com/Modding:Installing_SMAPI_on_Steam_Deck).
2. Download files from this repository as a ZIP archive.
3. Extract files from ZIP archive into Stardew Valley's directory.
4. For updates -> Delete all mods. Download and extract ZIP archive again.

# Stardrop Settings

**SMAPI Path**

```bash
/home/dany/.steam/steam/steamapps/common/Stardew Valley
```

**Mod Folder Path**

```bash
/home/dany/.steam/steam/steamapps/common/Stardew Valley/Mods
```

**Stardrop Mod Installed Path**

```bash
/home/dany/.steam/steam/steamapps/common/Stardew Valley/Mods/Stardrop Installed Mods
```

# Mods

Each mod has to be manually downloaded, then added to Stardrop. After, it can be updated within Stardrop.

| Name                                                                          | Description                                                                                          |
| ----------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| [Automate](https://www.nexusmods.com/stardewvalley/mods/1063)                 | Automate crafting machines, fruit trees, and more by connecting them to chests.                      |
| [AutomaticGates](https://www.nexusmods.com/stardewvalley/mods/3109)           | Open and close gates automatically. Only for players, not animals.                                   |
| [Billboard Anywhere](https://www.nexusmods.com/stardewvalley/mods/492)        | View the billboard from anywhere.                                                                    |
| [Chests Anywhere](https://www.nexusmods.com/stardewvalley/mods/518)           | Access your chests from anywhere. It can be restricted, like not usable when in mines.               |
| [Data Layers](https://www.nexusmods.com/stardewvalley/mods/1691)              | Overlay the world with visual data like accessibility, bee/Junimo/scarecrow/sprinkler coverage, etc. |
| [DisplayEnergy](https://www.nexusmods.com/stardewvalley/mods/10662)           | Permanently display the player's current and max energy. Supports split-screen.                      |
| [Experience Bars](https://www.nexusmods.com/stardewvalley/mods/509)           | Show experience bars for your skills.                                                                |
| [Fast Animations](https://www.nexusmods.com/stardewvalley/mods/1089)          | Speed up many animations in-game (configurable).                                                     |
| [Generic Mod Config Menu](https://www.nexusmods.com/stardewvalley/mods/5098)  | Add in-game UI to configure other mods (which support it)                                            |
| [Lookup Anything](https://www.nexusmods.com/stardewvalley/mods/541)           | Read information about anything under your cursor.                                                   |
| [Loved Labels Redux](https://www.nexusmods.com/stardewvalley/mods/8880)       | Quickly see if an animal was petted or not today.                                                    |
| [NPC Map Locations](https://www.nexusmods.com/stardewvalley/mods/239)         | Show NPCs on the map.                                                                                |
| [Pony Weight Loss Program](https://www.nexusmods.com/stardewvalley/mods/1232) | Allow horses to pass through a single tile opening.                                                  |
| [Self Serve](https://www.nexusmods.com/stardewvalley/mods/20985)              | Do not wait for NPCs to be at their shop to use their services.                                      |
| [Simple Crop Label](https://www.nexusmods.com/stardewvalley/mods/314)         | Hover your cursor on a crop to see what it is.                                                       |
| [Skip Intro](https://www.nexusmods.com/stardewvalley/mods/533)                | Skip the game introduction.                                                                          |
