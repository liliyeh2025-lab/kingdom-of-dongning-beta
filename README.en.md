<p align="center"><img src="docs/icon.png" width="96" alt="Kingdom of Dongning"></p>

<h1 align="center">Kingdom of Dongning　東寧王國</h1>

<p align="center"><b>1661 · The Strait and the Dynasties</b>　|　Public beta v1.0.0　|　Windows 64-bit</p>

<p align="center">
<a href="README.md">繁體中文</a> ·
<b>English</b> ·
<a href="README.ja.md">日本語</a>
</p>

---

In 1661, all that remained of the Ming realm was the sea. Koxinga led his fleet across the Black Ditch to take Taiwan from the Dutch East India Company —
and for the next thirty years, the Kingdom of Dongning struggled to survive between the monsoons, the Qing court, the Three Feudatories and the sea trade.

*Kingdom of Dongning* is a strategy game set in Ming-loyalist Taiwan (1661–1690): **a turn-based campaign map** combined with **real-time land and naval battles**.
On the map you move armies, build fleets, run trade and manage loyalty. When armies meet, you can auto-resolve the fight or take command yourself —
Rattan Shields, Iron Men, matchlock companies and fleets of Fujian junks.

> This is a **public beta**. The game can be played from start to finish, but balance, interface and translations are still being tuned, and there are certainly bugs.
> Please play it and tell us what you find — your reports decide what the next version fixes.

## Download and run

1. Download `KingdomOfDongning-1.0.0-beta-win64.zip` from [Releases](../../releases).
2. Extract it to any folder. **Do not run it from inside the zip.**
3. Run `KingdomOfDongning.exe`.

- There is no installer and nothing is written to the registry; to uninstall, delete the folder (saves are kept elsewhere, see "Saves and logs").
- The executable is not code-signed, so Windows may show "Windows protected your PC" the first time: click "More info" → "Run anyway".
- The first battle compiles shaders, so it may stutter for a few seconds; it runs smoothly after that.

## System requirements

| | Minimum (estimated) | Tested on |
|---|---|---|
| OS | Windows 10/11 64-bit | Windows 11 |
| Graphics | Dedicated GPU with Vulkan support (GTX 1060 class or better) | NVIDIA RTX 5060 Ti 16 GB |
| Memory | 8 GB | 48 GB |
| Storage | About 1 GB free (0.9 GB unpacked) | |

So far the game has **only been tested on one mid-to-high-end GPU**; performance on entry-level and integrated graphics is unknown.
If it runs poorly, lower 3D Resolution, Shadow Quality and Soldiers Shown per Unit in Settings, or turn off Battlefield Detail.
Reports with your GPU model and FPS are very welcome.

## What's in the game

- **Campaigns** (turn-based strategy map + real-time battles)
  - **The Eastern Expedition (1661–1662)**: short scenario. Play the Zheng or the Qing. Cross the strait, besiege Fort Zeelandia, and hold Xiamen and Kinmen.
  - **Struggle for the Strait (1661–1690)**: the main campaign. Play the Zheng, the Qing or the Dutch East India Company. The Coastal Evacuation Edict, the Five Merchants and overseas trade, Legitimacy and the dynastic choice, characters and succession, the Revolt of the Three Feudatories.
  - **All Under Heaven: Revolt of the Three Feudatories (1674–1690)**: the large map. Play the Qing, the Wu Zhou or the Zheng.
  - Three difficulty levels (Easy / Normal / Hard) and three history settings (Historical / Romance / Alternate).
- **Historical battles**: Lu'ermen Landing, Baxemboy, Battle of Taijiang, Fort Zeelandia and Battle of Penghu — five battles in historical order, each playable from either side, with challenges.
- **Custom battle**: build your own armies and choose a field battle, siege, landing or naval battle.
- **Tutorial**: about ten minutes to learn the camera, selection, formations, control groups, ambushes and attacking.
- Interface languages: Traditional Chinese, Simplified Chinese, English, Japanese (switch at the bottom right of the main menu).
  English and Japanese are translations of the Chinese original; corrections are welcome.

## Controls

| | Campaign map | Land / naval battle |
|---|---|---|
| Select | Left click | Left click, drag a box, Ctrl+A select all |
| Order | Right click (march, sail, land, assault) | Right click to move / attack, right-drag to draw a battle line, double right click = run |
| Camera | WASD, mouse wheel, middle-drag | WASD, Q/E rotate, Z/X tilt, mouse wheel, middle-drag |
| Other | Enter end turn, Tab next unit, F2–F8 overview | Space pause (you can give orders while paused), +/− game speed |
| Help | F1 | F1 (full controls), Esc menu |

## Reporting problems

Open a new report in [Issues](../../issues) and pick the "Bug report" or "Suggestion" template.
**No programming knowledge needed** — "what I did, what I saw, what I expected" is already very helpful.

The most useful attachments:

1. **Version**: bottom right of the main menu (for example `v1.0.0 Beta`).
2. **Screenshot**: press `Win + Shift + S`.
3. **Log file**: `%APPDATA%\Godot\app_userdata\Dongning\logs\godot.log`
   (paste `%APPDATA%\Godot\app_userdata\Dongning\logs` into the File Explorer address bar and press Enter, then drag `godot.log` into the report).
4. For campaign problems, attach the **save**: the newest `.json` in `%APPDATA%\Godot\app_userdata\Dongning\campaign\`.

## Saves and logs

| | Location |
|---|---|
| Campaign saves and autosaves | `%APPDATA%\Godot\app_userdata\Dongning\campaign\` |
| Settings | `%APPDATA%\Godot\app_userdata\Dongning\settings.json` |
| Logs | `%APPDATA%\Godot\app_userdata\Dongning\logs\` |

Saves are **not guaranteed to work across beta versions**. If an old save cannot be loaded after an update, please start a new game
(the game shows "Failed to load" and does not damage your other saves).

## Known issues

See the [release notes](../../releases) of each version.

## License

- This repository only contains **the game build and documentation**; the game's source code is not public.
- The beta is free to download, play, record and stream (please do!). Please do not modify and redistribute it, or sell it. See [LICENSE.md](LICENSE.md).
- Third-party software, fonts and assets used by the game, and their licenses, are listed in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

## About the history

The game is built on real history (people, events, cities, ships and troop types are based on sources, cited in the scenario data),
but numbers and some details are estimates and trade-offs made for gameplay, and the "Romance" and "Alternate" settings are not history at all.
If you spot a historical error, please report it too.

---

<p align="center">© 2026 liliyeh</p>
