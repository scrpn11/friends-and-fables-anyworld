# Race Profile Image Standards

Use this standard for race overview images representing the shared physical identity of a playable or non-playable people rather than a specific named character.

## Required Output

- Square 1:1 image.
- One representative adult shown from head to feet.
- Clear anatomy, proportions, scale, and defining racial traits.
- Restrained cold-neutral profile background, not a full scene.
- No text.

The accompanying race Markdown is the source of truth. Read its name and complete Description before generating. Preserve every established anatomical, physical, cultural, magical, and environmental trait. Infer only minor visual details required to produce a complete image. Do not ask the user to repeat information already present in the Markdown.

A race image represents common defining traits, not every possible member of the race. Do not portray unusual mutations, exceptional beauty, extreme age, rare equipment, elite status, or individualizing marks unless the race Markdown establishes them as broadly representative. Where the entry allows wide variation, choose a grounded neutral example without implying that one skin tone, sex, hairstyle, occupation, or social role defines the entire race.

## Copy-Ready Prompt Template

Replace only `[PATH OR NAME OF RACE MARKDOWN]`. The optional override line may be deleted when no change is needed.

```text
Create a square 1:1 full-body race profile image for Kato using the accompanying race Markdown at [PATH OR NAME OF RACE MARKDOWN] as the complete source of truth.

Read the entire Markdown before generating. Use the race's established anatomy, body proportions, size, facial structure, skin, hair, eyes, ears, limbs, natural markings, age presentation, magical traits, limitations, cultural cues, environmental adaptations, and all other relevant details exactly as written. Infer only minor visual details needed to complete the image and never contradict the entry. Do not ask for information already contained in the Markdown.

Optional override for this image only: [NONE]

COMPOSITION
Show one representative adult from head to feet with all important anatomy visible and enough empty space around the figure to avoid cropping hair, ears, horns, tails, wings, hands, feet, or other defining features. Use a neutral, readable standing pose and normal perspective. Keep the subject centered and dominant in frame. Use a restrained cold-neutral background such as desaturated gray-beige, cold parchment, muted stone, charcoal haze, pale fog, or a subtle fog-dark gradient. Add only a faint floor shadow, low haze, or soft atmospheric grounding. Do not add a full landscape, interior, unrelated props, other people, or a narrative action scene.

REPRESENTATIVE DESIGN
Depict a grounded, broadly representative member of the race rather than a named individual, champion, noble, villain, or adventurer. Emphasize shared anatomical and physical traits that distinguish the race. Do not invent a universal costume, profession, weapon, hairstyle, personality, or social rank. When clothing is necessary, use simple practical Kato clothing appropriate to the race's established culture, environment, and material access without making the outfit the focal point. Where the race permits broad humanlike variation, choose one plausible example while avoiding visual claims that all members look identical.

ART DIRECTION
Use polished, clearly 2D dark-anime fantasy profile art with clean confident anime linework, controlled cel shading, restrained painterly detail, readable silhouettes, and cinematic but clear lighting. The image should feel cold, ancient, isolated, mysterious, melancholic, and slightly dreamlike, matching Kato's northern world. Use attractive stylized facial construction while keeping all established nonhuman anatomy physically credible and immediately readable.

Use Kato's restrained northern palette of charcoal, slate, cold blue, weathered brown, moss green, iron gray, fog white, muted teal, and subdued amber accents. Materials must read clearly as wool, linen, leather, fur, wood, iron, bone, scales, hide, feathers, or other substances established in the Markdown. Any innate magic should be subtle and secondary unless the race description makes it a constant defining visual trait.

RACE FIDELITY
Preserve every established written trait. Do not change body size, proportions, limb structure, facial construction, skin or covering, natural markings, sensory organs, adaptations, lifespan cues, or magical characteristics. Do not make the representative more glamorous, sexualized, muscular, youthful, mature, monstrous, heroic, ornate, wealthy, battle-ready, or culturally specific than the Markdown supports. Do not add generic elf ears, horns, tails, wings, fangs, claws, glowing eyes, runes, armor, jewelry, or weapons unless established.

NEGATIVE REQUIREMENTS
No text, captions, labels, logos, borders, UI, signatures, watermarks, fake letters, species lineup, multiple figures, named-character portrait, dramatic pose, action scene, full environment, photorealism, semi-realistic western fantasy, western comic style, chibi proportions, mascot-like design, glossy 3D rendering, generic AI-fantasy face, modern clothing, sci-fi props, random armor, unrelated weapons, excessive jewelry, random runes, neon glow, excessive magic, obscured anatomy, extra limbs, distorted hands, mismatched eyes, cropped head, cropped feet, cropped defining anatomy, or any detail that contradicts the Markdown.
```
