VOXEL MYTHOS — a living voxel sandbox (v2.9 “True World”)
==========================================================

PLAY: double-click voxel-sandbox.html (Chrome, Edge, Firefox or Safari). One self-contained file, no install, no
internet needed to play solo. Worlds save in this browser automatically. v1 through v2.8 saves (including v2.7 hotfix 1) load in v2.9 unchanged (same storage keys;
v2.8 only adds small new sections for block states, the world's memory of what happened where, Watch Bells, Defense Nights,
Guard preferences, favorites and recipe pins, plus safety copies kept separately in the browser). v2.9 adds only a few True World settings. A v2.8 world still opens in v2.7.1 and older: the new sections are kept but ignored
(a world larger than about 1.5 MB opens there as a small placeholder that says it needs v2.8; its full copy stays safe). Existing worlds keep
their land: ruins and the Strata layers (v2.7) appear only in chunks generated after that update, and the Frontier (v2.8) only begins beyond
the farthest place you have built. In v2.6 and older, the v2.7 blocks
(deepstone, ores, ancient bricks, plinths) appear as a familiar stand-in such as stone, bricks, cobble or dirt instead of disappearing.

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
    W A S D .......... move (diagonals are normalized — same speed in every direction)
    Shift (hold) ..... sprint, ~1.6× speed with a FOV kick; uses stamina (green bar above the hotbar) (also double-tap W; "Toggle sprint" option in Accessibility)
                       Sprint also works on mounts. Shift descends while flying.
    Space ............ jump / swim up / fly up        C descend while flying
    Walking into a 1-block ledge steps up onto it smoothly (setting "Step-up onto ledges").
  Acting
    Left click (hold)  mine / attack      Right click  place · eat · use · talk · tame · ride
    1-9 / wheel ...... hotbar             0  cast your bound Light/Dark path power (duel bolt in a duel)     -  Crossroads / Light panel
    E inventory & crafting   M market (Shift+M living Market)   , (comma) quest board & journal   F talk   T or / chat & commands   Q cast spell   G map & realm
    R mount / dismount / land   V thermal vision (Stress View while holding the Engineer's Hammer)   X weapon ability   B armory   N tech tree   J Story Journal (Shift+J creature codex)
    O Living Codex (Shift+O party)   U Field Journal (Shift+U trophies)   Y gallery   H Hearth claim view (airship camera on a ship)
    .  (period) Celestial Almanac — while looking up at the night sky it toggles star & planet labels instead
    ;  (semicolon) or middle-click: ping the spot you look at for your party (Shift: everyone) — multiplayer, v2.7.1
    ' (apostrophe) quick-chat wheel   [ emote wheel — hold, steer with the mouse, let go — multiplayer, v2.7.1
    L spellbook   I journal   Z blueprints   K save now   Esc pause   F3 performance overlay (v2.8: also the slowest tick hooks)
    Shift+F8 ......... 🩺 Report a problem (also /report, or Esc → 🩺 Report a problem) — v2.8
  Guard (v2.8)
    Right mouse (hold) with a weapon or bare hands: block (less damage, uses stamina). Start the block just before a hit to
                       parry: the attacker staggers; hit a staggered foe to counter (it is knocked out, never killed).
    Left Alt ......... dodge: a quick sidestep with a moment of safety
    ; (hold) ......... ping wheel: Threat, Trap, Help, Look, Loot, Dig, Danger, Ring the nearest bell (a quick tap still pings)
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
  New in v2.6: /bucket [level N|all|empty]  /ww [stats|settle (creative)|on|off]  /ls [view|physics on|off (creative)]
  New in v2.7: /realm [council|vote N|found <name>|stance <choice>]  /banner (Banner tab)  /strata (Field Journal)  /friends (where your friends are)
  New in v2.7.1: /party [invite <name>|accept|leave] (Esc → 👥 Party)  /ping [look|danger|loot|dig|help] [all]  /wp [add <name>|list|del <name>]
    /travel <name>  /netstat (connection health)  /emote <name>|stop  /qc 1-8  /fellow social on|off
  New in v2.8: /report and /diag (Report a problem)  /firstnight (a gentle first Defense Night)  /votekick <name>  /mute <name>
  Creative only: /dim ember|canopy|tidal|void|over /boss /give /time /weather /fly

WHAT'S NEW IN v2.9 — TRUE WORLD
  🌍 TRUE WORLD LIGHTING (every quality level): the sky now lights the world the way it looks. Land under a floating island
    is softly shaded instead of turning black, overhangs and cave mouths fade gradually into shadow, and the sun leaves
    shade on the side of hills and buildings that face away from it. Lanterns, lava, crystals and glowing ores give off
    their own colored light, and on Medium and up that light bounces off nearby walls (a lantern in a red room fills it
    with a warm red glow). Rooms full of lanterns now light up properly even near a big lava sea.
  🌅 A REAL SKY: the sky is a gradient now, blue overhead at noon and deep violet over an orange horizon at sunset, and
    distant ridges fade into blue-gray haze toward the sky instead of a flat band of fog.
  👁 EYE ADAPTATION: step into a dark cave and your eyes adjust over a few seconds; step back into daylight and the
    glare fades.
  🌬 WIND: gusts now travel across fields. Plants, leaves, rain and banners all feel the same wind as each gust passes.
  ☀️ SOFT SUN SHADOWS (High): real shadows from the sun on High (they used to be Ultra only), crisp where an object
    touches the ground and softer further away, like real sunlight. Ultra's shadows get the same soft edges.
  ✨ SMOOTHER EDGES (High): temporal anti-aliasing smooths jagged edges on blocks, fences and leaves.
  🚩 CLOTH BANNERS (Medium and up): realm banners are real cloth now. They hang limp in calm air, stream out in a
    storm and swing when the wind turns. Reduced motion keeps them still.
  👥 STEADIER MULTIPLAYER: if the host's computer freezes for a few seconds (for example while saving or loading a new
    area), friends now wait for it instead of dropping and rejoining.
  Every part has a switch in Settings → Graphics → 🌍 True World.

