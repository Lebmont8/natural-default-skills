# Provider notes

Capabilities change. Check the exact provider, model ID, API surface, and wrapper fields before using any feature.

## OpenAI GPT Image 2

- Use a creative brief with purpose, scene, subject, composition, light, materials, exact copy, and constraints.
- Use references and edits for identity-sensitive or product-sensitive work.
- Prefer edit for a local defect.
- Verify generated text exactly.
- Do not set `input_fidelity` for `gpt-image-2`; the model does not use that parameter because high fidelity is built in.
- Keep avoidance constraints in the main prompt unless the active tool exposes a documented separate control.

Official guide: https://developers.openai.com/cookbook/examples/multimodal/image-gen-models-prompting-guide

## OpenAI Sora 2

- Prompt one storyboard-like shot with framing, depth, action beats, light, and palette.
- Prefer short clips; two edited four-second shots can be more reliable than one overloaded eight-second shot.
- Use character, extend, and edit workflows when available instead of reconstructing continuity in prose.
- Put concise dialogue in a separate block.

Official guide: https://developers.openai.com/cookbook/examples/sora/sora2_prompting_guide

## Runway Gen-4

- Gen-4 video uses an input image plus text; the source image establishes appearance and composition.
- Use the text mainly for subject, camera, and scene motion.
- Use simple positive phrasing. Negative prompts are unsupported and may cause unpredictable or opposite results.
- Say `locked camera`, not `no camera movement`.
- Add one motion element per iteration.

Official guide: https://help.runwayml.com/hc/en-us/articles/39789879462419-Gen-4-Video-Prompting-Guide

## Google Veo

- Check the exact Veo model for reference images, first/last frames, audio, resolution, duration, and seed.
- Use image-to-video prompts mainly for motion.
- The Vertex AI surface can expose a separate `negativePrompt`; use a short list of unwanted content rather than instructional prose.
- Treat seed as repeatability within the same model and settings, not across model versions.

Official first/last-frame guide: https://docs.cloud.google.com/vertex-ai/generative-ai/docs/video/generate-videos-from-first-and-last-frames

## Google Imagen

Negative prompt support is model-version specific. Google documents it for older `imagen-3.0-*-001` models and excludes `imagen-3.0-generate-002` and later. Never infer support from provider name alone.

When supported, use a list such as `text, watermark, extra fingers`, not `do not show text`.

Official guide: https://docs.cloud.google.com/vertex-ai/generative-ai/docs/image/omit-content-using-a-negative-prompt

## Adobe Firefly

Start with subject plus location/context. Add action, composition, lighting, and texture only as needed. Give product and portrait references distinct roles for series consistency.

Official tutorial: https://www.adobe.com/learn/firefly/web/generate-realistic-photos

## Current OpenClaw runtime

Only use features exposed by the active tool. Provider documentation does not prove the wrapper passes a parameter. If video generation is unconfigured, keep video guidance dormant and do not claim it was tested.
