# Task: Creating the "Heart of Eternity" 3D Model in Blender

You are working in the `crystal_heart` folder. Use **Blender MCP**. If Blender MCP is unavailable, report this immediately and do not claim that the work has been completed.

Your task is to create an incredibly beautiful, detailed, magical 3D model of a crystal heart with a striking internal glow, high-quality materials, carefully designed lighting, and an impressive presentation.

**There are no references.** Create a completely original model based on the artistic description below. Do not use random images as mandatory references.

The main goal is to achieve a level of visual quality that makes the heart look like a unique magical artifact from a modern fantasy game or a professional cinematic 3D render.

Priorities:
1. A beautiful, recognizable heart-shaped silhouette.
2. High-quality crystal geometry.
3. A mesmerizing internal glow.
4. Convincing glass and crystal materials.
5. A magical atmosphere, depth, and visual expressiveness.
6. Refined detailing without excessive clutter.

The model must not look like a plastic heart, an ordinary glass figurine, or a primitive object with an Emission material.

---

# Artistic Concept

## "Heart of Eternity"

A large floating crystal heart is at the center of the composition.

Its shape resembles a gemstone cut by ancient mages.

The heart has a three-dimensional, fundamentally symmetrical shape, with a distinctive upper indentation, two upper lobes, and a pronounced pointed lower tip.

However, the geometry should not be perfectly smooth: the surface is divided into numerous facets of different sizes, creating a complex interplay of light.

**Color palette:**
- Main crystal — rich ruby pink transitioning into purple.
- Facet edges — light pink, with cool lilac tones in some areas.
- Internal energy — bright pinkish white and deep magenta.
- Magical accents — soft cyan-turquoise.
- Environment — deep navy blue, almost black.

There should be a palpable energy core inside the crystal, as though the heart contains a living magical force.

Light should pass through the crystal, refract, reflect off its facets, and create a sense of depth.

**Important:** The heart is the main object in the scene. All additional elements should enhance its beauty rather than compete with it.

---

# General Workflow Rules

Work in stages, progressing from large forms to small details.

After each stage:
1. Check the overall composition and silhouette.
2. Check the geometry, normals, and topology.
3. Eliminate unwanted intersections.
4. Check the materials and how the light behaves.
5. Inspect the model from the front, side, and back, as well as at 30°, 45°, 60°, 90°, and 120° angles.
6. Produce a test render or screenshot.
7. Save a separate `.blend` version.

Do not move on to micro-details until the main shape and lighting look convincing.

Use a consistent coordinate system, a consistent scale, clear object names, and well-organized Blender collections.

---

# Stage 1 — Main Heart Shape

Create the three-dimensional geometry of the crystal heart.

Requirements:

- A clear and beautiful heart-shaped silhouette.
- Three-dimensional front and back surfaces.
- Smooth overall variation in thickness.
- Two neatly shaped upper lobes.
- A pronounced central indentation.
- A pointed lower section.
- Natural proportions without excessive stretching.
- Controlled geometry without unintended deformations.

The heart should not look flat or resemble an inflated balloon.

Create a beautiful base shape suitable for subsequent crystal faceting.

Check the silhouette from several angles using a solid-color material.

Only then proceed to the next stage.

# Stage 2 — Crystal Faceting

Transform the base shape into a visually striking gemstone.

Create a system of geometric facets:

- Large facets define the main silhouette.
- Medium-sized facets add volume.
- Small facets create interesting reflections.
- Some surfaces are slightly angled relative to one another.
- Both the front and back must be fully faceted.
- The facets must be geometrically consistent with one another.

Avoid randomly protruding polygons, gaps, excessively sharp spikes, and unnatural fractures.

Do not create the impression of multiple individual gemstones glued together. It must be **a single crystal** with high-quality faceting.

If necessary, apply small bevels to some edges without compromising the crispness of the crystal shape.

Check the result under neutral lighting.

