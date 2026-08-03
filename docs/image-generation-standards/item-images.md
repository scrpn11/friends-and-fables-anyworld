# Item Image Standards

Use this standard for weapons, armor, tools, relics, Channeler devices, consumables, materials, and other inventory assets.

## Required Output

- Square 1:1 image.
- One centered item, fully visible.
- Restrained neutral background.
- Clear silhouette, materials, condition, construction, and magical behavior.
- No text.

The accompanying item Markdown is the source of truth. Read its name, Description, Appearance, category, rarity, magical status, weight, cost, equip slot, mechanics, and all established details before generating. Do not ask the user to repeat information already present there.

## Copy-Ready Prompt Template

Replace only `[PATH OR NAME OF ITEM MARKDOWN]`. The optional override line may be deleted when no change is needed.

```text
Create a square 1:1 item profile image for Kato using the accompanying item Markdown at [PATH OR NAME OF ITEM MARKDOWN] as the complete source of truth.

Read the entire Markdown before generating. Use the item's established name, Description, Appearance, exact object type, scale, silhouette, dimensions, materials, construction, moving parts, condition, wear, craftsmanship, origin, ornamentation, rarity, magical behavior, and all other relevant fields exactly as written. Infer only minor visual details required to render a complete object and never contradict the entry. Do not ask for information already contained in the Markdown.

Optional override for this image only: [NONE]

COMPOSITION
Show one complete item centered and fully visible against a restrained cold-neutral profile background. Use a square 1:1 frame. Angle long weapons, tools, or staffs diagonally only when needed to fit without cropping. Keep the object large enough to read clearly at small interface size. Use a subtle grounding shadow, faint cold haze, or restrained reflected light. Do not show a character holding or using the item unless the optional override explicitly requests a use scene. Do not add unrelated props, display stands, cards, borders, labels, or scenery.

ART DIRECTION
Use polished, clearly 2D dark-anime fantasy object art with clean confident edges, controlled cel shading, restrained painterly material detail, readable construction, and cinematic but practical lighting. The item should belong unmistakably to Kato's cold, ancient, isolated, mysterious, melancholic, and slightly dreamlike world. Use a restrained northern palette of charcoal, slate, cold blue, weathered brown, moss green, iron gray, fog white, muted teal, and subdued amber accents.

Make metal, wood, leather, wool, linen, bone, stone, glass, crystal, ceramic, and other established materials visually distinct and physically believable. Common equipment should look practical, maintained, and used. Rare relics may show unusual construction, superior materials, traces of lost craftsmanship, or subtle magical behavior, but must remain mechanically believable. Channeler devices must look purpose-built, engineered, and usable rather than like generic glowing artifacts.

OBJECT FIDELITY
Preserve every established written detail and any supplied reference-image shape. Do not change the exact object type, dimensions, silhouette, curvature, construction, materials, damage, wear, moving parts, ornamentation, or magical behavior unless the optional override explicitly requires it. Do not substitute a similar weapon or tool. Do not invent gems, chains, skulls, runes, gold trim, blades, spikes, handles, or magical effects unless established.

NEGATIVE REQUIREMENTS
No text, captions, labels, logos, borders, UI, signatures, watermarks, fake inscriptions, legible runes, character hands, active use scene, photorealism, western fantasy realism, chibi style, 3D rendering, generic treasure-card presentation, random gems, excessive gold, skull decoration, chains, excessive glow, neon magic, unrelated props, cropped edges, incorrect silhouette, modern manufacturing, sci-fi styling, or any detail that contradicts the Markdown.
```