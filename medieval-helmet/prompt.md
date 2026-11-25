# NIGHTFALL SIDE PROJECT — MEDIEVAL HELMET
## Technical Specification for a High-Fidelity Knight Helmet Asset

Document type: 3D asset production specification
Asset: MEDIEVAL_KNIGHT_HELMET_AAA
Deliverable: Native Blender master scene, supporting scripts, QA reports, and technical renders
Production mode: Single autonomous execution with internally managed stages
Quality target: AAA-style hero prop suitable for close-up inspection
Asset scope: One highly detailed medieval knight helmet with articulated visor, internal lining, fastening system, and physically coherent construction
Reference policy: No external references, no web research, no imported third-party geometry, no neighboring folders

---

## 1. Project objective

Create a new, standalone, high-detail medieval knight helmet from scratch in Blender.

The helmet must be a plausible late-medieval / fantasy-grounded knight helmet suitable for a premium game asset. It must not be a vague fantasy shell or a generic bucket shape. It must feel manufactured, structurally believable, and mechanically coherent.

The result should work both as:
1. a hero prop for close-up rendering;
2. a game-world asset conceptually suitable for a medieval game.

The main production priorities are:

1. Clear and coherent helmet architecture.
2. Correct shell thickness and layered construction.
3. A well-built articulated visor with believable hinge logic.
4. Real fastening, rivet, strap, and lining systems.
5. Rich but controlled fine detail.
6. Plausible steel, leather, fabric, and padding materials.
7. Elimination of unintended geometric intersections.
8. Clean scene organization suitable for later rigging, animation, and game-asset optimization.

The full assignment must be executed within this single prompt through internally managed production stages. Do not stop after an early stage and present a partial model as final.

If the environment cannot complete the entire asset in one execution, save the latest valid scene and truthfully report what remains incomplete.

---

## 2. Working environment

### 2.1 Required tools

Use Blender MCP for all Blender operations.

Use Blender Python (`bpy`) where appropriate for:
- repeated rivet generation,
- hinge component generation,
- pattern placement,
- object organization,
- transform checks,
- collision checks,
- camera setup,
- QA support,
- file saving.

Use GPT-6.2 Sol High for the director and specialist agents if available.
If unavailable, report the actual configuration instead of pretending.

### 2.2 Project isolation

Work only inside the explicitly authorized project directory.
Create a separate helmet workspace, for example:

`nightfall_hypercar/medieval_helmet/`

Do not inspect neighboring folders.
Do not overwrite unrelated project files.

### 2.3 Reference restrictions

Do not:
- browse the web,
- download references,
- import third-party models,
- use external concept art,
- use scans,
- use external blueprints,
- search neighboring folders for examples.

The helmet must be designed from general internal knowledge and internal construction logic only.

This means the final design should be historically plausible in spirit and mechanically believable, but it is not required to reproduce any specific museum piece.

---

## 3. Asset definition

Create a full-face knight helmet with the following core identity:

- Gothic / late-medieval inspired silhouette.
- Fully enclosed steel helmet.
- Articulated front visor.
- Distinct eye-slit area or vision openings integrated into the visor.
- Ventilation perforations or slots.
- Defined lower-face and chin protection.
- Rear neck protection.
- Internal leather/fabric lining.
- Chin strap or fastening strap system.
- Rivets, hinges, and fastening hardware.
- Premium forged-steel feel suitable for a hero asset.

The design should feel suitable for:
- a high-ranking knight,
- a cinematic close-up prop,
- a serious medieval game,
- a richly detailed standalone model.

Avoid exaggerated cartoon fantasy forms unless they remain grounded in believable metal construction.

The helmet should feel elegant, protective, and heavy-duty.

---

## 4. Scale and dimensions

Use metric units.

Suggested physical scale:

- Overall helmet height: approximately 320–380 mm
- Width at widest point: approximately 220–260 mm
- Front-to-back depth: approximately 300–360 mm
- Steel shell thickness: typically 1.5–3.0 mm depending on local region
- Visor thickness: similar to shell or slightly reinforced where justified
- Rivet head sizes, hinge sizes, and strap thicknesses must be proportionally plausible

These values are design targets, not rigid locked dimensions.