# Stage 3 — Crystal Materials

Create a sophisticated artistic material that conveys the appearance of a real gemstone.

Main properties:

- Partial transparency.
- Light refraction.
- Reflective facets.
- Rich internal color.
- Variations in brightness and hue across different facets.
- A sense of depth inside the object.
- Clean, bright highlights.

Use the appropriate features of Principled BSDF and any other necessary Blender nodes.

The material should be as physically plausible as possible while still achieving the desired artistic effect.

The visual result is more important than an excessively complex node setup.

Do not use a single, uniformly bright Emission material across the entire heart. This will destroy the perception of volume and faceting.

The crystal should remain visually readable even when the internal energy source is turned off.

# Stage 4 — Magical Core

This is one of the most important stages.

Create a bright energy core inside the heart that appears to be enclosed within the crystal.

It should be:

- Smaller than the heart itself.
- Very bright at its center.
- Pinkish white in the most energy-intensive areas.
- Magenta and violet around the periphery.
- Non-uniform in its glow intensity.
- Visually deep and layered.

Add several internal energy structures that can be seen through the transparent facets.

Possible elements:
- Thin, glowing energy veins.
- Small internal crystalline inclusions.
- Streams of light around the core.
- Several concentrated areas of glow.

The effect should convey the feeling that the heart contains **magical energy that is alive and pulsating**.

Avoid visual noise.

It is very important to preserve the distinction between the bright core and the darker crystalline shell.

# Stage 5 — Floating Shards and Magical Particles

Make the composition more impressive.

Add a small number of floating crystal shards around the heart.

They should:
- Match the color palette of the main crystal.
- Have their own faceting.
- Vary in size.
- Be positioned at different distances from the heart.
- Create a sense of motion and weightlessness.

Do not arrange them chaotically or too densely.

Some of the smaller shards may have a faint internal glow.

Add magical particles:
- Small glowing points of light.
- Individual bright sparks.
- Barely visible energy trails.
- A subtle glow around the center of the composition.

If necessary, add two or three thin arcs of magical energy around the heart, but do not obscure its silhouette.

The model should look impressive even without the particles.

# Stage 6 — Pedestal and Composition

Create a small ancient magical pedestal above which the heart will float.

Pedestal style:
- Dark stone.
- Clean geometric forms.
- Metal inlays.
- Thin glowing runes.
- Small cracks with a subdued magenta glow.

The pedestal should be significantly less bright than the heart itself.

Position the heart slightly above the pedestal, leaving a clearly visible gap between them.

Add a barely visible energy connection between the pedestal and the heart if it improves the composition.

Do not make the pedestal too bulky or complex.

# Stage 7 — Lighting

**This stage is critically important.**

Create a professional lighting setup that brings out the beauty of the crystal as much as possible.

Use:
- A soft key light to make the shape readable.
- A cool rim light to highlight the silhouette.
- Additional side lighting to create reflections on the facets.
- Actual internal illumination from the energy core.
- Subtle lighting for the surrounding shards.
- A dark environment for contrast.

Pay particular attention to the interaction between light and the crystal material.

The glow should be bright but controlled.

Avoid:
- A completely overexposed heart.
- Loss of detail on the facets.
- A solid white blob instead of the core.
- Excessive Bloom/Glare.
- An unnaturally bright pedestal.
- Complete loss of the silhouette against the dark background.

Use compositing, Glare, and other effects only when they genuinely improve the image.

Preferably use Cycles with an appropriate sample count, denoising, and proper color management.

The goal is to achieve a premium-looking, deep, atmospheric cinematic render.

# Stage 8 — Animation

If the main model and lighting are complete and have been thoroughly checked, add a short looping animation.

Duration: approximately 5 seconds at 24 FPS.

The animation should include:

1. Very slow upward and downward floating motion of the heart.
2. Subtle pulsation of the internal core.
3. Smooth variation in glow intensity.
4. Slow movement of the surrounding shards.
5. Subtle rotation of some magical particles.

