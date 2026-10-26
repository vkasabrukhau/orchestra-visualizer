# Project state

Edited only on `main` (or in the PR that merges). Everything Claude needs to
know about *where we are* lives here; *what we're building* lives in `docs/spec/`.

Last updated: 2026-10-22

## Status by requirement

| # | Requirement | Status | Branch / owner | Notes |
|---|---|---|---|---|
| 1 | Upload score (MusicXML) + optional MP3 | not started | | |
| 2 | Sync score and audio (auto + manual, confidence) | not started | | alignment method undecided |
| 3 | Information map | not started | | schema in `.claude/rules/score-and-info-map.md` |
| 4 | Customize display (one style, colors, positions, 64 parts) | not started | | |
| 5 | Generate the visual | not started | | |
| 6 | Export (project file, MP4) | not started | | |
| 7 | Playback (controls, measure highlight, click-to-play) | not started | | |
| 8 | Local saving (manual project file) | not started | | |

Status values: not started · in progress · in review · done · blocked

## Screens

| Screen | Status | Notes |
|---|---|---|
| Import | not started | |
| Sync | not started | only with uploaded audio |
| Customize | not started | rename the two "Dynamics" rows; label pitch ramp + Mappings as later phase |
| Preview | not started | |
| Export | not started | |

## Open questions (need a human decision)

1. **Stack** – framework, rendering library (PixiJS + pixi-filters suggested), audio handling, export pipeline.
2. **Alignment method** – see `.claude/skills/score-audio-alignment/SKILL.md` for candidates.
3. **Visual direction** – A (concert program) vs B (one material).
4. **Audience** – new listeners following a symphony vs musicians maximizing prep time; needs confirmation.
5. **MP4 export** – in-browser (WebCodecs / ffmpeg.wasm) vs server-side.

## Known breakage

None recorded.

## Later-phase backlog (not in scope)

Other score/audio formats · custom mappings and gradients · pitch, articulation,
ramps, look-ahead ring · browser auto-restore · sign-in and cloud storage.
