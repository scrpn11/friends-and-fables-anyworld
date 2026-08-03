# Character Profile Image Standards

Use this standard for player characters, NPCs, villagers, explorers, scholars, and other humanoid profiles.

## Required Output

- Square 1:1 image.
- Full body from head to feet unless a different crop is explicitly requested.
- One centered character with a readable silhouette.
- Restrained cold-neutral profile background, not a full scene.
- No text.

The accompanying character Markdown is the primary source of truth for identity, history, personality, appearance, inventory, and other character-specific details. The Markdown for the character's established class is a required secondary source of truth for class identity, training, combat role, magical practice, posture, equipment implications, and visual role cues. When a subclass is established and has its own Markdown, read that as an additional required source. Do not ask the user to repeat information already present in those files.

A supplied reference image is optional. Unless the user explicitly says otherwise, extract only the character's facial features, build, and body proportions from it. Treat those as abstract identity information, not as instructions to reproduce any visible design from the source image. The Markdown sources must independently determine hairstyle, colors, clothing, equipment, pose, expression, posture, class cues, occupation cues, and presentation. Never preserve a reference-image detail merely because the Markdown does not explicitly forbid it.

## Copy-Ready Prompt Template

Replace `[PATH OR NAME OF CHARACTER MARKDOWN]` and `[PATH OR NAME OF CLASS MARKDOWN]`. Replace `[PATH OR NAME OF SUBCLASS MARKDOWN]` only when an established subclass file exists; otherwise use `[NONE]`. The optional override line may be deleted when no change is needed. Attach a reference image only when one is available.

