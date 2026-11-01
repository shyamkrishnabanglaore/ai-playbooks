# Two Consistent Characters — 180–200 Second Music Video

This is a combined workflow specification and browser-agent prompt kit, not a rendered video or a tested software integration. It adapts the two repositories linked below. Their controls and plan limits must be checked in the live apps before execution.

## Start here
1. Put SYSTEM_PROMPT.md in your browser-capable agent's project instructions. Attach the other files as reference material.
2. Sign in to CloneVoice.ai, Artistly.ai and VideoExpress.ai in the browser available to that agent.
3. Attach two character reference images and supply a song topic. If you have no images, have the agent create and obtain your approval of two canonical character references before scene production.
4. Paste START_PROMPT.txt. Edit the topic and references first. Review the concrete production plan and credit ceiling before authorizing paid generations.
5. Say Resume after interruption. The agent must reconcile saved state and live jobs before continuing.

## Defaults
- Original children's music video, English, ages 3–8, landscape 16:9.
- Target 190 seconds; final permitted duration 180–200 seconds, including intro and outro.
- Polished Pixar-like 3D feature-animation aesthetic: appealing original characters, rounded forms, expressive eyes, soft materials, warm cinematic lighting, colorful environments. Do not copy an existing film character.
- Exactly two recurring characters in every story scene. No extra people or humanoid background figures.
- A continuous externally sung soundtrack. Characters dance and act with closed mouths; lip-sync is off.
- Default 38 unique five-second scenes, recalculated after measuring the actual approved audio. Five-second scenes are a planning choice, not a claim about every account's available controls.
- FullHD MP4, 1920×1080 where supported. Never describe an upscaled export as native generation resolution.

## Combined production route
Brief → canonical references → song → measured song and lyric timing → storyboard → reference-controlled scene images → checked prompt book → video batches → visual and continuity checks → timeline and continuous song → sync audit → saved project → export queue → completed export verification.

Artistly remains useful for song-led storyboard planning. Its Nursery Rhymes tool, as documented in the source, has no character-reference prompt field. Therefore it cannot be assumed to preserve two visual identities. Use its images only if both identities actually pass reference comparison. Otherwise generate scene start images in VideoExpress with Reference Photo 1=A and Reference Photo 2=B. Do not waste three whole storyboard retries trying to solve missing reference controls.

## What is retained and changed
| Concern | Combined decision |
|---|---|
| Two-character source: 10/30 second videos | Replace the total-length limit with 180–200 seconds |
| Fixed reference slots and identity tags | Retain for both characters throughout production |
| Continuity, screen sides, layout and lighting | Retain and extend to all scenes |
| Nursery source: CloneVoice → Artistly → VideoExpress | Retain music-first route; add reference-controlled image fallback |
| Nursery source: first completed take, no previews | Replace with visual checks because identity consistency is required |
| Two-character source: generated sound/dialogue | Override with silent clips and one external music track |
| Advanced Mode conflict | Use it only when required for the live manual-duration controls |
| Nursery source: dynamic storyboard scene count | Use music timing and available durations to decide scene count; split or add planned shots as needed |
| Fixed batch of five | Cap concurrency at the smaller of five and the visible account limit |
| Export queue as completion | Report queued separately; verify completed output before calling the MP4 delivered |
| Existing runtime state in source repo | Never reuse it; start a fresh state file with no historical IDs |

## Sources inspected
- https://github.com/ai-playbooks/videoexpress-two-character-agent — README.md and SYSTEM_PROMPT.md.
- https://github.com/ai-playbooks/nursery_rhyme_music_video — README.md, SYSTEM_PROMPT.md, PROMPT_GUIDE.md, WORKFLOW.json, prompt_book.json and WORKFLOW_STATE.json.
- Inspected 2026-11-01 via raw default-main file URLs. No live generation or app-control validation was performed. Source state/config files contain legacy and run-specific values; none are imported into this kit.

## Files
- SYSTEM_PROMPT.md: complete operating instructions.
- START_PROMPT.txt: paste-ready launch request.
- PRODUCTION_PLAN.md: 190-second arrangement and prompt examples.
- workflow.json: machine-readable defaults and policies.
- character_bible.json: editable identity and set locks.
- prompt_book.json: 38 fresh planned scene slots, not submission-ready prompts.
- WORKFLOW_STATE.json: clean checkpoint.

Character consistency is a production target supported by references and review, not a guarantee that generative models will never drift. Only approved frames and clips may progress.
