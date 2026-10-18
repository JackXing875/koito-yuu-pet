# Koito Yuu Pet

**English** | [简体中文](README.zh-CN.md)

Unofficial fan-made animation assets inspired by Yuu Koito from *Bloom Into You* (终将成为你 / やがて君になる). The character has peach-colored twin tails, golden-brown eyes, and a relaxed, cheerful expression, with clear silhouettes and readable expressions at small sizes.

![Waving](previews/waving.gif)
![Jumping](previews/idle-jump-idle.gif)
![Looking around](previews/look-around.gif)

## What's included

- A transparent sprite sheet: `assets/spritesheet.png`
- 9 animation states: idle, running right, running left, waving, jumping, failed, waiting, working, and review
- 16 gaze directions; 73 active frames in total
- A human-readable layout description in `layout.json` and animated GIF previews

The artwork was created with AI assistance, followed by frame-by-frame adjustments, alignment, transparency processing, and animation checks. No manga pages, anime screenshots, or official character illustrations are directly bundled or redistributed.

## Usage and compatibility

This repository provides animation assets. **It does not include a standalone desktop application, an installer, or account configuration.** Download the repository as a ZIP, then use the layout below to integrate the assets into a tool that supports custom sprite sheets.

This sprite sheet has been used with the ChatGPT Work v2 pet format. Import options and local desktop-pet formats may vary between clients; this repository does not currently provide a verified, universal one-command installation method. `layout.json` documents this repository's layout and is not the client-required `pet.json`; the two are not interchangeable. Do not use the full 11-row sheet as a legacy 9-row sheet.

### Sprite sheet layout

- Image: 1536 × 2288 pixels, RGBA PNG
- Grid: 8 columns × 11 rows
- Cell: 192 × 208 pixels
- Indices are zero-based, with the origin at the top-left corner
- Frame position: `x = column × 192`, `y = row × 208`

| Row | State | Active frames |
| --- | --- | --- |
| 0 | idle | 6 |
| 1 | running-right | 8 |
| 2 | running-left | 8 |
| 3 | waving | 4 |
| 4 | jumping | 5 |
| 5 | failed | 8 |
| 6 | waiting | 6 |
| 7 | running | 6 |
| 8 | review | 6 |
| 9 | First 8 gaze directions | 8 |
| 10 | Remaining 8 gaze directions | 8 |

Active frames start at column 0 in each row; unused cells are blank. Preview frame durations are recorded in `layout.json` as demonstration timings. Adjust them as needed when integrating the assets into another player.

## Character rights and licensing

Yuu Koito, the original characters from *Bloom Into You*, and the associated rights belong to Nio Nakatani and their respective rights holders. This is an unofficial fan project and is not affiliated with or endorsed by the original creator, publishers, animation studios, or OpenAI.

The original documentation in this repository is available under the [MIT License](LICENSE). **That license does not cover the character likeness, sprite sheet, GIFs, or other artwork, and does not grant any third-party character intellectual property rights.** The artwork is publicly available for viewing and study. Before further use, adaptation, redistribution, or commercial use, confirm that you have the necessary rights. Public availability does not constitute authorization from the original rights holders.

Official anime website: https://yagakimi.com/
