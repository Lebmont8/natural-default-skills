---
name: "natural-media-default"
description: "Art direction, prompting, continuity, provider routing, and quality gates for generated images and video."
---

# Natural media default

Use anti-slop as a production workflow, not as a single visual style. Preserve explicit user, brand, character, campaign, meme, illustration, anime, advertising, surreal, UI, or project art direction. The requested style wins.

## Workflow

1. Define or infer a short creative brief:
   - purpose and destination;
   - audience;
   - primary subject;
   - first visual priority;
   - one main action;
   - intended impression;
   - must-preserve and must-avoid constraints.
2. Choose the actual mode: text-to-image, image edit, text-to-video, or image-to-video.
3. Check the selected provider/model capabilities before using references, character workflows, first/last frames, seed, negative prompts, audio, edit, extend, or other controls. Never pretend an unavailable feature is active.
4. Build the prompt from observable decisions rather than generic quality labels.
5. Generate the least complex asset that satisfies the brief.
6. Inspect the viewable result using the rejection rubric.
7. Diagnose one dominant defect. Prefer a local edit for a local image defect; regenerate when the concept, composition, or overall geometry is wrong.
8. Make at most one safe, focused correction automatically. Do not loop or spend paid credits without authorization.

## Core direction

- Make the visual hierarchy intentional: one primary subject, one readable action, and a clear first point of attention.
- Keep only details that support the story, product, place, or action.
- Use motivated light, color, texture, wear, asymmetry, and negative space. Random grain, pores, clutter, crooked framing, or "imperfections" do not create authenticity by themselves.
- Describe visible materials, spatial relationships, light direction, and physical motion instead of relying on `8K`, `masterpiece`, `ultra-detailed`, `cinematic`, `epic`, or similar cargo-cult labels.
- Treat each reference as a named constraint for identity, product, wardrobe, location, composition, palette, or style. Do not use one reference as an ambiguous source for everything.
- Use camera and lens language only when it communicates a useful visual result. Do not imply exact optical simulation.
- Keep model-generated text short and task-critical. Verify required copy character-for-character. Prefer post-production for subtitles, long copy, and stable video logos.
- Do not force documentary realism onto advertising, illustration, anime, memes, surreal work, diagrams, UI, icons, or intentionally synthetic art.

## Mode routing

- For text-to-image and image edits, read [references/images.md](references/images.md).
- For text-to-video and image-to-video, read [references/video.md](references/video.md).
- For provider-specific behavior, read [references/providers.md](references/providers.md).
- Before delivery or retry, read [references/rejection-rubric.md](references/rejection-rubric.md).

## Delivery discipline

Inspect the asset when a view is available. Do not claim identity, text, anatomy, continuity, or motion passed unless it was actually checked. If inspection is unavailable, state that limitation instead of inferring quality from the prompt.
