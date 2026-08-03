# Image Generation Standards

These files define Kato's repository-only image standards. They should not be imported into Friends & Fables as lore.

Each category file contains a detailed copy-ready prompt template that uses the accompanying subject Markdown as the complete source of truth. In normal use, replace only the Markdown path or filename. Add an optional one-line override only when this specific image should intentionally differ from the written entry.

Do not manually re-enter Description, Appearance, anatomy, clothing, equipment, materials, layout, lighting, or other details that already exist in the subject Markdown. The image-generation prompt must instruct the model to read the complete entry first and preserve it exactly.

## Standards

- [Global Standards](global-standards.md)
- [Character Profiles](character-profiles.md)
- [Race Profiles](race-profile-images.md)
- [Class Profiles](class-profile-images.md)
- [Monster Profiles](monster-profile-images.md)
- [Item Images](item-images.md)
- [Area and POI Covers](area-and-poi-cover-images.md)
- [Prompt Review Checklist](prompt-review-checklist.md)

## Priority

When requirements conflict, follow this order:

1. The user's explicit override for the current image.
2. The subject's accompanying Markdown entry.
3. An established reference image, interpreted according to the Markdown.
4. The relevant category prompt template.
5. The global standards.

Do not silently change established identity, anatomy, scale, object shape, location layout, materials, or magical behavior.
