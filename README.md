# ScamLoader

The mod loader for **Scam With Your Friends**. Install it once, then drop mods into its `Mods` folder.

- **MODS** button on the main menu and a **MODS** tab in Settings (also in the pause menu)
- See every mod's status: Loaded, Disabled, or Failed with the reason
- Switch mods on or off without deleting them, and change each mod's settings in one place
- A broken mod can't crash the game or the other mods
- Makes no network connections. Client-side only: friends don't need it

BepInEx and MelonLoader can't run on this game (its code is heavily stripped), so ScamLoader was built specifically for it.

## Download

**[Download ScamLoader 1.0.0](https://github.com/keiranross/ScamLoader/releases/download/v1.0.0/ScamLoader-1.0.0.zip)**, or see [Releases](https://github.com/keiranross/ScamLoader/releases).

SHA-256 of `ScamLoader-1.0.0.zip`: `c216380900dbc4074821a9717b1afca54ff66ba2558f5e7f8204ec90659755ed`

## Install

1. Open the game folder: in Steam, right-click **Scam With Your Friends** → **Manage** → **Browse local files**.
2. Copy everything from the zip into that folder: the `ScamLoader` folder, `winhttp.dll` and `doorstop_config.ini`. They must sit right next to `Scam With Your Friends.exe`, not inside another folder. If Windows asks to replace files, say **Yes**.
3. Start the game. A **MODS** button on the main menu means it worked.

## Add mods

Each mod goes in its own folder inside `<game folder>\ScamLoader\Mods\`. Every mod zip comes with its own `HOW TO INSTALL.txt`. Then restart the game.

Mods: [ClipCleaner](https://github.com/keiranross/ClipCleaner) (auto-delete recorded clips).

## Uninstall

Delete `winhttp.dll`, `doorstop_config.ini` and the `ScamLoader` folder from the game folder.

## Making your own mods

The download includes `ScamLoader\MODDING.md`: a ready-to-build project template, an example mod, the API, and the traps of this stripped game. You're free to release your own mods for ScamLoader, as long as they don't include ScamLoader's files.

## License

Copyright (c) 2026 KeiranR. All rights reserved. Personal use only: **please don't re-upload these files or send them to others** — link to this page instead. See [LICENSE](LICENSE).

The download includes [Unity Doorstop](https://github.com/NeighTools/UnityDoorstop) 4.5.0 by NeighTools (`winhttp.dll`, `doorstop_config.ini`), unmodified, under its own LGPL-2.1 license (included in the zip).
