# Ideas and integration concepts

Collected **2026-10-24**. This is an idea collection, not a feature backlog accepted for implementation. Sources are indexed in the [ledger](sources.md); existing capabilities are in [components](components.md).

## Sourced ideas

| Idea | Provenance and classification |
| --- | --- |
| Ingest a module into NPC portraits, voices, dynamic maps and soundscapes; eventual AI GM | Historical vision: Echo Forge idea-intake lines 251–254; lines 300–305 keep it outside that project's scope. [S2](sources.md#s2-echo-forge). |
| Continuously listen and surface relevant sounds, pictures, town names and NPC names/personalities | Future idea in Echo Forge inbox, “Ultimate Dream”; internal headless audio is a stepping stone, not the complete system. [S2](sources.md#s2-echo-forge). |
| Players prepare character sound packages and suggest sounds; GM approves or grants trusted autoplay | Future multi-user idea in Echo Forge inbox. Preserve approval/trust distinctions; no player-control integration assumed. [S2](sources.md#s2-echo-forge). |
| Capture room/module context on a phone while a tablet remains the table audio panel | Echo Forge idea-intake/spec direction. Remote transport, paired identity and session behavior remain unproven. [S2](sources.md#s2-echo-forge). |
| Campaign/room assets shared across modalities | Existing audio extraction layout suggests a future connection; NPC/monster/image/lore extractors remain proposed. [S2](sources.md#s2-echo-forge). |
| Spell reference data informs sound design, with explicit versus imagined sounds kept separate | Unpublished Echo Forge spell-sound report analyzes the local dnd-spells catalog. Candidate Magic-panel categories are research, not an adopted shared taxonomy or finished sound library. [S2](sources.md#s2-echo-forge). |
| Phone map capture, erase secrets, zoom/rotate/flip, physical-grid lock; optional projection for tracing/play | Cam's current desired workflow, related to projector's earlier map-to-mat concept. [S1](sources.md#s1-cams-current-direction), [S3](sources.md#s3-rpg-map-projector). |
| Link player/seat/miniature/enemy identities to initiative and highlight current/next actor or group | New Cam idea. Project a ring around a miniature/group or an indicator in front of a player; advance by GM button or possible later listening. Separate initiative component proposed. [S1](sources.md#s1-cams-current-direction). |
| A central session-running tool page; selectively show an image from Mac to player iPad; fast reference/random generators | Historical General DMing Notes ideas. Notes also favor simple screen-hung initiative cards and easy atmosphere switching. Current use is not revalidated. [S5](sources.md#s5-general-dming-notes). |
| Modular, quickly composable physical lighting and terrain | Obsidian torch references; LED miniature build also shows the cost of fragile power/contact mechanisms. No automatic software integration exists. [S4](sources.md#s4-local-obsidian-notes). |

## Grounded scene illustration and shared display

**Cam's direction, 2026-10-24:** a GM may eventually narrate what is happening, have the system generate an illustration, then click to show it on a screen everyone can see. Support three kinds of view: the area itself, the characters within the area, and a particular event in progress. Display should work without projection.

Cam also envisions possible player access: render funny or exciting campaign moments, revisit an event, or show it from another angle. In both GM and player use, images should be **grounded** in adventure references and canonical character appearances, with the actual session account determining the depicted event. Generating an image and choosing to display it are distinct actions; player access and its relationship to shared display are not yet specified.

The [existing Waterdeep workspace](sources.md#s8-waterdeep-campaign-illustration-workspace) supplies a concrete manual workflow: use portraits and character profiles for identity, named miniature photos for battle-mat identification and positioning, and relevant adventure descriptions/map crops for environmental grounding. Translate these into an immersive D&D sourcebook-style scene, then use the approved image as a continuity reference for corrections. Preserve saved versions and prompts. Its instructions prioritize Cam's scene corrections over module assumptions and avoid revealing unexplored content.

**Evidence limit:** instructions, saved prompts, image files and a confirmed encounter note were read/inventoried; images were not visually evaluated and generation was not rerun. Narration input, automatic scene interpretation, a player-facing tool and one-click shared display are future capabilities. This does not establish an image extractor in Echo Forge or expand its scope.

**Assistant proposal:** reuse this workflow as a reference for a separate illustration integration, retaining explicit GM display control, fast correction, and player-safe adventure context. Speech capture, generation timing/cost, canonical-reference maintenance, player permissions, display ownership and the implementation component remain open choices; continuous listening is not selected.

## Proposed integration seams

These are **assistant proposals**, not adopted architecture or implementation tasks.

- **Scene context:** a future coordinator could associate campaign/room identity and GM-approved content references with audio, a player-safe map, images and NPC notes. Retain source provenance and keep GM-only information separate from anything displayed to players. Investigate compatibility before designing a shared schema.
- **Audio adapter:** a separate caller could eventually control Echo Forge through an explicit supported boundary. First inspect its internal session contract and establish ownership/versioning. Do not import private React state or assume its internal TypeScript exports are a stable API.
- **Map preparation without projection:** map capture/cleanup and grid preparation should deliver value independently. A player-safe screen view or tracing reference is a candidate fallback, not a selected UI. A projection adapter can be added only if the hardware earns its place.
- **Turn coordinator:** keep initiative order, actor/group identities, player-seat associations and optional miniature registration outside the audio/map MVPs. It could produce a current/next cue for a screen, optional projector, or future physical indicator. Exact messages, persistence and synchronization are undecided.
- **Human correction:** retain next/back, explicit reassignment and cue suppression as proposed interaction needs. A missed speech cue or moved miniature must not silently dictate the game state.

## Proposed turn-cue sequence

Suggested incremental approach; **Cam has not selected this roadmap**:

1. Manual next-turn with fixed player-seat cues. Establish whether it helps, using a screen if projection is unavailable.
2. Manual miniature/group registration. Test stable identities, duplicate-looking enemies, group turns and simple reassignment.
3. Camera tracking only after registration works. Measure occlusion, moved terrain, hands, lost identity and correction burden.
4. Optional audio-based advancement only after manual turn state is dependable. Preserve explicit correction and GM override; distinguish turn-change detection from rules adjudication.

Projected rings require camera/projector geometry and a stable table coordinate frame as well as actor identity. Seat cues are simpler, but projected seat cues still depend on viable optics. Neither is a requirement for map preparation, references or audio.

The autonomous DM horizon would require separate choices about game state, rules, uncertainty, player consent and narrative control. It is not a dependency for any step above.
