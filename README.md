🍁 Super Canadian
An 8-bit, top-down adventure where you roam the Great White North, gear up your
character at five very Canadian shops, and earn the title of Super Canadian.
Built as a one-file browser game — no build step, no dependencies, no install.
Just open it and play.

What it is
A retro, Zelda-style overworld rendered with chunky pixel art and a chiptune
soundtrack. You start by creating a character, then walk the map entering
buildings to collect a piece of gear from each. As you grab items, they appear
on your live paperdoll. Collect the full set and the win screen rolls.
How to play

Press Space (or tap) on the title screen.
Create your Canadian — type a name and pick a skin and hair color from a
32-color palette. A live preview shows your character as you choose.
Roam the overworld and walk into a building's door to enter.
Inside each shop, walk over the glowing item to grab it.
Step on the EXIT mat to return to the map, then on to the next shop.
Collect all 5 pieces of gear to become SUPER CANADIAN and roll the credits.

The gear
BuildingItemSlotHockey ShopHockey StickLeft handLumber Co.Flannel ShirtChestRCMP HQMountie HatHeadHospitalWrit of Free HealthcareRight handPet StoreDrake-Fan OwlShoulder companion
Controls
ActionKeyboard / MouseTouchMoveArrow keys / WASDOn-screen D-padStart / continueSpace or EnterTapGrab an itemWalk over itWalk over itToggle soundM, or the SOUND buttonTap the SOUND buttonRestart (on end)RTap
Features

Overworld + five interiors — a single hand-built map with trees, water,
paths, and five themed shops you can enter and exit.
Live paperdoll — your character gears up in real time, with a 5-slot
checklist and gear counter.
Character creator — custom name plus a 32-swatch palette for skin and hair
(natural tones, neons, and pastels — go wild), with a live avatar preview.
8-bit "O Canada" — a looping chiptune of the anthem's opening strain
(square-wave melody over a triangle bassline), with a sound toggle.
Hidden game-over — idle too long and... well, you'll find out. 🇺🇸
Mobile friendly — responsive canvas with an on-screen D-pad on touch devices.
Self-contained — everything (art, sound, logic) lives in one HTML file.

Running it
No server or build required.
bash# Just open the file in any modern browser:
open super-canadian.html        # macOS
start super-canadian.html       # Windows
xdg-open super-canadian.html    # Linux
Or drag the file onto a browser tab. To share it, host the single file anywhere
that serves static pages (GitHub Pages, Netlify, etc.).
GitHub Pages (optional)

Put super-canadian.html in your repo (rename to index.html if you want it
served at the root).
In Settings → Pages, set the source to your default branch.
Visit the published URL and play.

Tech

HTML5 Canvas for all rendering (pixel art drawn programmatically).
Web Audio API for sound effects and the chiptune music — no audio files.
Vanilla JavaScript — zero libraries, zero build tooling.
Press Start 2P webfont (loaded from Google Fonts, with a monospace
fallback so it still works offline).

Project structure
super-canadian.html   # the entire game (markup, styles, and game code)
README.md             # this file
Credits

Game design & code: Casey Flinn
Music: O Canada — composed by Calixa Lavallée (1880), public domain.
Font: Press Start 2P by CodeMan38 (SIL Open Font License).

License
© 2026 Casey Flinn. All rights reserved.

Swap this section for an open-source license (e.g. MIT) if you'd like others
to reuse the code.
