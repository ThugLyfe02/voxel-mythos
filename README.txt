VOXEL MYTHOS — a living voxel sandbox (v2.5 “Wild Skies”)
=========================================================

PLAY: double-click voxel-sandbox.html (Chrome, Edge, Firefox or Safari). One self-contained file, no install, no
internet needed to play solo. Worlds save in this browser automatically. v1 through v2.4 saves load in v2.5 unchanged (same storage keys;
v2.5 only adds new sections for the ecology and the almanac, so a v2.5 world still opens in v2.4, which ignores them —
except placed Nest Boxes and star-metal ore, which older versions don't know and leave out).

FIRST STEPS: click the game view ("🖱 Click to play") to capture the mouse, then move the mouse to look around.
Esc releases the mouse and pauses; click again to carry on.

CONTROLS — desktop (most keys can be rebound in Esc → Settings → Accessibility → Key bindings)
  Looking / camera
    Mouse ............ look around (after clicking the view; pointer lock)
    No pointer lock? . drag with the right (or left) mouse button to look — switches on automatically
    ← / → ............ turn left / right (smooth; speed in Settings → Movement & camera)
    PageUp / PageDown  look up / down
    F5 ............... camera view: first person → third person behind → third person front (also /view)
    F9 ............... free orbit camera     P photo mode (1-6 filters, Enter snapshot, H hides UI)
  Moving
    W A S D .......... move (diagonals are normalised — same speed in every direction)
    Shift (hold) ..... sprint, ~1.6× speed with a FOV kick; uses stamina (green bar above the hotbar) (also double-tap W; "Toggle sprint" option in Accessibility)
                       Sprint also works on mounts. Shift descends while flying.
    Space ............ jump / swim up / fly up        C descend while flying
    Walking into a 1-block ledge steps up onto it smoothly (setting "Step-up onto ledges").
  Acting
    Left click (hold)  mine / attack      Right click  place · eat · use · talk · tame · ride
    1-9 / wheel ...... hotbar             0  cast your bound Light/Dark path power (duel bolt in a duel)     -  Crossroads / Light panel
    E inventory & crafting   M market (Shift+M living Market)   , (comma) quest board & journal   F talk   T or / chat & commands   Q cast spell   G map & factions
    R mount / dismount / land   V thermal vision   X weapon ability   B armory   N tech tree   J Story Journal (Shift+J creature codex)
    O Living Codex (Shift+O party)   U trophies   Y gallery   H Hearth claim view (airship camera on a ship)
    .  (period) Celestial Almanac — while looking up at the night sky it toggles star & planet labels instead
    L spellbook   I journal   Z blueprints   K save now   Esc pause   F3 performance overlay
    E while facing a villager, worker, mage or caravan: Kindred talk menu    Bard's Lute in hand: 1-9 play notes

CONTROLS — phones & tablets (on-screen controls appear automatically)
  Left thumb: virtual joystick to move.  Right side: drag anywhere on the view to look around.
  🏃 button toggles sprint · 🎥 button changes camera view · jump / mine / place / menu buttons on screen.
  Rotating the phone (portrait ↔ landscape) resizes the game correctly.

SETTINGS (Esc → Settings)
  Mouse sensitivity, Invert Y, Toggle sprint (Accessibility), FOV, Quality: Auto / Low / Medium / High / Ultra.
  🎮 Movement & camera: keyboard turn speed, arrow keys turn, head bob, double-tap W sprint, step-up onto ledges.
  🌪 World Chaos slider 0-200 % (host-controlled in multiplayer, saved with the world): more mobs, faster cataclysms,
     better loot and smarter packs at higher values.
  🐾 Living creatures → Creature detail: High (full rigs, cloth, foot IK) / Medium / Low (impostors start nearer) /
     Classic blocks (the v2.2 look). "Damage numbers" and "Screen shake" toggles are in the main list.
  Ultra (desktop GPUs): real-time shadows, planar water reflections, hi-res textures, light shafts, depth of field and
  motion blur in photo mode. If the frame rate stays too low, the game switches itself back to High and tells you.

USEFUL COMMANDS (T or /)
  /help /build castle of bricks glowing /daily /replay /ascend /home /sethome /host /players /view /chaos 0-200
  /path [status|open|choose light|dark|cast N|trial|apex|step|legion|fuse|twilight|sim N]  /magic /arts /way /bp
  /weapon /enchant /armory /era /tech /tame /pet /season /festival /storm /tornado /ship /gallery /cinema
  New in v2.1: /stamina  /beast [start|calm|cure]  /duel <name>|accept|decline  /path guests (host)
    /hearth [view|list|rewind <minutes> [uid]|trust <name> <co|guest|stranger>] (also /claim)
    /codex [stats|creatures|<name>|all (creative)]  /mentor off|quiet|helpful|tip|tts
  New in v2.2: /story [sim N]  /chronicler [on|off|persona <name>|cap N|fewer]
    /music [on|off|status|motif|mutate|stinger|density|visual|credits]  /kindred [status|who|rumors|gossip|talk]
  New in v2.5: /eco [stats|rewild|days N (creative)]  /sky [next|labels|goto <event> (creative)]
  Creative only: /dim ember|canopy|tidal|void|over /boss /give /time /weather /fly

WHAT'S NEW IN v2.5 — WILD SKIES
  🌿 LIVING ECOLOGY: every 64 × 64 patch of land tracks plants, water, soil and the animals living there. Hares and deer
    feed lynx, owls and wolves; herds follow the seasons between biomes and you can watch them migrate past. Hunting,
    taming and farming all change the numbers, and the animals that spawn around you come from what really lives there.
    The simulation is kept in bounds (a full in-game year was tested with no runaway or vanished species).
  🐺 Keystones & Sanctuaries: each biome has a keystone species. Lose the wolves of a forest and it slowly withers, its
    colours fading. Plant saplings, dig ponds, place Nest Boxes (3 planks + 1 stick) and release companions to bring life
    back. A patch rich and balanced for three days becomes a Sanctuary: legendary creatures appear only there, and once
    a season it gives you a Heartseed, which completes one Ascension step for a companion.
  🧬 Evolving wildlife: animals hunted hard grow faster, smaller and warier over many days; those in cold land grow paler
    coats. When a trait drifts far enough a new subspecies appears and you name it (it shows in the Codex).
  🔭 Ecology Lens: craft a Naturalist's Spyglass (2 glass, 1 copper, 1 plank) and use it on the land, or Pause → Ecology
    Lens, or /eco. Land-health map, 30-day life graphs, every species with capacity and trend, Sanctuary progress and
    field notes. Ecology feeds the Questforge (replant, lead escaped animals home, survey — never a hunt; predators are
    never quest targets) and Market prices for meat, bone, herbs and more.
  🌌 CELESTIAL ALMANAC: two moons, Lumen (8 days) and Vesper (29 days), four wandering stars, twelve named constellations,
    comets every 40-60 days, meteor showers about every 12 days, blood moons and winter auroras far north or south.
    The whole sky is computed from your world seed, so everyone in a party sees the same sky.
  🌑 Eclipses to the minute: craft an Astrolabe (2 gold, 2 copper, 1 glass) to predict eclipses, comets, showers and
    conjunctions 10 days ahead (60 days with an Observatory in the village) and set alarms. Totality falls exactly on
    the predicted minute. The sky matters: full Lumen speeds companion bonding, new Lumen strengthens dark arts,
    conjunctions bless the anvil (and Star Charts add +10 % upgrade success), showers drop star-metal ore and a comet
    starts a quest chain that ends with a Comet Ember. Pause → Almanac, the period key, or /sky.
  📜 Omens & lore: eclipses, comets and blood moons enter the Chronicle, the music follows the aurora, villagers tell sky
    stories in three voices and the Questforge reads the sky as omens. You can name a star; the name is shared with
    your party.
  🐉 Refinements: dragon horns fold flat while you ride in first person, the roc's breast barring reads at a distance,
    player name tags stay small and fade out up close (no more banner over a mech), worker wages follow the village's
    cost of living and are spent at the village market, Logic Cores can run market stalls (PRICE / STOCK / PROFIT /
    SELL / BUY / SHIP through the same host checks as players), and new worlds' markets settle before you arrive so
    early-game prices don't swing.
  Esc → "🌌 New in v2.5" lists all of this in game.

WHAT'S NEW IN v2.4 — QUESTS AND COIN
  📜 QUESTFORGE: quests come from what is really happening in your world — a town short of iron, raiders or wolves near
    the village (you drive predators off, you never hunt them), a villager's wish or feud, someone lonely, a ruin or omen the
    Chronicler noticed, a dungeon, a blueprint, a festival, the season, a celestial event, a pet to tame, your Light/Dark
    road, a dimension you haven't visited. Every quest has a "Because: …" line naming its cause. If that need goes
    away, the quest closes itself (half reward if you hadn't started; finish it for the full reward if you had).
  🔗 Sagas of 3-7 steps, complications (storm, curse, rival party, a deadline of at least a day) and forks with two
    good-faith endings. Finished quests leave lasting echoes: restored ruins, restocked towns, warmer villagers and
    entries in the Chronicle.
  🎯 Difficulty adapts to how you play, and the Chronicler leans toward the kinds of quest you enjoy (abandoning one
    tells it something too). Rewards scale with era, difficulty and chain length. You can have up to 8 active quests
    and track 3 on the HUD, which shows direction arrows and soft light beacons. Comma (,) or Pause → Quest board opens
    the board, journal and echoes.
  🪙 THE LIVING MARKET (Shift+M, or the link in the M market): 83 goods priced by supply and demand across your village,
    19 trading towns, the four dimension bazaars and travelling caravans. Production, consumption, spoilage, local
    industries, shocks (mine collapses, blights, fairs), festivals and the seasons move stock and prices, and the
    Ledger shows each good's price history. One deal can take at most 25 % of a market's stock, and dumping
    lowers the price you get, so prices can't be cornered.
  🏪 Farmers, Smiths, Mystics and Traders run shops (talk → Shop) with friendship discounts of up to 10 %. Towns post
    contracts that you hand in at the guild board. Couriers and airships carry goods between towns (fees, travel time,
    occasional storm delays). The old M market now follows the same prices.
  🏦 Bank: deposits earn about 1 % interest each in-game week (at most 500 coins a week). Loans go up to 3× your
    weekly income for a 5 % fee in 4 installments; a missed installment only blocks new loans. Merchant ranks run
    from Peddler to Merchant Prince.
    A slow governor adjusts market fees and quest/contract payouts so that coins keep their value.
  🤝 Friends: list up to 6 items on the Exchange Board (2 % listing fee, 3 % sales tax). Sellers are paid even if they
    were offline. You can also open a trade window with a player within 12 m: any change restarts a 3-second lock,
    both players must accept, and goods move together or not at all. The host checks every deal, so nothing can
    be duplicated, and repeated or flooded requests are ignored.
  🎮 Coins are earned only in the game. There is no real money, nothing to buy and no pay-to-win. All towns and
    factions are fictional.
  🐉 Refinements: the dragon has a reptilian silhouette, the roc hovers properly and particles are soft glowing sprites.
    Guests now see ability effects and other players' mech rigs. Mounted first-person eye height is correct, birds
    have barred feathers, the badger's blaze shows from the front and tamed pets have new Codex models.
  Esc → "🪙 New in v2.4" lists all of this in game.

WHAT'S NEW IN v2.3 — LIVING CREATURES
  🐺 LIVING BODIES: every animal, mob, villager, NPC, worker, mage, pet, mount, summon, construct and boss now has an
    articulated, skinned body (bones, not blocks) — necks, spines, jaws, tails, ears, wings, fins, tentacles and capes all
    move. The player has a full third-person body too (F5): walk/sprint/jump/swing, a seated riding pose on mounts, a hurt
    flinch, a cast pose and a dead pose; mounts now stand on the ground instead of sinking into it.
  👁 Eyes blink and glance around, and creatures turn their heads to track you when you come near. Magical creatures have
    emissive glowing eyes; rim light picks out silhouettes at dusk.
  🦶 Procedural, blended animation: idle breathing, walk → run → gallop, flying, gliding and swimming gaits, leaps,
    attacks with jaw/claw/tail strikes, flinches and deaths blend smoothly. Feet are planted on uneven ground (foot IK);
    cloth, hair, manes, ears and tails follow with secondary motion.
  🦓 Procedural skins: fur with directional strands, overlapping directional scales (smaller on face and limbs, larger on
    the back), feathers, chitin, hide, bark, stone, crystal and slime; darker backs and lighter bellies; texture contrast
    softens with distance. Per-species markings: wolf saddles, lynx/frog/salamander spots, stalker stripes, manticore
    rosettes, deer dapples, banded dragons and serpents, the boar's dorsal stripe, the badger's blaze, the raccoon's mask
    and ringed tail, dolphin and otter countershading, a fox's white tail tip and dark stockings, barred hawks and owls.
  ✨ Ability effects come from the body: breath jets from the mouth, spit and gaze bursts, shimmering hex shields that
    ripple when hit and shatter, healing helixes, quake rings, gust vortices, ink clouds, blink flashes, dash streaks,
    burrow spray and landing dust.
  ⚔ Combat feedback: hits spark where they land (steel/blue sparks on armour and shields), the creature flashes, and
    optional floating damage numbers rise from the wound (gold for big hits, blue when shielded).
  📖 The Living Codex (O) turntable shows each creature's animated rig (silhouette until discovered).
  ⚙ Performance: full detail up close, a lighter body at mid range, and shared instanced impostors far away; the rig
    manager spreads rig building over frames. Settings → Living creatures → Creature detail lets slower machines trade detail for speed.
  Esc → "✨ New in v2.3" lists all of this in game.

WHAT'S NEW IN v2.2 — THE LIVING STORY
  📜 THE CHRONICLER: an AI storyteller paces your world in chapters (calm → rising tension → climax → breather),
    drawing from a deck of event cards — caravans, strangers, wizard duels, golden hours, buried things — for you and
    your friends, and it eases off when you are struggling. Pick its persona when you create a world (the Bard, the
    Tyrant, the Weaver's Echo and more); J opens the Story Journal with every chapter so far. Settings → Chronicler:
    on/off, intensity cap, "fewer events". F3 shows the per-system timing overlay.
  🎼 THE LIVING SCORE: music composed live from where you are, what you face and how tense the story is. Each dimension
    has its own mode, tempo follows danger, stingers land on the beat. You have your own five-note leitmotif that changes
    a little at each milestone; bosses and legends have themes too (hear them on the Music Box).
  🪕 Bard's Lute (3 planks + 1 iron): hold it and press 1-9 — every note snaps to the current scale, and friends within
    40 blocks hear you. On touch, using the lute opens a fretboard.
  💬 KINDRED MEMORY: every villager, worker, mage, witch, caravan and goblin warren remembers what you did — gifts, rescues,
    harm, trades, help building, trampled crops, broken or kept promises. Face someone and press E to greet, gift what you
    hold, ask for rumors, request help, apologize, compliment their home, return a lost item, or (as a confidant) hear a
    personal request. A glyph over their head shows how they feel (😠 😒 🙂 😊 💖).
    Memories fade (small things in ~10 days, big ones in ~60) and personalities matter (kind, greedy, honest, brave).
    Gifts count for at most +25 a day and the same gift again is worth half as much.
  🗣 Gossip: people trade stories each in-game hour — up to three people away, weaker each retelling, and sometimes
    wildly exaggerated. Read what is being said in Codex (O) → Rumors.
  💖 Friends give discounts, morning gifts, hints and help in a fight; workers' morale follows their opinion of you;
    goblins learn to avoid the home of someone who caught their thieves. Villages pick a mayor from the best-liked.
  🕯 Apprentices inherit their mentor's strongest memories. When someone dies, their friends carry what they knew;
    place a Memorial Stone (3 cobble + 1 red flower) to honor them.
  Esc → "✨ New in v2.2" lists all of this in game.

WHAT'S NEW IN v2.1
  🏠 HEARTH GUARD: craft a Hearthstone (4 cobble, 1 gold, 1 Ember Shard; Ember Shard = 2 coal + 1 iron) and place it to
    claim a 32×32 home (expandable to 128). Friends get trust tiers (Co-builder / Guest / Stranger): strangers can look
    but not touch, containers, machines and mounts are protected, and the host enforces it. Every block change in a claim is recorded,
    so griefing can be rewound (/hearth rewind 10), and repeat griefers are frozen automatically. H shows claim borders.
  🦉 MENTOR & LIVING CODEX (O): an encyclopedia of 630 pages in 12 categories that fills itself in as you see, mine,
    craft, tame and fight things, each with a rotating 3D model, lore, stats, links and when/where you found it.
    Search, filters, "What next?" suggestions, and share pages with friends (they see a silhouette until they find it).
    The Mentor owl offers short lessons only for things you haven't shown you can do, at most one tip per 5 minutes,
    with Off / Quiet / Helpful modes and optional read-aloud. Hosts can switch on "Mentor for my guests".
  💨 Stamina: sprinting costs stamina (HUD bar), it regenerates when you slow down, and a good meal makes it last.
  ⚔ Light vs Dark duels (multiplayer, opt-in): challenge a player on the opposite road, away from villages. Duels are
    non-lethal (first to 0 duel-HP yields), consent-based, and never touch villagers. Turn challenges off in Settings.
  🩺 Infected beasts: a real quest to weaken, cleanse (Cleansing Salve) and free a blighted beast — a Radiant Deed.
  ✨ Companion evolutions now visibly change your pet (Ascended, Dawnkin, Umbral looks).
  🌗 Hosts save each friend's Light/Dark road by player id, so it is restored when they rejoin.
  Phones: clearer touch tutorial. Third person: crosshair offset/hidden and the held item hidden.
  Esc → "✨ New in v2.1" lists all of this in game.

WHAT'S NEW IN v2 (highlights)
  Eras (Primal → Cosmic) with a tech tree · 44 weapons across 6 eras with 35 enchantments · evolving bosses
  Seasons, festivals, weather fronts, tornadoes and cataclysms · farming, brewing and the dungeon vaults
  Airships · creature codex, companions and mounts · blueprints, workers and growing villages
  Wayfarer bands and their Pact · elemental magic schools, goblin warrens and the Forbidden Arts
  THE CROSSROADS: reach the Arcane era with a magic school at level 5 and a shrine rises nearby. Choose a road — forever:
    🌑 Dark: Forbidden Arts I–VII, then Umbral Sovereignty (shadow-step, a Shade legion of 3, +40 % during eclipses).
    ☀ Light (rarer): needs 3 Radiant Deeds and an aurora or full-Lumen night (every 8th night). Tiers: Dawn Ward,
      Mending Light, Sun Lance, Sanctuary Dome, Halo of Many, Phoenix Rite, Dawnbringer Form, Solar Covenant — each
      earned through a trial (protect, heal, sacrifice, restore) at a Dawn Altar (4 gold, 2 lumen, 1 relic).
    Sub-schools at tier IV, talents, a fusion spell, relics, oaths and pacts, hunters and inquisitors, an Apex boss
    and an ending. Twilight Penance (a long quest) resets your road — and keeps nothing. No power can hurt villagers.
  Achievements & trophies, accessibility options, Ultra graphics, World Chaos, third-person camera, smoother movement.

SAVING
  Autosave every 30 s, on dimension change, and when you close or hide the tab ("saved Ns ago" chip top-right).
  Esc → Worlds & backups: 4 named world slots + the Daily slot, Export (.json backup file), Import, rename, delete.

PLAYING WITH FRIENDS (peer-to-peer, free, no accounts)
  v2.1, v2.2, v2.3, v2.4 and v2.5 play together (v2 still connects too). The living ecology, Ecology Lens and star
  naming need a v2.5 host (a v2.5 guest at an older host is told so); the sky itself is computed from the world seed, so
  v2.5 guests see the almanac sky at any host. Older guests see the old sky and wildlife.
  Guests see the host's creatures, pets and helpers with v2.3 bodies, and see
  friends seated on their mounts. Party quests and the living Market need a v2.4 host. Everyone in a party gets the full
  reward, and members who are offline are paid when they come back. Older guests just don't see these features. Story, score and Kindred talk turn on when the host runs v2.2 or later (a newer guest at an
  older host just plays without them); v2.1-only features such as claims, duels and Codex sharing switch off for v2 players.
  v1 can't join v2–v2.5 games (or host for them): the game refuses politely and explains who should update.
  Kindred memories, the Chronicler, quests, the market, the ecology and the music are run by the host and saved in the host's world.
  Host (you):
    1. Open voxel-sandbox.html, load or create a world.
    2. Press Esc → "🌐 Host for friends" → "Host & get a room code".
    3. A 5-letter room code appears (e.g. K7QPM). Send it to your friends any way you like.
    Keep your tab open: your computer runs the world (mobs, bosses, weather) and saves it.
  Each friend:
    1. They need the same voxel-sandbox.html file (send them the zip) and an internet connection.
    2. Open it → on the title screen press "🌐 Multiplayer — join a friend".
    3. Type a name, enter the room code, press Join. They spawn next to you within a few seconds.
  In game: T to chat; you see each other's names, building, sprinting, spells, Light/Dark auras and mobs.
  A Light player and a Dark player fighting side by side form an uneasy alliance (+10 % power, /path twilight combo).
  If "Join" can't find the room (strict network, or the free PeerJS server is down), use the manual invite:
    Host: Esc → Host for friends → "🔧 Manual invite" → Create invite code → Copy, send it to the friend.
    Friend: title screen → Multiplayer → "🔧 Manual invite" → paste it → Make reply code → Copy, send it back.
    Host: paste the reply code → Connect. (One invite per friend.)
  Note: very strict firewalls on BOTH sides can block any direct peer-to-peer connection.

TECH NOTES
  Chunk generation stays on the main thread, time-sliced, because World.POST hooks touch game state; meshing runs in
  Web Workers. v2.3 creatures are skinned meshes merged to a few draw calls each (one per material), with shared
  geometry per species, a lighter mid-range LOD and InstancedMesh impostors; skins and coat patterns are procedural in the
  shader (no image files). v2.4's market runs as typed arrays (30 markets × 83 goods, about 0.3 ms per in-game
  hour) and saves compactly (about 70 KB). Market deals are host-authoritative with escrow and idempotent transaction ids. v2.5's ecology is a
  Lotka-Volterra-style model per 64 × 64 cell (20 overworld species plus dimension food webs) stepped hourly on the host;
  the almanac is a pure function of seed and time (eclipse contacts found by bisection), costing about 0.01 ms a frame.
  Multiplayer uses WebRTC data channels with PeerJS's public signaling server (or copy-paste invites).
