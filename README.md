Mods and their configs when playing Stardew Valley.

# Setup on Arch Linux

Whenever a mod/config is changed/updated, it happens on this device. It pushes
the changes to this Git repository.

1. [Install SMAPI](https://stardewvalleywiki.com/Modding:Installing_SMAPI_on_Linux).
2. Install `stardrop-bin` package from AUR.
3. Start Stardrop and add my Nexus Mods API key for Stardrop (it's in 1Password).
4. Clone this Git repostiory.
5. Symlink mods from this Git repository to Stardew Valley's directory:

```bash
ln -s "$(pwd)/Stardrop Installed Mods" ~/.steam/steam/steamapps/common/Stardew\ Valley/Mods/Stardrop\ Installed\ Mods
```

# Setup on Steam Deck

1. [Install SMAPI](https://stardewvalleywiki.com/Modding:Installing_SMAPI_on_Steam_Deck).
2. Download files from this repository as a ZIP archive.
3. Extract files from ZIP archive into Stardew Valley's directory.
4. For updates -> Delete all mods. Download and extract ZIP archive again.
