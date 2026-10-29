RooTsFact Video Production Architecture

Goal

Build a repeatable, zero-budget workflow for producing high-quality Arabic YouTube Shorts.

Repository Safety

- Preserve existing files.
- Add new files in small, reversible changes.
- Never overwrite or delete files without explicit approval.

Production Pipeline

1. Research: Gather reliable historical sources and distinguish verified facts from disputed claims.
2. Script: Write an engaging Arabic narration with a strong opening and a clear ending.
3. Shot planning: Specify timestamps, visuals, narration, sound effects, and asset sources.
4. Asset collection: Use public-domain or properly licensed images and footage.
5. Audio: Accept user-provided recordings or use a genuinely free text-to-speech option.
6. Transcription: Generate Arabic captions and align them with the narration.
7. Editing: Use Remotion for scenes, titles, animation, and compositing.
8. Audio processing: Use FFmpeg when available.
9. Rendering: Export a vertical MP4.
10. Quality assurance: Verify video dimensions, playback, captions, audio, and factual accuracy.
11. Publishing package: Prepare a title, description, hashtags, thumbnail concept, and source list.

Target Export

- Resolution: 1080x1920
- Aspect ratio: 9:16
- Frame rate: 30 fps
- Container: MP4
- Video codec: H.264
- Audio codec: AAC when supported
- Captions: Arabic, right-to-left, readable, and synchronized

Free-First Policy

Prefer open-source tools and assets with compatible licenses. Check current usage limits before relying on cloud services. Do not assume that an API, hosting service, or AI generation service is free.

Honest Completion Policy

A successful code edit is not proof of a successful render. Report a finished video only after the actual MP4 has been generated and checked.

Initial Implementation

Start with content files before introducing the Remotion application. Add code only after the content structure and execution environment have been verified.
