
I want to create a site that documents the process of a large scale multifaceted project but focus on the design aspects. I need some good references.

Searched the web
Good process-documentation sites tend to fall into a few different models — worth picking one before designing yours:

Agency-style "making of" writeups

Instrument, Active Theory, Resn, Ueno — their own case study pages often break a project into research → concept → prototype → build → ship, with process artifacts (sketches, failed directions, code snippets) alongside polished shots
Basecamp's Shape Up (basecamp.com/shapeup) — not a portfolio piece, but a masterclass in narrating a working method as its own content
Product teams documenting design decisions publicly

Stripe's engineering/design blog — deep technical-meets-design writeups
Figma's blog posts on redesigning their own product
Notion's design blog — strong on "here's what we tried and rejected"
Duolingo design blog — playful but rigorous about process
Devlog format (great for long, multifaceted builds)

Panic's posts on building the Playdate — a good model if your project has hardware/software/brand threads running in parallel
The Browser Company's Arc devlogs
Curation/inspiration sources to browse many at once

Awwwards' "Process" tag/element library
Are.na channels people build around design process
One Page Love's case-study category
Since you work across UX, systems, and technical implementation, the agency "making of" model or a devlog format would probably suit a large multifaceted project best — they let you show research, technical constraints, and visual decisions as parallel threads rather than one linear narrative.

Is this for documenting one of your own projects, or a standalone reference site? That'd change which structure fits best.

This is for one of the projects I'm involved in, called imaginal airlines , I designed the system and I want to show how it all fits together, the design and all the visual  artifacts as well as the liver performance that it augments

Updated memory
That's a great subject for this format — a system with a visual/design layer and a live-performance layer gives you natural threads to weave together rather than a single linear case study.

A structure that tends to work well for this kind of project:

1. The system, top-down
Open with what Imaginal Airlines is as a whole — the concept, then a diagram of how the pieces relate (visual system ↔ live performance ↔ any technical layer connecting them). This orients people before you zoom into any one artifact.

2. Artifact galleries, grouped by function not chronology
Rather than "here's everything I made," group by what each artifact does in the system — identity/branding, environment or stage visuals, any generative or real-time elements, printed/physical pieces if there are any. Each group gets its own short rationale.

3. The live performance as the connective tissue
This is the part most process sites skip and that would make yours distinctive — show how the visual system responds to or shapes the performance. Options:

Video/stills from an actual performance with annotations pointing to which design decisions are visible in the moment
A "signal flow" style diagram if the system reacts to audio/performer input in real time
Before/after: the static design artifact next to what it becomes live
4. Process, not just output
Sketches, early concepts, things you tried and dropped — this is what separates a portfolio piece from a documentation site.

One thing worth deciding upfront: is the live-performance element something with real-time/reactive behavior (audio-driven, sensor-driven, etc.), or is it a fixed visual design that's used consistently across performances? That changes whether the site itself should have any interactive/generative component demonstrating it, versus just document it in video.

The visual system is controlled by a user using Ableton and touch designer

Updated memory
That's a real-time, audio-driven pipeline — Ableton feeding show control/audio into TouchDesigner to drive the visuals live. That's a great case for making the system itself legible on the site, not just its output. A few things worth building in:

Show the signal chain explicitly
A diagram of Ableton → (MIDI/OSC/Link) → TouchDesigner → output — this is the kind of thing that's invisible to an audience watching the performance but is exactly what a design-process site should surface. If there's a translation layer (Max for Live, OSC routing, custom scripting), that's worth its own callout.

TouchDesigner network screenshots as artifacts
Node networks are visually interesting in their own right and read as "process" immediately — even non-technical visitors get that something intricate is happening. Annotate a few key operators/networks rather than dumping the whole patch.

Ableton session view as a companion artifact
Shows how the performance is structured (scenes, cues, stems) — pairs well with the TD network to tell "this is what triggers, this is what renders."

Live capture mapped to the system
Video of an actual performance with a side-by-side or overlay showing what's happening in TD/Ableton at that moment — this is the strongest way to prove the augmentation is real-time and reactive, not just pre-rendered visuals played alongside music.

Consider a tiny interactive demo
Since you're already comfortable with Web Audio API and custom components, a simplified web version — even just audio-reactive shader responding to a sample track — could let visitors feel the reactive relationship rather than just watch a video of it. Not required, but it would set the site apart from a typical case study.

Is the performance a recurring live show (so you have real footage to pull from), or is this documenting a system that's still being built out?

There is no audio reactivity, the user triggers video clips that are arranged an projected

Updated 2 memories
Good to know — that's a clip-triggering/VJ-style setup rather than generative reactivity, which actually makes it easier to document clearly:

Show the clip library as a design artifact
The video clips themselves are core visual output — worth a gallery treating them like any other design deliverable (stills, thumbnails, maybe short loops), organized by category (mood, scene, sequence, whatever logic you used to build them).

Document the triggering/arrangement layer
Ableton's session view here is functioning like a cue sheet — screenshot it and annotate what each scene/row corresponds to. This shows the structure behind a live show without needing real-time diagrams.

TouchDesigner's role
Worth being specific about what TD is doing — compositing multiple clips, adding transitions/effects, mapping to specific projection surfaces, warping/blending for the space? That's the part that turns "playing video clips" into a designed visual system, so it deserves its own explanation with network screenshots.

Performance footage stays the payoff
Since a person is triggering clips live (a performative act itself), footage of that triggering happening alongside the projected result would show the "instrument" as well as the output — that's a nice detail most documentation sites skip.

Simplify the earlier interactive-demo idea
Since there's no audio reactivity, a web demo could instead simulate the triggering experience — a simple pad/grid interface where clicking swaps between a few sample clips, which mirrors what the live operator is actually doing.

Is there a specific performer or context this is built for (a VJ set, a theater piece, an installation)? That'd help pin down how much to emphasize the "instrument" versus the visual output itself.





Claude is AI and can make mistakes. Please double-check responses.
