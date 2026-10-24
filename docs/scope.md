# Scope and decisions

Status: documentation umbrella established **2026-10-24**. No umbrella application or cross-component integration has been built. [Source ledger](sources.md).

## Cam's current direction

- Gather scattered RPG enhancement ideas and pointers into one durable project, including the failed projector experiment.
- Preserve live-table momentum, particularly the time lost while drawing battle maps.
- A phone photographs a module map. The GM can erase hidden/unwanted information, zoom, rotate, flip, and lock the map to the physical battle-mat grid. A calibrated camera/projector may project it for tracing or direct play. This is the desired workflow, not a statement that every operation exists today.
- Projection is **optional**, never a dependency for the overall system. If used, the rig must sit on a tripod beside the table. Ceiling mounting is unacceptable. This supersedes older projector notes allowing other placements for this new integration concept; it does not edit those source documents.
- Preserve the new idea of associating player identities, seats, miniatures, and enemies with initiative, then indicating the current/next miniature or group and/or the relevant player's position. A GM next-turn button is a candidate; listening for turns is a possible later input.
- Ground scene illustrations in the adventure and canonical character appearances. A future GM could narrate an area, the party in that area, or a particular event, generate an image, and explicitly click to show it on a shared screen. Player access could also support funny/exciting moments and alternate viewpoints. This is Cam's desired direction, not a shipped integration; see the [illustration concept](ideas-and-integrations.md#grounded-scene-illustration-and-shared-display) and [existing workspace](sources.md#s8-waterdeep-campaign-illustration-workspace), added 2026-10-24.
- Keep the human GM in control. An autonomous DM is optional exploration, not the initial requirement.

These requirements come from the [2026-10-24 conversation](sources.md#s1-cams-current-direction). No platform, shared backend, deployment, universal data model, or first implementation component has been selected for the umbrella.

## Historical vision

Echo Forge's [idea intake](sources.md#s2-echo-forge) records a larger all-in-one assistant: ingest a module, produce NPC portraits and AI voices, dynamic maps and soundscapes, and eventually an AI GM. The same source explicitly places that vision outside Echo Forge's scope. Its early native iPad preference was superseded by accepted web/PWA-first ADR-001 for Echo Forge; that ADR does not select the platform for this umbrella.

The old [General DMing Notes](sources.md#s5-general-dming-notes) include a possible custom page collecting session-running tools. This is historical motivation, not evidence that a central software project already existed.

## Ownership boundaries

| Area | Owner / treatment |
| --- | --- |
| Vision, inventory, cross-project ideas and decisions | This umbrella |
| Soundscapes, audio catalog, sound actions, internal audio session | Echo Forge |
| Module-map cleanup, calibration and projection research | RPG Map Projector |
| Spellbook and Wild Shape references | Their own source projects; narrow delivery through copper-dog-dnd-site |
| Party-consistent scene illustration | Existing Waterdeep campaign workspace; broader narration, player access and shared display are future integration direction with ownership undecided |
| Initiative, seats, miniatures, turn cues | Proposed separate component/integration; owner and contract undecided |
| Continuous listening, autonomous DM, multimodal module package | Future exploration; not implemented umbrella capability |

Echo Forge Story 053 expressly excludes player/initiative/combat-state tracking. RPG Map Projector excludes initiative and monster/token management. Connections must respect these boundaries or involve an explicit decision with each owner.

## Scope of this kickoff

Create and verify Markdown documentation and project instructions; retain source pointers and failed experiments. The original kickoff did not authorize dependency installs, feature implementation, component edits or publication. On 2026-10-24, Cam subsequently authorized checking in this documentation and creating/publishing the public `copperdogma/dnd-assistant` GitHub repository. Implementation and component edits remain outside this documentation scope. The [integration sequence](ideas-and-integrations.md#proposed-turn-cue-sequence) is an assistant suggestion awaiting selection, not Cam's locked roadmap.
