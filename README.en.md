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

> **Press F1 at any time in the game for the full controls** (one page each for the campaign map, land battles and naval battles; also in the Esc menu during battles).
> If this is your first time, start with **"Tutorial"** on the main menu (about 10 minutes: selecting, deploying, starting the battle, ambushes). A new campaign also has a guide for the first steps.
> The control hints at the bottom left of a battle can be collapsed or expanded with a click.

### Campaign map (turn-based)

- Turn: Enter ends the turn · F1 interface tour and help · Esc menu (save, load, settings)
- Select: left-click an army, fleet or city · Tab cycles through units that can still act · Esc deselects
- Orders: with an army selected, right-click the map = march (the gold area is reachable this turn; red = battle)
  - Right-click your own fleet = embark; with the army aboard, right-click adjacent land = land (a contested landing if enemies are there)
  - Right-click an adjacent enemy city = assault (auto-resolve only); stay beside the city = besiege
- At Sea: with a fleet selected, right-click the sea = sail; sailing against the monsoon costs double; ships passing close to an enemy fortress come under cannon fire
  - The Lu'ermen Shoals can only be crossed with a channel chart (He Bin's Chart arrives on turn 1)
- Supply Lines: armies outside your territory must link back to one of your cities (within 5 hexes by land, or by sea without being blocked by enemy fleets), or they lose men every turn
  - Struggle for the Strait: before marching out, use “Load Rations” in the army panel; when the supply line is cut, the army eats its rations first. Spare silver in the treasury can also Reward the Troops (morale) or Fortify the Walls (settlement panel)
- Siege: port cities need a fleet blockading the sea, or enemy ships will resupply them by sea; once the food runs out, the garrison collapses and surrenders
- Overview: F2 Overview · F3 Economy · F4 Diplomacy · F5 Characters · F6 Spies · F7 Institutions · F8 Cities (tabs for systems the scenario lacks are absent; press the same key again to close) · Ctrl+S quicksave, Ctrl+L quickload
- Dispatches: bottom-left tabs Military, Naval, Diplomacy, Domestic, Characters, Spies, Events (the number on a tab = new messages this turn); click an entry ending in “›” to move the camera to where it happened
- Map: M or the bottom-left buttons switch overlays: Factions, Diplomacy (relations with you), Silver, Grain (yield per season under each city name), Turmoil (sieges, revolts, blockades, Coastal Evacuation Edict)
- Camera: WASD / mouse at screen edge to pan · Q/E rotate · mouse wheel zoom · Home jumps to the selected unit (your leader if none) · End faces north · Ctrl+F9–F12 save a view, F9–F12 recall · hold Space for diplomacy · Ctrl+T toggles nameplates

### Land battles (real time)

- Selection: left-click a unit or its banner · left-drag to box-select · Shift adds to selection · Ctrl+A selects all · click the unit cards at the bottom
- Groups: Ctrl+0–9 puts the selected units in a group · 0–9 selects that group (Shift adds) · press twice = camera jumps there
- Orders: right-click ground = move · right-click an enemy = attack · right-drag = draw a battle line (sets width and facing) · double right-click = run
  - H halt · Y hold fire (shoot only at targets you order; hidden troops reveal themselves when they fire, so hold fire until the enemy walks in) · Backspace also halts (withdraw with the button) · Deployment: place your troops in the yellow area, Enter to begin
- Cursor: arrow with red crossed swords = right-click attacks this target · pointing hand = left-click to select · thick arrow = scrolling in that direction
- Fatigue: running, fleeing and melee are tiring; halting to rest recovers (walking barely tires) · Tired: slower walking and running, poorer melee accuracy, lower morale · Exhausted: cannot run, a double right-click only walks
  - Heavily armoured troops such as Iron Men tire fast, cavalry slowly, and rain tires everyone more; unit cards show "Tired" or "Exhausted". Walk toward distant enemies and save stamina for the final dash
- Camera: WASD/arrow keys or mouse at screen edge to pan (Shift = faster) · Q/E rotate · Z/X tilt · hold the middle button (wheel) and drag = rotate and tilt
  - Wheel to zoom (fully in = ground-level view) · V or double-click a unit = follow · Home returns to your lines · click the minimap to jump there
