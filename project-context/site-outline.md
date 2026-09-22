# Imaginal Airlines — Documentation Site Outline

**Audience:** Potential clients with similar live/immersive projects.  
**Format:** One scroll. Sticky nav jumps between acts. Composition act uses scroll-driven zoom (whole → player focus → exploded annotations).

**System model:** One projection · three improvising musicians · one maestro operating the instrument (Ableton → TouchDesigner · clip triggers, no audio reactivity).

---

## Scroll path

```
1 Frame it        → outcome + maestro tease
2 Problem         → why this was hard
3 Messy start     → raw score before systematization
4 Solution        → how the system was designed (overview only)
5 Composition     → whole layout → player focus → exploded detail
```

**Nav:** `Frame · Problem · Mess · Solution · Composition`  
**Composition sub-nav:** `Whole · Player 1 · Player 2 · Player 3` (+ subsection jumps when focused)

---

## References

| Asset | Use |
|---|---|
| [Raw Digital Score (FigJam)](https://www.figma.com/board/EsR2QVA5Nvr3tYO2MqZFXc/Imaginal-Airline-Digital-Score?node-id=0-1&t=KVHNzFh4eNg3bcfG-1) | Act 3 — messy start |
| [DSP Visual Design — cues & layouts](https://www.figma.com/design/b1A4QLSb9tmb6L361Ip6tL/DSP---Visual-Design?node-id=163-5184&t=5EpjAMuY0EtoUdmE-1) | Act 4 intro + Act 5 full breakdown |
| [Live site](https://imaginal-site.vercel.app/preflight) | Optional link in Act 1 |
| `CUES/` clip library | Act 5 — video previews in subsections |

---

## Act 1 — Frame it

**Job:** Show the final experience before explaining anything.

**Content:**
- **Participant view:** performance footage / projection in the room
- **System view (compact):** maestro at instrument + three musicians + one projection
- One line: what Imaginal Airlines is (immersive performance, not a travel brand)

**Leaves knowing:** This is the caliber of outcome — and it's live-operated.

---

## Act 2 — Problem

**Job:** Name the client's pain.

**Content:**
- Complex score, not systematized
- Three improvisers + one maestro — no fixed timeline
- Operator can't navigate live without structure
- Visual assets not grouped by function or musician territory

**Leaves knowing:** "They've seen my situation."

---

## Act 3 — Messy start

**Job:** Show the before state.

**Content:**
- Raw [Digital Score board](https://www.figma.com/board/EsR2QVA5Nvr3tYO2MqZFXc/Imaginal-Airline-Digital-Score?node-id=0-1&t=KVHNzFh4eNg3bcfG-1) — dense, hard to perform from
- What was missing: player territories, cue vocabulary, maestro legibility

**Leaves knowing:** The starting point was real complexity, not a blank slate.

---

## Act 4 — Solution

**Job:** Explain design decisions — don't break the composition apart yet.

**Content:**
- Player sections = one improviser's territory on the score (not separate projections)
- Maestro conducts the full layout from one instrument
- Cue types: improv, rhythm, intensity, pitch, etc.
- Ableton = cue sheet · TouchDesigner = one composited output
- Introduce [DSP Visual Design](https://www.figma.com/design/b1A4QLSb9tmb6L361Ip6tL/DSP---Visual-Design?node-id=163-5184&t=5EpjAMuY0EtoUdmE-1) as the systematized score
- Bridge: "Scroll to go inside the composition."

**Leaves knowing:** How the system was structured and why.

---

## Act 5 — Composition

**Job:** Progressive proof — describe each layer only when the user is inside it.

### Level 1 — Whole composition

- Full 3-musician layout from DSP Visual Design
- Annotate: one projection, three territories, one maestro
- Callouts to each player region

### Level 2 — Player focus (×3)

On scroll: **one player expands, others fade.** Walk subsections in order:

| Subsection | Explain |
|---|---|
| Improv cues | Open vocabulary — maestro picks when musician is leading |
| Rhythm cues | Structured pulse/grid triggers |
| Intensity | Visual weight scaling in the moment |
| Pitch | Register/role mapping for that musician |

Each: short copy + video preview where available (`CUES/`).

### Level 3 — Exploded annotations

Player section breaks apart. Every control group labeled:

- Name · function · maestro use · linked clip(s)

Repeat Level 2→3 for Player 2 and 3 (full depth on Player 1 acceptable for v1).

**Leaves knowing:** The deliverable is documented, operable, and decomposable.

---

## Clip library (Act 5 cross-cut)

| Category | Clips |
|---|---|
| **01 Rhythm** | Legato, Free, Cycle, Drone and Pulse, Silence and Space, Call and Response, Flowing, Poly, Steady |
| **02 Improvisational** | Layer, Thematic Variation, Deluge, Pulse and Groove, Null, Drone |

---

## Still to gather

- Performance footage (participant + maestro views)
- Figma exports for Acts 3–5
- Player 1/2/3 role names (if any)
- Ableton ↔ TouchDesigner protocol label
- Whether maestro layers multiple territories in one moment