All specialists must use a consistent scale.

Do not independently scale components later to hide intersections.

---

## 5. Coordinate system and datums

Set Blender to metric units.

Define:
- Z axis: vertical
- X axis: left-right
- Y axis: front-back

Create a master assembly object:

`HELM_MASTER`

Create datums / empties for:
- `DATUM_CENTER`
- `DATUM_HELM_BASE`
- `DATUM_HELM_FRONT`
- `DATUM_HELM_REAR`
- `DATUM_VISOR_AXIS_L`
- `DATUM_VISOR_AXIS_R`
- `DATUM_CHIN_LINE`
- `DATUM_NECK_GUARD`
- `DATUM_STRAP_L`
- `DATUM_STRAP_R`

Use these consistently for shell, visor, hinge, and strap placement.

The visor hinge axis must be defined before detailed visor modeling begins.

---

## 6. Component inventory

The helmet must include at minimum the following component groups.

### 6.1 Outer shell

Required:
- main crown shell,
- brow region,
- cheek protection geometry,
- jaw / lower-face protection,
- rear head coverage,
- neck guard or rear flare,
- shell edge treatments,
- local reinforcement features where appropriate.

Requirements:
- the shell must have real thickness;
- it must not be a single infinitely thin surface pretending to be metal;
- it must contain believable curvature transitions;
- it must feel forged and finished, not sculpted as a vague blob.

### 6.2 Articulated visor

Required:
- primary visor plate,
- vision slit / opening system,
- ventilation holes or slots,
- visor rim treatment,
- hinge connection areas,
- locking or resting interface in closed position,
- correct opening arc,
- realistic shell-to-visor overlap.

Requirements:
- the visor must open and close coherently;
- it must not interpenetrate the shell in either closed or open states;
- the hinge mechanism must be structurally understandable;
- the visor must not float or attach ambiguously.

### 6.3 Hinge and fastening system

Required:
- left hinge assembly,
- right hinge assembly,
- hinge pins or pivot system,
- mounting plates or hinge loops,
- relevant rivets or bolts,
- visor stop logic if needed,
- latch or hold-down logic if appropriate.

Requirements:
- the hinge geometry must support the visor mechanically;
- opening motion must be plausible;
- the hinge system must survive close-up inspection.

### 6.4 Internal structure

Required:
- inner shell or internal offset representation as needed,
- padded lining,
- liner attachment points,
- head-contact cushioning zones,
- internal suspension or support logic if used,
- strap anchor points.

Requirements:
- the helmet must not be empty and unfinished inside;
- the interior must contain a believable comfort/protection system;
- internal components must fit inside the shell without bad intersections.

### 6.5 Strap system

Required:
- chin strap or side fastening strap,
- buckle or fastening hardware,
- leather thickness,
- hole pattern or fastening logic,
- connection rivets / anchors,
- secondary fastening tabs where appropriate.

Requirements:
- straps must connect to the helmet meaningfully;
- buckle scale must be plausible;
- strap geometry must not clip badly through the shell or liner.

### 6.6 Fine metal details

Required:
- rivet families,
- edge rolls or reinforced edges where appropriate,
- seams or plate boundaries if justified,
- embossed ridges or subtle decorative reinforcement,
- plate overlaps where mechanically sensible,
- local surface variation indicating manufacture.

Do not spam meaningless decoration.
Use detail where it reinforces construction and visual richness.

---

## 7. Modeling standards

### 7.1 Geometry hierarchy

Use four scales of geometry:

1. Primary geometry
- shell silhouette,
- visor form,
- neck guard,
- large plate transitions.

2. Secondary geometry
- hinge parts,
- strap anchors,
- reinforced edges,
- visor locking interfaces,
- liner blocks and padding forms,
- buckle hardware.

3. Microgeometry
- rivets,
- stitching where visible,
- buckle holes,
- hinge pins,
- small fasteners,
- local attachment tabs,
- perforation refinement.

4. Surface detail
- hammered / forged subtle irregularity where appropriate,
- brushed or polished steel response,
- leather grain,
- fabric texture,
- edge wear if justified.

Primary and secondary structures should use real geometry.
Surface detail may use shader-level detail where appropriate.

