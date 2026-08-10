# Eyes: The Horror Game — Door Removal Mod

A small difficulty mod for **Eyes: The Horror Game** that makes doors less reliable as hiding spots.

In the original game, certain doors can be used as safe hiding places because enemies cannot pass through them. This mod randomly removes some of these doors, making the game more unpredictable and difficult.

## Features

* Randomly removes doors that can normally be used as hiding spots.
* Configure the percentage of doors to remove.
* In-game configuration menu.
* BepInEx is already included in the release archive.
* The mod is **disabled by default**.

## Installation

1. Download the latest release archive.
2. Open the folder where **Eyes: The Horror Game** is installed.
3. Extract the contents of the archive directly into the game folder.
4. Start the game.

That's it.

You do **not** need to install BepInEx separately. It is already included with the mod.

> **Important:** Extract the archive into the game's main folder, where the game executable is located. Do not extract it into a separate subfolder.

## Configuration

The mod is configured directly in the game through the F6 settings menu.

1. Start **Eyes: The Horror Game**.
2. Press **F6** to open the mod settings menu.
3. Enable the mod using the **Enable** checkbox.
4. Set the desired door removal percentage.
5. Close the settings window and start playing.

### Important

The mod is **disabled by default**. You need to enable the **Enable** checkbox in the F6 menu before it will have any effect.

The mod's settings menu is only available outside of an active game. **You cannot open the mod settings menu while playing.**

The door removal percentage determines how many eligible doors can be removed.

For example:

* **0%** — no doors are removed.
* **25%** — approximately one quarter of eligible doors are removed.
* **50%** — approximately half of eligible doors are removed.
* **100%** — all eligible doors can be removed.

No configuration files need to be edited manually.

## Uninstallation

To completely remove the mod, delete the files that were added by the mod archive.

If you installed the mod on a clean game without BepInEx already installed, you can remove the BepInEx files and folders that were included with the mod.

If you already had BepInEx installed before using this mod, **do not remove your existing BepInEx installation**. In that case, only remove the files belonging to this mod.

If you are unsure which files belong to the mod, the safest option is to verify the game files through your game platform.

> **Do not delete your save files.**

## Compatibility

This mod is intended for **Eyes: The Horror Game**.

It may not be compatible with other mods that modify the same doors, levels, or game objects.

## Third-Party Software

This release includes **BepInEx 5.4.23.5** and other third-party components required by BepInEx.

See [`THIRD-PARTY-NOTICES.md`](THIRD-PARTY-NOTICES.md) for information about the included third-party software and their respective licenses.

## Credits

* **BepInEx** — modding framework.
* **Your Name** — Door Removal Mod.

## License

This mod is distributed under the license specified in [`LICENSE`](LICENSE).

Third-party software included with the release is distributed under its respective licenses. See [`THIRD-PARTY-NOTICES.md`](THIRD-PARTY-NOTICES.md).
