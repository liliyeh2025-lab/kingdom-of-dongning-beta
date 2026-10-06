# Third-party notices / 第三方授權聲明 / サードパーティ通知

《東寧王國 Kingdom of Dongning》v1.0.0 Beta uses the software, fonts, data and assets listed below.
Full license texts are in the [`licenses/`](licenses/) folder (also included in the game download).

本遊戲使用下列第三方軟體、字型、資料與素材；完整授權條文在 `licenses/` 資料夾（遊戲下載檔裡也有一份）。
本ゲームは以下のサードパーティ製ソフトウェア・フォント・データ・素材を使用しています。ライセンス全文は `licenses/` フォルダーにあります。

---

## Engine and runtime

### Godot Engine 4.7.2
- © 2014-present Godot Engine contributors; © 2007-2014 Juan Linietsky, Ariel Manzur. **MIT License.** https://godotengine.org/license
- Godot bundles third-party components (FreeType, ENet, Mbed TLS, HarfBuzz, ICU, libogg/libvorbis/libtheora, libwebp, libpng, zlib, Zstandard, Brotli, Jolt Physics, Basis Universal, and others), each under its own license.
  The complete list and license texts: [`licenses/Godot-LICENSE-and-COPYRIGHT.txt`](licenses/Godot-LICENSE-and-COPYRIGHT.txt).
- Portions of this software are copyright © The FreeType Project (www.freetype.org). All rights reserved.
- The Godot logo shown at startup is © 2017 Andrea Calabró, licensed under CC BY 4.0.

### .NET runtime 10.0
- © .NET Foundation and Contributors. **MIT License.**
  [`licenses/dotnet-LICENSE.txt`](licenses/dotnet-LICENSE.txt), [`licenses/dotnet-THIRD-PARTY-NOTICES.txt`](licenses/dotnet-THIRD-PARTY-NOTICES.txt).

### "Hash without Sine" (shader noise)
Used in the game's terrain, water, sky, vegetation and effect shaders.