### 7.2 Thickness

All major metal plates must have real thickness.

Do not deliver a single-surface shell as the final result unless a justified internal construction approach produces an equivalent visual and structural result.

Plate edges must look like actual metal thickness, not paper.

### 7.3 Shape quality

Avoid:
- lumpy surfaces,
- accidental asymmetry,
- broken smooth shading,
- random dents unless intentionally designed,
- paper-thin visor edges,
- low-quality booleans around openings,
- inconsistent edge widths.

The helmet may contain mild handcrafted character, but not sloppiness.

### 7.4 Repeated detail

Create reusable rivet, buckle, and fastening libraries.
Use linked or instanced repeated details where appropriate.

Do not create dozens of unrelated rivet styles unless there is a good reason.

---

## 8. Intersections, collisions, and motion checks

This is a critical subsystem.

The visor is a moving part, and the helmet contains multiple nested and adjacent components. Unintended intersections are not acceptable.

### 8.1 Interaction categories

Classify object relationships as:

- CONTACT:
  intended surface seating or direct contact

- FIT:
  intended fitted engagement, such as hinge pin through hinge loop

- CLEARANCE:
  parts that should remain separate

- INTERFERENCE:
  unintended penetration or clipping

- UNKNOWN:
  not yet verified

Do not treat all contact as an error.
Do not ignore obvious clipping because it is small.

### 8.2 Critical anti-intersection targets

Special attention is required for:

1. visor against main shell in closed position
2. visor against main shell during opening
3. hinge loops and hinge pins
4. strap anchors against shell
5. strap geometry against liner and shell
6. interior padding against inner shell
7. rivets and hardware against plate thickness
8. ventilation cut geometry and visor structure
9. neck guard against rear shell
10. all decorative edge details near plate boundaries

### 8.3 Motion states

The visor must be checked in at least three states:

- State A: fully closed
- State B: partially open
- State C: fully open display position

The asset does not need a full animation rig unless useful, but these states must be represented and verified.

No bad penetrations should occur in the tested motion states.

### 8.4 Collision detection

Where supported, create a Blender Python utility:

`qa_helmet_intersections.py`

The script should:

1. gather evaluated geometry,
2. detect candidate object overlaps using bounding volumes,
3. test likely colliding pairs,
4. distinguish intended hinge fits from accidental penetration where possible,
5. flag suspicious intersections,
6. generate a structured report.

Export:
- `helmet_collision_report.json`
- `helmet_collision_report.txt`

### 8.5 Manual inspection

Because automated checks are limited, combine them with:
- orthographic views,
- high-contrast temporary materials,
- isolated collection checks,
- section views,
- close-up renders,
- specific open/closed visor inspections.

### 8.6 Clearance policy

Use project-specific visual clearance goals such as:

- unrelated rigid parts: ~1–2 mm minimum visual clearance
- moving visor near shell: enough clearance to avoid clipping while maintaining believable fit
- leather straps against rigid parts: may rest on or lightly contact intended surfaces
- hinge fit: intentional controlled contact allowed

These are modeling targets, not certified real engineering tolerances.

---

## 9. Materials

Create a PBR material system with at least:

### Metal
- forged/polished steel
- brushed steel
- darker treated steel where needed

### Leather
- strap leather
- padded leather surface where appropriate

### Fabric / padding
- cloth or padded liner materials
- interior cushion materials

### Optional accents
- subtle decorative trim if justified
- restrained engraved or embossed elements

Requirements:
- the exterior steel must feel premium and believable;
- the interior must contrast visually with the shell;
- leather must not look like generic plastic;
- materials should remain suitable for close-up inspection.

Avoid excessive grime.
This should look like a high-quality maintained helmet, not a ruined relic.

Subtle wear is acceptable if controlled.

---

## 10. Specialist organization

Use a specialist structure.
These are responsibility assignments and should be executed via real subagents where available, or sequentially if actual parallel execution is limited.

