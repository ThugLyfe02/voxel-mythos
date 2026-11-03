# Voxel Mythos

**[Play now](https://thuglyfe02.github.io/voxel-mythos/)**

A living voxel sandbox (v2.9.3 “Arsenal”). One self-contained file, no install, and no internet needed to play solo. Worlds save in this browser automatically. v1 through v2.8 saves (including v2.7 hotfix 1) load in v2.9.3 unchanged. The join fix from hotfix 1 is kept. v2.9.3 adds one small section for worn armor, the off-hand, firearm settings, and each gun's state. A v2.9.3 world still opens in v2.9.2, and your armor, off-hand, and guns are still there when you come back to v2.9.3.

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
- **Shift (hold)** sprint, ~1.6× speed with a FOV kick; uses stamina (green bar above the hotbar) (also double-tap W; "Toggle sprint" option in Accessibility). Sprint also works on mounts. Shift descends while flying.
- **Space** jump / swim up / fly up
- **C** descend while flying
- Walking into a 1-block ledge steps up onto it smoothly (setting "Step-up onto ledges").

### Acting

- **Left click (hold)** mine / attack · **Right click** place · eat · use · talk · tame · ride
- **1–9 / wheel** hotbar · **0** cast your bound Light/Dark path power (duel bolt in a duel) · **-** Crossroads / Light panel
- **E** inventory & crafting · **M** market (Shift+M living Market) · **,** quest board & journal · **F** talk (off-hand a shield, charm, or throwable when nobody is nearby) · **T or /** chat & commands · **Q** cast spell · **G** map & realm
- **R** mount / dismount / land (reload a firearm) · **V** thermal vision (Stress View while holding the Engineer's Hammer) · **X** weapon ability · **B** armory · **N** tech tree · **J** Story Journal (Shift+J creature codex)
- **O** Living Codex (Shift+O party) · **U** Field Journal (Shift+U trophies) · **Y** gallery · **H** Hearth claim view (airship camera on a ship)
- **.** (period) Celestial Almanac — while looking up at the night sky it toggles star and planet labels instead
- **;** (semicolon) or middle-click: ping the spot you look at for your party (Shift: everyone)
- **'** (apostrophe) quick-chat wheel · **[** emote wheel — hold, steer with the mouse, let go
- **Guard (v2.8):** hold right mouse to block; block just before a hit to parry, then strike to counter. **Left Alt** dodges. Hold **;** for the ping wheel.
- **Shift+F8** Report a problem (also `/report`)
- **L** spellbook · **I** journal · **Z** blueprints · **K** save now · **Esc** pause · **F3** performance overlay
- **E** while facing a villager, worker, mage or caravan: Kindred talk menu
- **Bard's Lute** in hand: **1–9** play notes

## Controls — phones & tablets

On-screen controls appear automatically.

- Left thumb: virtual joystick to move. Right side: drag anywhere on the view to look around.
- 🏃 button toggles sprint · 🎥 button changes camera view · jump / mine / place / menu buttons on screen.
- Rotating the phone (portrait ↔ landscape) resizes the game correctly.

## Settings (Esc → Settings)

Mouse sensitivity, Invert Y, Toggle sprint (Accessibility), FOV, Quality: Auto / Low / Medium / High / Ultra.

🎮 **Movement & camera:** keyboard turn speed, arrow keys turn, head bob, double-tap W sprint, step-up onto ledges.

🌪 **World Chaos** slider 0–200 % (host-controlled in multiplayer, saved with the world): more mobs, faster cataclysms, better loot and smarter packs at higher values.

🐾 **Living creatures → Creature detail:** High (full rigs, cloth, foot IK) / Medium / Low (impostors start nearer) / Classic blocks (the v2.2 look). "Damage numbers" and "Screen shake" toggles are in the main list.

**Ultra** (desktop GPUs): real-time shadows, planar water reflections, hi-res textures, light shafts, depth of field and motion blur in photo mode. If the frame rate stays too low, the game switches itself back to High and tells you.

## Useful commands (T or /)

`/help` `/build castle of bricks glowing` `/daily` `/replay` `/ascend` `/home` `/sethome` `/host` `/players` `/view` `/chaos 0-200`

`/path [status|open|choose light|dark|cast N|trial|apex|step|legion|fuse|twilight|sim N]` `/magic` `/arts` `/way` `/bp`

`/weapon` `/enchant` `/armory` `/era` `/tech` `/tame` `/pet` `/season` `/festival` `/storm` `/tornado` `/ship` `/gallery` `/cinema`

New in v2.1: `/stamina` `/beast [start|calm|cure]` `/duel <name>|accept|decline` `/path guests` (host)

`/hearth [view|list|rewind <minutes> [uid]|trust <name> <co|guest|stranger>]` (also `/claim`)

`/codex [stats|creatures|<name>|all (creative)]` `/mentor off|quiet|helpful|tip|tts`

New in v2.2: `/story [sim N]` `/chronicler [on|off|persona <name>|cap N|fewer]`

`/music [on|off|status|motif|mutate|stinger|density|visual|credits]` `/kindred [status|who|rumors|gossip|talk]`

New in v2.5: `/eco [stats|rewild|days N (creative)]` `/sky [next|labels|goto <event> (creative)]`

New in v2.6: `/bucket [level N|all|empty]` `/ww [stats|settle (creative)|on|off]` `/ls [view|physics on|off (creative)]`

New in v2.7: `/realm [council|vote N|found <name>|stance <choice>]` `/banner` `/strata` `/friends`

New in v2.7.1: `/party [invite <name>|accept|leave]` `/ping [look|danger|loot|dig|help] [all]` `/wp [add <name>|list|del <name>]` `/travel <name>` `/emote <name>|stop` `/qc 1-8` `/fellow social on|off`

New in v2.8: `/report` `/diag` `/firstnight` `/votekick <name>` `/mute <name>`

Creative only: `/dim ember|canopy|tidal|void|over` `/boss` `/give` `/time` `/weather` `/fly`

## What's new in v2.9.3 — Arsenal

- **Swing meter:** a small arc under the crosshair refills after every melee swing. A full swing hits hardest; swinging early hits for less. A full swing while falling onto a foe is a critical hit. Blades sweep nearby foes, axes knock a shield aside, and a hammer or mace after a fall of more than 1.5 blocks smashes the ground. Settings → Arsenal → "Classic combat" turns the meter off. A Training Dummy (3 planks and 4 wheat) shows the damage of every hit.
- **Off-hand:** press **F** with a shield, charm, or throwable selected, and nobody nearby to talk to, to put it in your off-hand. The Round Shield blocks hits from the front while you hold right-click.
- **Bows:** hold attack to draw, then let go. A full draw is a critical shot. Arrows fly in an arc, drift with the wind, stick where they land, and can be picked up. Every bow owner starts with 32 arrows. Settings → Arsenal → "Infinite plain arrows" if you would rather not carry any.
- **Armor:** six sets for head, chest, legs, and feet — Hide, Copper, Iron, Gilded, Aether, and Voidsteel. Right-click a piece to wear it. Armor cuts hit damage; falls, hunger, drowning, and the void ignore it. The Armory (**B**) lists what you wear.
- **Throwables and the Second Wind Charm:** Snowballs shove a foe back without hurting it. A Blink Pearl teleports you to where it lands for 2 health. The Second Wind Charm, carried in your inventory, is used up to stop a knockout and bring you back with 8 health.
- **Firearms, opt-in per world:** Settings → Arsenal → Firearms is Off by default (also Less-lethal only, or On; in co-op the host decides). Four fictional guns: Pocket Warden pistol, Six-Bell revolver, Hearthguard pump shotgun, and Skylark flare gun. **R** reloads; hold right-click to aim. The Kin Rule holds: rounds only knock out or drive off. Rubber rounds, beanbag shells, tranquilizer darts, and flares never kill. Villagers, pets, and passive creatures are never targets. Guns wear, can jam, and a Cleaning Kit restores them. A friend still on probation cannot fire.
- **Sights, lasers, and lights:** iron sights, Ember Dot and Halo sights, a Beam Module laser friends can see, and a Lantern Rail. Right-click an attachment to fit it to the gun you last held.
- **Wind and polish:** arrows, thrown items, and rounds drift with the wind. Thunder-in-a-Bottle reads more clearly against the sky, and friends can use it and the Rainbow Bridge in a host's world. Usable wild items and worn gear can go on the hotbar.

## What's new in v2.9.2 — Wild Works

- **Custom curios:** twelve items crafted from Spoils, including Bottled Rapids, Current Compass, Ember Jar, and Slag Skillet, plus Lava Lamp, Lantern Wick Torch, Brine Pearl Diving Helm, Gloam Silk Cloak, Sludge Boots, Spring Coil Boots, Frost Bristle Brush, and Echo Shell. Worn helm, cloak, and boots show beside the hotbar.
- **River crafting:** toss River Grit, Cobblestone, Sludge Gel, a Log, or Amber into moving water and it tumbles for 15 seconds into sand and flint, planks, Clean Gel, or Polished Amber. Heat Iron, Glass, or a Slag Core beside lava, then toss it into a waterfall to quench it into Tempered Steel, Toughened Glass, or Basalt Glass.
- **Bastion defenses:** Current Pump drives a Moat Current, Holding Eddy catches swept creatures until dawn, Waterfall Gates shove hostile creatures back, and Gale Fans blow creatures, swarms, and drops away.
- **Wild recipes:** Lava Surfboard, Rainbow Bridge, and Thunder-in-a-Bottle.
- **Codex:** the six new creatures have Living Codex pages with a turning model, where they live, when they are active, health and damage, how many you have knocked out, and the Spoils they can drop.
- **Co-op:** friends on v2.9.2 see the new creatures with their real look, and Spoils burst where a friend knocks one out. Older friends see a plain stand-in, still get coins, and see a familiar stand-in block for the new blocks.

## What's new in v2.9.1 — Wild Waters

Switches are in **Settings → Living Currents** and the Lens.

- **Flowing water and lava:** hillside springs feed streams that run downhill, with ripples, foam, and waterfalls where a stream reaches a cliff. Ember Vents push lava in pulses; it creeps downhill, pours over ledges as lavafalls, and crusts as it cools.
- **Currents that push:** step into a stream and the current carries you downstream. Swimming upstream is harder. Creatures and dropped items drift with it too.
- **Fluid sound:** streams babble, waterfalls roar, and lava bubbles, placed left or right as you turn. With subtitles on, captions name them.
- **Visible drops (Spoils):** knocked-out hostile mobs burst into coins and items that bounce, glint, float on water, and fly to you when you walk close.
- **Six new mobs:** Gloamstalker, Sludgeback, Cinderling Swarm, Brinejaw, Clockwork Scuttler, and Slag Golem. Each warns before it strikes, and each has a way to beat it. Defeated creatures are knocked out, not killed.
- **Feature Atlas:** Esc → Feature Atlas lists everything running in your game, with NEW badges and a Show me button.
- **Look-At Lens:** look at a block, fluid, or creature and a card by the crosshair shows its name, the tool it needs, what it drops, which way water or lava flows, and a creature's health and Spoils. Hold Alt for more. Turn it off in Settings.

New creatures and visible drops appear in solo play for now. In co-op, coins still go straight to your purse.

## What's new in v2.9 — True World

Every part has a switch in **Settings → Graphics → True World**.

- **Deeper lighting:** the sky lights the world the way it looks, on every quality level. Land under a floating island is softly shaded instead of turning black. Overhangs and cave mouths fade into shadow, and the sun leaves shade on the sides of hills and buildings that face away from it. Lanterns, lava, crystals, and glowing ores give off their own colored light. On Medium and up, that light bounces off nearby walls.
- **Sky:** a real gradient, blue overhead at noon and deep violet over an orange horizon at sunset. Distant ridges fade into blue-gray haze instead of a flat band of fog.
- **Exposure:** step into a dark cave and your eyes adjust over a few seconds; step back into daylight and the glare fades.
- **Wind:** gusts travel across fields. Plants, leaves, rain, and banners feel the same wind as each gust passes.
- **TAA and cloth:** on High, temporal anti-aliasing smooths jagged edges on blocks, fences, and leaves, and the sun casts soft shadows. On Medium and up, realm banners are real cloth: limp in calm air, streaming in a storm, and swinging when the wind turns. Reduced motion keeps them still.
- **Fixes:** dark land under sky islands, dawn artifacts, and gold and lava tones.
- If the host's computer freezes for a few seconds, friends wait for it instead of dropping and rejoining.

## What's new in v2.8 — Bedrock

- **Endless Worlds:** land keeps generating out to the World's Rim at ±30 million blocks. Past the heartland, the Frontier holds hamlets, ruins, faction outposts, and named Marches. Only the chunks you change are saved.
- **Safer saves:** every save is also kept in IndexedDB, with the last 6 versions of each world. Esc → Save safety restores an earlier version and exports or imports a `.vmworld` file. Older `.json` backups still import.
- **A new look:** a filmic grade on High and a lite grade on Low and Medium, glowing ores and lanterns, rain wetness and ripples, and True Light water, glints, and grass on higher settings. Settings → Graphics → Look & light and True Light.
- **Watch Bells, tripwires, and opt-in Defense Nights:** a bell rings a code for what crossed a wire. Defense Nights are off by default; raiders come only for the coins you put in the Raid Chest. `/firstnight` starts a gentle first night.
- **Guard:** hold right mouse to block, parry just before a hit, then counter. Left Alt dodges. Hits have a short on-screen hit-stop, a stagger, and a swing trail.
- **Inventory:** search, star favorites, and up to 3 recipe pins with a live ingredient checklist.
- **Smoother multiplayer:** if the host leaves, the world moves to the next player, including a friend who was still loading. New guests have a 10-minute grace period before TNT, fire, or fluids unless the host trusts them. `/votekick`, `/mute`, and a Help-defend card when a bell rings.
- **Everyone Plays:** captions for important sounds, high contrast, color-blind palettes, and comfort settings. Screen shake at 0 means no shake at all, and "Limit flashing lights" caps lightning, blasts, and fireworks.

## What's new in v2.7.1 — Fellowship

The join fix from hotfix 1 is kept: TURN relays, cleaned-up room codes, up to 3 join tries, clearer errors, and Enter to join.

- **Join-code chip:** in every world the room code sits next to the coins. Hosting shows the code with a one-click Copy button; a guest sees the code of the world they joined; single-player shows a compact Host button. It follows a host change, hides in photo mode, and moves aside so it never covers a menu. In the pause menu it sits in the menu's empty top corner. A manual-invite session shows the host's name and an Invite button instead.
- **Fellowship A:** emotes and quick chat, extra party-panel tools, pings and shared waypoints, travel to a party member, co-dig, duo taming and co-op quests, council voting blocs, and Codex party credit. Esc → Party, or `/party`. Middle-click or **;** pings; hold **'** for quick chat and **[** for emotes.
- When the original host comes back, merge-back asks for the world only after the welcome, so a guest who is still loading is not left behind.
- Heir snapshots no longer freeze players.
- Party actions are rate-limited. Going too fast gets a "Slow down" reply instead of the action being dropped silently.

## v2.7-hotfix1 — Join fix

Friends behind a strict NAT, or on mobile data, can connect. The game now uses TURN relay servers when a direct peer connection cannot get through.

- Pasted room codes are cleaned up: spaces, dashes, a `vxm-` prefix, and links are stripped before the join.
- A failed join retries up to 3 times.
- Error messages say more clearly what went wrong.
- Pressing Enter joins.

Saves and worlds are unchanged from v2.7. v2 through v2.7 players can still play together.

## What's new in v2.7 — Realms and Ruins

**Esc → "🏺 New in v2.7"** lists all of this in game. Esc → "❔ Help & Controls" has a "Realm & ruins" section.

Saves from v1 through v2.6 still load. v2 through v2.6 players can still play together with v2.7 players. The realm and the dig record need a v2.7 host; older guests join and simply do not see those features.

- 🚩 **Banners of the Realm:** five fictional factions hold regions of the world, each with a capital, borders, and a leader who remembers what you did. They trade, quarrel over borders, lay sieges, and make peace. **G** opens the realm map, with Diplomacy, Council, and Banner tabs (`/realm`). Any group of friends can raise a banner and design its crest (`/banner`). The Grand Council meets every 7 days and votes on an edict that changes quest rewards, prices, raids, magic, and research.
- 🪨 **Strata:** deepstone and primeval rock hold Orichalcum, Amber, and Fossils. Each world has a seeded history of 3–6 lost cultures and their buried cities, temples, tombs, and battlefields. Brush a Buried Find to keep it intact, decipher inscriptions, and show artifacts on Museum Plinths. **U** opens the Field Journal; trophies moved to **Shift+U**.
- 👥 **Friends on the map:** other players show on the minimap and the world map (**G**) as colored arrows with their names. When a friend is out of range, the arrow waits at the edge, points the way, and shows the distance. `/friends` lists everyone's distance and direction.
- Refinements: plank decks fail from the free end, wave by wave, instead of all at once; falling debris is textured; Stress View turns red only past the breaking point; old stone grows moss; settled water lies level. Game text uses US spelling throughout.

## What's new in v2.6 — Elements and Engineering

**Esc → "💧 New in v2.6"** lists all of this in game. Esc → "❔ Help & Controls" has a "Water & building" section.

- 💧 **Waterworks:** water, lava, mud, honey, mana-essence and void-tar have real levels from 1 to 15. They pour, spread, fill basins and push through U-bends. Break a dam and the valley floods, then settles. Water on lava makes obsidian, and rivers slowly wear soft beds (claimed land and anything you built are never eroded). Water Wheels, Pumps, Valves, Sluice Gates, Aqueducts and Level Sensors run from a Logic Core. The Bucket (3 iron) scoops or pours; `/bucket` sets how much.
- 🧱 **Load and Stone:** every block has a strength, a weight and a span. Stone reaches about 4, wood 5, Iron Beams 12 and Weaver Silk 32. A failing block cracks and creaks for 2 seconds, then falls. Builds from before v2.6 are left standing until an edit makes them worse. The Engineer's Hammer reinforces a block you built or reads its load. **V** while holding the hammer opens Stress View.
- In a v2.6 game the host runs the water and decides what collapses. v2.6 guests see the same levels and falling debris. Guests on v2.5 or older see the result as ordinary blocks.
- Refinements: the village market sells Tanned Hide, comets are bigger, and Nest Boxes and star-metal ore appear as planks and iron ore in versions that don't know them.

## What's new in v2.5 — Wild Skies

**Esc → "🌌 New in v2.5"** lists all of this in game.

- 🌿 **Living Ecology:** every 64×64 patch of land tracks plants, water, soil and the animals living there. Herds follow the seasons, and hunting, taming and farming change what spawns around you. Each biome has a keystone species — lose the wolves of a forest and it slowly withers. Plant saplings, dig ponds, place Nest Boxes (3 planks + 1 stick) and release companions to bring it back. A rich, balanced patch becomes a Sanctuary. Craft a Naturalist's Spyglass, or use Pause → Ecology Lens, or `/eco`.
- 🌌 **Celestial Almanac:** two moons (Lumen, 8 days, and Vesper, 29 days), wandering stars, twelve constellations, comets, meteor showers, blood moons and winter auroras. The sky is computed from your world seed, so a party shares it. Craft an Astrolabe to predict eclipses, comets and showers. Open it with **period (.)**, Pause → Almanac, or `/sky`. Looking up at night, period toggles star and planet labels.
- The living ecology, Ecology Lens and star naming need a v2.5 host. A v2.5 guest still sees the almanac sky at an older host, because the sky comes from the world seed.
- Refinements: dragon horns fold flat while riding in first person, worker wages follow the village's cost of living, and new worlds' markets settle before you arrive.

## What's new in v2.4 — Quests and Coin

**Esc → "🪙 New in v2.4"** lists all of this in game.

- 📜 **Questforge:** quests come from what is really happening in your world — a town short of iron, raiders or wolves near the village (you drive predators off, you never hunt them), a villager's wish or feud, a ruin or omen the Chronicler noticed, and more. Every quest has a "Because: …" line naming its cause, and it closes itself if that need goes away. Sagas run 3–7 steps, with complications and two good-faith endings. Up to 8 active quests; track 3 on the HUD. **Comma (,)** or Pause → Quest board opens the board, journal and echoes.
- 🪙 **The living Market (Shift+M,** or the link in the **M** market): 83 goods priced by supply and demand across your village, 19 trading towns, the four dimension bazaars and travelling caravans. Shops, town contracts, couriers, a bank, and an Exchange Board where friends can list up to 6 items. Coins are earned only in the game — no real money and no pay-to-win.
- Party quests and the living Market need a v2.4 host. Everyone in a party gets the full reward.
- Refinements: the dragon's silhouette, the roc's hover, softer particles, and guests now see ability effects and other players' mech rigs.

## What's new in v2.3 — Living Creatures

**Esc → "✨ New in v2.3"** lists all of this in game.

- 🐺 **Living bodies:** every animal, mob, villager, NPC, worker, mage, pet, mount, summon, construct and boss now has an articulated, skinned body (bones, not blocks) — necks, spines, jaws, tails, ears, wings, fins, tentacles and capes all move. The player has a full third-person body too (**F5**): walk/sprint/jump/swing, a seated riding pose on mounts, a hurt flinch, a cast pose and a dead pose; mounts now stand on the ground instead of sinking into it.
- 👁 Eyes blink and glance around, and creatures turn their heads to track you when you come near. Magical creatures have emissive glowing eyes; rim light picks out silhouettes at dusk.
- 🦶 Procedural, blended animation: idle breathing, walk → run → gallop, flying, gliding and swimming gaits, leaps, attacks with jaw/claw/tail strikes, flinches and deaths blend smoothly. Feet are planted on uneven ground (foot IK); cloth, hair, manes, ears and tails follow with secondary motion.
- 🦓 Procedural skins: fur with directional strands, overlapping directional scales (smaller on face and limbs, larger on the back), feathers, chitin, hide, bark, stone, crystal and slime; darker backs and lighter bellies; texture contrast softens with distance. Per-species markings: wolf saddles, lynx/frog/salamander spots, stalker stripes, manticore rosettes, deer dapples, banded dragons and serpents, the boar's dorsal stripe, the badger's blaze, the raccoon's mask and ringed tail, dolphin and otter countershading, a fox's white tail tip and dark stockings, barred hawks and owls.
- ✨ Ability effects come from the body: breath jets from the mouth, spit and gaze bursts, shimmering hex shields that ripple when hit and shatter, healing helixes, quake rings, gust vortices, ink clouds, blink flashes, dash streaks, burrow spray and landing dust.
- ⚔ Combat feedback: hits spark where they land (steel/blue sparks on armour and shields), the creature flashes, and optional floating damage numbers rise from the wound (gold for big hits, blue when shielded).
- 📖 The Living Codex (**O**) turntable shows each creature's animated rig (silhouette until discovered).
- ⚙ Performance: full detail up close, a lighter body at mid range, and shared instanced impostors far away; the rig manager spreads rig building over frames. Settings → Living creatures → Creature detail lets slower machines trade detail for speed.

## What's new in v2.2 — The Living Story

**Esc → "✨ New in v2.2"** lists all of this in game.

- 📜 **The Chronicler:** an AI storyteller paces your world in chapters (calm → rising tension → climax → breather), drawing from a deck of event cards — caravans, strangers, wizard duels, golden hours, buried things — for you and your friends, and it eases off when you are struggling. Pick its persona when you create a world (the Bard, the Tyrant, the Weaver's Echo and more); **J** opens the Story Journal with every chapter so far. Settings → Chronicler: on/off, intensity cap, "fewer events". **F3** shows the per-system timing overlay.
- 🎼 **The Living Score:** music composed live from where you are, what you face and how tense the story is. Each dimension has its own mode, tempo follows danger, stingers land on the beat. You have your own five-note leitmotif that changes a little at each milestone; bosses and legends have themes too (hear them on the Music Box).
- 🪕 **Bard's Lute** (3 planks + 1 iron): hold it and press **1–9** — every note snaps to the current scale, and friends within 40 blocks hear you. On touch, using the lute opens a fretboard.
- 💬 **Kindred Memory:** every villager, worker, mage, witch, caravan and goblin warren remembers what you did — gifts, rescues, harm, trades, help building, trampled crops, broken or kept promises. Face someone and press **E** to greet, gift what you hold, ask for rumors, request help, apologize, compliment their home, return a lost item, or (as a confidant) hear a personal request. A glyph over their head shows how they feel (😠 😒 🙂 😊 💖). Memories fade (small things in ~10 days, big ones in ~60) and personalities matter (kind, greedy, honest, brave). Gifts count for at most +25 a day and the same gift again is worth half as much.
- 🗣 **Gossip:** people trade stories each in-game hour — up to three people away, weaker each retelling, and sometimes wildly exaggerated. Read what is being said in Codex (**O**) → Rumors.
- 💖 Friends give discounts, morning gifts, hints and help in a fight; workers' morale follows their opinion of you; goblins learn to avoid the home of someone who caught their thieves. Villages pick a mayor from the best-liked.
- 🕯 Apprentices inherit their mentor's strongest memories. When someone dies, their friends carry what they knew; place a Memorial Stone (3 cobble + 1 red flower) to honor them.

## What's new in v2.1

- 🏠 **Hearth Guard:** craft a Hearthstone (4 cobble, 1 gold, 1 Ember Shard; Ember Shard = 2 coal + 1 iron) and place it to claim a 32×32 home (expandable to 128). Friends get trust tiers (Co-builder / Guest / Stranger): strangers can look but not touch, containers, machines and mounts are protected, and the host enforces it. Every block change in a claim is recorded, so griefing can be rewound (`/hearth rewind 10`), and repeat griefers are frozen automatically. **H** shows claim borders.
- 🦉 **Mentor & Living Codex (O):** an encyclopedia of 630 pages in 12 categories that fills itself in as you see, mine, craft, tame and fight things, each with a rotating 3D model, lore, stats, links and when/where you found it. Search, filters, "What next?" suggestions, and share pages with friends (they see a silhouette until they find it). The Mentor owl offers short lessons only for things you haven't shown you can do, at most one tip per 5 minutes, with Off / Quiet / Helpful modes and optional read-aloud. Hosts can switch on "Mentor for my guests".
- 💨 **Stamina:** sprinting costs stamina (HUD bar), it regenerates when you slow down, and a good meal makes it last.
- ⚔ **Light vs Dark duels** (multiplayer, opt-in): challenge a player on the opposite road, away from villages. Duels are non-lethal (first to 0 duel-HP yields), consent-based, and never touch villagers. Turn challenges off in Settings.
- 🩺 **Infected beasts:** a real quest to weaken, cleanse (Cleansing Salve) and free a blighted beast — a Radiant Deed.
- ✨ Companion evolutions now visibly change your pet (Ascended, Dawnkin, Umbral looks).
- 🌗 Hosts save each friend's Light/Dark road by player id, so it is restored when they rejoin.
- Phones: clearer touch tutorial. Third person: crosshair offset/hidden and the held item hidden.

**Esc → "✨ New in v2.1"** lists all of this in game.

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

v2.1 through v2.9.3 play together (v2 still connects too). In co-op the host decides whether firearms are on. Friends on v2.9.2 see the new creatures and Spoils; older friends see stand-ins. True World lighting follows each player's own graphics settings. Watch Bells, Defense Nights, and the Frontier need a v2.8 host. The v2.7-hotfix1 join fix is kept in v2.7.1. Parties, pings, waypoints, and travel need a v2.7.1 host. The realm and the dig record need a v2.7 host; v2.7 players at the same host see the same ruins and the same politics. v2.6 and older guests join a v2.7 game and just don't see these features. A v2.7 guest at an older host is told that world has no Strata. In a v2.6+ game the host runs the water and decides what collapses. v2.6 guests see water levels change smoothly and watch the same falling debris, because every peer computes it from the same seed. Guests on v2.5 or older see the result as ordinary blocks, with familiar stand-ins for the new v2.6 blocks. The living ecology, Ecology Lens and star naming need a v2.5 or later host (a v2.5 guest at an older host is told so). The sky itself is computed from the world seed, so v2.5 and v2.6 guests see the almanac sky at any host. Guests see the host's creatures, pets and helpers with v2.3 bodies, and see friends seated on their mounts. Party quests and the living Market need a v2.4 host. Everyone in a party gets the full reward, and members who are offline are paid when they come back. Older guests just don't see these features. Story, score and Kindred talk turn on when the host runs v2.2 or later (a newer guest at an older host just plays without them); v2.1-only features such as claims, duels and Codex sharing switch off for v2 players. v1 can't join v2–v2.7 games (or host for them): the game refuses politely and explains who should update.

Kindred memories, the Chronicler, quests, the market, the ecology, water, structures, the realm, the dig record and the music are run by the host and saved in the host's world.

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

Chunk generation stays on the main thread, time-sliced, because World.POST hooks touch game state; meshing runs in Web Workers. v2.3 creatures are skinned meshes merged to a few draw calls each (one per material), with shared geometry per species, a lighter mid-range LOD and InstancedMesh impostors; skins and coat patterns are procedural in the shader (no image files). Multiplayer uses WebRTC data channels with PeerJS's public signaling server (or copy-paste invites).
