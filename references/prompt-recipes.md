# Prompt recipes

Use these recipes when compiling or rendering. Fill only relevant fields and keep mandatory user inputs unchanged.

## Production prompt schema

```text
Use case: ads-marketing
Asset type: vertical campaign poster
Primary request: <subject, product, event, or campaign idea>
Scene/backdrop: <urban canyon, courtyard, street, or subject-relevant radial environment>
Subject: <hero identity, wardrobe/material, pose or product orientation>
Foreground thrust: <one meaningful element projected toward the lens>
Style/medium: premium stylized 3D CGI, designer-toy or product-campaign finish
Composition/framing: <ratio>; ground-level 14–16 mm fisheye; three depth bands; central sky/focal opening; title-safe lower zone
Lighting/mood: bright central daylight; darker perimeter; warm practical lights; rim light; <campaign mood>
Color palette: <deep primary>, <high-energy accent>, charcoal, warm white, optional amber
Materials/textures: <fur/skin/fabric/rubber/metal/concrete/glass>; restrained wear and airborne particles
Graphic layer: <T1/T2/T3/T4 hierarchy, brush strokes, labels, reticles>
Text (verbatim): "<only short mandatory copy>"
Constraints: original design; readable hero silhouette; preserve logo-safe and title-safe zones; no watermark
Avoid: malformed anatomy; duplicated limbs; random text; unrelated logos; uniform clutter; flat lighting
```

## Character campaign recipe

```text
Use case: ads-marketing
Asset type: 3:4 vertical youth-culture campaign poster
Primary request: an original <character type> mascot launching into an energetic urban scene for <campaign idea>
Scene/backdrop: dense contemporary city courtyard; tall buildings curve inward around a bright oval of blue sky and clouds; warm glowing windows around the darker perimeter
Subject: original expressive 3D mascot wearing <wardrobe>; face remains clearly readable near the central axis
Foreground thrust: one <hand, paw, shoe, accessory, or subject-specific element> reaches dramatically toward the camera and breaks the lower frame
Style/medium: premium stylized 3D CGI, designer-toy proportions, cinematic streetwear advertising, tactile realistic materials
Composition/framing: extreme ground-level 14 mm fisheye; strong forced perspective; oversized lower-corner foreground; sharp midground hero; radial architectural background; title-safe lower third
Lighting/mood: high-energy optimistic daylight, volumetric sun from the center, warm practical lights, crisp rim light, dark vignette at the corners
Color palette: saturated cobalt blue, vivid golden yellow, charcoal black, warm white, small amber highlights
Materials/textures: detailed fibers, fabric weave, rubber tread, worn concrete, glass reflections; localized dust and gravel burst along one diagonal
Graphic layer: distressed white condensed title block at the bottom; one yellow brush accent overlapping the title; blue/yellow dry-brush corner strokes; sparse technical callouts and thin rules near the edges
Constraints: original character and graphics; keep face unobstructed; leave brand and long-copy areas blank for post-production; no watermark
Avoid: third-party logos, copied characters, random letters, extra fingers, duplicated limbs, broken joints, flat front view, symmetrical static pose, excessive particles
```

## Product campaign recipe

```text
Use case: ads-marketing
Asset type: 3:4 vertical product key art
Primary request: a heroic campaign image for <product and benefit>
Scene/backdrop: subject-relevant urban environment bending around a clear central opening; architecture and signage provide scale without competing with the product
Subject: <product> centered slightly below the optical center, accurate silhouette and functional details
Foreground thrust: <product feature> projects toward the lens and becomes the near-band anchor
Style/medium: premium product CGI mixed with kinetic street-campaign art direction
Composition/framing: ground-level 16 mm fisheye; three clear depth bands; diagonal motion; uncluttered logo zone and lower title zone
Lighting/mood: bright central key light, controlled reflections, warm edge practicals, confident and youthful
Color palette: <brand deep primary>, <brand accent>, charcoal, warm white
Materials/textures: physically believable <materials>; subtle wear only where appropriate; dust or particles used sparingly
Graphic layer: oversized condensed campaign title, one gestural brush accent, small product annotations, thin callout rules
Text (verbatim): "<short campaign title>"
Constraints: accurate product geometry; title exactly once; no unrelated branding; no watermark
Avoid: warped product, fake controls, illegible label, random copy, excessive grunge, muddy reflections
```

## Reference-analysis output template

```text
Visual signature: <one concise paragraph>
Palette: <functional color roles and approximate values>
Lens and composition: <camera, depth bands, focal path, copy zones>
Rendering: <medium, materials, lighting, focus>
Graphic layer: <type hierarchy, marks, labels, texture>
Reusable grammar: <elements safe to transfer>
Do not copy: <logos, watermarks, proprietary characters, exact slogans>
```

## Negative prompt

Use only the items relevant to the generator:

```text
malformed hands, extra fingers, fused fingers, duplicated limbs, broken joints, distorted face, warped product geometry, flat eye-level camera, weak perspective, empty background, muddy colors, uniform sharpness, overfilled particles, illegible random text, repeated words, unrelated logos, trademarked branding, watermark, creator handle, border
```

## Copy plan

Keep copy planning separate from the image prompt when accuracy matters:

```text
T1 — campaign title: <2–5 words>; bottom 25–32%; condensed uppercase or bold Chinese display face
T1 accent — action word: <1–3 words>; yellow brush style; overlaps T1 without covering the hero
T2 — promise: <one short sentence>; upper-left or beside the hero
T3 — facts/CTA: <date, place, feature, URL>; compact lower or upper edge module
T4 — micro-labels: <2–4 short labels>; outer frame only
Brand zone: <top-left or top-right>; insert supplied logo in post-production
```

## Controlled variants

When the user asks for options, vary one axis at a time:

- **A — Heroic:** cleaner center, fewer labels, stronger product or character silhouette.
- **B — Street:** more brush texture and dust, deeper shadows, sharper diagonal energy.
- **C — Editorial:** more typography, flatter particle field, quieter foreground action.

Keep the palette, hero identity, copy, and brand invariants constant unless the user asks to compare them.
