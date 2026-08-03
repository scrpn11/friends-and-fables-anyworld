# Area and POI Cover Image Standards

Use this standard for settlements, buildings, roads, shores, forests, ruins, vaults, interiors, and other environmental assets.

## Required Output

- Square 1:1 image.
- Full environmental scene rather than a studio background.
- Accurate layout, terrain, architecture, materials, weather, lighting, and scale.
- No text or map labels.

The accompanying Area or POI Markdown is the source of truth. Read its name, Area, Type, Description, Appearance, and all established spatial, environmental, historical, and situational details before generating. Do not ask the user to repeat information already present there.

Use a wide shot for settlements, coastlines, landscapes, forests, and large ruins. Use a medium-wide shot for buildings, interiors, gates, caves, docks, vault chambers, and encounter locations. Infer the appropriate camera distance from the entry unless an override is provided.

## Copy-Ready Prompt Template

Replace only `[PATH OR NAME OF AREA OR POI MARKDOWN]`. The optional override line may be deleted when no change is needed.

```text
Create a square 1:1 environmental cover image for Kato using the accompanying Area or POI Markdown at [PATH OR NAME OF AREA OR POI MARKDOWN] as the complete source of truth.

Read the entire Markdown before generating. Use the location's established name, Area, Type, Description, Appearance, spatial layout, landmarks, architecture, materials, terrain, elevation, vegetation, roads, paths, water, walls, boundaries, weather, lighting, population cues, condition, dangers, and all other relevant details exactly as written. Infer only minor visual details required to create a coherent scene and never contradict the entry. Do not ask for information already contained in the Markdown.

Optional override for this image only: [NONE]

COMPOSITION
Show the actual location as a coherent environmental scene, not a symbolic illustration or generic fantasy backdrop. Choose a wide shot for a settlement, coastline, landscape, forest, or large ruin; choose a medium-wide shot for a building, interior, gate, cave, dock, vault chamber, or encounter location. Make the important landmarks, approach, terrain, elevation, architecture, boundaries, and usable spaces immediately understandable. Preserve established spatial relationships and include enough surrounding context to communicate scale. Keep one clear visual focal point while allowing the location itself to remain the subject. Small unnamed figures, animals, boats, carts, lights, smoke, or silhouettes may appear only as scale and life cues. Do not feature a named character or resolved plot event unless the Markdown or optional override specifically requires it.

ART DIRECTION
Use polished, clearly 2D dark-anime environmental art with clean confident linework, controlled cel shading, restrained painterly detail, readable architecture and terrain, and cinematic lighting. The place must feel unmistakably part of Kato: cold, ancient, isolated, mysterious, dangerous, melancholic, and slightly dreamlike. Use a restrained northern palette of charcoal, slate, cold blue, weathered brown, moss green, iron gray, fog white, muted teal, and subdued amber lantern or firelight.

Use cold overcast daylight, blue twilight, moonlight, dim dawn, lantern light, firelight, pale fog-light, or another restrained source appropriate to the Markdown. Use subtle mist, drifting fog, wet surfaces, distant silhouettes, soft bloom, empty negative space, or unusual light falloff to create unease and dreamlike mystery without hiding the layout. Show weathered timber, old stone, practical construction, lonely coastlines, dense forests, worn paths, and restrained traces of forgotten civilization only where established.

LOCATION FIDELITY
Preserve every established written detail and any supplied reference-image layout. Do not change coastline, fog boundary, elevation, building placement, roads, paths, walls, docks, bridges, ruins, vegetation, materials, weather, hazards, or important landmarks unless the optional override explicitly requires it. Do not turn a specific location into a generic Nordic village, generic fantasy forest, generic dungeon, or unrelated ruin. Communicate danger through composition, damage, tracks, scale, silence, lighting, unnatural absence, or environmental distortion rather than adding random monsters.

NEGATIVE REQUIREMENTS
No text, captions, labels, map markers, banners, logos, borders, UI, signatures, watermarks, legible signage, fake letters, photorealism, western fantasy realism, chibi style, 3D rendering, generic fantasy castle, excessive gothic ornament, random statues, random monsters, named-character focus, active battle scene, resolved story event, modern objects, sci-fi elements, neon magic, excessive glow, muddy darkness, hidden landmarks, incorrect architecture, incorrect terrain, or any detail that contradicts the Markdown.
```