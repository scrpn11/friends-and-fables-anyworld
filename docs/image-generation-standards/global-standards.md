# Kato Image Generation Standards

These standards apply to every Kato image unless a category-specific prompt or current user instruction overrides them.

## Fixed Art Direction

Use polished, clearly 2D dark-anime fantasy art with clean confident linework, controlled cel shading, restrained painterly detail, readable silhouettes, and cinematic lighting. Kato should feel cold, ancient, isolated, mysterious, dangerous, and slightly dreamlike. The atmosphere may be eerie or melancholic, but essential anatomy, objects, and landmarks must remain clear.

Favor charcoal, slate, cold blue, weathered brown, moss green, iron gray, fog white, muted teal, and subdued amber light. Reserve brighter colors for meaningful magic, fire, lanterns, rare materials, or focal accents. Use subtle haze, drifting fog, soft bloom, distant silhouettes, and unusual light falloff to create dreamlike unease without making the image abstract.

Default to a square 1:1 composition suitable for Friends & Fables. Use no text, captions, logos, borders, interface elements, signatures, or watermarks. Keep the focal subject readable at small size.

Written descriptions always take priority. Reference images are secondary visual evidence and must be interpreted according to the relevant category standard. A reference image must never override Kato's fixed art direction, the subject Markdown, composition requirements, or negative requirements. For character images, preserve only build, body proportions, and facial features by default; do not preserve the reference's style, rendering, lighting, background, pose, clothing, equipment, hairstyle, colors, accessories, or scene unless the user explicitly requests a specific exception.

Avoid photorealism, semi-realistic western fantasy, western comic rendering, chibi proportions, glossy 3D rendering, generic AI-fantasy faces, neon overload, random runes, decorative clutter, excessive glow, muddy shadows, modern objects, sci-fi props, fake lettering, extra limbs, distorted hands, mismatched eyes, cropped important anatomy, and changes that contradict established Kato lore.

## Universal Prompt Block

Include this fixed block in every image prompt unless the category template already includes it:

```text
Create a square 1:1 image for the Kato dark-fantasy setting. Redraw the subject from scratch in Kato's fixed visual language: polished, clearly 2D dark-anime fantasy art with clean confident anime linework, controlled cel shading, restrained painterly detail, readable silhouettes, and cinematic lighting. The final image must not preserve the rendering style, realism level, lighting design, background, composition, pose, costume design, or decorative language of any supplied reference image unless an explicit override requires one of those specific details.

The world should feel cold, ancient, isolated, mysterious, dangerous, melancholic, and slightly dreamlike. Use a restrained northern palette of charcoal, slate, cold blue, weathered brown, moss green, iron gray, fog white, muted teal, and subdued amber light. Use subtle haze, drifting fog, soft bloom, distant shapes, and unusual light falloff only where they improve atmosphere without hiding important details.

Preserve all established written details. Interpret any reference image only according to the relevant category standard. Never let a reference image override the subject Markdown, Kato's art direction, required composition, or negative requirements.

No text, captions, labels, logos, borders, UI, signatures, watermarks, fake letters, modern objects, sci-fi elements, random runes, unrelated weapons, extra limbs, distorted hands, mismatched eyes, cropped important details, excessive glow, generic medieval-fantasy decoration, photorealism, western fantasy realism, chibi style, or 3D-render appearance.
```