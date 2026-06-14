# Owen's Neon Abyss Mod Menu

<p align="center">
  <strong>A polished single-player mod menu for Neon Abyss.</strong><br>
  Gameplay tools, resource utilities, experimental spawners, weapon helpers, and developer diagnostics built for offline PC play.
</p>

<p align="center">
  <img alt="Game" src="https://img.shields.io/badge/Game-Neon%20Abyss-7c3aed?style=for-the-badge">
  <img alt="Version" src="https://img.shields.io/badge/Version-1.0.0-16a34a?style=for-the-badge">
  <img alt="Platform" src="https://img.shields.io/badge/Platform-Windows-64748b?style=for-the-badge">
  <img alt="Mode" src="https://img.shields.io/badge/Use-Single%20Player%20Only-f97316?style=for-the-badge">
</p>

<p align="center">
  <a href="../../releases/latest"><strong>Download Latest Release</strong></a>
  ·
  <a href="#installation">Installation</a>
  ·
  <a href="#features">Features</a>
  ·
  <a href="#screenshots">Screenshots</a>
  ·
  <a href="#disclaimer">Disclaimer</a>
</p>

---

## Overview

**Owen's Neon Abyss Mod Menu** is an offline mod menu for the PC version of **Neon Abyss**. It is designed for players who want extra sandbox-style control in single-player runs and for developers who want to inspect how different gameplay systems behave at runtime.

The project focuses on practical tools such as resource editing, room utilities, gameplay modifiers, item/chest spawning experiments, weapon-related helpers, debug logging, and runtime browsers.

> This project is intended for **offline, single-player, educational, and personal use only**.

---

## Project status

| Category | Status |
| --- | --- |
| Public release | `1.0.0` |
| Game version target | PC / Steam build |
| Platform | Windows |
| Development state | Active development |
| Intended use | Offline single-player |
| Loader package | Included with release ZIP |

Some systems are experimental and may change between versions. Weapon tools, item spawning, and reflection-based utilities are especially likely to evolve as the project improves.

---

## Features

### Gameplay tools

- Kill all enemies in the current room.
- Toggle weak enemies.
- Apply gameplay modifiers during a run.
- Use room-focused tools for testing and experimentation.
- Access quality-of-life options for single-player gameplay.

### Room controls

- Open room doors.
- Close room doors.
- Trigger room interaction utilities.
- Use exploration and testing helpers.

### Currency and resources

- Add gold.
- Add keys.
- Add crystals.
- Use resource modification utilities.
- Test toggleable currency-related behavior.

### Item and chest tools

- Spawn items.
- Spawn chests.
- Spawn pickups.
- Test prototype spawner systems.
- Experiment with weapon bundle spawning.

### Weapon systems

- Gun core support.
- Gun graph support.
- Launcher support.
- Gun part support.
- Runtime weapon modification experiments.
- Weapon testing utilities.

### Developer utilities

- Runtime dumpers.
- PowerUp browser.
- Weapon browser.
- Reflection helpers.
- Debug logging.
- Developer-focused inspection tools.

---

## Screenshots

### Main menu

![Main Menu](attachments/main_menu.png)

### Item spawner

![Item Spawner](attachments/spawner.png)

### Weapon tools

![Weapon Tools](attachments/weapon_tools.png)

### Gameplay tools

![Gameplay Tools](attachments/gameplay.png)

---

## Installation

### Requirements

- **Neon Abyss** on PC.
- Steam version recommended.
- Windows.
- A clean game install is recommended before adding the mod package.

### Install steps

1. Go to the [latest release](../../releases/latest).
2. Download the release ZIP.
3. Extract the ZIP into your **Neon Abyss** installation folder.
4. Keep the included folder structure exactly as provided.
5. Launch the game normally.
6. Open the menu using the configured hotkey.

### Example install layout

```text
Neon Abyss/
├── Mods/
├── plugins/
├── config/
├── [included loader files]
├── [included dependency files]
└── Neon Abyss.exe
```

> The release ZIP is packaged with the required loader files and dependencies. For the cleanest install, copy the full release package instead of mixing files from older builds.

---

## Recommended setup

For the most stable experience:

- Back up your save data before testing new releases.
- Install on the Steam version of Neon Abyss.
- Avoid mixing old mod files with new releases.
- Use the latest release ZIP from this repository.
- Read the release notes before updating.

---

## Compatibility

This mod menu is designed for:

| Target | Supported |
| --- | --- |
| Neon Abyss PC | Yes |
| Steam version | Recommended |
| Offline single-player | Yes |
| Multiplayer / online use | Not supported |
| Future game updates | Not guaranteed |

Game updates can change internal methods, fields, or runtime behavior. If a game update breaks the menu, wait for a compatible mod update instead of forcing older files into a newer build.

---

## Known limitations

- Some weapon systems are still experimental.
- Item spawning behavior may vary depending on room state and game progression.
- Reflection-based tools may change as better direct hooks are found.
- Future game updates may require compatibility fixes.
- Debug/developer tools are intended for testing and may expose raw game data.

---

## Safety and trust notes

This repository is meant to be transparent about what the project is and how it should be used.

- The mod is for offline single-player gameplay.
- The release package should only be downloaded from this repository.
- The project does not claim official support from the game developers or publisher.
- Backing up saves before modding is strongly recommended.
- Experimental tools may behave differently across game versions.

---

## Changelog

Version history and update notes are published on the [GitHub Releases page](../../releases).

---

## License

This project is distributed under the **Owen's Cheat Menu Custom Use License**.

Read the included [`LICENSE`](./LICENSE) file before using, modifying, or redistributing any part of this project.

---

## Disclaimer

This project is not affiliated with, endorsed by, sponsored by, or associated with **Veewo Games**, **Team17**, or any rights holders of **Neon Abyss**.

All game names, trademarks, assets, and intellectual property belong to their respective owners.

This project is provided for educational, personal, offline, and single-player modding purposes only.

---

## Credits

Created and maintained by **Owen**.

Built using reverse engineering, runtime reflection, mod-loader research, and custom tooling for educational single-player modding.

Special thanks to the broader game modding community and the developers of the tools that make PC modding possible.
