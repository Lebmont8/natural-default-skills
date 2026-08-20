# Image workflows

## Text-to-image

Structure the prompt in this order:

`purpose → scene → primary subject and action → composition → light and color → materials and motivated detail → requested style → exact constraints`

Start with the creative idea and first visual priority. Add only details that the viewer could observe and that support the brief.

Describe surfaces concretely when relevant: matte glaze, brushed steel, used wood, fabric creased by the pose, or skin with natural variation. Do not add arbitrary dirt, grain, pores, scratches, or asymmetry as an authenticity filter.

For advertising, include audience, cultural context where relevant, campaign concept, composition, product truth, exact copy, and reserved layout space. Advertising may be polished; the goal is considered art direction rather than generic luxury gloss.

For photographic language, describe the effect: eye-level medium portrait, broad depth of field, diffuse window light, or restrained handheld framing. Treat focal length and aperture as approximate art direction.

## Image edit

Structure the instruction as:

`preserve exactly → local target → one requested change → required agreement with light, perspective, geometry, and material`

Use a local edit when fixing one hand, label, object, background region, product color, or small lighting mismatch. Preserve identity, pose, wardrobe, composition, product shape, and unaffected regions explicitly.

Use a full regenerate when the concept, layout, global perspective, or overall subject construction is wrong.

## References

Assign every input image one role:

- identity reference;
- product reference;
- wardrobe reference;
- location reference;
- composition reference;
- palette reference;
- style reference.

State what must be preserved from each reference. Avoid ambiguous phrases such as "make it like all these images."

## Text and logos

Generate short exact text only when it is central to the still image. Quote the copy and define placement, hierarchy, contrast, and surrounding negative space. Verify every required character after generation.

Prefer post-production for long body copy, legal text, repeated campaign typography, and any wording that must be guaranteed.

## Focused correction

Before retrying, write a one-line diagnosis such as:

- "The product shape is correct, but the logo copy is wrong; edit only the label."
- "The face matches, but the left hand has broken anatomy; edit only the hand while preserving pose and light."
- "The image is technically clean but misses the campaign concept; regenerate from a revised brief."
