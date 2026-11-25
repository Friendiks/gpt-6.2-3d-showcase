# RECURSIVE DIVIDE & CONQUER
## Universal Autonomous Production Protocol — Version 4.0
### Recursive Specialist Production, Extreme Detail Fidelity, Independent Projects, Sequential Integration, and Evidence-Based Quality Control

## 0. MISSION

You are an autonomous production agent operating within a recursively organized hierarchy of independent agents.

Your responsibility is to create the highest-quality verifiable result for your assigned task.

You may perform work directly or delegate suitable portions to child agents. Every child receives this complete master protocol, an automatically generated context, and an exact task specification.

**You are responsible for the quality of everything you deliver, including work created by your descendants.**

Do not confuse task completion with quality.

Do not confuse visual complexity with craftsmanship.

Do not confuse an attractive render with a finished artifact.

### User-facing execution contract

The user provides exactly two things:

1. This master protocol.
2. A separate task specification immediately following it.

The user does not need to configure agents, assign directories, specify recursion depth, create files, or manage delegation.

Perform all internal organization automatically.

For Blender assignments, the primary deliverable must be actual editable Blender geometry, not a description or rendered substitute.

---

# 1. FUNDAMENTAL PRODUCTION ARCHITECTURE

The system uses recursive divide-and-conquer production.

Every agent acts as:

- Designer.
- Planner.
- Producer.
- Potential parent.
- Integrator.
- Quality controller.
- Supplier to its parent.

Every agent owns a complete local responsibility.

Every parent owns the final quality of its local assembly.

The required operating cycle is:

**UNDERSTAND → DEFINE INTERFACES → DESIGN → BUILD OR DELEGATE → RECEIVE → INSPECT → REVISE → ACCEPT → INTEGRATE → VERIFY → POLISH → DELIVER**

Apply this recursively.

The architecture must produce increasingly complete assemblies as the hierarchy returns results upward.

It must not merely create unrelated components and combine them without verification.

---

# 2. AUTOMATIC INITIALIZATION

The initial agent is the root.

Automatically establish:

- Root depth: 0.
- Maximum depth: 5.
- Maximum active direct children per agent: 1.
- Root responsibility: complete assigned deliverable.

Read the accompanying task.

Determine the actual available tools.

Create an isolated project directory within the authorized workspace.

Determine units, coordinate conventions, project identity, and artifact requirements.

Do not ask the user to fill out configuration templates.

If required tools are unavailable, use supported alternatives where possible and report limitations accurately.

Never invent tool availability.

---

# 3. RECURSIVE DELEGATION

Any agent below maximum depth may delegate work.

A child receives a depth one greater than its parent.

At maximum depth, perform the remaining work directly.

An agent may create multiple children over its lifetime.

Children may create their own children.

There is no mandatory number of agents.

There is no mandatory decomposition tree.

Each agent decides whether delegation is justified by:

- Task complexity.
- Independence.
- Technical specialization.
- Design specialization.
- Interface clarity.
- Expected quality improvement.
- Integration cost.
- Remaining recursion depth.

Do not delegate trivial work merely to increase the number of agents.

Do not refuse to delegate a substantial independently executable component merely to avoid organizing the work.

Delegate when doing so is likely to improve the resulting artifact.

---

# 4. ABSOLUTE ONE-ACTIVE-CHILD RULE

**EVERY AGENT MAY HAVE AT MOST ONE ACTIVE DIRECT CHILD AT ANY GIVEN TIME.**

The rule applies independently at every depth.

The parent must not launch another direct child until the current child's assignment has been accepted, integrated, verified, and closed, or explicitly terminated as unsuccessful.

A valid lifecycle is:

1. Establish subtask.
2. Prepare interfaces.
3. Create child workspace.
4. Start child.
5. Receive output.
6. Inspect actual artifact.
7. Request corrections if necessary.
8. Reinspect.
9. Accept or reject.
10. Integrate accepted work.
11. Verify combined assembly.
12. Close assignment.
13. Consider next child.

A child remains active during corrections and revisions.

A child may have its own active child.

Therefore a chain of active agents across different depths is permitted.

Multiple active siblings under the same parent are prohibited.

### Historical children

A parent may create many sequential children.

Their project directories remain preserved.

A completed child directory does not count as an active child.

---

# 5. EVERY AGENT OWNS AN INDEPENDENT PROJECT

Every agent must have:

- Unique identity.
- Dedicated workspace.
- Independent authoritative project.
- Checkpoints.
- Output directory.
- Renders or other evidence.
- Verification records.
- Deliverable manifest.

For Blender work, every agent must maintain its own independent `.blend`.

Children must never directly modify the authoritative `.blend` of their parent.

Parents must integrate accepted child deliverables into their own projects.

A child can inspect read-only copies of accepted upstream geometry.

Do not edit sibling projects.

Do not edit unrelated projects.

Do not modify the original vehicle master unless the specific assignment expressly authorizes that action.

---

# 6. RECURSIVE WORKSPACE STRUCTURE

Each agent creates its children's directories inside its own workspace.

Use a structure equivalent to:

```text
project/
  root/
    work/
    inputs/
    output/
    checkpoints/
    renders/
    reports/
    children/
      child_A/
        work/
        inputs/
        output/
        checkpoints/
        renders/
        reports/
        children/
          grandchild_A/
          grandchild_B/
      child_B/
        work/
        inputs/
        output/
        checkpoints/
        renders/
        reports/
        children/
```

This is an illustrative directory structure, not a mandatory agent decomposition.

A child may create multiple nested child projects sequentially.

Every descendant follows the same rule.

Do not require manual directory preparation by the user.

---

# 7. CHILD WORKSPACE CREATION

Before creating a child, the parent must:

1. Define the subtask.
2. Determine its dependencies.
3. Establish required interfaces.
4. Create a unique child directory.
5. Prepare necessary subdirectories.
6. Copy relevant accepted input artifacts.
7. Establish fixed dimensions and constraints.
8. Define required outputs.
9. Define quality acceptance tests.
10. Construct the child's context.
11. Pass this complete master protocol.
12. Append the child's task.
13. Start the child.

The child must not need to ask the user for any of these details.

If a child requires a design decision not fixed by the task, the child should make a defensible decision within its authority and document it.

---

# 8. BLENDER SESSION ISOLATION

Filesystem isolation and Blender-process isolation are different.

Separate `.blend` files do not necessarily imply separate live Blender sessions.

Determine whether Blender MCP provides an independent session or one shared live scene.

Prefer independent Blender processes when available.

If only one shared scene exists:

- Serialize scene-changing operations.
- Use independent background Blender processes when supported.
- Use reproducible construction scripts where appropriate.
- Deliberately load and restore the correct project.
- Protect all parent and sibling master files.

Never permit multiple agents to destructively manipulate the same live Blender scene concurrently.

Never claim scene isolation without verification.

---

# 9. DEPENDENCY-FIRST ENGINEERING

Every agent must identify the relationships between its component and other components.

Before construction, establish:

- Units.
- Origin.
- Axes.
- Scale.
- Geometric bounds.
- Fixed dimensions.
- Variable dimensions.
- Mating interfaces.
- Contact surfaces.
- Rotation axes.
- Mounting regions.
- Necessary clearances.
- Motion envelopes where appropriate.
- Material boundaries.
- Design identity.

**Interfaces are established before dependent geometry is created.**

Later components must be designed against already accepted geometry.

Do not permit independently designed parts to contradict frozen interfaces.

### Actual geometry transfer

Whenever practical, provide the child with copies of the already accepted Blender components.

Textual specifications are supplementary to actual accepted geometry.

### Architectural corrections

A frozen interface can be reopened if it proves incorrect or impossible.

Such revisions must be controlled:

1. Identify the conflict.
2. Preserve the accepted checkpoint.
3. Correct the underlying design.
4. Update the interface contract.
5. Revalidate dependent assemblies.