WHAT'S NEW IN v2.8 — BEDROCK
  🛡 SAFER SAVES: every save is now also kept in a second browser store (IndexedDB), with the last 6 versions of each world
    and a short journal of your latest edits. A crash, a closed tab or a full disk loses a few seconds at most; if the quick-save
    copy is ever damaged, the game opens the safety copy and tells you. Esc → 🛡 Save safety shows what is kept, restores an
    earlier version, and exports or imports a .vmworld file. A .vmworld file carries a checksum for every part, so a damaged or
    edited file is refused instead of half-loading. Plain .json backups from older versions still import.
  🌍 ENDLESS WORLDS: new worlds no longer repeat as you travel. Land keeps generating out to the World's Rim, 30 million blocks
    from the center in every direction (about a year of walking; flying gets you there sooner). Past the heartland, the Frontier
    holds hamlets, ruins and faction outposts, grouped into named Marches with discovery notes and distance milestones. Only
    the chunks you change are saved, so a long journey doesn't grow your save, and the view stays steady far out (the renderer
    re-centers itself as you travel). Older worlds keep their land; a world that was built on past 20,000 blocks keeps its
    classic terrain everywhere.
    Why a Rim at all: positions are checked and sent to friends in a compact form that tops out just past 30 million blocks,
    and the game's numbers lose precision beyond that. At the Rim the land ends in a soft edge and the game tells you.
  🎞 A NEW LOOK: a color grade with a mood per biome on every quality level, ores, lava and lanterns that glow at
    night, rain that wets the ground with ripples and splashes, and photo-mode depth of field; on High also a filmic tone
    curve, soft bloom, height fog and light shafts. Settings → Graphics → 🎞 Look & light.
  ☀️ TRUE LIGHT: puddles that form in rain, gusts that sweep across fields, and water that stays clear and green in the
    shallows and turns deep blue further out, with foam on the shore (Medium and up); plus sun glints on wet and smooth
    surfaces and grass that bends as you walk through it (High). Low is unchanged. Settings → Graphics → ☀️ True Light.
  🔔 WATCH BELLS: place a Watch Bell with Tripwires or Pressure Plates nearby. When something crosses, the bell rings a code:
    1 ring for a beast, 2 for raiders, 3 for something big (ring it by hand for 4: a call to arms). Everyone in your party
    hears it with a caption naming the threat, the bell and its direction. Players and pets never trip wires.
  🏰 DEFENSE NIGHTS (opt-in, off by default): raiders come for your Raid Chest, and only the Raid Chest: the coins you
    choose to put in it. Homes are never lost: raiders never break blocks, explosions inside claims are stopped, and anything
    else that changes inside a claim during the night is put back at dawn. Dying to a raider costs no coins; knock a raider out
    and what it carried drops back. /firstnight starts a gentle first night with a guide.
  🗡 GUARD: creatures now show a short wind-up (a red glint and a warning tone) before they swing. Hold right mouse to block,
    block just before the hit to parry, then strike the staggered foe to counter. Left Alt dodges. Guard works at any frame rate.
  💥 COMBAT FEEL: a brief hit-stop on solid hits (30-70 ms, on screen only, so a multiplayer world never pauses or drifts),
    a short stagger on creatures, a swing trail and clearer hit feedback. Screen shake 0 means no camera kick at all.
  🎒 INVENTORY AND CRAFTING: a search box, ★ favorites (a favorite can't be sold and quick-stack never moves it), up to 3
    recipe pins on your screen with a live ingredient checklist, and quick-stack into nearby Site Supply Chests.
  👥 SMOOTHER MULTIPLAYER: if the host leaves, the world moves to the next player within seconds, now also for a friend who was
    still loading. New guests can't use TNT, fire or fluids for their first 10 minutes in a world unless the host trusts them.
    /votekick (a majority of v2.8 players, 30-second vote), /mute, and an optional chat word filter keep games friendly.
    When a bell rings, nearby friends get a small "Help defend?" card with a marker to follow.
  ♿ EVERYONE PLAYS: every important sound has a caption with an urgency icon (so color is never the only signal) and a
    direction when the game knows where it happened; a high-contrast option; color-blind palettes for the new interface; and
    comfort settings that really turn things off: screen shake at 0 means no shake at all, and "Limit flashing lights" caps
    lightning, blasts and fireworks.
  🩺 REPORT A PROBLEM: Esc → 🩺 Report a problem (Shift+F8, /report) shows recent errors with the part of the game they came
    from, the frame rate, settings and boot timing, and builds a report you can copy or open as a prefilled issue. Player names
    are removed. Nothing is sent anywhere unless you choose to.
  ⚙️ STEADIER FRAME RATE: on Auto quality the game measures your display and picks a target (30, 50, 60 or 72 fps). It steps down
    within about 2 seconds when the game struggles (view distance first when the processor is the bottleneck, otherwise
    resolution, then the quality level) and steps back up after 15 calm seconds.

WHAT'S NEW IN v2.7.1 — FELLOWSHIP
  👥 PARTIES OF UP TO 8: in a multiplayer world, Esc → 👥 Party (or /party) invites friends. Quests a party member accepts
    are shared: everyone's progress counts and everyone gets the full reward. The Party log keeps the story. Party members
    stay on your minimap, map and party frames wherever they are; a friend in another dimension shows with a hint to the
    portal that leads there.
  📍 PINGS: middle-click or ; pings the spot you look at — Look here, Danger, Loot, Dig site or Need help. Your party sees it
    in the world, on the new compass strip, the minimap and the map; Shift pings everyone. Pings are rate-limited and work
    up to 120 blocks away.
  📌 SHARED WAYPOINTS: up to 20 per world (8 per player), shown as light beacons, on the compass and on both maps. Add them
    from the Party panel or with /wp add <name>. Only the player who placed one, or the host, can rename or remove it.
    Waypoints are saved with the host's world.
  ✨ TRAVEL TO A FRIEND: hold still for 2 seconds and arrive beside a party member. A trip costs 20 coins and has a 5-minute
    cooldown, or is free with a Kinstone (gold + essence, used up on arrival). Not during a fight, never into a Hearth claim
    where you aren't trusted, and every player chooses in the Party panel who may travel to them (party, anyone, nobody).
  🖌️ DIG TOGETHER: brush the same Buried Find with friends. Every stroke counts toward one shared find, it goes faster with
    more hands (up to ×2.8 with four), and everyone nearby gets Lore and their name in the Field Journal.
  ⚔️ FAIR FIGHTS FOR GROUPS: hostile creatures near a party grow with its size (more health, slightly more damage, a few
    extra foes for big groups), so a group of friends still meets a challenge. Solo play is unchanged; falls, fire and
    drowning are never scaled.
  🛟 BACKUPS: every world keeps its last 6 snapshots (one every 5 minutes of saving) and one per day for 7 days, stored
    separately in the browser. Esc → Worlds & backups → 🛟 Backups restores one; a damaged save offers the newest backup
    on the title screen. Restoring also rolls each Hearth ledger back to the same moment, so the Rewind history matches the
    world. The game asks the browser to keep its storage (persistent storage) where that is allowed.
  🔗 STURDIER MULTIPLAYER: every message is checked and rate-limited, oversized or malformed traffic is dropped, and a
    peer that keeps misbehaving is disconnected. If the host leaves or loses connection, the world passes to the next
    player and everyone carries on, within seconds. When the original host comes back, the world goes home to them with
    everything that was built in the meantime. Manual-invite games survive a host change too. A world is tested with 8 players (bigger groups depend on the host's upload and are not yet tested):
    snapshots are binary and delta-coded, each guest gets what is near them, within a per-guest budget.
  🚩 REALM REFINEMENTS: one merged faction list on the map, banners standing in the world as real 3D cloth flags, more
    varied ruin inscriptions (no more repeats at one site), a proper 3D Museum Plinth, and the Council clock shows the right
    time for players who join in the middle of a council.
  🤝 CO-OP-ONLY QUESTS: while a party of 2 or more is online, the quest board offers jobs no one can do alone. Only a
    player in a party can accept them, and the whole party shares them. Twin-Lever Vault: two levers 22 blocks apart
    spring back after 2.5 seconds, so two friends must hold them at the same moment. Jacketed fossil: a plaster-jacketed
    find moves only while two friends carry it together, at walking pace, to the camp lamp. Primeval: tame one together
    (below).
  🦣 DUO TAMING: Primeval grazers (big, calm elk, yak, tortoise or deer) trust only two tamers at once. One friend
    stands at its head holding food it likes and feeds it on its heartbeat (right-click), while the other soothes it
    from behind, moving gently. After four beats each it bonds: the feeder keeps it, and the friend is named its co-owner
    on the companion card.
  ⚑ COUNCIL VOTING BLOCS: a party can vote as one at the Grand Council. The leader forms the bloc and picks the edict it
    backs; members join with one click. Every member's own vote weight counts (a member without standing still adds a
    voice of 1), and a united bloc of two or more adds +1 per member. Bloc results are remembered in the realm log and the
    Party panel.
  📖 PARTY CODEX CREDIT: when anyone in your party discovers a new Codex page, every member gets the page too, marked
    "discovered by <friend> (party credit)". Friends who join the party later catch up on what it has found. Common block
    and item pages arrive quietly with one summary line.
  👋 EMOTES & QUICK CHAT: hold ' (apostrophe) for the quick-chat wheel or [ for the emote wheel, steer with the mouse and
    let go (tap for a wheel that stays open; 1-8 or click picks). 16 emotes use the existing character animations: wave,
    cheer, point, bow, three dances, sit, laugh, clap, facepalm, thumbs up, shrug, salute, kneel and sleep. Wave, cheer,
    thumbs up or clap facing a friend for a high five; dance together and you fall in sync. Quick chat has 40 phrases
    (8 on the wheel, chosen in the Party panel) and fills in [ping], [held item] and [here] for you. It only sends set
    phrases, so it is safe in any group. /emote <name> and /qc 1-8 do the same from chat.
  🌐 JOIN CODE BY YOUR COINS: the room code now sits right next to the coins counter. Hosting shows your code with a
    one-click 📋 Copy button (tooltip: "Share this code so friends can join"); a guest sees the code of the world they
    joined; in single-player a compact 🌐 Host button opens the world to friends and then shows the code. It follows a host
    change or a new code, hides in photo mode, can be reached with Tab while the mouse is free (Esc) and has screen-reader
    labels. It never covers a menu: in the pause menu it moves into the menu's empty top corner (still one click to copy),
    and it steps aside while any other menu or a dialog is open. A manual-invite session has no room code, so it shows the host's name and an Invite button instead.
  NOT IN THIS RELEASE (moved to v2.8, named so nothing is dropped silently):
    • Co-op escort and siege-parley quests: v2.7.1 ships three co-op quest types (Twin-Lever Vault, jacketed fossil,
      Primeval). The other two need escort pathing and council hooks that were not ready to the same standard.
    • Co-op builds and Wonders hooks, and a shared party museum: group digs ship; building together and a shared museum
      come with Fellowship part B.
    • The co-owner of a duo-tamed Primeval is named on its card but cannot yet command or ride it; only the feeder can.
    • Relay assist for bigger groups: host + 7 (8 players) is what the release is tested with; bigger groups depend on
      the host's upload, and a relay fallback comes later.
    • Emotes use the existing character animations; blended emote animation arrives with the Living Flesh update.
    • If the host leaves while you are still loading into their world (the first few seconds after joining), your game
      does not follow the new host yet; rejoin with the room code.

WHAT'S NEW IN v2.7 HOTFIX 1 — JOINING BY CODE (included in v2.7.1)
  🔗 Joining a friend by room code works on far more networks. Before, the game only used STUN servers, so two players
    behind strict or carrier-grade NAT (mobile data, hotspots, school or work Wi-Fi, many home routers) could find the room
    but never connect. The game now also uses PeerJS's free public TURN relays (over UDP and TCP).
  🔗 The code box accepts a code however it was pasted: lowercase, with spaces or dashes, "vxm-abcde", "Room code: ABCDE"
    or a link ending in ?room=ABCDE. It keeps the last code you typed, and Enter joins.
  🔗 Join tries 3 times (the last try goes through a relay) and says what went wrong: no world hosted with that code
    (codes never use O, I, L, 0 or 1), the room was found but your network blocked the connection, the host didn't answer,
    or the free matchmaking server couldn't be reached. A host whose tab was in the background registers its code
    again when you come back to it.

WHAT'S NEW IN v2.7 — REALMS AND RUINS
  🚩 BANNERS OF THE REALM: five fictional factions now hold regions of the world, each with a capital, borders, values and a
    leader who remembers what you did. They trade, sign treaties, quarrel over borders, lay sieges and make peace. The Map
    (G) has a realm overlay and Diplomacy, Council and Banner tabs (/realm).
    Your own banner: any group of friends (1 or more) can raise a banner and design its crest (/banner). Regions where
    members hold a Hearth claim become banner land. Factions treat banners as peers: envoys, treaty offers carried by
    Wayfarer couriers, trade pacts (15 % off at their towns, a small banner tax on sales) and rivalries. An offline
    banner is frozen and is never besieged.
    The Grand Council meets every 7 days at a neutral site. Factions and eligible players (standing 25+, or a landed
    banner) vote on one of three edicts: bridge-building, free trade, a truce, an arcane ban in Verdant lands, or
    scholarship. An edict lasts 7 days and really changes quest rewards, prices, raids, magic and research.
    Reputation: relieve a siege, mediate one, carry word as an envoy or help an exiled people return, and your standing
    rises; break a treaty and gossip spreads. Questforge, the living Market, the Chronicler and Kindred gossip all follow
    the politics.
  🪨 STRATA: the deep world has layers. Deepstone starts below about y 18 and Primeval rock lies near the bottom, with
    three new finds: Orichalcum, Amber and Fossils.
  🏺 ANCIENT RUINS: each world has a seeded history of 3-6 lost cultures across 20,000 years, each with its own name, god,
    building style and script. They left buried cities, temples, observatories, tombs and battlefields. Some peek out
    at the surface; the rest wait under the ground.
  🖌 ARCHAEOLOGY: craft an Archaeologist's Brush (stick + copper) or a Trowel (stick + iron). Three careful brush strokes keep a
    Buried Find intact; a trowel is quicker but rougher; a pickaxe or an explosion breaks it. Restore finds, show them on
    Museum Plinths (4 cobble + 2 planks) and earn Lore and boons: ancient building styles, old weapon patterns and
    faster deciphering.
  🔣 LOST SCRIPTS: every inscription you read reveals glyphs of that culture's script; at 60 % the meaning shows. Observatories
    still count the nights to the Almanac's next comet, and one inscription remembers the Sundering of Light and Dark.
  📔 FIELD JOURNAL (U): sites, finds, scripts, a timeline of the deep past running up to the Present Age of your own Living
    Mythos, and your museum. Trophies moved to Shift+U (also a button at the top of the journal). Curious villagers
    sometimes tell legends that point to a ruin, the quest board offers excavations, and dungeons name the culture that
    built them.
  🧱 STURDIER BUILDING (refinements): plank decks fail from the free end, wave by wave, instead of all at once; falling
    debris is textured; the Stress View turns red only past breaking point; old stone grows moss; settled water lies
    level; /build shapes and blueprints are checked for load when placed (they brace themselves with short props).
  👥 FRIENDS ON THE MAP: other players show on the minimap and the big map (G) as colored arrows with their names. When a
    friend is out of range the arrow waits at the edge, points the way and shows the distance. /friends lists everyone's
    distance and direction. It uses the player positions the host already sends, so it adds no network traffic.
  🔗 MULTIPLAYER: a v2.7 host shares the realm and the dig record with every v2.7 player. Logic Core settings, crate orders,
    taming requests and potions now sync between players (an old bug).
  Esc → "🏺 New in v2.7" lists all of this in game, and Esc → "❔ Help & Controls" has a "Realm & ruins" section.

WHAT'S NEW IN v2.6 — ELEMENTS AND ENGINEERING
  💧 WATERWORKS: water, lava and four new fluids (mud, honey, mana-essence and void-tar) now have real levels from 1 to 15.
    They pour, spread, find their level, fill basins and push through U-bends under pressure. Existing lakes and seas
    stay calm until you change them. Break a dam and the valley floods, then settles. The host runs the simulation
    with a fixed budget per tick, close to players. Areas no one is near freeze and pick up again when someone returns.
  🌋 Fluids react: water on lava makes obsidian (or basalt from thin lava) with steam. Mana and void-tar cancel out in a
    flash, and every 8 units leave a Twilight Crystal. Lava sears honey and tar. Water wets nearby farmland, and ash
    carried downstream feeds the crops it passes.
  🏞 Living rivers: rivers remember where they flow and, over many days, wear soft beds deeper and drop sand where the
    water slows (claimed land and anything you built are never eroded). Rain refills old riverbeds and hollows, puddles
    dry in the sun, ice keeps its level when it freezes, and wellsprings bubble up forever.
  ⚙ Water machines (Logic Core): the Water Wheel turns flowing water into power and drives belts and drills. The Pump lifts
    water, the Valve balances two sides, the Sluice Gate opens on a signal, the Aqueduct carries water across flat land
    and the Level Sensor reports the depth. Build canals, mills, locks and fountains.
  🪣 Bucket (3 iron): right-click to scoop up to 15 levels or pour. Click the HUD chip (or use /bucket level N) to pour
    only up to 4, 8, 12 or 15. Hold Shift to force a pour. In multiplayer, the host checks Hearth permissions for guests.
    The Ecology Lens has a new 💧 Hydrology tab showing depth, riverbeds and flow.
  🧱 LOAD AND STONE: what you build now has to stand up. Every block has a strength, a weight and a span (how far it
    can reach from support). Stone reaches about 4, wood 5, Iron Beams 12 and Weaver Silk 32. Long overhangs, wide
    floors and top-heavy towers can fail. A failing block cracks and creaks for 2 seconds, so you can prop it up. Then it
    falls as real debris that can hurt you (2-8 damage; Creative is immune). Some of it settles as rubble and the rest
    drops as items.
    Builds from before v2.6 are not suddenly knocked down. Anything already over its limit is left as it is (Stress
    View shows it in violet). It is checked again only when an edit makes it worse.
    Only changes made by players are judged (placing, mining, explosions, guests' edits, and river erosion). Villages,
    camps, mage towers, warrens, airship frames and /build structures are never knocked down by the world itself.
  🏛 Building that stands: stepped stone arches and corbels reach twice as far and carry four times the load.
    Buttresses strengthen walls taller than 8. Soil soaked with water is half as strong. Rain and snow slowly weather
    exposed blocks (up to -20 %), and hired workers patch the weathering at dawn.
  🔨 Engineer's Hammer (2 iron + 1 plank): right-click a block you built to reinforce it (+50 % strength and span, costs
    1 iron). Shift+right-click reads its load. Press V while holding the hammer to open Stress View: green blocks carry
    their load easily, yellow ones are working hard, red ones are over their limit, violet ones are old builds left
    alone, and flashing ones are about to fall. Iron Beam (3 iron → 2), Weaver Silk (aether + essence + 2 red flowers
    → 4) and the Stress Sensor (2 iron + 1 glass) are new blocks. The Stress Sensor sends the load of the block above
    it to the Logic Core, so you can wire up a collapse alarm. After three collapses the Mentor offers an engineering
    lesson and shows a ghost pillar where one would have helped. Creative worlds can switch physics off (/ls physics off).
  ✨ Refinements: the village market is busier and sells Tanned Hide (gathered from shed coats, no harm done). Comets
    are bigger, and "Show me" frames the head with its tail. Nest Boxes and star-metal ore now appear as planks and
    iron ore in versions that don't know them. The late-game economy governor wobbles less.
  Esc → "💧 New in v2.6" lists all of this in game, and Esc → "❔ Help & Controls" has a "Water & building" section.

WHAT'S NEW IN v2.5 — WILD SKIES
  🌿 LIVING ECOLOGY: every 64 × 64 patch of land tracks plants, water, soil and the animals living there. Hares and deer
    feed lynx, owls and wolves; herds follow the seasons between biomes and you can watch them migrate past. Hunting,
    taming and farming all change the numbers, and the animals that spawn around you come from what really lives there.
    The simulation is kept in bounds (a full in-game year was tested with no runaway or vanished species).
  🐺 Keystones & Sanctuaries: each biome has a keystone species. Lose the wolves of a forest and it slowly withers, its
    colors fading. Plant saplings, dig ponds, place Nest Boxes (3 planks + 1 stick) and release companions to bring life
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
    19 trading towns, the four dimension bazaars and traveling caravans. Production, consumption, spoilage, local
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
  ⚔ Combat feedback: hits spark where they land (steel/blue sparks on armor and shields), the creature flashes, and
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
  v2.7.1: 🛟 Backups per world (last 6 snapshots + one per day for 7 days), restore from that list or from the damaged-save prompt.
  v2.8: 🛡 Save safety (Esc menu): a second copy of every world in IndexedDB with 6 earlier versions and a journal of recent
    edits; restore any of them, or export/import a checked .vmworld file. Safari can clear website data after a week without a
    visit, so on Safari the game reminds you to export now and then.

PLAYING WITH FRIENDS (peer-to-peer, free, no accounts)
  v2.8 plays with v2.7.1 and older (v2.8 guests and hosts use the same connection). Watch Bell alerts, the ping wheel, "Help
  defend?", block states and vote-kicks need v2.8 on both sides; v2.7.1 guests at a v2.8 host get alarms and defense news as
  chat lines and play normally. In an endless v2.8 world a v2.7.1 guest sees the same land near the center but different
  land beyond about 27,000 blocks, and no Frontier sites; they are told so when they join.
  A friend who is still loading when the host leaves now follows the new host automatically.
  v2.1 through v2.7.1 play together (v2 still connects too). Parties, pings, waypoints, travel, digging together and host
  hand-over need v2.7.1 on both sides: v2.7 and older guests still join a v2.7.1 host and play normally, see "everyone" pings as
  chat lines, and are left out of parties; if the host leaves, they are disconnected and rejoin with the new room code the new host
  sees (v2.7.1 guests follow the hand-over automatically).
  v2.1 through v2.7 play together (v2 still connects too). The realm and the dig record need a v2.7 host; v2.7 players
  at the same host see the same ruins (computed from the seed) and the same politics. v2.6 and older guests join a v2.7
  game and just don't see these features (new blocks they meet appear as stand-ins; the v2.7-only realm and dig data are left out of what they receive); a v2.7 guest at an older host is
  told that world has no Strata. In a v2.6+ game the host runs the water and decides what
  collapses. v2.6 guests see water levels change smoothly and watch the same falling debris, because every peer computes
  it from the same seed. Guests on v2.5 or older see the result as ordinary blocks, with familiar stand-ins for the new
  v2.6 blocks. The living ecology, Ecology Lens and star naming need a v2.5 or later host (a v2.5 guest at an older host
  is told so). The sky itself is computed from the world seed, so v2.5 and v2.6 guests see the almanac sky at any host.
  Guests see the host's creatures, pets and helpers with v2.3 bodies, and see
  friends seated on their mounts. Party quests and the living Market need a v2.4 host. Everyone in a party gets the full
  reward, and members who are offline are paid when they come back. Older guests just don't see these features. Story, score and Kindred talk turn on when the host runs v2.2 or later (a newer guest at an
  older host just plays without them); v2.1-only features such as claims, duels and Codex sharing switch off for v2 players.
  v1 can't join v2–v2.7 games (or host for them): the game refuses politely and explains who should update.
  Kindred memories, the Chronicler, quests, the market, the ecology, water, structures, the realm, the dig record and the music are run by the host and saved in the host's world.
  Host (you):
    1. Open voxel-sandbox.html, load or create a world.
    2. Press Esc → "🌐 Host for friends" → "Host & get a room code".
    3. A 5-letter room code appears (e.g. K7QPM). Send it to your friends any way you like.
    Keep your tab open: your computer runs the world (mobs, bosses, weather) and saves it.
  Each friend:
    1. They need the same voxel-sandbox.html file (send them the zip) and an internet connection.
    2. Open it → on the title screen press "🌐 Multiplayer — join a friend".
    3. Type a name, enter or paste the room code, press Join (or Enter). They spawn next to you within a few seconds.
       If the first try fails the game retries twice by itself, the last time through a relay.
  In game: T to chat; you see each other's names, building, sprinting, spells, Light/Dark auras and mobs.
  A Light player and a Dark player fighting side by side form an uneasy alliance (+10 % power, /path twilight combo).
  If "Join" still can't connect (a very strict network, or the free PeerJS server is down), the message says which, and you can use the manual invite:
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
  v2.6 water is a leveled-cell simulation with a capped active set (40,000 cells), a fixed per-tick cell budget and
  an adaptive radius (32-128 blocks). It is sent to v2.6 guests as per-chunk run-length diffs 5 times a second and
  smoothed at 20 Hz on screen. Erosion scoring runs in a Web Worker. Load and Stone solves only the connected structure
  around an edit, using typed arrays and capped at 4,096 blocks; blocks past the cap count as anchored. Typical edits
  take well under 1 ms, and a solid 16×16×16 cube takes about 12-20 ms. Falling debris is one instanced mesh of up to
  300 blocks, stepped with fixed 1/60 s physics from a shared seed.
  v2.7's realm steps once per in-game day on the host (about 0.3 ms at the 95th percentile) and saves in about 9.5 KB (240 simulated days). The
  deep history is a pure function of the seed (a 200-century simulation on a 32 × 32 grid, 5-35 ms once per world); Strata
  and ruins add about 10 % to chunk generation. Guests get the realm and dig record as small host snapshots.
  Frame rate vs v2.6 on the same machine and seeds (3 alternating runs): idle 106 %, crowd 110 %, night sky 105 %,
  flooding water 96 %, deep-layer room 103 %. Friends on the map cost about 0.03 ms per minimap draw and add no network traffic.
  v2.7.1 multiplayer: per-link token buckets with per-message-type caps, size and shape checks on every message and capped
  chunk reassembly; snapshots are binary and delta-coded with area-of-interest filtering and a per-guest byte budget, so
  one host's upload carries 8 players in testing (bigger groups are not yet tested). The host keeps a ranked successor list; on a host loss the successor reopens the
  room (code rooms) or takes over pre-opened standby links (manual invites). Backups live in IndexedDB, separate from the save.
  Frame rate vs v2.7 (v2.7 hotfix 1 has identical rendering code) on the same machine and seeds (alternating runs): idle 99 %, crowd 98 %, night sky 98 %, flooding water 100 %, deep-layer room 98 %.
  v2.8: Bedrock writes each save to IndexedDB as gzip with a SHA-256 per generation and keeps localStorage as a mirror for
  older versions; a 200-kill crash test lost no saves. The renderer keeps a floating origin (re-centered every 4,096 blocks),
  so precision stays under 0.002 blocks even at the Rim. Block states (a sparse per-chunk channel) and the world's memory
  (16 events per 32-block cell, about 0.002 ms per record, a summary under 4 KB) are small and saved with the world.
  Frame rate vs v2.7.1 on the same machine and seeds (6 alternating runs): Low idle 95 %, crowd 103 %, night sky 102 %, flooding water 98 %,
  deep-layer room 95 %; Medium idle 97 %, crowd 99 %, night sky 100 %, flooding water 98 %, deep-layer room 99 %.
  Known limits in v2.8: block ids stay 8-bit (block states carry the extra detail instead); True Light derives roughness from
  the texture instead of a material map; Auto quality adjusts view distance, resolution and the quality level but not each
  effect separately; the settings panel has no search or presets yet; the world's memory of events is kept by the host,
  and blocks that guests place or break are not part of it yet.
  v2.9: True World bakes sky visibility (12 soft rays, so a floating island no longer acts as a roof), a sun-direction mask
  and colored block light with one bounce into each chunk's mesh in the meshing workers; the shaders only decode it, so Low
  costs about the same as before. High's soft shadows reuse Ultra's two shadow cascades at 1024 pixels with a percentage-closer
  soft-shadow filter; anti-aliasing reprojects the previous frame through the depth buffer. Cloth runs on a small deterministic
  position-based physics solver (the same seed and inputs give the same result on every computer).
  Frame rate vs v2.7.1 on Low (same machine and seeds, 12 alternating runs, software rendering): idle 123 %, crowd 95 %,
  night sky 95 %, flooding water 97 %, deep-layer room 97 %; Medium vs v2.8 (3 alternating runs): idle 105 %, crowd 100 %,
  night sky 97 %, flooding water 94 %, deep-layer room 97 %.
  Known limits in v2.9: knocked-out creatures do not go limp with physics yet (ragdoll knockouts are planned for v2.10); cloth
  banners use smaller grids than planned (8×12 on Medium, 12×18 on High, 16×24 on Ultra) to keep the frame budget;
  temporal anti-aliasing is High only (Ultra keeps its own anti-aliasing); light does not yet tint through colored glass
  and sunlight does not bounce (only block light does); wind does not yet slow down behind walls or hills.
  Multiplayer uses WebRTC data channels with PeerJS's public signaling server (or copy-paste invites), STUN, and PeerJS's
  public TURN relays as a fallback.
