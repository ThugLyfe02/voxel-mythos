# Voxel Mythos

**[Play now](https://thuglyfe02.github.io/voxel-mythos/)**

A living voxel sandbox (v2). One self-contained file, no install, and no internet needed to play solo. Worlds save in this browser automatically. v1 saves load in v2 unchanged (same storage keys).

## Play

Open the [live game](https://thuglyfe02.github.io/voxel-mythos/) in Chrome, Edge, Firefox, or Safari. To play from a local copy, open `index.html` (the same file as `voxel-sandbox.html`).

## First steps

Click the game view ("🖱 Click to play") to capture the mouse, then move the mouse to look around. Esc releases the mouse and pauses; click again to carry on.

## Controls — desktop

Most keys can be rebound in **Esc → Settings → Accessibility → Key bindings**.

### Looking / camera

- **Mouse** look around (after clicking the view; pointer lock)
- **No pointer lock?** drag with the right (or left) mouse button to look — switches on automatically
- **← / →** turn left / right (smooth; speed in Settings → Movement & camera)
- **PageUp / PageDown** look up / down
- **F5** camera view: first person → third person behind → third person front (also `/view`)
- **F9** free orbit camera
- **P** photo mode (1–6 filters, Enter snapshot, H hides UI)

### Moving

- **W A S D** move (diagonals are normalised — same speed in every direction)
- **Shift (hold)** sprint, ~1.6× speed with a FOV kick (also double-tap W; "Toggle sprint" option in Accessibility). Sprint also works on mounts. Shift descends while flying.
- **Space** jump / swim up / fly up
- **C** descend while flying
- Walking into a 1-block ledge steps up onto it smoothly (setting "Step-up onto ledges").

### Acting

- **Left click (hold)** mine / attack · **Right click** place · eat · use · talk · tame · ride
- **1–9 / wheel** hotbar · **0** cast your bound Light/Dark path power · **-** Crossroads / Light panel
- **E** inventory & crafting · **M** market · **F** talk · **T or /** chat & commands · **Q** cast spell · **G** map & factions
- **R** mount / dismount / land · **V** thermal vision · **X** weapon ability · **B** armory · **N** tech tree · **J** creature codex
- **O** party · **U** trophies · **Y** gallery · **H** airship camera · **L** spellbook · **I** journal · **Z** blueprints · **K** save now · **Esc** pause

## Controls — phones & tablets

On-screen controls appear automatically.

- Left thumb: virtual joystick to move. Right side: drag anywhere on the view to look around.
- 🏃 button toggles sprint · 🎥 button changes camera view · jump / mine / place / menu buttons on screen.
- Rotating the phone (portrait ↔ landscape) resizes the game correctly.

## Settings (Esc → Settings)

Mouse sensitivity, Invert Y, Toggle sprint (Accessibility), FOV, Quality: Auto / Low / Medium / High / Ultra.

🎮 **Movement & camera:** keyboard turn speed, arrow keys turn, head bob, double-tap W sprint, step-up onto ledges.

🌪 **World Chaos** slider 0–200 % (host-controlled in multiplayer, saved with the world): more mobs, faster cataclysms, better loot and smarter packs at higher values.

**Ultra** (desktop GPUs): real-time shadows, planar water reflections, hi-res textures, light shafts, depth of field and motion blur in photo mode. If the frame rate stays too low, the game switches itself back to High and tells you.

## Useful commands (T or /)

`/help` `/build castle of bricks glowing` `/daily` `/replay` `/ascend` `/home` `/sethome` `/host` `/players` `/view` `/chaos 0-200`

`/path [status|open|choose light|dark|cast N|trial|apex|step|legion|fuse|twilight|sim N]` `/magic` `/arts` `/way` `/bp`

`/weapon` `/enchant` `/armory` `/era` `/tech` `/codex` `/tame` `/pet` `/season` `/festival` `/storm` `/tornado` `/ship` `/gallery` `/cinema`

Creative only: `/dim ember|canopy|tidal|void|over` `/boss` `/give` `/time` `/weather` `/fly`

## What's new in v2

- Eras (Primal → Cosmic) with a tech tree
- 44 weapons across 6 eras with 35 enchantments · evolving bosses
- Seasons, festivals, weather fronts, tornadoes and cataclysms
- Farming, brewing and the dungeon vaults
- Airships · creature codex, companions and mounts
- Blueprints, workers and growing villages
- Wayfarer bands and their Pact
- Elemental magic schools, goblin warrens and the Forbidden Arts
- Achievements & trophies, accessibility options, Ultra graphics, World Chaos, third-person camera, smoother movement

### The Crossroads

Reach the Arcane era with a magic school at level 5 and a shrine rises nearby. Choose a road — forever:

- 🌑 **Dark:** Forbidden Arts I–VII, then Umbral Sovereignty (shadow-step, a Shade legion of 3, +40 % during eclipses).
- ☀ **Light** (rarer): needs 3 Radiant Deeds and an aurora or full-Lumen night (every 8th night). Tiers: Dawn Ward, Mending Light, Sun Lance, Sanctuary Dome, Halo of Many, Phoenix Rite, Dawnbringer Form, Solar Covenant — each earned through a trial (protect, heal, sacrifice, restore) at a Dawn Altar (4 gold, 2 lumen, 1 relic).

Sub-schools at tier IV, talents, a fusion spell, relics, oaths and pacts, hunters and inquisitors, an Apex boss and an ending. Twilight Penance (a long quest) resets your road — and keeps nothing. No power can hurt villagers.

## Saving

Autosave every 30 s, on dimension change, and when you close or hide the tab ("saved Ns ago" chip top-right).

**Esc → Worlds & backups:** 4 named world slots + the Daily slot, Export (.json backup file), Import, rename, delete.

## Playing with friends (peer-to-peer, free, no accounts)

Everyone needs the **same version (v2)**. If versions differ, the game refuses politely and explains who should update.

### Host (you)

1. Open the game, load or create a world.
2. Press **Esc → "🌐 Host for friends" → "Host & get a room code"**.
3. A 5-letter room code appears (e.g. K7QPM). Send it to your friends any way you like.

Keep your tab open: your computer runs the world (mobs, bosses, weather) and saves it.

### Each friend

1. They need the same game (this page, or the `index.html` file) and an internet connection.
2. Open it → on the title screen press **"🌐 Multiplayer — join a friend"**.
3. Type a name, enter the room code, press **Join**. They spawn next to you within a few seconds.

In game: press **T** to chat; you see each other's names, building, sprinting, spells, Light/Dark auras and mobs.

A Light player and a Dark player fighting side by side form an uneasy alliance (+10 % power, `/path twilight` combo).

### Manual invite

If **Join** can't find the room (strict network, or the free PeerJS server is down), use the manual invite:

- **Host:** Esc → Host for friends → **"🔧 Manual invite"** → Create invite code → Copy, send it to the friend.
- **Friend:** title screen → Multiplayer → **"🔧 Manual invite"** → paste it → Make reply code → Copy, send it back.
- **Host:** paste the reply code → Connect. (One invite per friend.)

Very strict firewalls on both sides can block any direct peer-to-peer connection.

## Tech notes

Chunk generation stays on the main thread, time-sliced, because World.POST hooks touch game state; meshing runs in Web Workers. Multiplayer uses WebRTC data channels with PeerJS's public signaling server (or copy-paste invites).