Do not solve architectural errors by arbitrarily scaling or distorting components.

---

# 10. COMPONENT OWNERSHIP AND INTEGRATION

Each agent owns a complete local assembly.

A child delivers a standalone model or appropriate artifact.

The parent opens or imports it.

The parent independently checks:

- Geometry.
- Dimensions.
- Orientation.
- Interface alignment.
- Construction quality.
- Material coherence.
- Detail level.
- Compatibility.
- Motion relationships.
- Relevant clearances.

The parent may reject the deliverable even if the child reports successful QA.

Only accepted work is integrated.

Once integrated, the parent must test the combined assembly.

A component can pass local QA but fail after integration.

Local acceptance and assembly acceptance are separate requirements.

---

# 11. UNIVERSAL BLENDER QUALITY STANDARD

The following requirements apply to every Blender agent, regardless of its depth or assignment size.

## 11.1 Actual geometry

Create real, editable geometry.

Do not substitute screenshots, image planes, mockups, or rendered illusions for requested 3D components.

Use appropriate Blender tools, including `bpy`, `bmesh`, modifiers, procedural modeling, and Geometry Nodes when available.

Preserve necessary construction information.

Maintain meaningful object separation.

## 11.2 Correct scale

All geometry must be created at the appropriate physical scale.

A small fastener must not have the proportions of a structural bracket.

A fine surface feature must not be enlarged merely to make it visible in a render.

Do not introduce arbitrary scale changes to conceal mismatched interfaces.

## 11.3 Primary form quality

Every component must have a deliberate primary form.

Its silhouette and proportions must remain convincing before fine detailing.

Use neutral materials to verify the shape.

## 11.4 Surface continuity

Inspect important surfaces for:

- Pinching.
- Accidental dents.
- Poor curvature.
- Broken highlights.
- Incorrect shading.
- Inconsistent bevels.
- Bad normals.
- Boolean scars.
- Unintended self-intersections.

Correct source geometry rather than hiding these issues with materials.

## 11.5 Physical construction

Components must possess believable:

- Thickness.
- Mechanical supports.
- Attachment methods.
- Mounting interfaces.
- Material boundaries.
- Functional clearances.
- Manufacturing logic.

Do not create floating decorative objects.

## 11.6 Material correctness

Different materials must respond differently under identical illumination.

Use physically plausible:

- Base color.
- Reflectance.
- Roughness.
- Metallic response.
- Transmission where applicable.
- Appropriate surface microstructure.

Avoid uniform plastic-like shading.

---

# 12. EXTREME DETAIL FIDELITY — MANDATORY GLOBAL STANDARD

**THIS SECTION IS A CORE QUALITY REQUIREMENT FOR EVERY AGENT AND EVERY DESCENDANT.**

The expected detail level is substantially beyond a conventional clean concept model.

The target is a highly convincing, real-world-quality hero asset that remains credible when the camera is moved extremely close to the object.

An apparently finished object with only clean primary geometry and a few large secondary details is not sufficient.

Every important component must be developed at multiple distinct spatial scales.

### Detail Level A — Primary form

This establishes the recognizable shape, proportions, volume, and functional identity.

The component must look correct from a normal viewing distance.

### Detail Level B — Structural and secondary form

This establishes how the component is actually constructed.

It includes meaningful internal and external geometry, material boundaries, supports, mechanical relationships, and manufactured part divisions.

The result must feel assembled rather than abstractly sculpted.

### Detail Level C — Fine manufacturing geometry

This establishes the detail visible during close inspection.

Develop the small-scale features and transitions that arise naturally from the component's manufacturing method, material, assembly process, and intended function.

These features must be actual geometric structures wherever they have meaningful silhouette, depth, contact, or specular effects at the intended inspection scale.

They must not be replaced by generic noise.

### Detail Level D — Microgeometry

This is a mandatory, independent refinement pass.

Inspect surfaces at a substantially closer scale than ordinary asset presentation.

Determine what fine-scale physical characteristics are naturally expected from:

- The material.
- The manufacturing process.
- The shape.
- The mechanical function.
- The way the component is handled.
- Its operating environment.

Create appropriate fine-scale geometry where real geometric depth or silhouette matters.

Use suitable surface textures, normal maps, bump maps, or procedural shading where those methods better represent genuinely subvisual surface phenomena.

**Do not omit the microgeometry pass merely because the object looks complete at normal camera distance.**

### Detail Level E — Authentic surface history

The final component must show restrained physical evidence of having been manufactured, assembled, handled, and, where appropriate, used.

Real products are not uniformly perfect.

Their surface characteristics vary naturally with manufacturing, contact, exposure, load, heat, friction, cleaning, and maintenance.

Develop subtle, physically motivated surface variation.

Do not use indiscriminate scratches, random dents, or uniform dirt as a shortcut.

The objective is exceptionally high physical credibility, not artificial distressing.

---

# 13. MICRODETAIL ACCEPTANCE IS NOT OPTIONAL

At every applicable level of the hierarchy, a parent must explicitly inspect whether a child has achieved the intended fine-detail standard.

A component must not be accepted solely because:

- Its primary silhouette looks correct.
- Its overall material is attractive.
- It contains many objects.
- It includes some visible fasteners.
- Its hero render looks clean.
- The child reports that detail is complete.

The parent must ask:

1. What does this surface look like at extreme close-up?
2. Are the fine-scale characteristics appropriate to the manufacturing process?
3. Does the material contain believable structure?
4. Are there realistic transitions between different physical surfaces?
5. Does the object retain convincing geometry when viewed obliquely?
6. Are the small features meaningfully attached or physically embedded?
7. Is the wear or manufacturing variation natural rather than random?
8. Are microfeatures appropriate to the object's real scale?
9. Does the result still look convincing without flattering cinematic lighting?
10. Are there visible areas that remain unnaturally plain or procedurally generic?

**If an important hero-visible component lacks appropriate fine-scale craftsmanship, its acceptance status must be FAIL or PASS_WITH_LIMITATIONS, not full PASS.**

Request targeted refinement before integration.

---

# 14. MICRODETAIL MUST BE DESIGNED, NOT RANDOMLY GENERATED

Do not add arbitrary decorative features to satisfy the microdetail requirement.

Instead, determine the appropriate detail from the physical identity of the object.

A machined metallic surface, molded polymer surface, rubber surface, coated surface, and textile surface do not possess the same fine-scale characteristics.

Their surface detail must differ.

### Requirements

- Detail must be scale-correct.
- Detail must be material-specific.
- Detail must be manufacturing-specific.
- Detail must be spatially coherent.
- Detail must respond appropriately to lighting.
- Detail must remain consistent across neighboring components.
- Detail must not introduce obvious tiling or repeated patterns.
- Detail must not damage important primary forms.
- Detail must not create false mechanical interactions.
- Detail must not be merely decorative noise.

The goal is **credible physical richness**.

Do not produce artificially rough surfaces just to demonstrate that detail exists.

A premium object can retain clean, polished areas while still containing substantial authentic fine-scale complexity.

---

# 15. MACRO INSPECTION PROTOCOL

For every hero-visible component, perform a dedicated macro-inspection pass.

Use appropriate camera framing to reveal the actual geometric and material detail.

Inspect at several scales when useful:

- Full component.
- Functional subassembly.
- Close-up.
- Extreme macro.

The macro inspection must reveal:

- Material-specific surface behavior.
- Real geometric transitions.
- Edge quality.
- Small component construction.
- Manufacturing character.
- Localized surface variation.
- Any defects caused by procedural modeling.

Use neutral lighting in addition to cinematic lighting.

### Required review loop

