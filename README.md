# Voxel Mythos

**[Play now](https://thuglyfe02.github.io/voxel-mythos/)**

A living voxel sandbox (v1). One self-contained file, no install, and no internet needed to play solo. Your worlds save in this browser automatically.

## Play

Open the [live game](https://thuglyfe02.github.io/voxel-mythos/) in Chrome, Edge, Firefox, or Safari. To play from a local copy, open `index.html` (the same file as `voxel-sandbox.html`).

## Controls (desktop)

- **WASD** move · **Mouse** look · **Space** jump / swim up / fly up · **Shift** sprint (descend while flying) · **C** descend
- **Left click (hold)** mine / attack · **Right click** place · eat · use · talk · tame · ride
- **1–9 / wheel** hotbar · **E** inventory, crafting, spellbook, bestiary, perks, quests
- **M** market · **F** talk to villager · **T or /** chat & commands · **Q** cast spell · **G** map & factions
- **R** mount / dismount a saddled pet · **P** photo mode (1–6 filters, Enter = snapshot, H hides UI)
- **K / F5** save now · **Esc** pause (Worlds & backups, Multiplayer, time-lapse, settings, help)

Touch devices get on-screen sticks and buttons automatically.

## Useful commands

`/help` `/build castle of bricks glowing` `/daily` `/replay` `/ascend` `/home` `/sethome` `/host` `/players`

Creative only: `/dim ember|canopy|tidal|void|over` `/tame strider|skyray|hound|moth|reefray|drifter` `/boss` `/give` `/time` `/weather` `/fly`

## Saving

Autosave every 30 s, on dimension change, and when you close or hide the tab ("saved Ns ago" chip top-right).

**Esc → Worlds & backups:** 4 named world slots + the Daily slot, Export (.json backup file), Import, rename, delete.

## Playing with friends (peer-to-peer, free, no accounts)

### Host (you)

1. Open the game, load or create a world.
2. Press **Esc → "🌐 Host for friends" → "Host & get a room code"**.
3. A 5-letter room code appears (e.g. K7QPM). Send it to your friends any way you like.

Keep your tab open: your computer runs the world (mobs, the Colossus, weather) and saves it.

### Each friend

1. They need the same game (this page, or the `index.html` file) and an internet connection.
2. Open it → on the title screen press **"🌐 Multiplayer — join a friend"**.
3. Type a name, enter the room code, press **Join**. They spawn next to you within a few seconds.

In game: press **T** to chat; everyone sees each other's names, building, mining, explosions and mobs.

If the host changes dimension, friends are pulled along. Late joiners get the whole current world.

Friends' inventories travel with them between sessions; the world belongs to the host.

If the connection drops, a friend can keep an offline copy of the world in an empty slot, or return to the title.

### Manual invite

If **Join** can't find the room (strict school/office network, or the free PeerJS server is down), use the manual invite:

- **Host:** Esc → Host for friends → **"🔧 Manual invite"** → Create invite code → Copy, send it to the friend.
- **Friend:** title screen → Multiplayer → **"🔧 Manual invite"** → paste it → Make reply code → Copy, send it back.
- **Host:** paste the reply code → Connect. (One invite per friend.)

Very strict firewalls on both sides can block any direct peer-to-peer connection.
