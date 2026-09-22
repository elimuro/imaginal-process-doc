# Imaginal Airlines — Documentation Site Outline

A process-documentation site for one large-scale project, focused on **design**: the visual system, the artifacts that make it, and the live performance those artifacts are built to hold.

---

## How the site is organized

**One project, one continuous scroll — told as process documentation.**

The story reveals linearly as the user scrolls down. Each section builds on the last. A sticky nav and left jump rail let them skip ahead to any chapter without breaking the through-line.

- The **flight** is the spine — every visual decision answers to the dramaturgy of Flight 001.
- Visual work is grouped by **what it does in the system**, not by the order it was made.
- **Ableton** is the cue sheet a person plays live.
- **TouchDesigner** sends those clips to the room.
- There is **no audio reactivity** — a person triggers video clips arranged and projected.
- Sketches and dropped directions stay in the story.

### Scroll path (with jump links)

```
Hero
  ↓ scroll reveals
01 Frame → 02 Flight → 03 System → 04 Room
  ↓ scroll reveals
05 Visuals → 06 Instrument → 07 Performance → 08 Process
  ↓
Footer
```

**Navigation:** Sticky top bar (01–08 jump links) + fixed left rail (chapter names, active state on scroll).

---

## Existing references

| Asset | Role in the site |
|---|---|
| [Digital Score (Figma)](https://www.figma.com/board/EsR2QVA5Nvr3tYO2MqZFXc/Imaginal-Airline-Digital-Score?node-id=0-1&t=KVHNzFh4eNg3bcfG-1) | Master map of the show — link from System and Instrument chapters |
| Live website (booking flow) | Public-facing layer of the same world — link from Frame and Visuals |
| `CUES/` clip library | Core visual deliverable — organized by category (see Visuals chapter) |

---

## Chapters

### 01 — The Frame

**Job:** Say what Imaginal Airlines is before any artifact appears.

**On this page:**
- Collective of artists, musicians, designers, and meditators
- Non-profit under Temporary Frames Arts Society
- Metaphysical theatre of consciousness, qualia, and subjectivity
- Airport and airplane as a communal in-between, not a destination
- Aim: deep listening, fluid ways of seeing, cosmopoesis

**Reader leaves knowing:** A liminal container for an inner journey, held by a collective. Not a travel brand.

**Still to gather:** A single diagram of the whole, and a plain-language version of the philosophical frame.

---

### 02 — The Flight

**Job:** Show the dramaturgy every visual decision answers to.

**On this page:**
- Flagship flight: *The Imaginal Realm*
- Neural-field annealing: heat → malleable state → slow cooling
- Three phases: Ascent, Apex, Descent
- 2.5 hours with boarding and disembark, low light, lying down
- The First Law: permissive, loving attention

**Reader leaves knowing:** Flight 001 is a three-phase annealing journey. Later pages hang off this arc.

**Still to gather:** How each phase is scored visually, and what a participant actually sees.

---

### 03 — The System

**Job:** Make the link between the design and the live show legible in one view.

**On this page:**
- Chain: flight structure → clip library → Ableton cues → TouchDesigner → projection → participant
- The operator is part of the instrument
- What is designed ahead of time vs. what is chosen live
- Link to the [Digital Score (Figma)](https://www.figma.com/board/EsR2QVA5Nvr3tYO2MqZFXc/Imaginal-Airline-Digital-Score?node-id=0-1&t=KVHNzFh4eNg3bcfG-1)

**Reader leaves knowing:** A person triggers a designed clip library. TouchDesigner carries it into the room. Nothing follows the audio.

**Still to gather:** Confirm each link, and name how Ableton talks to TouchDesigner (MIDI, OSC, etc.).

---

### 04 — The Room

**Job:** Document the space the bodies and the projections share.

**On this page:**
- Physical space transformed into an airport-airplane setting
- Boarding and disembark as designed thresholds
- Conditions: low light, reclined, communal
- What people bring: comfortable clothes, eye mask, journal

**Reader leaves knowing:** A real room is recast as a terminal and a cabin, built for stillness and low light.

**Still to gather:** Plans or photos, projection surfaces, materials, and lighting notes.

---

### 05 — The Visuals

**Job:** Present the artifacts grouped by their job in the system.

**On this page:**
- Identity and wayfinding of the fictional airline
- Environment and scenic images
- **Clip library** — stills, thumbnails, short loops (the core visual deliverable)
- Any print or physical pieces
- Link to the live website and its booking flow

**Clip library structure (from `CUES/`):**

| Category | Clips |
|---|---|
| **01 Rhythm** | Legato, Free, Cycle, Drone and Pulse, Silence and Space, Call and Response, Flowing, Poly, Steady |
| **02 Improvisational** | Layer, Thematic Variation, Deluge, Pulse and Groove, Null, Drone |

**Reader leaves knowing:** The clip library is a design deliverable, sorted by the logic of the flight — not just a folder of files.

**Still to gather:** The real sorting logic (phase, sequence, mood, or another cut), and how categories map to flight phases.

---

### 06 — The Instrument

**Job:** Show how the show is played.

**On this page:**
- Annotated Ableton session view: scenes and rows as cues
- TouchDesigner networks, annotated at the key operators only
- What TouchDesigner is actually doing: compositing, transitions, mapping, warp and blend
- Side-by-side with the Digital Score in Figma

**Reader leaves knowing:** Ableton is the cue sheet. TouchDesigner is what turns clips into an image in that room.

**Still to gather:** Session screenshots, network screenshots, and a note on how a cue is fired.

---

### 07 — The Performance

**Job:** Show the system in use: the person choosing, and the image in the room.

**On this page:**
- Triggering beside the projected result
- A designed still next to the same moment live
- Annotations back to the phase and the cue
- The operator as a visible part of the instrument

**Reader leaves knowing:** The augmentation is live. The footage is the proof.

**Still to gather:** Whether a showing was recorded, and which one to use.

---

### 08 — The Process

**Job:** Keep the decisions, including what was set aside.

**On this page:**
- Early sketches and concepts
- Directions that were tried and dropped
- Constraints from the duration, the body, the room, and the cue structure

**Reader leaves knowing:** The finished system comes from constraints and rejected directions.

**Still to gather:** The process archive.

---

## Open questions

These decide how deep the next pass goes. The outline holds without them.

1. **Audience** — Collaborators and funders, or a public document?
2. **TouchDesigner role** — Compositing, transitions, surface mapping, or all of them?
3. **Clip sorting logic** — How do Rhythm and Improvisational categories map to flight phases?
4. **Footage** — Is there a recording of a showing, with the operator and the projection?
5. **Scope** — Flight 001 only, or the wider collective as well?
6. **Interactive demo** — Later, a click-to-trigger page that mimics the cue grid, or stills and video only?

---

## Site model (reference)

Inspired by agency "making of" writeups and devlog formats — they allow research, technical constraints, and visual decisions as **parallel threads** rather than one linear narrative.

Good references to browse:
- Instrument, Active Theory, Resn — case studies with process artifacts alongside polished output
- Panic's Playdate posts — parallel hardware/software/brand threads
- Stripe / Figma / Notion design blogs — design decisions with rejected directions
- Basecamp's *Shape Up* — narrating a working method as content
