# Sources and setup record

Compiled and checked **2026-10-24 (UTC)** for this umbrella kickoff. This is a curated synthesis, not an exhaustive archive or a live status dashboard. Original sources remain authoritative for their own projects.

## S1: Cam's current direction

Source: the initiating conversation and trusted research handoff on 2026-10-24. Cam requested this exact folder as the central collection of disparate RPG tools and ideas, including the failed RPG Map Projector. The handoff supplies the map/photo/edit/grid workflow, side-tripod-only placement, reported optical failure, optional projection, initiative/seat/miniature cue idea and human-control boundary.

The manual-seat-first progression is an assistant suggestion recorded in that handoff, not a user decision. This document preserves those distinctions in [scope](scope.md) and [integration concepts](ideas-and-integrations.md). No durable conversation export is added; this provenance note is the retained record.

## S2: Echo Forge

GitHub files below were successfully fetched through the connected GitHub tool, using the repository's default branch. Local source files were also read to compare capabilities and older notes. All branch links are moving references; the file blob IDs below identify the observed snapshots.

| Source | Use / observed blob |
| --- | --- |
| [README](https://github.com/copperdogma/echo-forge/blob/main/README.md) | Current component identity; `c5bc8623afd96a5bfc8ed2cb4451bdba069a62bd` |
| [idea-intake.md](https://github.com/copperdogma/echo-forge/blob/main/docs/idea-intake.md) | Lines 251–254 larger module-to-AI-GM vision, 280–287 companion/platform ideas, 300–305 out-of-scope boundary; `675aa5592da162518a092a30e47839b1d5f26fb3` |
| [inbox.md](https://github.com/copperdogma/echo-forge/blob/main/docs/inbox.md) | Multi-user character sound packages near line 257; continuous listening/“Ultimate Dream” near line 289. Idea evidence only; stale implementation summaries are not accepted as current status. `38f127a666a7fbb057dcdcb5459957fad8aa90ca` |
| [Story 030](https://github.com/copperdogma/echo-forge/blob/main/docs/stories/story-030-persistent-global-soundscape-session.md) and [session.ts](https://github.com/copperdogma/echo-forge/blob/main/src/soundscape/session.ts) | Internal session boundary; story `3f655779665f101b5ebaa7853daeab6cc47d4a7d`, code `886d43f575dd86151e7f332994c62debfc74e3f5` |
| [Story 034](https://github.com/copperdogma/echo-forge/blob/main/docs/stories/story-034-module-to-soundscape-extraction.md) and [asset schema](https://github.com/copperdogma/echo-forge/blob/main/data/campaigns/campaign-asset.schema.json) | Campaign/room layout, audio-only implementation and future modalities; story `b0e09a2e67e06d0fe0dc83e84ee9fdcc43d808d2`, schema `e821eb7fbb648150e8c791e8332fc0deeebc9e32` |
| [Story 036](https://github.com/copperdogma/echo-forge/blob/main/docs/stories/story-036-soundscape-assembly.md) and [Story 037](https://github.com/copperdogma/echo-forge/blob/main/docs/stories/story-037-soundscape-execution-auto-play.md) | Bounded SceneUpdate assembly/execution; `159520e9af4e5fed2e79bf42086d69c918fd89a1`, `6584d6b9d1ffc0767818b8cfcb75aa67aa25ca9e` |
| [Story 053](https://github.com/copperdogma/echo-forge/blob/main/docs/stories/story-053-combat-denizen-source-panels.md) | Combat denizen panels exclude initiative/player/combat-state tracking; `42c5ef21f178d28ec3261815782698f3dd299e1a` |
| [ADR-001](https://github.com/copperdogma/echo-forge/blob/main/docs/decisions/adr-001-platform-surface/adr.md) | Accepted web/PWA-first direction supersedes historical native-first preference; explicit capture, no v0 always-listening. `ed3eaa1b07c1862f5913b7d42d9275d13fd9cf37` |
| [spec.md](https://github.com/copperdogma/echo-forge/blob/main/docs/spec.md) | Companion direction interpreted as design, not completed remote integration; `8f39ee7b176e1f4b805d8611bf44293fa1f2b95e` |

Local [checkout](/Users/cam/Documents/Projects/echo-forge) was dirty at HEAD `cc3c777` (2026-06-27); its cached origin/main was `bb91a27bf410375e5bc03b2c7dd30a770a14b217`. No fetch, merge, reset or component edit was performed. Local status is not the remote state. Local AGENTS and skill filenames were inspected for context; no implementation/setup workflow was imported into this documentation-only umbrella.

Additional unpublished source: the opening scope, grounding summary and category framing of the untracked [2026-06-28 spell-sound design report](/Users/cam/Documents/Projects/echo-forge/docs/reports/spell-sound-design/20260628-dnd-spell-sound-design.md) were read. It reports analysis of 391 local dnd-spells catalog rows and distinguishes explicit clues from imaginative sound design; target pain/death sounds remain separate outcome layers. This supplies a concrete cross-project research connection, not proof of finalized taxonomy or generated audio. Its CSV, corpus and downstream registry adoption were not independently checked.

## S3: RPG Map Projector

Fetched [README](https://github.com/copperdogma/rpg-map-projector/blob/main/README.md), [Ideal](https://github.com/copperdogma/rpg-map-projector/blob/main/docs/ideal.md), [Spec](https://github.com/copperdogma/rpg-map-projector/blob/main/docs/spec.md), and [assumptions](https://github.com/copperdogma/rpg-map-projector/blob/main/docs/assumptions.md). Observed blobs respectively: `76b22365f835d91ba9af864f62f92fe01da12832`, `848c7a80b45e53a3706ee5712beead791ec08e87`, `37e0c0f52b238d8fc198957d43f17d4634bcc61e`, `e47c1145d1732980a1bc280e2618924ea959f5ee`.

Local [initial concept](/Users/cam/Documents/Projects/rpg-map-projector/docs/initial-concept.md) was also read. It explains the live-table delay, tracing versus direct play, and reversible map work. Older placement alternatives do not override Cam's new side-tripod requirement.

**Unpublished material integrated:** local modified [Story 001](/Users/cam/Documents/Projects/rpg-map-projector/docs/stories/story-001-calibration-projection-spike.md), especially the June 5–8 work-log entries, and the modified [ESP32 webcam story](/Users/cam/Documents/Projects/rpg-map-projector/docs/stories/story-005-esp32-s3-wifi-webcam-prototype.md). These distinguish prototype software, physical mapping, exposure/capture limitations, unreliable visible output and blocked grid/coverage proof. Referenced test-results artifacts were not independently replayed or visually inspected in this kickoff. The synthesis in [constraints](constraints-and-next-steps.md) attributes results to the logs.

Local HEAD `7d628da` (2026-06-03); cached origin/main `99b8682275c5a08554afb5ee7ce482cbb3af9994`; dirty source/prototype/script files were preserved. Cam's current failure report is separately attributed to S1, not retroactively invented as a source-log conclusion.

## S4: Local Obsidian notes

Both exact local equivalents were found and read, without modification:

- [LED D&D Miniature](</Users/cam/Library/Mobile Documents/iCloud~md~obsidian/Documents/obsidian/Projects/LED D&D Miniature.md>): built druid miniature, LR41 battery compartment, magnetic tin retention, rotating brass staff contact switch; reported heat/contact/retention failures. The note includes a 2025-09-02 undo-test line, which is not project evidence and was excluded.
- [LED D&D Scatter Terrain](</Users/cam/Library/Mobile Documents/iCloud~md~obsidian/Documents/obsidian/Projects/LED D&D Scatter Terrain.md>): dated 2025-01-03; torch tutorial pointers and preferences for quick modular light inserts, with reservations about disposable/non-flickering modules.

These are verified local paths, not fabricated connected-note URLs. Their linked video content was not fetched; no claims about those tutorials beyond Cam's note summaries are made. No initiative/tracking link is demonstrated by either build.

## S5: General DMing Notes

[General DMing Notes](https://docs.google.com/document/d/1jJR4jr08-qhWMpBbi2qEk1UsHBbQmmgqj258jrHK7z4/edit) was successfully read through the Google Drive connector on 2026-10-24. Relevant sections: Music/Sound, Reference/Random Generators, Reference/Tools and NPCs. Retained ideas: a central session-running page, showing an image from Mac to player iPad, soundboard/atmosphere access, quick reference, names/NPC aids and simple initiative cards.

This is general historical reference. It does not prove a pre-existing umbrella project, current app usage, or adopted integration. Personal contacts, campaign details and rules-text lists were not copied.

## S6: Reference and delivery projects

Each linked README was successfully fetched on 2026-10-24. The first three were compared with local copies; the worksheet's explicit abandonment was verified locally and remotely.

| Source | Observed README blob / coverage |
| --- | --- |
| [copper-dog-dnd-site](https://github.com/copperdogma/copper-dog-dnd-site/blob/main/README.md) | `ad8d2603c497cf4a2c36f50ac98aa60b0aa069a4`; narrow deploy bundle and pinned sources |
| [dnd-spells](https://github.com/copperdogma/dnd-spells/blob/main/README.md) | `b79fe3129df114b3a1fdfbf1dab6050dd5ef8823`; XML/catalog/render workflow |
| [dnd-5e-monsters](https://github.com/copperdogma/dnd-5e-monsters/blob/main/README.md) | `bb2dec79f9f46eb5c8099eb109e1c1cc688de4dd`; remote sheet/cards direction is newer than local README |
| [dnd-phb-5e-index](https://github.com/copperdogma/dnd-phb-5e-index/blob/master/README.md) | `343b85731c14e022ebe816e2b21b892e37a059f5`; revised index and PDF pointer; PDF not inspected |
| [dnd-5e-spell-summarizer](https://github.com/copperdogma/dnd-5e-spell-summarizer/blob/master/README.md) | `8edc3133237ee87c9a22cac1175e6acee55dc083`; title-only README; implementation unknown |
| [Abandoned worksheet](https://github.com/copperdogma/dnd-5e-2024-char-creation-worksheet/blob/main/README.md) | `8c7205c0d715fe6d5f007bc495adf6aab5d11241`; explicit abandonment outweighs stale work-in-progress/checklist prose |

Local observed HEADs: delivery hub `716c39e`, spells `01e5a27`, monsters `8fc5062`, abandoned worksheet `2ddee39`. Monsters had untracked PDFs; worksheet had a modified Markdown file. All preserved. The additional local character-sheet folder was inventoried only (PDF/PSD/photos); its artwork was not opened.

## S7: Setup conventions, checks and limits

The target folder was empty on first inspection: no existing Markdown, Git repository, AGENTS or .agents directory. Ancestor instructions were checked. Local Codex AGENTS and memory-summary guidance were consulted read-only for project conventions: compact outcome-only Ideal, project-specific ownership, preservation of dirty work, and separation of source claims from acceptance. No memories were edited or copied into the project. Component .agents/skills were inventoried; their app implementation/methodology scaffolds were not needed for this umbrella.

This kickoff adds README, AGENTS and six focused documents. It installs no dependencies, copies no component code, and initially created no external repository or publication. Cam subsequently authorized a public GitHub repository and publication on 2026-10-24; see the publication record below. Source coverage is bounded to the material listed above; it is not a search of every RPG note or repository. No application tests, physical experiments, listening tests, deployment checks or live-table acceptance were performed.

Verification: reread authored Markdown; check every internal file/heading link and absolute local pointer; verify linked repository source files through successful connector reads. Google Doc content and the two local Obsidian files were accessible. Machine-local links depend on this Mac; private GitHub links require access. Branch links may change, so retain blob IDs and refresh before implementation decisions.

## S8: Waterdeep campaign illustration workspace

Added **2026-10-24**, following Cam's request to include this existing setup and the accompanying narration/display/player-tool vision in the umbrella. That future direction is recorded in [scope](scope.md) and the [illustration concept](ideas-and-integrations.md#grounded-scene-illustration-and-shared-display); it is not implementation evidence.

Local private source: [images workspace](</Users/cam/Documents/RPG/!Campaigns/2025 Matt's 5e Waterdeep Campaign/images>). Read its [README](</Users/cam/Documents/RPG/!Campaigns/2025 Matt's 5e Waterdeep Campaign/images/README.md>), [AGENTS](</Users/cam/Documents/RPG/!Campaigns/2025 Matt's 5e Waterdeep Campaign/images/AGENTS.md>), [drider grounding note](</Users/cam/Documents/RPG/!Campaigns/2025 Matt's 5e Waterdeep Campaign/images/scene-references/drider-encounter-grounding.md>), and five saved prompt files covering the drider scene and cocoon revision, roper scene and spider-Forgle correction, and alchemist mushroom delivery.

The instructions define D&D sourcebook art direction, canonical party portraits and characterization, miniature-to-character matching for battle-mat photos, local module lookup, spoiler avoidance, scene correction, and saving images/prompts without overwriting earlier versions. The drider note records a user-confirmed location while keeping session facts and uncertain positioning separate from module grounding. Saved prompts show how these instructions were applied and revised; they do not prove every requested visual detail was achieved.

Inventoried portrait/miniature reference files, five scene PNGs and a focused map crop. No images were visually inspected, generation rerun, PDF opened, alias target reverified, or component Git state inspected during this addition. The source workspace was not modified. Private adventure text and character dossiers remain there; no assets or module passages were copied into the umbrella. This inventory establishes an existing manual illustration workflow, not a deployed narration, player-access or screen-control system.

## S9: Public repository publication

On **2026-10-24**, Cam explicitly requested checking in the umbrella documentation, creating a public GitHub repository, and publishing it. Selected destination: [copperdogma/dnd-assistant](https://github.com/copperdogma/dnd-assistant). This supersedes the kickoff's publication restriction for this documentation publication. It does not authorize copying private campaign assets, module text, credentials or contact details, or modifying component repositories.

Publication preparation reviewed the eight Markdown files for sensitive content and conflicting scope statements. Only umbrella documentation is included; local source pointers remain machine-specific and do not grant access to their targets. No application build or dependency installation is needed.
