# Monster Profile Image Standards

Use this standard for fog creatures, beasts, vault creatures, constructs, spirits, hostile people, and other stat-block profile images.

## Required Output

- Square 1:1 image.
- Full creature visible whenever possible.
- Clear anatomy, scale, movement, attack cues, and supernatural nature.
- Restrained atmospheric background rather than a full battle scene.
- No text.

The accompanying monster Markdown is the source of truth. Read its name, Description, Appearance, size, type, movement, actions, statistics, defenses, and all established traits before generating. Do not ask the user to repeat information already present there.

## Copy-Ready Prompt Template

Replace only `[PATH OR NAME OF MONSTER MARKDOWN]`. The optional override line may be deleted when no change is needed.

```text
Create a square 1:1 monster profile image for Kato using the accompanying monster Markdown at [PATH OR NAME OF MONSTER MARKDOWN] as the complete source of truth.

Read the entire Markdown before generating. Use the creature's established name, Description, Appearance, exact size, type, anatomy, proportions, posture, movement, hide or material, attacks, defenses, equipment, wounds, supernatural behavior, and all other relevant fields exactly as written. Infer only minor visual details required to complete the image and never contradict the entry. Do not ask for information already contained in the Markdown.

Optional override for this image only: [NONE]

COMPOSITION
Show the complete creature with enough empty space around horns, limbs, claws, tails, wings, weapons, and supernatural effects so nothing important is cropped. Use a clear three-quarter, frontal, or side view that makes anatomy, scale, likely movement, and attack style immediately understandable. Keep the creature dominant in frame. Use only a restrained atmospheric background such as cold parchment, desaturated stone, charcoal haze, pale fog, dim forest silhouettes, or a subtle vault-dark gradient. Include a simple environmental or human scale cue only when necessary to communicate the established size, but do not turn the image into a scene or resolved battle.

ART DIRECTION
Use polished, clearly 2D dark-anime bestiary art with clean confident linework, controlled cel shading, restrained painterly detail, strong readable silhouettes, and cinematic lighting. The creature should feel dangerous, ancient, mysterious, physically credible, and slightly dreamlike. Use restrained horror rather than gore. Fog creatures should feel ferocious and powerful enough to kill ordinary travelers, but their bodies must remain fully readable instead of becoming shapeless darkness.

Use Kato's restrained northern palette: charcoal, slate, cold blue, weathered brown, moss green, iron gray, fog white, muted teal, subdued amber, and occasional pale unnatural highlights. Use subtle fog, haze, soft bloom, drifting particles, or unusual light falloff only where they accurately express the creature's established supernatural behavior without hiding anatomy.

CREATURE FIDELITY
Preserve every established written detail and any supplied reference-image anatomy. Do not change exact size, proportions, posture, number of limbs, hide, fur, scales, wounds, weapons, armor, movement, attacks, defenses, or magical behavior unless the optional override explicitly requires it. Do not add generic demonic horns, wings, skulls, armor, glowing runes, mouths, eyes, or limbs unless established.

NEGATIVE REQUIREMENTS
No text, captions, labels, logos, borders, UI, signatures, watermarks, fake letters, photorealistic gore, western fantasy realism, chibi design, mascot-like cuteness, 3D rendering, generic dragon anatomy, random demon features, shapeless darkness, excessive glow, hidden anatomy, cluttered scenery, unrelated victims, active battle scene, extra limbs, duplicated heads, distorted anatomy, cropped claws, cropped tail, cropped wings, modern objects, sci-fi elements, or any detail that contradicts the Markdown.
```