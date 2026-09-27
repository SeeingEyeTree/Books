# Magic System

## Motes: what they are

- Magic runs on stored energy ("aether") held in glowing crystals. A **mote** is a small chip of crystal, the basic unit of currency/fuel.
- **What characters believed at first:** energy comes from harvested bamboo.
- **The truth (revealed Ch7 by Brask, then refined):** killing *any* living thing generates the energy; a nearby crystal drinks it at the moment of death. "Nothing shines for free."
- **Refined rule (Ch7 ending):** yield depends on how much **living, metabolically active tissue** dies, not raw mass. Wood and bone count for little; yeast, larvae, and muscle count for a lot. (Not literal cell-count — fixed after author feedback: it's about active tissue, which stays mass-linked and doesn't imply humans are a good "crop.")
- **Harvest law:** only Houses may license killing near a crystal; unlicensed killing is poaching (hands cut off, first offense). The Houses own the *right to make money*, not just the money.
- **A mote weighs ~5 g.**

## Measured yields

| Yield | Value |
| --- | --- |
| Fish | ~0.8 motes/kg |
| Full bamboo stalk | 3,000-4,000 motes total (~0.01 motes/kg — mostly dead wood) |
| House bamboo fields (whole ecosystem) | ~0.33 motes/m² of ground/day |
| Duckweed floor (LED-lit) | 0.4 motes/m²/day |
| Bamboo shoots (cut young) | 0.6 |
| Oyster mushrooms on husk-wood (no light needed) | 0.9 |
| Black soldier fly larvae | 1.7 |
| Yeast (chamber 61) | ~7x larvae per kg |
| Stacked 30-floor farm (research-loop optimized) | ~50 motes/m² of ground/day — ~150x House fields |

## Effect costs and efficiencies

