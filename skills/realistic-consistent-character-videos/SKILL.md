---
name: realistic-consistent-character-videos
description: Produce a fast-paced photorealistic three-minute video of one or two real people from their reference photos, end to end in the VideoExpress web app with a browser - detailed character descriptions and voice locks, Consistent Character anchors, multi-shot image-to-video clips with lip-synced dialogue in a chosen English accent, dead-air trimming and export. Use when the user attaches photos of real people and asks for a consistent-character video, a video "starring" themselves or a colleague, a realistic talking scene with their face, or a VideoExpress consistent character video.
---

# Realistic Consistent Character Videos in VideoExpress

The full recipe is `../../PLAYBOOK.md` at the repository root (public URL: https://raw.githubusercontent.com/jdmckin/realism-1/main/PLAYBOOK.md). Follow it exactly. It is self-contained.

## Non-negotiables
1. **Browser only.** Work at https://app.videoexpress.ai/. Run no code, shell, tests or file processing. The only file action is uploading the user's reference photos (Media Library → My Media → Images → Upload file → + Add files → Upload files).
2. **No preflight.** No capability audit, readiness check, model verification, cost estimate or approval gate.
3. **One question.** Ask for 1–2 photos plus a name per character (1 or 2 characters; best a close, sharp, front-facing head-and-shoulders photo), a story, an English accent per character, and optionally pacing (Multi-shot default or Single-shot). The finished video length is 3:00 for every session. Then produce without stopping.
4. **Consent.** Adults only, real likenesses the user has the right to use. No sexual, humiliating, hateful, political-impersonation, fake-news or deceptive content of a real person.
5. **Realistic only.** Create Video From Prompt → **Landscape 16:9** → Image Type **Photorealistic (Cinematic)**, **Use Creative mode ALWAYS ON** (anchors, start images, retries), **Automatically enhance my image prompt OFF**, Lipsync HD and Narration OFF, **public gallery OFF** on every generation.
6. **Identity.** Write a very detailed **Character Description** per person (90–140 words: age/build, face shape, cheeks, jaw, chin, eyes, brows, nose, lips, skin, ears/facial hair, hair, accessories, plus a garment-by-garment Wardrobe Lock) and paste it verbatim into every image prompt; a Short Tag goes in video prompts. **Use Consistent Character** ON (the user clicks **I Agree** on the one-time Disclaimer). Make one chest-up anchor per character from only their photo in **Reference Photo**, select the closest carousel image (✓) and click **+ Consistent Character**. Then **Reference Photo** = Character 1's anchor, **Reference Photo 2** = Character 2's anchor.
7. **Voice Lock.** One voice line plus the normalized accent phrase per character, word for word identical in every video prompt. English only.
8. **Multi-shot.** Every session finishes at 3:00. Start with 25 clips × 8 s, 2–3 shots per clip joined by "A hard cut transitions to…". For Single-shot, start with 42 clips × 5 s, no cuts. Advanced Mode → **Automatically enhance my video prompt OFF** (it is ON by default). Every prompt starts with `C## —`.
9. **5 in parallel.** Never more than 5 videos rendering; work in waves.
10. **Dead-air trim** at each clip's head and tail only, never inside a clip, then **Auto Align Clips**. Set the editor canvas to **Landscape 16:9**, export High / FullHD / mp4, and verify the file is 1920×1080 before sharing the My Videos link.

**Story requirement.** Every video must be dramatic, intense and emotionally affecting. Choose one feeling the viewer should carry out of the story. Open on a moment of pressure, quickly show what the protagonist wants and what they could lose, and make each beat raise the stakes or change a relationship. Around 2:05, use an earned reveal or a difficult choice to turn the story. End with a visible consequence and a final image that lands the emotion. Use restrained dialogue, readable reactions, purposeful silence and sound to build intensity.

## Only stop for
A photo upload your browser can't do, the one-time Consistent Character Disclaimer (**I Agree**), a login page, a one-time Terms screen, or an out-of-credits screen. The user does it, says "done", and you continue where you stopped.

## References
- `references/videoexpress-ui-map.md`: every control, label, default and quirk
- `../../docs/video-prompting.md`: how to write multi-shot video prompts
- `../../examples/README.md` and `../../examples/realistic-rooftop-tickets.md`: a worked job with every prompt written out