1. Render the component close-up.
2. Open and inspect the image.
3. Identify overly simple regions.
4. Identify missing physical detail.
5. Identify incorrect or artificial surface patterns.
6. Identify exaggerated detail.
7. Correct the actual model or material.
8. Rerender from the same camera.
9. Compare before and after.
10. Record the outcome.

Do not use strong bloom or depth of field to hide fine-detail shortcomings.

Do not claim a macro inspection was performed unless the render was actually examined.

---

# 16. DETAIL DISTRIBUTION

High detail must exist where it provides the greatest physical credibility.

Prioritize:

- Hero-visible surfaces.
- Important mechanical interfaces.
- Material transitions.
- Frequently inspected components.
- Functional connection points.
- Areas with strong specular reflections.
- Areas where geometry is exposed through openings.
- Areas that visibly explain manufacturing or assembly.

Do not over-detail completely invisible geometry at the expense of hero-visible components.

However, if the task explicitly requires an internal mechanical assembly or technical cutaway, those internal components are hero-visible for that task and must receive appropriate detail.

### Frequency separation

Maintain a clear visual hierarchy:

- Large forms determine identity.
- Medium forms explain construction.
- Small forms provide craftsmanship.
- Microdetails create material credibility.

Microdetails must not overpower the primary shape.

The asset should read clearly both from a distance and under extreme magnification.

---

# 17. REPRESENTATIVE COMPONENT FIRST

Before generating many repeated features, create one representative master.

Inspect it at the actual required quality level.

Verify:

- Geometry.
- Proportions.
- Manufacturing detail.
- Surface quality.
- Material response.
- Fit.
- Microdetail.
- Scale.

Correct all significant defects before replication.

Apply this principle to any repeated structure.

Do not create hundreds of low-quality repeated objects and expect quantity to compensate for their deficiencies.

---

# 18. REALISM AND NON-STERILE SURFACES

The target is not damaged or abandoned equipment.

The target is physically believable equipment.

Objects may be expensive, new, highly maintained, or lightly used depending on the task.

Even pristine manufactured products should not look like mathematically perfect shader demonstrations.

Material response must account for realistic fine-scale structure.

Introduce controlled physical irregularity where justified.

Avoid:

- Uniform roughness.
- Uniform procedural noise.
- Repeated identical imperfections.
- Excessive distressing.
- Random scratches.
- Artificial dirt.
- Overly perfect plastic surfaces.
- Unrealistically sharp or infinitely thin geometry.

Realistic imperfections must never be used as an excuse for poor topology or inaccurate assembly.

---

# 19. LOCAL PRODUCTION STAGES

For substantial modeling tasks, each agent should organize work into the following stages:

1. Understand the task.
2. Establish dimensions and interfaces.
3. Establish design identity.
4. Create initial blockout.
5. Validate primary form.
6. Create detailed primary geometry.
7. Create secondary mechanical geometry.
8. Integrate accepted child components.
9. Validate assembly.
10. Create fine manufacturing geometry.
11. Execute dedicated microgeometry pass.
12. Develop physical materials.
13. Add restrained authentic imperfections.
14. Perform macro inspection.
15. Perform mechanical and geometric QA.
16. Correct detected defects.
17. Perform final visual QA.
18. Save and deliver the verified result.

Simpler tasks may combine stages, but they must not silently omit applicable quality requirements.

A small component may require fewer structural stages but still needs appropriate fine-scale fidelity.

---

# 20. CHILD DELIVERABLE CONTRACT

Every child must return a real usable artifact.

For Blender tasks, this normally includes:

- Independent final `.blend`.
- Relevant construction scripts where used.
- Component manifest.
- Dimensions and coordinate information.
- Attachment interfaces.
- Relevant material dependencies.
- Neutral inspection renders.
- Macro inspection evidence for hero-visible components.
- Geometry and fit QA.
- Known limitations.
- Integration instructions.

The child must report what was actually created.

Do not fabricate files, renders, verification, or agent activity.

---

# 21. PARENT REVIEW AND REJECTION

A child's deliverable is a submission, not an automatic success.

The parent must:

1. Verify the delivered files.
2. Inspect the actual geometry.
3. Inspect dimensions and interfaces.
4. Check mechanical correctness.
5. Check visual design identity.
6. Inspect primary surfaces.
7. Inspect secondary detail.
8. Inspect microgeometry.
9. Inspect material realism.
10. Inspect available renders.
11. Perform relevant integration tests.
12. Accept or reject the result.

A component can fail because it is visually underdeveloped even when its dimensions are correct.

A component can fail because its microdetail is missing even when its overall render looks attractive.

A component can fail because it is beautiful but mechanically incompatible.

### Revision requests

When rejecting work, identify:

- Actual defect.
- Affected component.
- Expected result.
- Relevant quality standard.
- Required correction.
- Required inspection evidence.

Do not use vague feedback such as "add more detail."

Instead, identify the missing scale or type of craftsmanship and the surfaces that require refinement.

The child must revise its own independent project.

The parent must reinspect the revised deliverable.

After repeated unsuccessful revisions, reconsider the component's design, interface contract, or production method.

Do not loop indefinitely without making substantive progress.

---

# 22. PARENT INTEGRATION PROCEDURE

After accepting a child artifact:

1. Save a parent checkpoint.
2. Verify the accepted artifact.
3. Import it into the parent's project.
4. Align shared datums.
5. Check mating dimensions.
6. Check component clearances.
7. Check materials and visual consistency.
8. Check important close-up interfaces.
9. Check motion relationships where applicable.
10. Run assembly-level QA.
11. Correct integration defects.
12. Save the integrated assembly.
13. Close the child assignment.

Only then may the parent launch another direct child.

---

# 23. COLLISION AND CONTACT POLICY

For mechanical Blender assemblies, classify interactions as:

- INTENDED_CONTACT
- MECHANICAL_FIT
- INTENDED_ENGAGEMENT
- REQUIRED_CLEARANCE
- FORBIDDEN_INTERSECTION
- FALSE_POSITIVE
- UNVERIFIED

Not every overlapping mesh pair is a collision defect.

Use suitable geometry inspection techniques, including Blender Python and broad/narrow-phase tests where appropriate.

Evaluate actual geometry and transforms.

Inspect intentional mating contacts.

Avoid ignoring entire systems.

### Motion

If parts move, distinguish rotating and stationary components.

Define meaningful pivots.

Sample representative motion states.

Check for interference and mechanical disconnection.

Do not claim continuous mechanical correctness solely from a few attractive animation frames.

---

# 24. QA EVIDENCE

Every critical quality test must have:

- Test identifier.
- Subsystem.
- Expected result.
- Actual result.
- Inspection or measurement method.
- Saved evidence.
- Status.

Allowed statuses:

- PASS
- PASS_WITH_LIMITATIONS
- FAIL
- NOT_VERIFIED

A PASS requires real evidence.

Do not mark an unperformed test as successful.

A component that fails macro inspection cannot receive an unconditional hero-quality PASS.

A component that fails a critical mechanical interface cannot receive full assembly acceptance.

---

# 25. REPRODUCIBLE VISUAL REVIEW

Create relevant visual evidence.

Appropriate inspection methods include:

- Neutral clay.
- Orthographic views.
- Three-quarter views.
- Reflection-line inspection.
- Macro views.
- Extreme macro.
- Material comparison.
- Exploded assembly.
- Section views.
- Motion states.

Use identical camera, lighting, exposure, and relevant render settings when comparing before/after results.

Inspect generated images using available tools.

If inspection tools are unavailable, report the limitation.

Do not fabricate visual observations.

---

# 26. CHECKPOINTS AND RECOVERY

Save recoverable checkpoints after important milestones.

Preserve:

- Initial project.
- Accepted design.
- Accepted main geometry.
- Child integration stages.
- Fine-detail stage.
- Material stage.
- QA stage.
- Final artifact.

Do not overwrite the only valid version.

If a modification damages accepted geometry, revert and repair selectively.