1. Project director
2. Scale and datums specialist
3. Main shell specialist
4. Shell edge and reinforcement specialist
5. Visor specialist
6. Hinge specialist
7. Visor locking / resting interface specialist
8. Ventilation and cutout specialist
9. Inner shell / interior fitting specialist
10. Liner and padding specialist
11. Strap specialist
12. Buckle and fastening hardware specialist
13. Rivet and repeated detail specialist
14. Materials specialist
15. Collision detection specialist
16. Motion-state validation specialist
17. Close-up QA specialist
18. Final independent QA specialist

If more agent capacity exists, add support roles for:
- decorative metalwork,
- stitching details,
- manufacturing microdetail,
- render setup,
- script QA.

Do not falsely claim parallel agents if the environment did not actually support them.

---

## 11. Production stages

Execute all stages within this single assignment.

### Stage 0 — Initialization

- Create the separate project workspace.
- Configure units.
- Define datums.
- Create collections.
- Define naming convention.
- Save the initial file.

Output:
A clean production scene with core project structure.

### Stage 1 — Blockout

- Create the overall helmet silhouette.
- Establish main shell proportions.
- Define visor dimensions.
- Establish hinge axis and visor motion path.
- Reserve interior volume for head space and padding.
- Check major proportions and relationships.

Output:
A coherent blockout with major volumes and motion concept.

### Stage 2 — Shell construction

- Build the actual outer shell.
- Add real plate thickness.
- Refine curvature.
- Define reinforced areas.
- Create edge treatments.
- Shape neck protection and lower-face coverage.
- Validate shell symmetry or intentional asymmetry.

Output:
A production-quality shell foundation.

### Stage 3 — Visor construction

- Build the visor from scratch.
- Create eye slit(s) or vision opening.
- Add ventilation features.
- Add thickness and edge quality.
- Ensure closure relationship with shell.
- Verify closed-state fit.

Output:
A detailed visor with proper fit against the shell.

### Stage 4 — Hinge and closure system

- Build hinges.
- Create pivot logic.
- Add hinge pins and attachment plates.
- Add closure or resting interfaces.
- Validate open / half-open / closed states.

Output:
Mechanically understandable articulated visor system.

### Stage 5 — Interior construction

- Build inner fitting surfaces.
- Build liner and padded elements.
- Add liner attachment logic.
- Add chin or side straps.
- Add buckle and fastening hardware.

Output:
A believable interior and wearing system.

### Stage 6 — Fine detail pass

- Add rivets.
- Add fastening details.
- Add local reinforcement features.
- Add subtle decorative / manufacturing detail.
- Add stitching where visible.
- Add microgeometry for high-value close-up zones.

Output:
High-detail hero prop geometry.

### Stage 7 — Materials

- Create metal, leather, and interior materials.
- Differentiate exterior and interior.
- Add subtle surface microstructure.
- Validate under neutral and studio lighting.

Output:
Complete material treatment.

### Stage 8 — Collision and motion audit

- Run automated checks where supported.
- Inspect visor in all required states.
- Inspect hinge fit.
- Inspect interior / shell relationships.
- Inspect straps and buckles.
- Fix confirmed unintended collisions.
- Re-run checks.

Output:
Collision-reviewed and motion-reviewed asset.

### Stage 9 — Final QA and delivery

- Perform close-up inspection renders.
- Verify geometry quality.
- Verify shading.
- Verify materials.
- Verify scene organization.
- Save final file.
- Reopen or validate the file.
- Export reports and render set.

Output:
Final deliverable package.

---

## 12. QA gate after every stage

Each stage must pass:

1. Geometry
- normals
- broken shading
- duplicate faces
- accidental holes
- bad booleans

2. Dimensions and proportions
- scale consistency
- shell thickness
- relative part size

3. Construction logic
- believable component relationships
- support / attachment logic

4. Interference
- no critical unintended intersections in the stage scope

5. Detail scope
- required components for the stage exist

6. Material readiness
- appropriate assignments or placeholders

7. Multi-angle inspection
- front
- side
- rear
- top
- bottom
- oblique close-up

8. Regression
- newly added work did not break previous work

Possible statuses:
- PASS
- FAIL
- PASS_WITH_LIMITATIONS
- NOT_VERIFIED

Critical failures must be repaired before acceptance.

---

## 13. Close-up quality requirements

The asset must survive three levels of inspection.

