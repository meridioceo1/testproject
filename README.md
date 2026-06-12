# Gaslamp & Gallows

*An isometric action RPG of gaslit Salem, 1894.*

A coven has seized the old Blackwood Mansion at the edge of town, and the people
who go to look at it do not come back. Choose an investigator, descend through
the mansion's fifteen floors (and the Hollows beneath them), and put the coven
to rest.

The whole game is **one self-contained HTML file** — no build step, no server,
no dependencies.

## How to play

**Easiest:** download `index.html` and double-click it. It runs in any modern
browser (Chrome, Firefox, Safari, Edge), on desktop or mobile.

**Or serve it locally** (avoids any browser file:// quirks):

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```

**Or host it:** enable GitHub Pages on this repository (Settings → Pages →
deploy from branch) and the game is playable at your Pages URL.

Saves are kept in your browser's localStorage — three character slots plus a
shared town stash.

## Controls

| Input | Action |
| --- | --- |
| Left click (hold to repeat) | Move, attack, pick up, talk, open coffers, smash crates |
| `1` `2` `3` `4` | Skills, aimed at the cursor |
| `Q` / `E` | Laudanum draught (heal) / aether tonic (mana) |
| `I` / `C` / `T` / `J` | Satchel · Dossier · Grimoire · Blackwood journal |
| `Tab` | Minimap: small → large → hidden |
| `M` / `Esc` | Music · menu (also closes panels) |
| Right click | Unequip a worn item / discard a bag item |

Touch is supported — tap to move and fight, use the corner buttons for panels.

## The four investigators

- **The Witchfinder** *(warrior)* — sabre arcs, pyre brands, gallows judgements.
  Every kill stokes his zealotry.
- **The Aetherist** *(mage)* — galvanic bolts, chained lightning, séance novas,
  and a plantable Tesla coil. Her aether veils her flesh.
- **The Resurrectionist** *(rogue)* — thrown knives, fans of scalpels, lamplight
  blinks, and an exhumed skeleton on call. Hard to hit.
- **The Mesmerist** *(occultist)* — mesmeric lashes, a slowing pendulum arc, a
  phantasmal double that baits the dark and bursts, and the Voice of Command
  that sends the weak-willed fleeing. Foes that strike him are transfixed.

Each class has four art branches plus **two rival specialization Paths** —
Pyre or Iron Court, Storm or Machine, Scalpel or Charnel Choir, Silver Tongue
or Twin Self — full of new mechanics (ricocheting knives, forked lightning,
multi-coil batteries, taunting skeletons, charmed enemies, twin doubles).
Sink twelve points into a Path and inscribe its **Mastery** capstone, which
changes how the class plays and adds a title to your dossier. Skill points
come faster now (a bonus point every fourth level), and Shift-hovering any
item compares it against what you're wearing.

## Quests that change you

Every closed investigation now unlocks a permanent power alongside its gold:
double-strength potions and a larger belt (Prudence), masterwork socket
drilling at the forge (Ezekiel), free Well-Rested lodging (+10% damage and
stride after sleeping — the Widow), the Brass Door-Knocker that makes town
portals reusable (Quill), and from Old Meg: two skill points, free respecs
forever, and the Indictment trade.

## After the ending: the Second Hanging

Past depth 9 the house stops being polite — enemies harden faster than the
old curve and elites crowd the deep floors. Beat Abigail and you can begin
the **Second Hanging (New Game+)**: the mansion re-arms with all quests and
bosses restored at a much crueler pitch (and again, and again — each Hanging
stacks), while you keep your level, gear, arts, pages and unlocks, and the
loot scales up to match. Between Hangings, Indictments, bounties and the
endless Hollows remain as endgame hunting grounds. Reloading a save also
offers a one-click "wake at your deepest floor" start.

## Bosses that fight like they mean it

Every boss telegraphs its harm on the floorboards — circles and lines that
fill in, then bite — has a phase change at half health, and a signature
mechanic: the Crone's cauldron mortar, Hathorne's Verdict slam behind a jury
that shields him until it falls, the Choir's crescendo rings you must step
out of, the Seamstress's red threads (she travels along them), Abigail's
tracking moonbeam and sabbat candles that mend her until snuffed, the
Coachman's full-gallop Ipswich Run, Carrion's inverted-cross sermon, and the
Clockwork Confessor, who drags you in to confess.

## Two endings

One page of the **Blackwood Papers** is lost on each story floor. Find all
fifteen and the killing blow on the final boss never lands — she kneels, and
you choose what 1692 is owed: **take the rope from her neck, or light the
pyre.** Each choice has its own epilogue and its own exclusive relic, and one
of them leaves a quiet woman standing by the gallows in town afterward,
selling hexstones pressed from her own ash. Skip the pages and you get the
plain ending — and a hint about what you missed.

## After the story: Indictments

Bosses from depth 9 drop **Indictments of the Hollows** — tiered writs that
open one-shot corrupted floors with rolled modifiers (*Vampiric Brood,
Iron-Boned, Cruel, Benighted, Volatile Dead, The Hungry Floor*), a guaranteed
warden, a guaranteed unique, richer fortune throughout, and a 60% chance of a
deeper writ. If you fall, the writ is void. Quill sells tier-1 writs once the
coven is broken.

## Hardcore, and what it leaves behind

Tick **⚰️ Hardcore** at character creation and death is the rope — no
rising. But the fallen are recorded: a hardcore investigator who dies leaves
a **Revenant** haunting the floor where they fell, wearing their old gear.
Any later character who strikes it down releases up to two of the items it
carried.

## What's in the mansion

- **21 named floors** in seven visual bands — oak parlors, cold halls, brick
  cellars, the bone garden, the blood foundations, and the Hollows past the end
  of the story — then endless depths beyond.
- **8 bosses** sealing every third floor, from the Crone of Gallows Hill to
  Abigail the Endless (and, deeper still, the Headless Coachman, Reverend
  Carrion, and the Clockwork Confessor).
- **18 enemy types** with their own behaviors: lunging black shucks, wailing
  widows that slow you, plague surgeons lobbing miasma pools, strung
  marionettes, clockwork footmen, charging headless coachmen, and the coven imp
  who flees with its sack of loot — kill it before it vanishes.
- **Loot**: seven equipment slots (weapon, coat, hat, gloves, boots, ring,
  amulet) plus a companion slot; magic, **set** (green) and unique rarities;
  17 unique relics with build-changing powers; three 3-piece sets with
  escalating bonuses (the Hangman's Trade, the Gravewatch, the Parlor Circle);
  durability, repair, and witch-ash crafting at the blacksmith.
- **Hexstones**: socketable gems (Wolf's Fang, Cinder Pearl, Miser's Eye,
  Witch-Knot, in three tiers) whose effect depends on whether the smith sets
  them in a weapon, coat, or hat. Weapons and armor roll up to two sockets.
- **Iron-bound coffers** (some gilded, some bait for an ambush), smashable
  crates, casks, and funerary urns.
- **Dungeon events**: séance tables that demand sitters in waves and pay in
  relics; caged townsfolk who fight beside you when freed (usually); cursed
  altars that bless or collect; and warded vaults whose Key-Warden walks the
  same floor.
- **The Blackwood Papers** — a 15-page journal, one page lost on each story
  floor, telling what actually happened in that house. Press `J`.
- **Salem Village**: five keepers (potions, smithing, lodging, curiosities, and
  the Sin-Eater who respecs you), a shared stash, the parish well, the stocks,
  the gallows kept in good repair, and a **parish notice board** with rotating
  bounties — culls and relic recoveries — paid in shillings and witch ash.
- A procedural **chamber score** in 3/4 — music box, pizzicato bass, a
  breathing string section, and a cello drone, all through a long parlor
  reverb — with five arrangements (title nocturne, town, the upper house, the
  deeps, and a timpani boss dirge), eight-bar call-and-answer phrasing, church
  bells at phrase ends, a toll when a boss falls, and music/effects volume
  sliders in the pause menu.
- **Your gear shows on your investigator**: the weapon model follows what's
  in hand (sabre, coachgun, cane, rapier…), the hat follows the hat (bowler,
  capotain, periwig, veil, stovepipe), the coat recolors and restyles by
  armor (brigandine studs, corset ribs, plague collar), and magic / set /
  unique pieces glint in their rarity color.
- **Interfaces**: the Grimoire is a proper tree — glowing seals with rank
  pips on connected rails, live damage/cooldown numbers for your four arts,
  hover writs, click to inscribe. Shopkeepers greet you with hand-drawn
  portraits, a pinned purse, tabbed counters (Forge / Arcanum / Socketry /
  Sell), hover tooltips with worn-gear comparison, and a click-to-sell grid.

## The art

Everything is drawn procedurally on a single canvas in an *ink-and-gaslight*
style: soot blacks and parchment, oxblood wallpaper over dark wainscot, long
oak floorboards, brick and weeping stone in the deeps, wet cobbles and
candlelit clapboard windows in town. Light comes from things that burn —
the player's lantern, gas lamps, candelabra, chandeliers — with fog, drifting
motes, and a vignette closing in at the edges. Every floor band has its own
palette, wall treatment, floor pattern, furniture set, and air tint.
