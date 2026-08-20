# Video workflows

## Shot design

Treat one generation as one shot. Prefer:

- one primary subject;
- one physical action;
- one camera behavior;
- at most one simple environmental motion.

Split action chains, location changes, transformations, or multi-beat stories into separate short clips and edit them together.

For short clips, describe two or three temporal beats only when they fit the duration. Dialogue must be concise enough to be spoken naturally in the allotted time.

## Text-to-video

Structure the prompt as:

`starting scene → subject → one action → camera motion → environmental motion → light and style → timing beats → audio if supported`

Describe physical behavior rather than abstract emotion. Translate "joyful greeting" into "she smiles and waves once."

Avoid mutually competing movements. If camera motion is important, keep subject and environment motion simpler.

## Image-to-video

The input image supplies subject appearance, composition, color, light, and style. Use the text primarily for motion.

Before animation, hard-check the source frame for:

- face and identity;
- hands and anatomy;
- product shape;
- text and logos;
- reflections and shadows;
- background geometry;
- unintended objects.

Do not animate a defective first frame; correct it first.

Structure the motion prompt as:

`subject motion → camera motion → environmental motion → pace → elements that remain visually consistent`

Do not restate the subject's full appearance unless the provider requires it. Repetition can cause reinterpretation or reduced motion.

Use first and last frames only when the selected model supports them and the transition is physically simple and plausible.

## Continuity

Preserve identity, anatomy, wardrobe, props, product, background geometry, time of day, light direction, exposure, and material appearance throughout the shot.

Prefer positive continuity language for providers that reject negative prompting:

`The subject, wardrobe, product, background, reflections, and lighting remain visually consistent throughout. Locked camera. Restrained natural motion.`

## Text and audio

Prefer post-production for subtitles, long labels, repeated UI, and stable logos.

Use generated dialogue or audio only when the selected model supports it. Put dialogue in a distinct block when the provider recommends it. Keep speakers and timing unambiguous.

## Focused correction

Diagnose the dominant temporal defect before retrying:

- identity drift;
- background drift;
- motion discontinuity;
- texture crawl;
- exposure pumping;
- object spawning/disappearance;
- physically implausible motion.

Change one motion, camera, timing, or reference decision at a time.
