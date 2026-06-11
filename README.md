# STARLINE: Cosmogenesis

> **You do not save the universe. You breed better ones.**

**STARLINE: Cosmogenesis** is a single-player cosmic evolution sim about breeding successor universes through stars, civilizations, black holes, entropy, and inheritance.

You are not a person, empire, god, spaceship, or civilization.

You are a **stellar-universal lineage**: a reproductive cosmic process trying to cultivate universes capable of producing stranger, richer, more fertile descendants.

Every universe dies.  
The question is what it leaves behind.

---

## Play

Open `index.html` in a browser.

No install.  
No server.  
No external assets.  
No dependencies.

The game is currently a self-contained HTML/CSS/JavaScript prototype using Canvas rendering.

---

## Core idea

Each run is one universe.

You guide a living cosmic web by spending **Entropy Gradient** on indirect cosmic actions:

- **Compress** matter into stars
- **Disperse** unstable regions
- **Enrich** systems with heavy elements
- **Shield** fragile life-bearing regions
- **Collapse** massive stars into black-hole candidates
- **Seed-Groom** black holes into better successor seeds

The universe evolves across eons. Stars form, metals spread, civilizations awaken, black holes feed, death pressure rises.

Eventually the universe dies.

At death, you choose which black hole becomes the seed of the next cosmos.

That seed changes the next universe.

The lineage continues.

---

## The loop

```text
Generate universe
    ↓
Shape cosmic regions
    ↓
Stars, metals, civilizations, black holes emerge
    ↓
Death pressure rises
    ↓
Universe dies
    ↓
Choose black-hole seed
    ↓
Successor universe inherits traits, scars, constants, and bias
    ↓
Repeat forever
```

---

## What makes it different

### Stars are genes

Star populations are not background decoration. They are reproductive structure.

Massive stars create metals and collapse potential.  
Old stars stabilize matter.  
Exotic stars increase diversity.  
Star formation choices affect what kind of universe can come next.

### Black holes are gametes

Black holes are the reproductive seed-vaults of the cosmos.

Each black hole has:

- class
- mass
- fidelity
- contamination
- mutation pressure
- fertility
- history tags
- successor bias

A clean **Quiet Seed** may produce a stable descendant universe.  
A violent **Devourer** may produce a dense, fertile, unstable cosmos.  
A **Civilized Seed** may carry the agenda of life forward.  
An **Anomalous Seed** may mutate the bloodline.

### Civilizations are dangerous symbionts

Civilizations are rare, autonomous, and consequential.

They may preserve stars, worship black holes, mine entropy, spread life, modify seeds, resist collapse, or sabotage the reproductive strategy of the universe itself.

You do not command them.  
You alter the conditions around them.

### Death is gameplay

The end of a universe is not a fail state. It is the reproductive decision.

Death modes include:

- **Heat Death**
- **Big Crunch**
- **Vacuum Rupture**
- **Sterile Fadeout**

Each ending alters inheritance.

Bad runs do not simply lose.  
They scar the lineage.

---

## Current prototype features

- Procedural universe generation
- Generated universe names and color palettes
- Cosmic web map with glowing regions and filaments
- Region-level simulation of:
  - gas
  - stars
  - massive stars
  - old stars
  - exotic stars
  - metals
  - radiation
  - instability
  - black-hole potential
- Six indirect player actions
- Eon-based simulation loop
- Resource systems:
  - **EG** — Entropy Gradient
  - **MC** — Matter Coherence
  - **MM** — Metallicity Memory
- Emergent civilizations:
  - Star Shepherds
  - Black-Hole Cults
  - Entropy Miners
  - Silent Gardeners
- Black-hole classes:
  - Quiet Seed
  - Devourer
  - Civilized Seed
  - Anomalous Seed
  - Residual Spark
- Death pressure and universe death
- Seed ledger at death
- Successor universe generation
- Persistent lineage record
- Traits and scars across generations
- Nested zoom concept:
  - Cosmic Web View
  - Local Star System View
  - Life / Civilization Spread View
- Fully self-contained browser prototype

---

## Controls

Click a region in the cosmic web.

Use actions from the right panel:

| Action | Function |
|---|---|
| Compress | Turns gas into stars and massive stars; increases instability |
| Disperse | Spreads matter outward; improves coherence |
| Enrich | Adds metals; increases life/civilization chance |
| Shield | Protects a region; lowers radiation and instability |
| Collapse | Forces massive stars toward black-hole birth |
| Seed-Groom | Improves a black hole as a successor seed |

Click **End Eon** to advance time.

At universe death, choose a black-hole seed to generate the next universe.

---

## Design philosophy

STARLINE is built around indirect control.

You do not create life.  
You create the conditions where life becomes likely.

You do not spawn black holes.  
You pressure stars until collapse becomes probable.

You do not win by preserving the present.  
You win by shaping what survives the end.

The game is about long-range consequence, not conquest.

---

## Visual direction

The universe is rendered as a living cosmic organism:

- glowing filaments
- breathing regions
- procedural palettes
- black-hole accretion rings
- nebular fields
- civilization glyphs
- death transitions
- successor-universe blooms

The aesthetic target is not sterile NASA realism.

It is biological cosmology: galaxies as tissue, black holes as seeds, civilizations as symbionts, and the lineage tree as ancestry.

---

## Roadmap

Near-term improvements:

- Deeper local star-system zoom
- More detailed life/civilization spread visualization
- Stronger procedural particle graphics per region
- More event variety
- More seed classes
- More meaningful civilization behavior
- Save/load support
- Better onboarding
- Balance pass for longer lineage play

Longer-term possible directions:

- Full Godot version
- Audio-reactive cosmic rendering
- Shareable universe seeds
- Branching lineage tree
- Rival cosmic lineages
- Dark-sector mechanics
- Artificial universe genesis
- Steam/web demo release

---

## Development status

Prototype.

The current version is playable, experimental, and intentionally compact. It is meant to prove the core fantasy:

> A universe can be treated as an organism, stars as genes, black holes as reproductive seeds, and death as inheritance.

---

## Repository structure

```text
.
├── index.html   # Complete playable game prototype
└── README.md    # Project introduction
```

---

## Running locally

Clone or download the repository, then open:

```text
index.html
```

in any modern desktop browser.

---

## Why this exists

Most space games treat the universe as a stage.

STARLINE treats the universe as the organism.

The player does not explore the cosmos.  
The player breeds it.

---

## License

TBD.

Until a license is added, all rights are reserved by the project creator.
