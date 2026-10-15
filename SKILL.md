---
name: street-lab-poster
description: Create or analyze kinetic urban campaign posters built from extreme fisheye perspective, premium 3D character or product rendering, bold two-color branding, distressed brush graphics, and editorial information overlays. Use for poster concepts, image-generation prompts, reference-image style extraction, or rendered vertical campaign key art. Do not use for quiet minimal posters, flat corporate layouts, or faithful reproduction of third-party logos and watermarks.
---

# Street Lab Poster

Turn a subject, product, mascot, event, or reference image into an original high-energy urban campaign poster. Preserve the user's message and brand inputs while applying the visual system; do not force unrelated story elements into a detailed brief.

## Choose the task

- **Analyze:** Extract palette, depth, lens, composition, rendering, typography, texture, and motion from supplied references. Distinguish reusable visual grammar from protected logos, copy, characters, and watermarks.
- **Compile:** Return a production-ready image prompt plus a separate copy/layout plan.
- **Render:** Compile first, then use the available image-generation tool. Treat supplied images as style references unless the user explicitly asks to edit them.
- **Adapt:** Keep the style contract but replace its palette, subject, environment, copy, or aspect ratio with the user's requirements.

Read [references/style-system.md](references/style-system.md) when analyzing a reference or making composition decisions. Read [references/prompt-recipes.md](references/prompt-recipes.md) when compiling or rendering a prompt.

## Default direction

Use these defaults only when the user has not specified an alternative:

- 3:4 vertical campaign poster.
- One hero subject in a dense urban courtyard or street canyon.
- Extreme ground-level 14–16 mm fisheye view.
- The face or primary product remains near the visual center; one meaningful element projects toward the lens.
- Premium stylized 3D CGI with tactile, believable materials.
- Cobalt blue, vivid yellow, charcoal, white, and small warm-orange highlights.
- Bright central sky, darker perimeter, warm windows, rim light, airborne debris, and controlled edge blur.
- Bottom-heavy headline block, brush lettering or paint stroke, and sparse technical micro-labels at the edges.

Do not blindly add a hand and sneaker. For a product, vehicle, animal, or abstract object, choose a subject-specific foreground element that can create the same forced-perspective thrust.

## Compile the design

1. Identify the poster's subject, audience, message, mandatory copy, brand palette, output ratio, and whether rendering is requested. Ask only when a missing choice would materially change the result.
2. Select one clear foreground action, one hero focal point, and one architectural or environmental frame. Maintain a readable silhouette despite the extreme perspective.
3. Build three depth bands: oversized foreground thrust, sharp midground hero, and radial background frame/open sky.
4. Assign the copy hierarchy separately from the scene: T1 campaign title, T2 subtitle or promise, T3 utility details, T4 micro-labels. Do not let decorative text cover the face or product.
5. Normalize the result into the prompt schema in `prompt-recipes.md`. Preserve user-provided specificity; add only details that strengthen this visual system.

## Text and brands

- Quote mandatory text verbatim and specify its hierarchy and placement.
- Prefer generating clean headline zones and adding dense or mission-critical copy in post-production. If rendering text inside the image, keep it short and require no extra characters.
- Use a user-provided brand, logo, or palette only when requested. Otherwise use generic brand blocks or blank logo zones.
- Never recreate reference watermarks, creator handles, barcodes, third-party slogans, or trademarked logos merely because they appear in a style reference.
- Create an original mascot or character unless the user explicitly supplies or requests a character they are authorized to use.

## Render and review

For generation, use the host's image-generation capability and label every input image by role. Generate one strong direction first unless variants are requested.

Review the result against these invariants:

- the fisheye geometry converges around a central sky or focal opening;
- the projected foreground element feels intentional rather than anatomically broken;
- the subject's face, logo zone, or product silhouette remains legible;
- blue/yellow or the chosen two-color system dominates without muddy midtones;
- type zones are integrated into the composition and do not become random gibberish;
- texture supports hierarchy instead of covering every surface;
- no unintended trademarks, watermarks, duplicated limbs, or extra fingers.

If iteration is needed, change one variable at a time and repeat the invariants.

## Deliver

For prompt-only work, return:

1. a one-paragraph visual direction;
2. the final English generation prompt;
3. the copy hierarchy and placement plan;
4. a compact negative prompt or avoid list;
5. optional model-specific aspect-ratio syntax only when the target model is known.

For rendered work, also return the generated image, its saved path when project-bound, and the exact final prompt used.