```text
Create a square 1:1 full-body character profile image for Kato using the accompanying character Markdown at [PATH OR NAME OF CHARACTER MARKDOWN] as the primary source of truth and the accompanying class Markdown at [PATH OR NAME OF CLASS MARKDOWN] as the required source of truth for class identity and visual role. Established subclass Markdown: [PATH OR NAME OF SUBCLASS MARKDOWN OR NONE].

Read every supplied Markdown file in full before generating. First create a private visual plan using only those Markdown sources. Use the character file for identity, age, build, face, hair, eyes, clothing explicitly established for that individual, inventory, social standing, personality, mannerisms, and personal history. Use the class file for training, battlefield or expedition role, magical practice, defensive habits, attack methods, mobility, durability, equipment implications, and the visual cues that make the character recognizably belong to that class. Use an established subclass file for its specific magical behavior and subclass identity. Do not ask for information already contained in the Markdown.

VISUAL PRIORITY
The character's current class is the dominant role identity of the profile image. Occupation and former livelihood are secondary background influences unless the character Markdown explicitly says the character is currently dressed or equipped for that work. A Vanguard who is also a fisherman must read first as a Vanguard: a disciplined front-line magical combatant with balanced readiness, practical combat access, controlled movement, and restrained magical reinforcement. Fishing experience may influence weathering, material choices, or minor personal equipment, but must not turn the portrait into a fisherman, dockworker, or fishing expedition image. Do not add nets, hooks, bait baskets, fishing spears, coils of fishing line, floats, or similar occupational props unless the character Markdown explicitly lists them as currently carried and they do not obscure the class identity.

If a reference image is supplied, ignore it during the visual-planning step. After the design is established from the Markdown sources, consult the reference only for three identity categories: facial features, build, and body proportions. Transfer only those three categories into the already-planned Kato design. Do not use the reference to choose or influence hairstyle, hair color, eye color, skin rendering, clothing, accessories, equipment, held objects, pose, expression, posture, silhouette, background, lighting, camera angle, composition, texture, realism level, art style, apparent profession, apparent class, social status, or age presentation.

The final outfit, equipment, stance, expression, silhouette, and magical presentation must be traceable to the Markdown sources rather than the reference. If the finished design shares any unestablished garment, accessory, held item, pose, or silhouette arrangement with the reference, reject that design and compose a different one before generating. The final result must look like a newly designed Kato character who shares the same face and body type, not like the reference character redrawn in another style.

Optional override for this image only: [NONE]

COMPOSITION
Show the complete figure from head to feet, including footwear, with no cropping of important anatomy or equipment. Center the character in a natural, readable full-body pose that reflects the personality and mannerisms in the character Markdown and the role and training in the class Markdown. Use normal perspective and grounded anime proportions. Keep hands visible and anatomically clear where practical. Use a restrained cold-neutral profile background such as desaturated gray-beige, cold parchment, muted stone, charcoal haze, or a subtle fog-dark gradient. Add only a faint floor shadow, low haze, or soft atmospheric grounding. Do not add a full landscape, room, unrelated props, or other characters.

Choose a fresh pose independently from the reference. Prefer a role-revealing stance supported by the class Markdown. Do not duplicate which hand is raised, which hand holds an item, the direction of the head, the placement of the feet, the bend of the elbows, the angle of the torso, or the arrangement of clothing and equipment from the reference.

MARKDOWN-DRIVEN DESIGN
Clothing and equipment must come only from the character, class, and established subclass Markdown. The class Markdown determines the dominant visual archetype. The character Markdown personalizes that archetype through age, wealth, culture, occupation history, established clothing, and inventory. When those sources create tension, preserve explicit character details but compose them so the class remains immediately readable.

Do not invent class equipment that the class Markdown does not support. Conversely, do not overemphasize miscellaneous inventory merely because it appears in the character sheet. Small tools, keepsakes, notebooks, tackle, or occupational supplies should remain holstered, pocketed, or visually secondary unless they are central to the current class role. A character profile is not an inventory display.

Do not add any object merely because it appears in the reference. In particular, do not copy lanterns, coats, shoulder straps, satchels, belts, jewelry, watches, armor, weapons, or other props unless that exact category is supported by the Markdown. Do not transform an unsupported reference prop into a superficially medieval equivalent.

ART DIRECTION
Redraw the subject entirely in polished, clearly 2D dark-anime fantasy character art. Use clean confident anime linework, controlled cel shading, restrained painterly detail, readable silhouettes, and attractive stylized anime facial construction. The image should feel cold, ancient, isolated, mysterious, melancholic, and slightly dreamlike, matching Kato's northern coastal world. Use expressive anime eyes, simplified but appealing nose and mouth shapes, clean facial planes, stylized brows, and sharp readable hair forms. Adult age, fatigue, scars, weathering, strong builds, or hardship must remain clearly visible but translated into anime design rather than realistic portrait rendering.

The reference image must not influence the rendering style. Do not retain photorealistic skin, cinematic realism, realistic fabric texture, photographic lighting, shallow depth of field, realistic environment rendering, or the reference's color grading. Use Kato's restrained palette of charcoal, slate, cold blue, weathered brown, moss green, iron gray, fog white, muted teal, and subdued amber accents. Clothing must reflect the exact wealth, age, circumstances, and culture established in the character Markdown while visually serving the role established in the class Markdown. Materials must read clearly as wool, linen, leather, fur, wood, iron, bone, or other established substances. Magic effects must follow the class and subclass Markdown and remain subtle and secondary unless those sources make magic visually dominant.

IDENTITY FIDELITY
Preserve all established written details exactly. When a reference image is supplied, preserve only its facial features, build, and body proportions by default. Translate those identity traits into Kato's anime facial language rather than reproducing the reference's realistic rendering. Do not use the reference as authority for any detail that the Markdown defines or leaves open. Unspecified visual details must be inferred from the character's class, subclass, setting, culture, and personal circumstances, never borrowed from the reference.

Never allow the reference image to determine apparent age, skin tone, hairstyle, eye color, scars, glasses, clothing, equipment, posture, expression, occupation cues, class cues, social status, or any other written or inferred trait. Do not make the character more glamorous, sexualized, muscular, youthful, mature, thin, heavy, heroic, ornate, wealthy, or battle-ready than described.

FINAL REJECTION CHECK
Before generating, confirm that the class is recognizable before the occupation or former livelihood. Reject and redesign the image if the dominant impression is fisherman, laborer, merchant, scholar, wanderer, or another occupation when the character has an established adventuring class that should define the portrait. Also reject it if any of the following remain substantially similar to the reference without explicit Markdown support: outfit silhouette, coat length, torn fabric placement, cross-body straps, belt layout, satchel placement, held object, hand positions, head direction, stance, camera angle, lighting pattern, background layout, or overall character archetype. Facial resemblance and body type are the only intended similarities.

NEGATIVE REQUIREMENTS
No text, captions, labels, logos, borders, UI, signatures, watermarks, fake letters, photorealism, semi-realistic western fantasy, western comic style, chibi proportions, 3D rendering, generic AI-fantasy face, modern clothing, sci-fi props, random armor, unrelated weapons, unsupported lantern, unsupported satchel, unsupported cross-body harness, unsupported long ragged coat, occupation-dominant fisherman design when the class is Vanguard, fishing expedition gear display, excessive inventory display, excessive jewelry, random runes, neon glow, excessive magic, dramatic action scene, extra limbs, distorted hands, mismatched eyes, cropped feet, cropped head, obscured face, busy scenery, copied reference-image outfit, copied reference-image hairstyle, copied reference-image accessories, copied reference-image held object, copied reference-image pose, copied reference-image posture, copied reference-image silhouette, copied reference-image composition, copied reference-image camera angle, copied reference-image lighting, copied reference-image color grading, copied reference-image texture, copied reference-image background, copied reference-image archetype, photorealistic facial rendering, or any detail that contradicts the Markdown sources or this prompt.
```