```
MIT License
Copyright (c) 2014 David Hoskins.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
https://www.shadertoy.com/view/4djSRW

## Fonts

### Noto Sans CJK, Noto Serif CJK (思源黑體、思源宋體)
- Noto Sans CJK: © 2014-2021 Adobe. Noto Serif CJK: © 2017-2023 Adobe. Noto is a trademark of Google Inc.
- **SIL Open Font License 1.1.** Subsets of TC/SC/JP Regular and Bold faces. https://github.com/notofonts/noto-cjk
- [`licenses/NotoCJK-OFL-1.1.txt`](licenses/NotoCJK-OFL-1.1.txt)

## Data

### OpenCC dictionaries (Chinese conversion)
- Dictionary data from [OpenCC](https://github.com/BYVoid/OpenCC), via [opencc-python-reimplemented](https://github.com/yichen0831/opencc-python) 0.1.7. **Apache License 2.0.**
- Modified: several dictionaries were merged into one table with additional overrides for game terms.
- [`licenses/OpenCC-Apache-2.0.txt`](licenses/OpenCC-Apache-2.0.txt), [`licenses/OpenCC-NOTICE.txt`](licenses/OpenCC-NOTICE.txt)

### ETOPO1 Global Relief Model (terrain elevation)
- NOAA National Centers for Environmental Information. Public domain (U.S. Government work).
- Amante, C. and B.W. Eakins, 2009. ETOPO1 1 Arc-Minute Global Relief Model: Procedures, Data Sources and Analysis. NOAA Technical Memorandum NESDIS NGDC-24. doi:10.7289/V5C8276M

## Sound effects (all CC0 1.0 — no attribution required; credited with thanks)

| Use in game | Author | Source |
|---|---|---|
| Interface clicks, error, end turn | Kenney | [Interface Sounds](https://kenney.nl/assets/interface-sounds), [RPG Audio](https://kenney.nl/assets/rpg-audio) |
| Arrow impacts, arrow shots | JoeDinesSound | Freesound [534940](https://freesound.org/s/534940/), [534941](https://freesound.org/s/534941/), [534942](https://freesound.org/s/534942/), [534943](https://freesound.org/s/534943/), [534944](https://freesound.org/s/534944/), [534945](https://freesound.org/s/534945/), [534946](https://freesound.org/s/534946/) |
| Arrow impact | Twisted_Euphoria | Freesound [205938](https://freesound.org/s/205938/) |
| Arrow loose | saturdaysoundguy | Freesound [394185](https://freesound.org/s/394185/) |
| Cannon | adeluc4, qubodup | Freesound [125348](https://freesound.org/s/125348/), [187767](https://freesound.org/s/187767/) |
| Naval cannon, splash, ship destroyed | Thimras | OpenGameArt [Battle at sea](https://opengameart.org/content/battle-at-sea) |
| Distant cannon | Andykub, Walking.With.Microphones | Freesound [415293](https://freesound.org/s/415293/), [634629](https://freesound.org/s/634629/) |
| Sword hits | qubodup | Freesound [442769](https://freesound.org/s/442769/) |
| Melee | DeadVDI | Freesound [376646](https://freesound.org/s/376646/) |
| Chinese drum (dagu) | sazanami12 | Freesound [856549](https://freesound.org/s/856549/), [856550](https://freesound.org/s/856550/), [856551](https://freesound.org/s/856551/) |
| Wooden ship break | Kodack | Freesound [257752](https://freesound.org/s/257752/) |
| Gong | airtaxi | Freesound [76886](https://freesound.org/s/76886/) |
| Musket shots and volleys | mlsulli, bruno.auzet, fennelliott | Freesound [234869](https://freesound.org/s/234869/), [538795](https://freesound.org/s/538795/), [347647](https://freesound.org/s/347647/) |
| Ship at sea | PimFeijen | Freesound [195193](https://freesound.org/s/195193/) |
| Shore waves | YevgVerh | Freesound [827530](https://freesound.org/s/827530/) |
| Big water splash | qubodup | Freesound [442773](https://freesound.org/s/442773/) |
| War cries | joelcarrsound | Freesound [521830](https://freesound.org/s/521830/), [521831](https://freesound.org/s/521831/), [521832](https://freesound.org/s/521832/) |
| Charge | florianreichelt | Freesound [563011](https://freesound.org/s/563011/) |

## Textures and 3D models (all CC0 1.0 — no attribution required; credited with thanks)

| Asset | Author(s) | Use in game |
|---|---|---|
| ambientCG [Grass004](https://ambientcg.com/view?id=Grass004), [Ground037](https://ambientcg.com/view?id=Ground037) | Lennart Demes (ambientCG) | Battlefield ground |
| Poly Haven [damp_sand](https://polyhaven.com/a/damp_sand) | eye-candy.xyz | Battlefield ground |
| Poly Haven [brown_mud_03](https://polyhaven.com/a/brown_mud_03), [dry_ground_01](https://polyhaven.com/a/dry_ground_01), [forrest_ground_01](https://polyhaven.com/a/forrest_ground_01) | Rob Tuytel | Battlefield ground |
| Poly Haven [red_laterite_soil_stones](https://polyhaven.com/a/red_laterite_soil_stones) | Amal Kumar | Battlefield ground |
| Poly Haven [granite_wall](https://polyhaven.com/a/granite_wall), [coral_fort_wall_01](https://polyhaven.com/a/coral_fort_wall_01) | Dimitrios Savva, Rico Cilliers | City walls |
| Poly Haven [dutch_ship_large_01](https://polyhaven.com/a/dutch_ship_large_01) | James Ray Cock, Rico Cilliers, Nicolò Zubbini | Dutch ships |
| Poly Haven [cannon_01](https://polyhaven.com/a/cannon_01) | James Ray Cock, Yann Kervran | Artillery |
| Poly Haven [black_painted_planks](https://polyhaven.com/a/black_painted_planks), [distressed_painted_planks](https://polyhaven.com/a/distressed_painted_planks), [brown_planks_03](https://polyhaven.com/a/brown_planks_03), [dark_wooden_planks](https://polyhaven.com/a/dark_wooden_planks) | Dimitrios Savva, Rob Tuytel, Amal Kumar | Chinese junk hulls |

## Public domain
- "Tiger head" (OpenClipart, via [freesvg.org](https://freesvg.org/tiger-head)) — recolored for the rattan-shield emblem.

## Animation
- Character animations from **Mixamo** (Adobe), used under Adobe's terms for Mixamo.

## Made with AI tools / 使用 AI 工具製作 / AI ツールの使用について

This game was developed by liliyeh, an independent developer, with extensive help from AI tools. In the spirit of transparency:

| Content | Tool |
|---|---|
| Game code, shaders, data, English and Japanese translations | Claude (Anthropic), AI coding assistant |
| Portraits, unit cards, title art, map and ground textures, foliage cards, opening-cinematic artwork | Krea 2 (Krea Community License), run locally in ComfyUI |
| Opening-cinematic animation (AI-generated video) | LTX-2.3 (Lightricks, LTX-2 Community License), run locally in ComfyUI, animated from the Krea 2 woodblock keyframes; target end frames edited by liliyeh with OpenAI ChatGPT (GPT image editing) |
| 3D unit, horse and junk models | Tripo AI; horse rig with Meshy |
| City and fortress models | Blender scripts written with GPT (OpenAI) |
| Music | Google Gemini |

本遊戲由獨立開發者 liliyeh 製作，大量使用 AI 工具（程式與翻譯：Claude；圖像：Krea 2；開場動畫：LTX-2.3（AI 生成的影片，尾幀用 OpenAI ChatGPT 修圖）；3D 模型：Tripo、Meshy；城池模型：GPT 撰寫的 Blender 腳本；配樂：Google Gemini）。
本作は個人開発者 liliyeh が AI ツールを多く活用して制作しました（コードと翻訳：Claude、画像：Krea 2、オープニングアニメーション：LTX-2.3（AI 生成の映像、終端フレームは OpenAI ChatGPT で編集）、3D モデル：Tripo・Meshy、城郭モデル：GPT が書いた Blender スクリプト、音楽：Google Gemini）。
