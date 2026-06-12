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

Each class has a six-branch Grimoire skill tree and its own draw of the loot pool.

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
  amulet) plus a companion slot; magic and unique rarities; 15 unique relics
  with build-changing powers; durability, repair, and witch-ash crafting at the
  blacksmith.
- **Iron-bound coffers** (some gilded, some bait for an ambush), smashable
  crates, casks, and funerary urns.
- **The Blackwood Papers** — a 15-page journal, one page lost on each story
  floor, telling what actually happened in that house. Press `J`.
- **Salem Village**: five keepers (potions, smithing, lodging, curiosities, and
  the Sin-Eater who respecs you), a shared stash, the parish well, the stocks,
  the gallows kept in good repair, and a **parish notice board** with rotating
  bounties — culls and relic recoveries — paid in shillings and witch ash.
- A procedural **Victorian waltz** soundtrack that sours when bosses wake.

## The art

Everything is drawn procedurally on a single canvas in an *ink-and-gaslight*
style: soot blacks and parchment, oxblood wallpaper over dark wainscot, long
oak floorboards, brick and weeping stone in the deeps, wet cobbles and
candlelit clapboard windows in town. Light comes from things that burn —
the player's lantern, gas lamps, candelabra, chandeliers — with fog, drifting
motes, and a vignette closing in at the edges. Every floor band has its own
palette, wall treatment, floor pattern, furniture set, and air tint.