### Level A — Full object
The helmet silhouette and construction should be immediately readable.

### Level B — Subsystem close-up
The visor, hinges, lining, and straps must show clear component separation and believable assembly logic.

### Level C — Extreme close-up
Rivets, hinge pins, edge rolls, buckle details, stitching, leather holes, and interior attachment features must hold up visually.

Do not rely on heavy depth of field or dramatic lighting to hide defects.

Use sharp technical close-ups.

---

## 14. Required render set

Produce at least:

1. Front three-quarter view
2. Rear three-quarter view
3. Front orthographic
4. Side orthographic
5. Rear orthographic
6. Top view
7. Bottom / underside interior view
8. Visor closed
9. Visor partially open
10. Visor fully open
11. Hinge close-up left
12. Hinge close-up right
13. Visor vent / slit close-up
14. Shell edge / thickness close-up
15. Rivet and fastening close-up
16. Interior lining close-up
17. Strap and buckle close-up
18. Neutral clay render
19. Collision / motion inspection view
20. Final studio hero render

If useful, also include an exploded technical render.

---

## 15. Naming and organization

Use clear names such as:

- HELM_MASTER
- HELM_SHELL_MAIN
- HELM_VISOR_MAIN
- HELM_HINGE_L
- HELM_HINGE_R
- HELM_STRAP_L
- HELM_STRAP_R
- HELM_BUCKLE
- HELM_LINER_MAIN
- HELM_RIVET_SET_A
- HELM_RIVET_SET_B

Use separate collections for:
- SHELL
- VISOR
- HINGES
- INTERIOR
- STRAPS
- FASTENERS
- MATERIALS
- QA_TEMP

Keep movable parts separate.

Do not collapse the entire helmet into one mesh.

---

## 16. Checkpoints and deliverables

Suggested structure:

`medieval_helmet/`
- `blend/`
- `scripts/`
- `renders/`
- `qa/`
- `reports/`

Save checkpoints after every stage.

Suggested files:
- `helmet_00_init.blend`
- `helmet_01_blockout.blend`
- `helmet_02_shell.blend`
- `helmet_03_visor.blend`
- `helmet_04_hinges.blend`
- `helmet_05_interior.blend`
- `helmet_06_details.blend`
- `helmet_07_materials.blend`
- `helmet_08_collision_qa.blend`
- `helmet_09_final.blend`

Final master file:
`MEDIEVAL_KNIGHT_HELMET_AAA_MASTER.blend`

Additional required files:
- `helmet_specification.json`
- `helmet_interfaces.json`
- `helmet_motion_states.json`
- `qa_helmet_intersections.py`
- `helmet_collision_report.json`
- `qa_summary.md`
- `production_report.md`

Do not claim deliverables exist unless they were actually created.

---

## 17. Final acceptance criteria

The project is acceptable when:

1. A new helmet was actually modeled from scratch.
2. The shell has real thickness and believable construction.
3. The visor is mechanically coherent.
4. The visor works in closed, half-open, and open states without obvious unintended clipping.
5. The hinge system is understandable and detailed.
6. The interior is not empty or unfinished.
7. Straps and buckle have believable construction.
8. Rivets and hardware are coherent and well integrated.
9. Materials are sufficiently differentiated.
10. Extreme close-up views remain convincing.
11. Automated and manual collision checks have been performed where supported.
12. Confirmed unintended intersections have been corrected.
13. The final Blender file has been saved.
14. The final file has been reopened or otherwise validated.
15. Required QA renders and reports exist.
16. Remaining limitations, if any, are documented honestly.

Do not call the asset AAA merely because it has many objects.
The modeling, construction logic, and close-up quality must justify that label.

---

## 18. Execution instruction

Begin by creating the isolated helmet workspace and establishing the project structure.

Proceed through the production stages in dependency order.

Use actual Blender operations for all geometry creation.

Validate visor mechanics before heavy microdetail work.

Perform collision and motion checks throughout, not only at the end.

Do not fabricate subagent execution, file outputs, QA results, or completion status.

The final goal is a technically coherent, richly detailed, articulated medieval knight helmet that functions as a premium hero prop and can support later rendering, rigging, and game integration.

End of specification. Begin production.