- Time: Space pauses (you can still give orders while paused) · +/− changes speed
- Banners: green bar = strength, yellow bar = morale (relative to the start of battle); a unit routs when its morale runs out, and a general nearby steadies morale
- Tips: gunmen fear melee and attacks on the flank or rear; Rattan Shieldmen stop shot from the front; units standing still in scrub are hidden; in rain matchlocks often misfire
- Terrain: hold Alt to show scrub that can hide troops (yellow-green outline; shown automatically during deployment and while drawing a line)
- Markers: selected missile units show their firing arc (they hit only this frontal wedge: guns ±50°, bows ±70°, cannon ±35°; range depends on height, longer downhill and from walls), and a red dashed line marks the current target · R toggles
- General: the medallion at bottom left is your general; click to select the general's unit, double-click to follow. The round buttons on each side are the general's abilities, two uses each per battle, with a cooldown after use —
  - Rally (G, left button): routing units near the general re-form at once · Inspire (F, right button): units near the general get a big morale boost for a while · unusable once the general routs or falls (enemy generals use them too)
- Unit abilities: with a unit selected, use the round buttons left of "Halt". Fire button = archers switch to Fire Arrows (heavy morale shock, burns rattan shields, slow reload; not in rain) · Roll button = Rattan Shieldmen make a Rolling Shield Charge (fast, hard to hit with shot or arrows) · Cut button = Iron Men take the Horse-Cutter Stance (stops charges, cuts down cavalry)
- Firing arcs: idle missile units won't turn on their own. If enemies get round your flank or rear, right-drag a new line to turn them, or right-click an enemy to order an attack (the unit turns to face its target)
  - Selected units show their march route (turning points around walls and through gates; pale green = march, red = attack) · T toggles
- Landing: select units still aboard (cards at the bottom), then right-click near a landing point or press its button on the panel. Boats are limited; the rest queue for the next trip. Once the tide ebbs, units still aboard cannot land
- Naval guns: press "Bombard", then left-click a target (right-click cancels). Shells scatter widely and can hit your own troops. Red circles mark where shells are about to land
- Siege: emplaced batteries cannot move and can only be given targets. Storm in through the breach and hold the objective inside the walls to win

### Naval battles (real time)

- Select: left-click a ship or its banner · left-drag to box-select · Shift to add · Ctrl+A to select all · click a ship card at the bottom
- Groups: Ctrl+0–9 puts the selected ships in a group · 0–9 selects that group (Shift to add) · press twice to jump the camera there
- Orders: right-click the sea = sail (course shown as a yellow line) · right-click an enemy ship = engage (red line)
- Formations: buttons below or C to pick Free / Line Abreast / Line Ahead / Wedge. With two or more ships selected, right-click the sea = sail in formation (all keep pace with the slowest ship, then form up and face forward on arrival)
  - Right-click an enemy ship = engage in formation (the squadron closes together and all charge once the nearest ship reaches the edge of range) · right-drag = draw the line (Line Abreast and Wedge: the drag sets the frontage; Line Ahead: ships form a single file along the drag)
  - F bombard at range · G close and board · H/Backspace stop · withdraw with the button
- Cursor: arrow with red crossed swords = right-click will engage · pointing hand = left-click to select · thick arrow = scrolling that way
- Can't move? Ships locked in a boarding action are lashed together by grapples until the hand-to-hand fight is decided or the enemy cuts the grapples; a grounded ship must wait for the tide to rise; sailing upwind, ships tack in zigzags, so slow progress is normal
- Wind and tide: the compass at top right shows the wind; ships cannot sail straight into it. With a ship selected, red water = she would run aground at the current tide
- Camera: WASD/arrow keys or mouse at screen edge to pan (Shift = faster) · Q/E rotate · Z/X tilt · hold the middle button (wheel) and drag = rotate and tilt
  - K cinematic camera (skims the sea, slowly circling the thickest fighting, all UI hidden; K or Esc to return)
  - Wheel to zoom (fully in = deck view) · V or double-click a ship = follow · Home returns to the fleet · click the minimap to jump there
- Banners: green = hull, blue = crew, yellow = morale; when crew or morale runs out, the ship strikes her colours
- Time: Space to pause (you can still give orders while paused) · +/− to change speed

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
