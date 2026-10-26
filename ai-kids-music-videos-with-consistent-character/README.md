# AI Kids Music Videos with Consistent Character

An end-to-end workflow for turning a children's song idea into a polished, landscape 16:9 animated music video with one recognizable 3D character throughout.

**CloneVoice → Artistly → VideoExpress.** Create an original song, design a song-led storyboard around a locked character bible, animate one clip per selected scene, assemble the clips with the music, then save and export the finished MP4.

## Start here

1. Sign in to CloneVoice.ai, Artistly.ai, and VideoExpress.ai in a supported browser session.
2. Give the agent `SYSTEM_PROMPT.md` and a song idea. Include any must-have character details or an authorized reference image.
3. The workflow resolves the title, lyrics direction, character, and shot plan, then presents a concise production brief and credit-use summary.
4. Reply **GO** to approve the named generation run. Nothing is generated or uploaded before GO. After approval, the agent completes the run and reports progress at meaningful milestones.
5. Find the editable project in VideoExpress and the exported MP4 in the app's export library or download location.

Example: “Make a cheerful counting song about a little red panda exploring a garden. The hero is a tiny red panda with a yellow raincoat, green boots, and a blue backpack. Landscape 16:9. GO.”

## Workflow files

| File | Purpose |
|---|---|
| [`SYSTEM_PROMPT.md`](SYSTEM_PROMPT.md) | Full browser-agent production contract and recovery plan. |
| [`PROMPT_GUIDE.md`](PROMPT_GUIDE.md) | Character-lock, storyboard, and image-to-video prompt rules. |
| [`WORKFLOW.json`](WORKFLOW.json) | Machine-readable settings, invariants, and phase map. |
| [`prompt_book.example.json`](prompt_book.example.json) | Example per-scene handoff from storyboard to VideoExpress. |
| [`examples/example-request.md`](examples/example-request.md) | Paste-ready request template. |
| [`evals/acceptance-checklist.md`](evals/acceptance-checklist.md) | Evidence-based completion review. |

## What's distinctive

- The frame is always **landscape 16:9** from storyboard through export.
- A single immutable character bible and one approved reference image anchor every scene.
- Song structure drives the visual arc; scene count and clip durations are planned from the actual track length.
- VideoExpress prompts preserve identity and use modest, pose-compatible movement. The default is a music montage, not generated dialogue or automatic lip-sync.
- A GO checkpoint summarizes the intended song, image, and clip generation before any credits are used.
- Generated references, storyboard images, clips, and timeline placement receive visible checks before proceeding.

## Requirements and boundaries

- Signed-in browser access to CloneVoice.ai, Artistly.ai, and VideoExpress.ai, plus enough included generation capacity for the approved run.
- A browser-capable agent that can operate the visible interfaces. The workflow does not require API keys or credential handling.
- Use only assets the user is authorized to use. Keep public-gallery sharing off. Do not buy credits, change plans, publish the finished video, delete saved assets, or change account-wide settings without separate authorization.
- GO covers only the stated production plan and bounded corrections. Login, CAPTCHA, a newly presented agreement, unexpected charges, unsupported controls, or a material scope change are stop points.
- The workflow cannot promise a specific output quality or exact duration. Report observed results and any review limitations.

## Source playbooks combined

This is an original combined workflow informed by the production patterns in [VideoExpress Consistent Character Talking Video](https://github.com/ai-playbooks/videoexpress-consistent-character-talking-video) and [Nursery-Rhyme Music Video Automation](https://github.com/ai-playbooks/nursery_rhyme_music_video). It adapts their character-bible, storyboard, prompt-book, scene mapping, timeline, and export ideas for a fixed landscape kids-music-video use case.