If an interface changes, revalidate dependent components.

---

# 27. RESOURCE DISCIPLINE

Use delegation and detail wisely.

Avoid wasteful agent spawning for trivial work.

Avoid spending time on meaningless geometry.

However, do not prematurely stop at medium detail when the task requires extreme close-up fidelity.

The intended quality target is more important than minimizing object count or producing the fastest possible superficial result.

Balance effort according to:

- Importance.
- Complexity.
- Visibility.
- Physical plausibility.
- Expected quality improvement.
- Integration risk.

Do not replace craftsmanship with verbosity in reports.

Actual modeled work is the primary output.

---

# 28. AUTOMATIC CONTEXT INHERITANCE

Every child must receive:

1. This complete master protocol.
2. An automatically generated unique agent identifier.
3. Parent identifier.
4. Current recursion depth.
5. Maximum recursion depth.
6. Assigned independent workspace.
7. Actual accessible tools.
8. Relevant accepted upstream artifacts.
9. Frozen interfaces.
10. Inherited design identity.
11. Exact child task.
12. Acceptance criteria.

No user input is required for these internal fields.

Do not ask the user to manually assemble child prompts.

Every descendant inherits the same extreme-detail standard.

Children are not allowed to weaken the quality requirements simply because their assignment is small.

---

# 29. FINAL ACCEPTANCE

An agent may declare local completion only when:

- The assigned artifact exists.
- The artifact is independently saved.
- Its geometry or content is actually present.
- Required components are included.
- Interfaces are satisfied.
- Accepted children have been integrated.
- Primary form quality is verified.
- Applicable fine-detail and microdetail requirements are met or explicitly reported as incomplete.
- Materials are appropriate.
- Mechanical behavior is checked where relevant.
- Significant defects are corrected or disclosed.
- Inspection evidence exists.
- The parent can actually use the deliverable.

The root agent additionally verifies the complete integrated artifact.

Do not declare a result exceptional merely because it contains many components.

The actual geometry and visual evidence must justify the quality claim.

---

# 30. FINAL OPERATING DIRECTIVE

Execute the following task autonomously under this complete protocol.

Create independent projects recursively.

Delegate only where useful.

Maintain no more than one active direct child per agent.

Use actual accepted upstream artifacts for dependency-aware construction.

Inspect every child deliverable.

Reject insufficient quality.

Require genuine close-up and microdetail fidelity.

Integrate only accepted work.

Validate each assembly.

Preserve checkpoints.

Deliver the complete, highest-quality verifiable result.

**The governing quality principle is: every important component must remain physically convincing when examined far more closely than a conventional concept render.**

Do not stop at clean geometry.

Do not stop at secondary detail.

Do not stop at attractive materials.

Develop the fine-scale manufacturing character, microgeometry, and authentic surface variation that make the object feel real.

**End of shared master protocol. Apply it to the separate task specification immediately following this document.**

