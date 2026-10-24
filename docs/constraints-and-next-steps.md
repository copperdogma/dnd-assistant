# Constraints, lessons and next steps

Recorded **2026-10-24**. [Scope](scope.md) records decisions; [sources](sources.md) distinguish direct reports from historical logs.

## Hardware failure and retained value

**Cam's report:** the original RPG Map Projector attempt failed because the projector lacked suitable short throw and coverage, particularly at the very steep projection angle needed. The new requirement is a tripod **beside the table**; ceiling mounting is not acceptable. Overall assistant work must not depend on projection.

**Local unpublished evidence:** projector Story 001's June 2026 work log records an accepted 9-point physical camera-to-projector mapping at a revised angle (2026-06-08 00:15), taking about 149 seconds. It did not establish an aligned playable battle grid. Later entries record desktop wallpaper appearing instead of the intended projector view, rejected structured-light mappings, and illumination appearing as bands/crescents rather than a clean grid. The final 03:10 entry leaves physical projector/camera/mount geometry blocked. These are source-log observations, not measurements reproduced here. [S3](sources.md#s3-rpg-map-projector).

Both findings matter: the rig failed its practical purpose, while software workbenches, calibration methods, refusal checks and diagnostics may still be useful. Do not label the entire software project valueless or label a mapping success as a proven deployment.

**Physical limits:** calibration can correct coordinate distortion; it cannot create missing projection coverage, improve optical focus across a steep plane, supply brightness, or remove shadows from hands/minis/terrain. More calibration code alone does not resolve the hardware feasibility question. A camera tracking success would also not prove projection quality.

## Other lessons and constraints

- The abandoned worksheet increased work and duplicate transcription. Any new assistant flow must reduce table effort rather than add bookkeeping. [S6](sources.md#s6-reference-and-delivery-projects).
- The LED miniature note reports LEDs failing after polymer-clay baking, magnets losing magnetism after heating, and unreliable thin-base contacts/retention. Treat these as this build's reported failures, not universal material thresholds. The terrain note favors modular, quick and composable lighting, with dislike of disposable/non-flickering options. [S4](sources.md#s4-local-obsidian-notes).
- Keep references and module assets linked, with private material retained in its source location. Existing source licensing and access do not imply redistribution permission.
- Historical native iPad, always-listening and unrestricted SceneUpdate claims must not override newer Echo Forge decisions or bounded runtime evidence. [Component limits](components.md#echo-forge-capability-limits).
- Grounded illustrations must preserve canonical character identity and distinguish session events from module facts and artistic interpretation. Avoid exposing hidden adventure material through either prompts or player-facing tools. Narration input, player access and shared-screen behavior remain undesigned; the existing [illustration workspace](sources.md#s8-waterdeep-campaign-illustration-workspace) demonstrates a manual reference workflow only.
- No new spend, hardware purchase, system platform, listening policy, tracking approach or component scope expansion is decided here.

## Open questions

1. Which pain should the first umbrella experiment address: live map setup, reference lookup, or turn visibility? The new map problem is clear; relative priority is not yet locked.
2. What is the current manual map-setup time, and what time/error/correction budget would count as useful? Which physical table area must be covered?
3. What useful map workflow should remain when no projector is present? Where should map preparation live without silently changing the projector MVP?
4. Should the first turn cue identify a player seat, a character, an enemy group or a specific miniature? How are group turns, delayed turns and corrections represented?
5. Is there feasible projector hardware for the side-tripod position? Required throw distance, table footprint, focus and room brightness need measurement before choosing equipment.
6. If continuous listening is ever revisited, what do players agree to capture, retain and send off-device? How does the GM correct false turn detection?
7. Which source projects should expose explicit integration contracts, and who owns/version-controls each? Is any shared account/backend actually needed?

8. For illustration, how should narration be captured, canonical character references maintained, and corrections handled? What may players generate or send to the shared screen, and who controls display? Generation latency/cost and the owning component are also undecided.

## Suggested next steps

No feature implementation is authorized by this list.

1. **Recommended next action:** write up one representative encounter's current map workflow, including the slow step, rough timing, table size and the useful no-projector fallback. Choose one small improvement and acceptance criterion with Cam.
2. If turn cues are chosen, consider the [manual-seat-first sequence](ideas-and-integrations.md#proposed-turn-cue-sequence) before adding miniature tracking or audio. Record selection as a dated decision.
3. If projection is revisited, first make a bounded side-tripod feasibility measurement of coverage, focus, brightness, shadows, placement and setup time. Define pass/fail thresholds before another calibration iteration. No purchase or new rig is implied.
4. Before any integration code, refresh each owner repo, inspect current boundaries, and propose the smallest explicit contract. Protect existing dirty work. Keep each component useful on its own.

Completion of this kickoff means the ideas and evidence are navigable and resumable, not that these open questions or experiments have been resolved.
