# 🍁 Super Canadian

An 8-bit, top-down adventure where you roam the Great White North, gear up your
character at five very Canadian shops, and earn the title of **Super Canadian**.

Built as a one-file browser game — no build step, no dependencies, no install.
Just open it and play.

**▶️ Play it:** https://caseyflinn.github.io/super-canadian/ &nbsp;·&nbsp;
**Repo:** https://github.com/caseyflinn/super-canadian

![Made with HTML5 Canvas](https://img.shields.io/badge/HTML5-Canvas-orange)
![Vanilla JS](https://img.shields.io/badge/JavaScript-vanilla-yellow)
![No build step](https://img.shields.io/badge/build-none-brightgreen)

---

## What it is

A retro, Zelda-style overworld rendered with chunky pixel art and a chiptune
soundtrack. You start by creating a character, then walk the map entering
buildings to collect a piece of gear from each. As you grab items, they appear
on your live paperdoll. Collect the full set and the win screen rolls.

## How to play

1. Press **Space** (or tap) on the title screen.
2. **Create your Canadian** — type a name and pick a skin and hair color from a
   32-color palette. A live preview shows your character as you choose.
3. Roam the overworld and **walk into a building's door** to enter.
4. Inside each shop, **walk over the glowing item** to grab it.
5. Step on the **EXIT** mat to return to the map, then on to the next shop.
6. Collect all **5** pieces of gear to become **SUPER CANADIAN** and roll the credits.

### The gear

| Building       | Item                       | Slot              |
| -------------- | -------------------------- | ----------------- |
| Hockey Shop    | Hockey Stick               | Left hand         |
| Lumber Co.     | Flannel Shirt              | Chest             |
| RCMP HQ        | Mountie Hat                | Head              |
| Hospital       | Writ of Free Healthcare    | Right hand        |
| Pet Store      | Drake-Fan Owl              | Shoulder companion|

## Controls

| Action            | Keyboard / Mouse        | Touch                 |
| ----------------- | ----------------------- | --------------------- |
| Move              | Arrow keys / WASD       | On-screen D-pad       |
| Start / continue  | Space or Enter          | Tap                   |
| Grab an item      | Walk over it            | Walk over it          |
| Toggle sound      | M, or the SOUND button  | Tap the SOUND button  |
| Restart (on end)  | R                       | Tap                   |

## Features

- **Overworld + five interiors** — a single hand-built map with trees, water,
  paths, and five themed shops you can enter and exit.
- **Live paperdoll** — your character gears up in real time, with a 5-slot
  checklist and gear counter.
- **Character creator** — custom name plus a 32-swatch palette for skin and hair
  (natural tones, neons, and pastels — go wild), with a live avatar preview.
- **8-bit "O Canada"** — a looping chiptune of the anthem's opening strain
  (square-wave melody over a triangle bassline), with a sound toggle.
- **Hidden game-over** — idle too long and... well, you'll find out. 🇺🇸
- **Mobile friendly** — responsive canvas with an on-screen D-pad on touch devices.
- **Self-contained** — everything (art, sound, logic) lives in one HTML file.

## Running it

No server or build required.

```bash
git clone https://github.com/caseyflinn/super-canadian.git
cd super-canadian

# Just open the file in any modern browser:
open super-canadian.html        # macOS
start super-canadian.html       # Windows
xdg-open super-canadian.html    # Linux
```

Or drag the file onto a browser tab. To share it, host the single file anywhere
that serves static pages (GitHub Pages, Netlify, etc.).

### GitHub Pages

This repo is set up to be served directly:

1. Make sure the game is reachable at the site root — either rename
   `super-canadian.html` to `index.html`, or keep both.
2. In **Settings → Pages**, set the source to your default branch (root).
3. Once it builds, play at **https://caseyflinn.github.io/super-canadian/**.

## Tech

- **HTML5 Canvas** for all rendering (pixel art drawn programmatically).
- **Web Audio API** for sound effects and the chiptune music — no audio files.
- **Vanilla JavaScript** — zero libraries, zero build tooling.
- **Press Start 2P** webfont (loaded from Google Fonts, with a monospace
  fallback so it still works offline).

## Project structure

```
super-canadian.html   # the entire game (markup, styles, and game code)
README.md             # this file
```

## Credits

- Game design & code: **Casey Flinn**
- Music: *O Canada* — composed by Calixa Lavallée (1880), public domain.
- Font: *Press Start 2P* by CodeMan38 (SIL Open Font License).

## License

© 2026 Casey Flinn. All rights reserved.

> Swap this section for an open-source license (e.g. MIT) if you'd like others
> to reuse the code.
