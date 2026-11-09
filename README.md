# 🕷️ Mechanical Spider Terrarium · 机械蜘蛛生态缸

An interactive 3D terrarium in a single HTML file. A high-detail mechanical spider lives in a big glass tank — it wanders on its own, climbs rocks, climbs the glass, and walks wherever you click.

一个单文件的交互式 3D 生态缸：高精度机械蜘蛛住在大玻璃缸里，会自己溜达、爬石头、爬玻璃，你点哪里它就爬去哪里。

**▶ Live demo: https://chamiriko96326.github.io/mecha-spider-terrarium/**

## How to play · 玩法

- **Click the ground / 点地面** — the spider walks there 它会爬过去
- **Drag / 拖动** — orbit 旋转视角 · **Scroll or pinch / 滚轮或双指** — zoom 拉近
- **喷淋 (Mist)** — mist rolls in and droplets bead on the front glass 起雾 + 玻璃挂水珠
- **灯光 (Light)** — switch day / night 切换昼夜

## Tech · 技术

- Three.js (WebGL), procedural everything — the spider, habitat, textures and brushed-metal PBR are all generated in code; no external assets
- Two-bone IK tetrapod gait: feet plant on soil, rock slopes and glass; the body pitches and rolls with the terrain
- The whole thing ships as **one self-contained `index.html`** (~760 KB) — no build step, no dependencies, works offline. Just open it.

## Series · 系列

Episode 1 — the spider. More mechanical creatures in more tanks may follow.

第 1 弹：蜘蛛。后续可能有更多机械生物、更多的缸。