- **Casting = intention + a mote.** User pulls energy from crystal into self, wills an effect. Precision improves with practice; imprecise casting wastes energy and can injure (Ch3, Bethany's hand).
- **Contact is cheap, distance is expensive** (learned by observing locals, Ch4) — see Distance attenuation below.
- **Measured effect efficiencies (Green side, contact range):**
  - Heat: ~1 MJ/mote (cheapest effect, ~100% efficient-ish baseline)
  - Force/push: ~25% efficient (0.8 mote lifts 2 t by 10 m)
  - Light: ~0.1% efficient (~1 kJ over ~20 min per mote) — the most expensive effect, cause never fully explained
  - Information (asking the world a question): works, needs a mind (no rune can do it) — ~3 motes per query
- **Earth tax:** all effects ~10x weaker on Earth (trials: 10x, 9.8x, 10.3x). A mote's heat value is ~100 kJ on Earth vs ~1 MJ on the Green.
- **Human focus limit:** casting spends the caster's *attention*, not just the mote's energy. After ~40 big casts, head aches, precision drops. This is *the* reason Angline needs machines, and the reason Shades can't simply carry unlimited motes into a fight (see world_building.md, "How war works").

### Capability table (established Ch3)

| Capability | Result |
| --- | --- |
| Fireball | Works |
| Elemental manipulation (fire, light-bending/invisibility) | Works |
| Force application (short flight, moving objects) | Works |
| Simple information about the world | Works |
| Healing | Fails (not "broadly," anyway) |
| Mind control | Fails |
| Direct removal of matter | Fails |
| Transmutation | Fails (can't change properties of existing matter; draining a crystal to try just wastes it) |
| Necromancy | Fails (only fake necromancy via force, i.e. moving a corpse) |

## Force and distance physics

Magic is hand-wavy about *why* effects happen, but strict about *what*: conservation of energy and momentum apply.

### Push has an equal and opposite

- **Every push has a target region and an anchor region.** A push rune (or caster) applies force **F** to the target and **−F** to the anchor.
- **Default anchor:** the rune's own body / whatever it's mounted to (or the caster's body/boots — this is why Angline's glove doesn't throw *her* backward: she's anchored through her boots to the floor).
- **Binding (a "keel" motif):** binds the reaction to a different chosen region (ground under the rune, a separate object). Costs efficiency: ~25% at contact with default anchor, ~15% at contact with a bound anchor; attenuation applies to the anchor's distance too.
- **Rune lifters (Ch8):** push down on the ground, ride up on the reaction — this was already consistent before the physics section formalized it. Later "keel" motif lifters are lighter (bind reaction straight to ground, no heavy platform needed).

### Clever uses of the opposite force

- **Mass driver:** rune on bedrock, target a projectile, anchor the planet. Basis for future ground-to-orbit launch.
- **Squeeze:** two runes pushing a target from opposite sides, each anchored to the other's mount — pure compression, no net force. Already used to grow dense cores.
- **Shear (weapon):** target one part of an object, anchor to another part of the *same* object — it tears. Expensive at range, devastating at contact.
- **Space travel:** a ship can't push *itself* with an internal rune (nothing to anchor to but itself). It must carry reaction mass (water) and push that out the back — a core is an excellent energy source for very high exhaust velocity per kg of water. Dry mass still matters.

### Distance attenuation

- **Any effect can be projected**, but efficiency falls with distance to target (and to a bound anchor).
- **Working rule:** efficiency multiplier ≈ 1 / (1 + (d/d₀)²), where d₀ ("reach") ≈ 1 m for ordinary people/runes. At d=d₀: 50%. At 3d₀: 10%. At 10d₀: ~1%.
- **Reach can be raised** by better intake hollow design (the Ch8 long-reach rune hit 22 m) or years of Shade training. Megalith runes have large d₀.
- **Why projectiles matter:** push a pebble at contact (cheap), let physics carry it (no attenuation) — this is why Shades throw pebbles rather than pushing people from across a field, and it's the in-world logic behind "the history of war is the history of hitting from further away."

## Runes

Old technology, predating the Houses, common and respected (a real guild, not a dying art).

- **One rune, one effect.** The carved shape *is* the program.
- **Always drinking:** a rune pulls from any mote within its reach (~arm's length for small runes) as long as one's there — no on/off switch traditionally (Angline's ferrofluid runes are the first to have one).
- **Size sets the rate:** bigger/better-shaped runes can pull and deliver more power. Kettle rune = saucer. Megalith rune = house-sized (crowns every House seat, fed by the great crystal).
- **Material matters:** different materials run a shape at different efficiencies. Best materials are scarce → a real supply chain (quarrying, casting, carving). Carving a rune takes real skill (~6 weeks for a master carver, historically, before Angline's CNC/ferrofluid tools).
- **Force-carved runes** (shaped in bulk material via magic) are possible but imprecise and inefficient; used desperately in sieges.
- **Logistics favor defenders:** powerful runes are heavy; an attacking force needs to haul multiple large ones for different effects.
- **Rune grammar (discovered by Bethany, Ch8):** spirals = heat, long bars = push (direction along the bar), cup-shaped hollows = intake (required for any effect). Motifs combine like protein domains.

### Angline's rune innovations

- **Ferrofluid runes (Ch8):** magnetic fluid over a 64×64 (later larger) electromagnet grid forms any relief pattern in milliseconds — the first rune with an off switch, and the first "rewritable" rune (a shape library, not a single carving).
- **Optimizer-driven rune search:** ~300 shapes tested per hour per rig; found the first mote motor (ring of push motifs spinning a wheel, ~20% efficient), and a dangerously effective long-reach intake.
- **The long-reach intake incident (Ch8):** an optimized hollow drained 4,160 motes from a vault 22 m away, through two concrete walls. Pattern encrypted, deleted from rigs — kept as a potential weapon against House treasuries. What physically blocks long-reach draining is unknown (distance is still what limits it).
- **Rune works (from Ch15):** Brask's operation on the coast plateau. CNC mills cut proven rune designs into the best materials (bronze for heat, dense Red Ridge stone for push) at 0.01 mm precision. Ferrofluid stays the research/prototyping medium; production runes get cast once proven.
- **Angline's structural advantage over House rune-craft (per author's design intent):** not raw mote output (Houses have centuries of head start there) but (1) rapid rune *discovery* via the optimizer, and (2) one reconfigurable magnet grid replacing a whole quarry-cast-carve pipeline per new effect.

## Cores (compressed storage)

- **Crystals grow naturally:** a "mother crystal" by a field keeps a sliver of each harvest; most is chipped off as motes. Old crystals are denser (the Lamp Hall crystal is ~400 years old).
- **Angline's cores:** grown fast, cold, and squeezed by push runes (compression, no net force — see above) in research chambers, ~5 weeks. Fist-sized, ~1 kg, hold ~10,000 motes (10 GJ) — ~50x denser than loose motes by weight. Deep clear blue, hum faintly.
- **Danger:** a flawed core cracked at 8,000 motes and released everything in under a second (~2 t TNT equivalent), leaving a 10 m crater (Ch11). Cores now get growth limits, flaw scans, and bleed-off cradles.
- **Strategic implication:** cores are what let a person carry huge mote reserves (breaking the "weight brake" on Shade warfare — see world_building.md). They're also why the Houses' *great* crystals (millions to tens of millions of motes each) are effectively unknowing/known nuclear weapons — see Ashfall in world_building.md; the Houses **do** know (confirmed and rewritten in Ch11).

## Doors (portals)

- **Origin:** the first door was a dormant "thin place" (a weak spot in reality) under an orphanage, pushed open by a **resonator** (a field-effect device) using a building's whole substation for ~4 seconds. Destroyed in Ch9.
- **Pushing a door open from one side only** (Earth side alone): a full-power pulse (Ch10, flywheel bank) makes a point of light lasting seconds; staged pulses can hold a small hole (~60 cm) for minutes.
- **Opening a proper door from one side needs the other side to pull too:** synchronized timing (radio/clock sync — signals pass through doors) plus a feeding ring of runes drinking motes on the receiving side. Door size scales with total energy/motes spent (~4.2 m Sable Gate at 9,000 motes fed; ~6.1 m Reach door at 30,000 motes/3 cores).
- **A door "settles" at a size set by the energy that opened it and holds with no upkeep** once formed.
- **Green-side-only opening (Ch15 breakthrough):** a ring of 24 car-sized stone megalith runes can tear a door with no push needed from Earth at all — ~120,000 motes for a ~1 m door (smaller 12-stone rings make smaller/temporary doors, ~8,000-30,000 motes depending on size/purpose).
- **Sealing (permanent closure, Ch15 breakthrough):** a second ring with reversed push bars and outward-facing hollows pulls a door's edges through each other, leaving *nothing behind* — no scar, no thin place, totally undetectable. Costs scale with what's being sealed: ~20,000 motes for a fresh, never-torn door; ~35,000 for an old torn scar (like sub-basement four); ~8,000 for a natural thin place (never torn, only thinned).
- **Key fact:** a **torn/scarred** door site (like sub-basement four after Ch9's closure) is much easier to *reopen* than tearing a fresh one — a scar remembers. This is why the government's 30 MW test (Ch14-15) nearly worked, and why *sealing* (not just closing) matters for true security.
- **Doors open at ground level on the Green side, even when the Earth-side origin point is deep underground** (confirmed via the salt mine).
- **One-to-one mapping** determines *where* any new door will land — see world_building.md.
