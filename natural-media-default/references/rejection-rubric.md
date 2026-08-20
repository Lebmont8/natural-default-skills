# Rejection rubric

Score each applicable category:

- `0`: failure;
- `1`: visible defect;
- `2`: clean or acceptable for the brief.

## Still image

1. Brief adherence and first visual priority.
2. Anatomy and identity.
3. Physics, perspective, and object geometry.
4. Light, shadows, and reflections.
5. Materials, skin, and surfaces.
6. Background detail and absence of random clutter.
7. Required text, logos, and branding.
8. Composition, hierarchy, and readability.

Pass at `13/16` or higher with no zero in brief, identity, physics, or required text.

## Video additions

9. Subject consistency.
10. Background consistency.
11. Motion smoothness and physical plausibility.
12. Temporal stability: flicker, texture crawl, and exposure pumping.

Pass at `19/24` or higher with no zero in identity, physics, subject consistency, background consistency, or temporal stability.

These temporal categories align with VBench dimensions such as subject consistency, background consistency, motion smoothness, imaging quality, and aesthetic quality.

VBench: https://openaccess.thecvf.com/content/CVPR2024/html/Huang_VBench_Comprehensive_Benchmark_Suite_for_Video_Generative_Models_CVPR_2024_paper.html

## Hard reject

Reject regardless of score when the output has any material:

- wrong identity or product;
- broken or extra limbs;
- incorrect required copy or logo;
- dominant impossible geometry, shadow, or reflection;
- face/body morphing;
- object spawning or disappearance;
- obvious temporal flicker;
- failure to communicate the requested concept.

Random grain, pores, noise, crooked framing, or synthetic "imperfection" do not increase the score unless motivated by the scene.
