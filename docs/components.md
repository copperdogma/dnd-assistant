# Component inventory

Evidence checked **2026-10-24**. Repository README links below were successfully read through GitHub. Local paths were checked separately. “Implemented” describes source evidence; no application, deployment, or physical rig was run during this documentation task. [Evidence and freshness](sources.md).

| Component | Observed status and useful role | Boundary |
| --- | --- | --- |
| [Echo Forge](https://github.com/copperdogma/echo-forge/blob/main/README.md) | Existing browser/PWA audio prototype: layered ambience, Sound Actions, source controls, typed input and explicit push-to-talk. Campaign/room-keyed audio extraction and an internal persistent session provide useful stepping stones. | No initiative tracking; no shipped all-in-one GM. Remote sessions and public library extraction remain deferred. |
| [RPG Map Projector](https://github.com/copperdogma/rpg-map-projector/blob/main/README.md) | Failed physical hardware experiment with reusable browser workbench, grid/calibration research, fixture labeling and diagnostics. Potential stepping stone, with hardware feasibility unproven. | Source docs exclude initiative and token/monster management. Software and bounded mapping results do not prove playable projection. |
| [copper-dog-dnd-site](https://github.com/copperdogma/copper-dog-dnd-site/blob/main/README.md) | Existing narrow delivery hub: pinned source projects build Spellbook Maker and Druid Shape-Change Beasts plus a small landing page. | Deployment machinery is source evidence; live hosting/auth was not tested. This is not the broad assistant umbrella. |
| [dnd-spells / Spellbook Maker](https://github.com/copperdogma/dnd-spells/blob/main/README.md) | Existing Aidedd XML/catalog extraction and local spellbook renderer; selection, design, print, and saved selection workflow. | Useful reference/print component; no initiative or campaign runtime contract established. |
| [dnd-5e-monsters / Druid Shape-Change Beasts](https://github.com/copperdogma/dnd-5e-monsters/blob/main/README.md) | Existing printable Wild Shape sheet. Current remote README also documents selectable poker-size shape-change cards, art and a custom player card; local checkout README is older. | Narrow reference generator, not an encounter-state tracker. |
| [dnd-phb-5e-index](https://github.com/copperdogma/dnd-phb-5e-index/blob/master/README.md) | Existing revised 5e PHB index and PDF pointer; reduces cross-reference lookup friction. | Historical reference artifact; not evidence of 2024 rules coverage. No local checkout found in this pass. |
| [dnd-5e-spell-summarizer](https://github.com/copperdogma/dnd-5e-spell-summarizer/blob/master/README.md) | Repository exists; fetched README contains only its title. Keep as a related pointer. | Implementation, usability and reuse status unknown; do not infer functionality from name. No local checkout found in this pass. |
| [2024 character creation worksheet](https://github.com/copperdogma/dnd-5e-2024-char-creation-worksheet/blob/main/README.md) | **Explicitly abandoned.** Added player work, back-and-forth and duplicate recording outweighed its value. | Preserve the lesson; do not resurrect as an active roadmap item. |
| [LED miniature and terrain notes](sources.md#s4-local-obsidian-notes) | A documented LED druid miniature build with mechanical issues; terrain note collects torch techniques and modular-light preferences. | Physical inspiration, with no camera identity/tracking or initiative integration demonstrated. |
| [Waterdeep campaign illustration workspace](sources.md#s8-waterdeep-campaign-illustration-workspace) | Existing private workflow with party portraits, named miniature photos, art direction, module-grounding notes, saved scene images and revision prompts. A concrete starting point for party-consistent scene art. | File-based image-generation workflow; no narration service, player tool or shared-screen control demonstrated. Source workspace remains read-only. |
| Local character-sheet artwork | [dnd-calc-page-char-sheet](/Users/cam/Documents/Projects/dnd-calc-page-char-sheet) contains PDF/PSD artwork and photos. | Files inventoried only; no Markdown spec or Git repository observed, no integration assumed. |

## Verified local locations

- [Echo Forge](/Users/cam/Documents/Projects/echo-forge)
- [RPG Map Projector](/Users/cam/Documents/Projects/rpg-map-projector)
- [Delivery hub](/Users/cam/Documents/Projects/copper-dog-dnd-site)
- [Spellbook Maker](/Users/cam/Documents/Projects/dnd-spells)
- [Wild Shape](/Users/cam/Documents/Projects/dnd-5e-monsters)
- [Abandoned worksheet](</Users/cam/Documents/Projects/dnd-5e-2024-char-creation-worksheet ABANDONED>)

- [Waterdeep campaign illustrations](</Users/cam/Documents/RPG/!Campaigns/2025 Matt's 5e Waterdeep Campaign/images>)

These are machine-local navigation conveniences, not portable dependencies or submodules.

## Echo Forge capability limits

[Story 034](https://github.com/copperdogma/echo-forge/blob/main/docs/stories/story-034-module-to-soundscape-extraction.md) organizes assets by campaign and room. Its [schema](https://github.com/copperdogma/echo-forge/blob/main/data/campaigns/campaign-asset.schema.json) explicitly implements **audio only**; NPCs, monsters, images and lore are future modalities.

[Story 030](https://github.com/copperdogma/echo-forge/blob/main/docs/stories/story-030-persistent-global-soundscape-session.md) and [session.ts](https://github.com/copperdogma/echo-forge/blob/main/src/soundscape/session.ts) establish an internal React/DOM-free session. This is a promising seam, not a published SDK or a remote-control service.

[Story 036](https://github.com/copperdogma/echo-forge/blob/main/docs/stories/story-036-soundscape-assembly.md) and [Story 037](https://github.com/copperdogma/echo-forge/blob/main/docs/stories/story-037-soundscape-execution-auto-play.md) provide limited SceneUpdate assembly/execution against existing sources/events. Arbitrary generated Source materialization is not a shipped capability. Phone capture/table control in the spec is direction, not proof of finished remote integration. Always-listening remains future; explicit push-to-talk exists. [Story 053](https://github.com/copperdogma/echo-forge/blob/main/docs/stories/story-053-combat-denizen-source-panels.md) excludes initiative/player/combat-state tracking.