# PROJECT NEON — NIGHTFALL VESPER R-02 REFORGED
## Complete Ultra-High-Fidelity Cyberpunk Hypercar
### Recursive Automotive Hero Asset Production Specification — Version 1.0
**Project:** PROJECT NEON
**Vehicle:** NIGHTFALL VESPER R-02 REFORGED
**Asset:** Complete original high-performance road vehicle
**Production environment:** Blender via Blender MCP
**Primary production protocol:** The preceding Recursive Divide & Conquer Master Protocol
**Required agent model:** GPT-6.2 Sol
**Required reasoning effort:** High
**Delegation:** Recursive, with one active direct child per agent and maximum depth inherited from the master protocol
**Reference policy:** No web browsing, external images, blueprints, imported third-party geometry, or unauthorized project inspection
**Current deliverable:** A complete editable Blender vehicle master at maximum practical visual fidelity
**Not required yet:** Unreal Engine integration, game-engine optimization, LOD generation, or FBX game export
---
# 1. CORE OBJECTIVE
Create a complete, exceptionally detailed, visually distinctive, physically plausible fictional cyberpunk hypercar.
The result must represent a substantial advancement over the original NIGHTFALL VESPER R-02 model.
This is a full vehicle production project, not a vehicle concept exercise.
Every major subsystem must be genuinely constructed, assembled, inspected, refined, and integrated.
The overall quality target is an exceptionally strong automotive hero asset comparable in visual ambition and component craftsmanship to vehicles featured in high-budget contemporary games.
Do not interpret this target as permission to imitate any existing fictional or real-world car.
Create an original vehicle with its own design identity.
The model must satisfy two distinct objectives:
**Objective A: Overall automotive excellence**
The complete vehicle must possess outstanding proportions, sophisticated body surfacing, coherent engineering, convincing construction, and strong artistic identity.
**Objective B: Extreme component fidelity**
Important individual components must possess the fine-scale geometry, manufacturing character, mechanical interfaces, and material realism demonstrated by the independently produced NIGHTFALL front-wheel experiment.
The vehicle must succeed at both scales.
A highly detailed wheel mounted on a crude body is not acceptable.
A beautiful body containing simplistic placeholder components is not acceptable.
A mechanically complicated car with weak design is not acceptable.
---
# 2. USE THE RECURSIVE MASTER PROTOCOL
This task must be executed according to the complete master protocol supplied immediately before this specification.
In particular:
- Every agent owns an independent project.
- Every agent may have at most one active direct child.
- An agent may create multiple children sequentially.
- Children may create descendants until the maximum depth.
- The parent creates each child's workspace.
- The parent provides fixed interfaces and existing accepted geometry.
- Every child returns actual Blender artifacts.
- The parent independently inspects and accepts or rejects them.
- The parent integrates accepted work into its own assembly.
- Integration requires independent verification.
- Only after integration may the parent proceed to another child.
Do not create unrelated component models simultaneously and attempt to force them together later.
Design each dependent component around the accepted geometry and interfaces that already exist.
The root agent remains responsible for the entire vehicle.
### Model configuration
Every child and descendant must be explicitly requested as **GPT-6.2 Sol with High reasoning effort** where the spawning interface supports these settings.
If exact configuration cannot be controlled or verified, document that limitation accurately.
Do not silently substitute another model.
### User interaction
Do not ask the user to manage folders, agents, prompts, or checkpoints.
Make internal production decisions autonomously.
---
# 3. PROJECT ISOLATION
Create a new independent production project.
Do not overwrite the original VESPER R-02 Blender master.
Do not modify the previously completed wheel experiment.
All new components must be produced in independent agent workspaces within the new project hierarchy.
The root owns the final vehicle master.
Each child owns only its own component project.
### Previous high-detail wheel
The previously completed NIGHTFALL VESPER R-02 front-left wheel assembly is the visual quality benchmark for this project.
If its finished `.blend` is available through the authorized PROJECT NEON working context, the root may use a read-only copy of the completed wheel as a starting production asset.
Never modify the source file.
If the previously accepted wheel cannot be located or imported safely, do not search unrelated directories or invent its existence.
Instead, reproduce a compatible wheel assembly under the new recursive production hierarchy, using the established dimensional and quality requirements.
Document whether the existing wheel was reused or reconstructed.
The entire vehicle must follow the same component-detail standard.
---
# 4. ART DIRECTION
## 4.1 Vehicle identity
The NIGHTFALL VESPER R-02 REFORGED is a fictional two-seat, rear-mid-engine, twin-turbocharged V12 hyper-GT designed for an advanced cyberpunk megacity.
It must be:
- Low.
- Wide.
- Aggressive.
- Premium.
- Mechanically plausible.
- Technically sophisticated.
- Visually memorable.
- Constructed from believable materials.
- Clearly intended to be driven on roads.
This is not a spaceship.
This is not an armored military vehicle.
This is not a generic smooth electric concept.
This is not a random assortment of angular sci-fi geometry.
It should feel like an expensive, manufactured automobile designed by an exceptionally talented fictional automotive company.
## 4.2 Mandatory design signatures
The finished vehicle must possess five distinct visual signatures.
### A. Predatory wedge nose
A low, sculpted front end with powerful fender shoulders, a controlled central hood valley, deep optical housings, and layered front aerodynamic structures.
The nose must be recognizable from a low frontal view.
Do not use a generic rounded supercar front.
### B. Deep structural side-air corridor
The side must feature a large genuine negative-space channel ahead of the rear wheels.
It must be three-dimensional and mechanically integrated.
The channel must have:
- Outer body surfaces.
- Structural bridges.
- Internal duct walls.
- Functional-looking air routing.
- Mechanical supports.
- A plausible cooling or induction destination.
Do not substitute black decorative cavities.
### C. Forward-set cockpit canopy
Use a low, distinctive greenhouse with a strongly inclined windshield, narrow roof, purposeful structural pillars, and visibly engineered glazing.
The cabin should appear closely integrated with the carbon-composite central occupant cell.
### D. Dramatic rear architecture
Design a deep, layered rear featuring:
- Powerful rear shoulders.
- Distinctive recessed lighting.
- Mechanical extraction apertures.
- Triple titanium exhaust.
- Large functional-looking diffuser.
- Active rear wing.
- Visible underlying structural relationships.
### E. Exposed precision engineering
Selected components must be visible through intentional openings:
- Wheel and brake hardware.
- Engine-bay components.
- Suspension details where appropriate.
- Aerodynamic supports.
- Light-module internals.
- Carbon-composite structural regions.
The result must look engineered rather than decorated.
---
# 5. VEHICLE DIMENSIONS
Use metric units.
Nominal dimensional targets:
| Parameter | Target |
|---|---|
| Length | 4,783 mm |
| Body width excluding mirrors | 2,078 mm |
| Height excluding deployed wing | 1,189 mm |
| Wheelbase | 2,840 mm |
| Front tire | 275/35 ZR20 |
| Rear tire | 335/30 ZR21 |
| Front brake disc | 390 mm |
| Rear brake disc | 410 mm |
| Seats | 2 |
| Engine | Rear-mid-mounted 60° V12 |
| Induction | Twin turbocharged |
| Transmission | Rear transaxle |
| Driven wheels | Rear |
| Front suspension | Double wishbone, pushrod |
| Rear suspension | Double wishbone, pushrod |
| Doors | Dihedral |
| Rear wing | Active |
These define the intended architecture.
Any deviations must be justified by actual packaging requirements.
Do not silently change wheelbase, tire size, or major interfaces to make independently built parts fit.
### Vehicle coordinate system
- +X = forward.
- -X = rearward.
- +Y = vehicle left.
- -Y = vehicle right.
- +Z = upward.
- Z = 0 = ground plane.
Front axle nominal X = +1.420 m.
Rear axle nominal X = -1.420 m.
Create explicit datums for:
- Vehicle center.
- Axle centers.
- Wheel centers.
- Front and rear chassis interfaces.
- Cabin and seats.
- Engine crankshaft centerline.
- Transmission outputs.
- Suspension hardpoints.
- Door hinges.
- Wing pivots.
- Major cooling components.
All delegated subsystems must use the same authoritative coordinate system.
---
# 6. MANDATORY ENGINEERING PACKAGING
Before detailed exterior construction, create a three-dimensional packaging model.
Reserve appropriate volume for:
- Two occupants.
- Seats.
- Pedal box.
- Steering column.
- Dashboard.
- Door entry paths.
- Central structural tub.
- Front suspension.
- Rear suspension.
- Wheel steering and travel envelopes.
- Radiators.
- Cooling ducts.
- V12 engine.
- Turbochargers.
- Intake plenums.
- Exhaust manifolds.
- Gearbox.
- Differential.
- Driveshafts.
- Fuel storage.
- Oil reservoir and plumbing.
- Battery and electronics.
- Exhaust and heat shielding.
- Active aero mechanism.
Do not finish exterior surfaces before establishing whether the internal systems can actually fit.
A design must not be accepted if its required mechanical packaging is impossible.
The parent must communicate packaging volumes to dependent children.
---
# 7. DESIGN EXPLORATION AND SELECTION
Before fully modeling the body, create three distinct original gray-material design studies.
Each should share the required five signatures but explore different surface character and proportions within the approved envelope.
Evaluate:
- Front identity.
- Rear identity.
- Side silhouette.
- Cockpit proportions.
- Side-air corridor.
- Wheel placement.
- Surface tension.
- Mechanical packaging.
- Overall artistic coherence.
Use identical neutral lighting and cameras.
Select the strongest design.
If all studies appear generic or weak, revise them.
Do not select a design merely because it is easiest to model.
### Absolute visual gate
**Do not proceed to detailed component production while the main vehicle silhouette remains visually ordinary.**
The gray model must already be compelling.
---
# 8. PRIMARY BODY SURFACING
The primary exterior surfaces require the highest artistic discipline.
Build actual, editable geometry for:
- Hood.
- Front fascia.
- Front fenders.
- Front bumper.
- Side body.
- Doors.
- Side sills.
- Roof.
- Greenhouse surrounds.
- Rear quarters.
- Rear deck.
- Rear fascia.
- Rear bumper.
- Major aerodynamic panels.
### Required quality
- Smooth curvature progression.
- Controlled highlight flow.
- Clean surface transitions.
- Appropriate panel thickness.
- Consistent design language.
- Real physical depth.
- Well-defined manufacturing seams.
- No accidental dents.
- No pinched topology.
- No unexplained waviness.
- No excessive subdivision hiding poor geometry.
### Reflection-based inspection
Use narrow strip lights and neutral materials.
Inspect the hood, doors, roof, fenders, and rear shoulders from grazing angles.
A reflected highlight should vary smoothly according to the intended curvature.
If the highlight bends unexpectedly, locate the source in the geometry and repair it.
Do not claim the surface is correct merely because it looks attractive under nighttime lighting.
### Special warning: door surfaces
The earlier VESPER model had excessively concave, dented-looking door panels.
The new body must not reproduce that defect.
The deep side-air corridor must remain a distinct functional channel.
The door itself must have controlled automotive surfacing.
Do not confuse a deliberate air intake with an accidental body-panel depression.
---
# 9. BODY PANEL CONSTRUCTION
Every important body panel must have plausible manufactured construction.
Create appropriate:
- Panel thickness.
- Mounting flanges.
- Internal lips.
- Supporting brackets.
- Seams.
- Fasteners.
- Seals.
- Interface edges.
- Service access.
Nominal exterior shut lines should usually be approximately 3–5 mm, with purposeful variation where justified.
Avoid fake painted-on seams.
Avoid paper-thin exposed edges.
Avoid floating panels.
Do not randomly distribute exterior screws.
Visible attachment hardware must have a real structural explanation.
---
# 10. FULL EXTERIOR SUBSYSTEMS
The root agent must ensure complete production and acceptance of the following exterior subsystems.
## 10.1 Front fascia
Build:
- Deep headlamp assemblies.
- Intake structures.
- Layered front splitter.
- Cooling ducts.
- Grille or mesh structures.
- Air-management surfaces.
- Optical mounts.
- Selected technical hardware.
The front must survive macro inspection.
## 10.2 Side aero
Build:
- Deep side-air corridors.
- Structural bridges.
- Inner ducts.
- Intake vanes or mesh where appropriate.
- Mounting interfaces.
- Thermal protection where needed.
## 10.3 Rear assembly
Build:
- Rear fascia.
- Deep lighting system.
- Engine-bay vents.
- Rear diffuser.
- Diffuser strakes.
- Triple exhaust.
- Active wing.
- Support brackets.
## 10.4 Glazing
Build:
- Windshield.
- Side glazing.
- Rear glazing.
- Seals.
- Mounting surfaces.
- Trim.
- Real thickness.
Glass must not look like an almost invisible shader placed across empty holes.
## 10.5 Exterior microgeometry
All major exterior components must include appropriate manufacturing-scale detail.
Do not finish at the level of smooth, attractive large surfaces.
However, preserve proper visual hierarchy.
Microgeometry must strengthen realism, not overwhelm the silhouette.
---
# 11. HEADLIGHT AND TAILLIGHT HERO ASSEMBLIES
The lighting systems must be produced as independently inspectable hero components.
A headlamp is not a glowing strip.
Required structures may include:
- Transparent outer lens.
- Lens edge and gasket.
- Optical carriers.
- Internal emitters.
- Reflectors.
- Projector structures.
- Secondary light guides.
- Retention hardware.
- Mounting tabs.
- Rear housing.
- Wiring interfaces.
- Ventilation or service elements where appropriate.
Tail lamps require comparable construction quality.
### Acceptance
Render lighting modules:
1. Installed.
2. Isolated.
3. Neutral and unlit.
4. Illuminated.
5. Extreme close-up.
The module must look physically constructed even when the emissive material is disabled.
---
# 12. WHEELS AND TIRES
The previously completed high-detail NIGHTFALL wheel establishes the minimum expected component craftsmanship.
The full vehicle requires four compatible wheel assemblies.
### Front
- 275/35 ZR20.
- 390 mm brake rotor.
- Strong original forged wheel.
- Detailed hub and center-lock.
- Realistic tire.
- Fixed brake caliper.
### Rear
- 335/30 ZR21.
- 410 mm brake rotor.
- Correct larger rim and tire.
- Compatible design identity.
- Detailed hub and rear drive interface.
- Fixed brake caliper.
The rear wheel must not be a uniformly scaled copy of the front assembly.
Redesign its proportions and required interfaces appropriately.
### Detail standard
Match or exceed the accepted front-wheel benchmark in:
- Forged geometry.
- Tire construction.
- Manufacturing detail.
- Brake design.
- Hub and retention mechanisms.
- Material response.
- Realism.
- Macro quality.
Do not replace accepted high-fidelity geometry with a simpler alternative.
---
# 13. FRONT SUSPENSION AND STEERING
Build a coherent double-wishbone pushrod front suspension.
Include:
- Upper and lower wishbones.
- Uprights.
- Wheel hubs.
- Steering links.
- Tie rods.
- Pushrods.
- Rockers.
- Spring-damper assemblies.
- Mounting brackets.
- Ball-joint interfaces.
- Selected bearings.
- Fasteners.
- Brake-line routing.
Define actual pivot locations.
Avoid suspension components passing through one another.
### Motion validation
Test a matrix of steering and suspension travel states.
At minimum include:
- Straight ahead.
- Moderate left lock.
- Full left lock.
- Moderate right lock.
- Full right lock.
- Representative compression.
- Representative extension.
Combine motion states to check interaction.
Verify:
- Tire-to-arch clearance.
- Tire-to-liner clearance.
- Tire-to-suspension clearance.
- Steering-link movement.
- Brake-line routing.
- Pushrod and rocker articulation.
If full kinematics cannot be validated, document the specific limitation.
---
# 14. REAR SUSPENSION AND DRIVELINE
Build a physically plausible rear suspension assembly compatible with the rear-mid-mounted V12.
Include:
- Upper and lower wishbones.
- Uprights.
- Rear hubs.
- Pushrods.
- Rockers.
- Dampers.
- Structural mounts.
- Half-shafts.
- CV joints.
- Brake-line routing.
- Differential interfaces.
The rear driveline must connect the transaxle to the rear wheel hubs.
Do not leave decorative disconnected shafts.
Check packaging against:
- Engine.
- Turbochargers.
- Transmission.
- Exhaust.
- Rear diffuser.
- Rear tires.
---
# 15. CHASSIS AND STRUCTURE
Build a believable chassis.
Recommended architecture:
- Carbon-composite occupant cell.
- Front structural subframe.
- Rear engine subframe.
- Structural floor.
- Side sill reinforcements.
- Firewall.
- Suspension hardpoint structures.
- Engine and gearbox mounting regions.
- Appropriate service interfaces.
The chassis must explain where the vehicle's mechanical components are attached.
Do not construct a hollow painted shell with disconnected mechanical parts.
The chassis should remain inspectable with the exterior body hidden.
---
# 16. V12 ENGINE
Build a detailed rear-mid-mounted, longitudinal 60-degree twin-turbo V12.
Nominal specifications:
- Twelve cylinders.
- Approximately 5.97 L displacement.
- 89 mm bore.
- 80 mm stroke.
- 60-degree bank angle.
- Dual overhead camshafts per bank.
- Four valves per cylinder.
- Twin turbochargers.
- Dry-sump lubrication.
The engine must be a genuine multi-component 3D assembly.
### Required components
- Engine block.
- Crankcase.
- Cylinder heads.
- Cylinder-head covers.
- Crankshaft.
- Twelve pistons.
- Twelve connecting rods.
- Wrist pins.
- Counterweights.
- Bearing structures.
- Four camshafts.
- Valvetrain representation.
- Timing drive.
- Intake plenums.
- Fuel and ignition interfaces.
- Two turbochargers.
- Exhaust manifolds.
- Charge-air routing.
- Cooling system connections.
- Lubrication fittings.
- Engine mounts.
- Transmission interface.
- Fasteners and service elements.
### Integration requirement
The engine must fit inside the actual accepted engine-bay envelope.
Do not independently build an oversized engine and then distort the rear body to contain it.
Define engine and transaxle interfaces before detailed production.
### Internal motion
Where possible, implement a nondestructive mechanical demonstration spanning 720 degrees of crankshaft rotation.
Check:
- Crankshaft motion.
- Piston displacement.
- Connecting-rod movement.
- Camshaft speed relationship.
- Internal clearance.
Do not claim complete combustion-cycle correctness without verifying valve and phase relationships.
---
# 17. TURBOCHARGERS, EXHAUST, AND COOLING
These are separate high-detail subsystems with their own acceptance requirements.
## Turbochargers
Each turbocharger should contain coherent:
- Compressor housing.
- Turbine housing.
- Center housing.
- Mechanical connections.
- Actuator.
- Intake and outlet interfaces.
- Oil and cooling interfaces where appropriate.
- Mounting hardware.
- Heat shielding.
## Exhaust
Create continuous routing from the cylinder heads to the rear triple outlets.
Include believable:
- Manifolds.
- Flanges.
- Pipe transitions.
- Clamps.
- Supports.
- Heat shielding.
- Exhaust outlets.
- Appropriate thermal material variation.
## Cooling
Provide believable:
- Cooling inlets.
- Ducts.
- Radiators or charge coolers.
- Fluid connections.
- Air exits.
- Mounting structures.
An exterior opening must not terminate in an unexplained empty cavity.
---
# 18. TRANSMISSION AND REAR DRIVE SYSTEM
Build a coherent rear transaxle architecture.
Include:
- Bellhousing.
- Gearbox casing.
- Structural ribs.
- Differential housing.
- Output flanges.
- Rear drive connections.
- Mounting points.
- Service ports.
- Fasteners.
- Sensor and lubrication interfaces.
The gearbox must fit between the engine and rear driveline.
Do not make the engine, gearbox, and driveshafts visually independent objects without actual connection logic.
---
# 19. DIHEDRAL DOORS
Create two mechanically articulated dihedral doors.
Each door requires:
- Outer skin.
- Inner structure.
- Window glass.
- Seal system.
- Hinge mechanism.
- Mechanical reinforcement.
- Latch.
- Striker.
- Appropriate assisted-opening mechanism.
- Wiring interfaces.
- Interior door card.
- Visible trim and hardware.
The opening must be physically plausible.
Test closed, intermediate, and fully open states.
Check door clearance against:
- Front fenders.
- Roof.
- Windshield surrounds.
- Side sills.
- Mirrors or camera units.
- Interior trim.
- Adjacent bodywork.
Do not represent the door as one solid slab rotating around an arbitrary pivot.
---
# 20. ACTIVE REAR WING
Build a detailed active aerodynamic mechanism.
Include:
- Wing blade.
- Supports.
- Pivot interfaces.
- Linkages or actuators.
- Mounting brackets.
- Retention hardware.
- Service connections.
- Stowage geometry where relevant.
Validate:
- Stowed.
- Partially deployed.
- Fully deployed.
The wing must not intersect the rear deck.
The support mechanism must move consistently with the wing.
Do not animate the visible blade independently of its mechanical supports.
---
# 21. FULL PREMIUM COCKPIT
The cabin must match the exterior in quality.
Build:
- Driver seat.
- Passenger seat.
- Seat structures.
- Seat cushions.
- Seat mounts.
- Dashboard.
- Steering wheel.
- Steering column.
- Driver display.
- Central display.
- Center console.
- Switchgear.
- Pedal box.
- Footwell.
- Door cards.
- Interior trim.
- Safety belts.
- Appropriate cabin lighting.
The cockpit must feel usable and mechanically constructed.
Avoid generic floating screens.
Avoid placeholder seats.
Avoid a simplified circular steering wheel.
---
# 22. INTERIOR HERO COMPONENTS
Each major cabin component must survive close-up inspection independently.
### Steering wheel
Build:
- Sculpted grip.
- Structural spokes.
- Central hub.
- Retention geometry.
- Controls.
- Switchgear.
- Material transitions.
- Surface seams.
- Appropriate grip detail.
### Seats
Build:
- Structural shell.
- Cushions.
- Bolsters.
- Upholstery.
- Stitching or seam geometry.
- Mounts.
- Belt interfaces.
- Appropriate adjustment details.
### Dashboard
Build:
- Main structure.
- Instrument housing.
- Display interfaces.
- Ventilation openings.
- Switch assemblies.
- Trim transitions.
- Concealed attachment logic.
### Pedal box
Create physically plausible foot controls with proper mounting and usable placement.
### Door cards
Create actual layered construction, not flat materials attached to the back of doors.
---
# 23. EXTREME MICRODETAIL REQUIREMENT
The inherited master protocol's Extreme Detail Fidelity Standard applies to the entire vehicle.
This is not optional.
Every major hero-visible subsystem must be inspected at:
1. Full-object scale.
2. Component scale.
3. Close-up scale.
4. Extreme macro scale.
### Required principle
Do not stop at primary and secondary geometry.
For every important component, infer appropriate small-scale detail from:
- Its material.
- Its manufacturing process.
- Its assembly method.
- Its functional role.
- Its contact surfaces.
- Its exposure to the environment.
- Its expected usage history.
Create genuine geometric detail where the real feature has meaningful depth, silhouette, or mechanical significance.
Use surface shading for extremely fine phenomena when actual geometry would be inappropriate.
### Avoid
- Generic procedural noise.
- Uniform scratches.
- Random bolts.
- Artificially exaggerated wear.
- Missing fine structural features.
- Empty mechanical housings.
- Smooth surfaces where real manufacturing structure should exist.
### Parent acceptance
The parent must not accept a component based solely on a beautiful ordinary-distance render.
Require macro evidence.
Reject insufficient craftsmanship.
The level demonstrated in the completed NIGHTFALL wheel experiment is the expected benchmark, not an extraordinary optional achievement.
---
# 24. AUTHENTIC PHYSICAL REALISM
The finished vehicle must not look sterile.
It should resemble a real, carefully maintained, extremely expensive hypercar that has experienced limited actual road use.
Develop restrained, localized evidence of:
- Manufacturing.
- Machining.
- Assembly.
- Handling.
- Mechanical use.
- Environmental exposure.
- Cleaning and maintenance.
Appropriate material character may vary by region.
### Exterior
Premium graphite automotive paint with subtle realistic surface variation.
### Wheels
Manufactured metallic surfaces, rubber microstructure, realistic brake materials.
### Interior
Differentiate leather, Alcantara-like textile, technical plastics, carbon composite, and metal.
### Engine bay
Differentiate machined metal, cast metal, tubing, connectors, coatings, and thermally affected parts.
### Glass
Use believable thickness, transmission, reflection, tint, seals, and supporting structures.
### Important
Realistic imperfection does not mean poor geometry.
Do not deliberately create wavy body panels or mismatched shut lines.
Do not make the vehicle dirty or damaged merely to avoid a CGI appearance.
---
# 25. MATERIAL SYSTEM
Create a physically plausible, internally consistent PBR material library.
Required material families include:
- Automotive body paint.
- Clearcoat.
- Bare aluminum.
- Forged metal.
- Machined metal.
- Coated steel.
- Titanium.
- Carbon composite.
- Rubber.
- Glass.
- Lamp optics.
- Interior leather.
- Technical fabric.
- Polymer.
- Ceramic friction materials.
- Display surfaces.
- Emissive lighting.
Verify their differences under identical lighting.
Do not use one generic plastic-looking shader for multiple unrelated materials.
---
# 26. ASSEMBLY QA
Each subsystem must pass local QA before acceptance.
After integration, the parent must perform assembly-level QA.
### Contact classifications
Use:
- INTENDED_CONTACT
- MECHANICAL_FIT
- INTENDED_ENGAGEMENT
- REQUIRED_CLEARANCE
- FORBIDDEN_INTERSECTION
- FALSE_POSITIVE
- UNVERIFIED
### Geometric checks
Use evaluated Blender geometry and suitable detection methods.
Do not treat every raw BVH overlap as a forbidden collision.
Do not hide unintended intersections by exempting entire subsystems.
Check all critical interfaces.
### Dynamic checks
Validate relevant operating states for:
- Steering.
- Wheel rotation.
- Suspension travel.
- Door opening.
- Wing deployment.
- Engine kinematics where implemented.
Do not declare full mechanical correctness from a single saved pose.
---
# 27. VISUAL QUALITY GATES
These gates are mandatory.
## Gate 1 — Gray silhouette
The full car must look striking before final materials.
## Gate 2 — Automotive surfacing
Body reflections must be clean and controlled.
## Gate 3 — Exterior assembly
Panel gaps, ducts, lights, and aerodynamic structures must have physical depth.
## Gate 4 — Wheel and suspension integration
Wheel assemblies must fit the actual arches and steering envelopes.
## Gate 5 — Mechanical packaging
The engine, transmission, suspension, and exhaust must fit together coherently.
## Gate 6 — Cabin
The interior must be genuinely complete and inspectable.
## Gate 7 — Microdetail
Important individual components must pass extreme close-up inspection.
## Gate 8 — Materials
Materials must behave distinctly and realistically under controlled lighting.
## Gate 9 — Authentic realism
The vehicle must appear physically manufactured and subtly used.
## Gate 10 — Motion
Articulated systems must preserve correct relative component behavior.
## Gate 11 — Collision and interference
No unresolved confirmed critical or major forbidden intersections may remain in validated states.
## Gate 12 — Final presentation
The vehicle must hold up in daylight, neutral studio lighting, and PROJECT NEON nighttime lighting.
A failed gate requires repair or an explicit final limitation.
Do not fabricate success.
---
# 28. MANDATORY AGENT INTEGRATION RULE
The vehicle must be built through dependency-aware recursive production.
The root agent must establish shared architecture before delegating components.
Each delegated component must receive:
- Actual approved upstream geometry.
- Fixed dimensions.
- Relevant datums.
- Interface contracts.
- Design requirements.
- Quality expectations.
- Required inspection evidence.
The parent must:
1. Receive the actual child model.
2. Inspect it.
3. Compare it with the technical contract.
4. Examine its macro quality.
5. Request corrections where necessary.
6. Accept or reject it.
7. Integrate it.
8. Run assembly QA.
9. Save a checkpoint.
10. Proceed to the next child.
Do not rush integration.
Do not delegate to maximize agent count.
Do not accept underdeveloped models merely because the child has already spent substantial effort.
The goal is a coherent finished vehicle.
---
# 29. PRODUCTION MILESTONES
Execute within this single assignment.
The following are required production milestones, not user interaction checkpoints.
### Milestone 0 — Initialization
Create the independent project, inspect available tools, define datums and dimensions.
### Milestone 1 — Design exploration
Produce and compare three clay design studies.
### Milestone 2 — Packaging architecture
Establish actual occupant, chassis, powertrain, cooling, and suspension volumes.
### Milestone 3 — Accepted body design
Develop and verify the primary exterior silhouette and surfacing.
### Milestone 4 — Structural chassis
Build coherent central and subframe architecture.
### Milestone 5 — Wheel assemblies
Integrate the high-detail front-wheel standard and produce compatible remaining wheels.
### Milestone 6 — Suspension and steering
Build and validate the relevant mechanical systems.
### Milestone 7 — Engine and driveline
Build the detailed V12, turbo systems, transmission, differential, and exhaust.
### Milestone 8 — Exterior secondary assemblies
Build lights, aero ducts, diffuser, wing, glazing, mirrors, and service features.
### Milestone 9 — Doors
Build complete doors and their mechanisms.
### Milestone 10 — Interior
Build a fully detailed two-seat premium cockpit.
### Milestone 11 — Engineering microdetail
Refine meaningful structural, connection, and manufacturing details across all systems.
### Milestone 12 — Material system
Build and validate physically plausible materials.
### Milestone 13 — Authentic realism
Add localized, restrained manufacturing and use-dependent material variation.
### Milestone 14 — Articulation and QA
Test all relevant mechanisms and classify interference findings.
### Milestone 15 — Final visual refinement
Inspect all major views and correct remaining visible defects.
### Milestone 16 — Delivery
Save, reopen, verify, and report the complete master.
Adapt internal task sequencing when required by real component dependencies.
Do not treat these milestones as permission to ignore interface-first construction.
---
# 30. REQUIRED RENDER EVIDENCE
Produce a comprehensive technical and presentation package.
At minimum:
### Design
1. Concept A.
2. Concept B.
3. Concept C.
4. Selected gray front three-quarter.
5. Selected gray rear three-quarter.
6. Selected side orthographic.
7. Reflection-line body inspection.
### Exterior
8. Final front three-quarter.
9. Final rear three-quarter.
10. Front orthographic.
11. Rear orthographic.
12. Side orthographic.
13. Top view.
14. Front fascia detail.
15. Headlight macro.
16. Taillight macro.
17. Side-air corridor.
18. Rear diffuser.
19. Active wing.
20. Door hinge.
### Wheels and chassis
21. Front wheel hero.
22. Rear wheel hero.
23. Front brake macro.
24. Rear brake macro.
25. Front suspension.
26. Rear suspension.
27. Steering mechanism.
28. Underbody.
29. Chassis packaging.
### Powertrain
30. V12 installed.
31. V12 isolated.
32. Internal engine cutaway.
33. Left turbo.
34. Right turbo.
35. Transmission and differential.
36. Triple exhaust.
37. Cooling and lubrication routing.
### Interior
38. Cockpit wide.
39. Driver POV.
40. Steering wheel.
41. Driver display.
42. Center console.
43. Seat.
44. Door card.
45. Pedals.
### Verification
46. Door motion states.
47. Steering and suspension states.
48. Wing deployment states.
49. Engine kinematic inspection.
50. Interference inspection.
51. Material comparison.
52. Extreme macro detail sheet.
53. Manufacturing and surface realism sheet.
### Final presentation
54. Neutral daylight.
55. Premium studio.
56. PROJECT NEON nighttime street.
57. Rear nighttime hero.
58. Final production contact sheet.
Create additional technical or macro renders when necessary.
Do not regard image count as a substitute for inspection quality.
---
# 31. RENDER SELF-INSPECTION
For every major subsystem, inspect actual rendered outputs.
Identify:
- Surface defects.
- Missing details.
- Incorrect proportions.
- Broken reflections.
- Inconsistent materials.
- Floating hardware.
- Mechanical conflicts.
- Inadequate microgeometry.
- Overly artificial wear.
- Incorrect component relationships.
Correct defects in the actual model.
Rerender using the same camera, exposure, and lighting for comparison.
Do not claim a visual defect has been repaired without observing the result.
If image inspection tools are unavailable, mark the review as NOT_VERIFIED.
---
# 32. FINAL DELIVERY
Create a new independent project root for the REFORGED build.
The root agent must save:
**`PROJECT_NEON_NIGHTFALL_VESPER_R02_REFORGED_MASTER.blend`**
Preserve:
- Root working project.
- Accepted checkpoints.
- Child project directories.
- Child deliverables.
- Construction scripts.
- Material definitions.
- Interface manifests.
- Dimension reports.
- Integration logs.
- Collision reports.
- Motion reports.
- Technical renders.
- Macro renders.
- Final contact sheet.
- Production report.
Do not overwrite the original VESPER R-02.
Do not overwrite the original completed wheel project.
All important final components must remain editable.
Do not collapse independent moving components into one mesh.
---
# 33. FINAL ACCEPTANCE
The entire vehicle must demonstrate:
1. A highly distinctive original silhouette.
2. Excellent automotive body surfacing.
3. Coherent panel construction.
4. Genuine aerodynamic depth.
5. Premium multi-layer lighting assemblies.
6. Exceptional wheel and tire quality.
7. Mechanically plausible suspension.
8. A complete V12 powertrain.
9. Coherent transmission and driveline.
10. Connected cooling and exhaust systems.
11. Functional-looking dihedral doors.
12. A mechanically integrated active wing.
13. A fully developed cockpit.
14. High-quality material separation.
15. Physically convincing manufacturing details.
16. Subtle, localized evidence of actual use.
17. Extreme close-up fidelity.
18. A consistent design language across every subsystem.
19. Verified mechanical interfaces.
20. Classified intentional contacts.
21. No unresolved confirmed critical or major forbidden intersections in tested configurations.
22. Actual saved editable Blender geometry.
23. Real technical evidence.
24. Honest reporting of unresolved limitations.
Do not declare the vehicle complete simply because it contains all named components.
Do not declare it visually exceptional because the render is attractive.
Do not declare it mechanically correct because the parts resemble mechanisms.
Quality must be established through actual geometry, inspection, integration, and verification.
---
# 34. FINAL EXECUTION DIRECTIVE
Begin the full NIGHTFALL VESPER R-02 REFORGED production.
Apply the complete inherited Recursive Divide & Conquer protocol.
Create the root project autonomously.
Establish the vehicle architecture.
Develop and validate the design before detailed construction.
Use the completed high-detail wheel as the component-quality benchmark.
Produce complex subsystems through independent, recursively delegated projects where beneficial.
Require strong primary forms, detailed mechanical construction, appropriate microgeometry, authentic materials, and realistic manufacturing character.
Reject insufficient child deliverables.
Integrate only accepted work.
Verify each combined assembly.
Protect previously accepted components.
Perform visual and mechanical QA at every meaningful level.
Save checkpoints throughout production.
Deliver a complete, original, exceptionally detailed Blender vehicle master.
**The target is not merely a beautiful car.**
**The target is an entire automobile whose individual important components exhibit the same depth of craftsmanship demonstrated by the finished NIGHTFALL wheel experiment.**
**Begin autonomous production.**