The movements should be smooth, calm, and magical.

Do not rotate the heart so quickly that the viewer cannot appreciate its geometry.

The animation should form a natural, seamless loop.

Do not sacrifice the quality of the model or static renders for the sake of animation.

---

# Checks After Each Stage

After each stage, perform the following review cycle:

**1. Geometry**
- No unwanted intersections.
- No flipped normals.
- No unintended holes.
- No deformed or damaged faces.
- The main crystal retains a coherent structure.

**2. Materials**
- Transparency is displayed correctly.
- No black artifacts caused by material errors.
- Reflections and refractions look convincing.
- The glow does not compromise the readability of the geometry.

**3. Composition**
- The heart remains the main element.
- Additional elements do not obscure it.
- The silhouette looks beautiful from all sides.
- There is no impression of randomly piled-up details.

**4. Lighting**
- The central core is clearly visible.
- The crystal edges stand out against the background.
- The facets have beautiful contrast.
- There is no excessive overexposure.

**5. Viewing Angles**
Inspect the model from the front, back, and side, as well as at 30°, 45°, 60°, 90°, and 120° angles.

Use consistent orthographic views to check the geometry. Use a perspective camera for the final presentation.

If any problems are found, fix them before proceeding to the next stage.

---

# Final Checks

After completing the modeling, perform three full review cycles.

**First cycle — Technical**
Check the geometry, normals, scene structure, materials, absence of errors, and integrity of the model.

**Second cycle — Visual**
Check the beauty of the silhouette, compositional balance, color palette, crystal depth, reflections, and internal glow.

**Third cycle — Artistic**
Assess whether the object genuinely makes a strong visual impression.

If the model looks too simple, lacks depth, appears dull, or looks like plastic, improve the specific elements causing those problems.

Do not add small details merely for the sake of quantity — prioritize improvements to the materials, shape, composition, and lighting.

---

# Saving and Deliverables

After each stage, save a separate `.blend` file in the `crystal_heart/stages` folder.

Save intermediate and final images in the `crystal_heart/renders` folder.

Required final deliverables:

1. `crystal_heart.blend` — the complete Blender project with all objects, materials, lights, cameras, and animation, if created.
2. `front.png` — front view.
3. `back.png` — back view.
4. `side.png` — side view.
5. `quarter.png` — an impressive three-quarter view.
6. `hero_render.png` — the main artistic render.
7. `geometry_check.png` — the model with a neutral material for evaluating its shape.

The main render must have a resolution of at least 1920×1080.

If sufficient resources are available, produce an additional render at 2560×1440 or higher.

If animation is created, save it separately in a video format.

If possible, export the geometry to `.glb`, keeping in mind that complex nodes, refraction, lighting, and compositing effects may not transfer completely.

All files must actually be created and verified before being mentioned in the final report.

---

# Additional Requirements

- Do not replace actual 3D modeling with image generation.
- Do not use a flat texture instead of a three-dimensional heart.
- Do not create the model from randomly overlapping primitives.
- Do not use a huge Emission object that obscures the main geometry.
- Do not make the heart too dark or completely opaque.
- Do not use excessively bright Bloom that turns the artifact into a blurry blob.
- Do not overload the scene with unnecessary decorations.
- Keep the project editable.
- Organize objects, materials, and collections logically.
- Before finishing, make sure to reopen the saved file and verify that the scene is not corrupted.

**Main artistic vision:**

Imagine an ancient, legendary heart-shaped crystal that has held incredible magical energy for centuries. A living magenta-pink core glows within it. Its precious gemstone facets refract light, small crystal shards float slowly around it, and the heart itself hovers weightlessly above an ancient altar.

The result should not look like an ordinary 3D model, but like **a mesmerizing magical artifact that makes you want to look at it again and again**.

Start with the first stage. Work sequentially, check the results, and bring the project to a fully finished state.
