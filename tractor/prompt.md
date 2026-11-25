# TASK: CREATE AN ULTRA-REALISTIC, MAXIMALLY DETAILED 3D TRACTOR

You are working in the `mega_tractor` folder.

**You must use Blender MCP.** If Blender MCP is unavailable, report this immediately. Do not substitute actual modeling with image generation, descriptions, pseudocode, or reports of nonexistent results.

Work in subagent mode. Use subagents actively throughout the project: to model individual systems, research technical design, refine geometry and materials, perform checks, and fix errors.

**Preferred model for the main agent and all subagents: `Sol 6.2 High`.**

If the system allows you to select the model and reasoning level, use `Sol 6.2 High` for all available specialized agents. If this configuration is unavailable, do not claim that it is being used. Report its unavailability and use the most suitable permitted alternative.

---

# MAIN OBJECTIVE

Create an incredibly realistic, exceptionally detailed, mechanically convincing 3D model of a modern heavy-duty agricultural tractor.

This must not be a simple game asset or a low-poly demonstration object.

**The goal is a Hero Asset of the highest quality, intended for close-up inspection, cinematic renders, and technical demonstrations.**

The appearance should resemble real, modern, premium-class agricultural machinery.

At maximum camera zoom, the following should be visible:
- actual three-dimensional bolts, nuts, and washers;
- functional gaps between panels;
- mounting hardware for individual components;
- complex wheel rim geometry;
- genuine three-dimensional tire tread;
- hydraulic hose connections;
- metal clamps;
- joints and axles;
- technical identification plates;
- seals;
- welded joints where appropriate;
- correct fillet radii;
- internal cab components;
- instruments, buttons, and levers;
- technical mechanisms of the rear hitch;
- undercarriage details;
- subtle differences in materials and finishes.

However, the detailing must not be arbitrary.

**Every technical detail must have an explainable purpose, a reasonable size, a mounting point, and a structural relationship with the other components.**

The tractor must not look like an artificial object with thousands of bolts and hoses simply stuck onto it.

It must look as though it was designed by real engineers.

---

# 1. GENERAL CONCEPT

Create an original modern four-wheel-drive agricultural tractor with approximately 250–350 hp.

The concept is a heavy-duty multipurpose tractor with an enclosed cab, a large diesel engine compartment, massive rear wheels, a driven front axle, and an advanced rear hydraulic system.

Do not copy any one specific tractor. Create an original design while following the general engineering logic of existing agricultural machinery.

## Appearance

- Primary body color — deep, rich dark green.
- Cab roof — graphite or a light neutral color.
- Wheel rims — light-gray painted metal.
- Chassis — dark graphite.
- Tires — natural black rubber.
- Metal components — steel, galvanized metal, aluminum.
- Hydraulic hoses — black industrial rubber.
- Interior — dark-gray fabric, plastic, and metal.

Appearance: powerful, heavy, modern, technologically advanced, realistic.

No cartoonish styling.

No excessively futuristic elements.

No random decorative panels.

## Scale and proportions

Preliminary dimensions:
- length without implements: approximately 5.5 m;
- width: approximately 2.6 m;
- height to the roof: approximately 3.2 m;
- rear wheel diameter: approximately 1.9–2.1 m;
- front wheel diameter: approximately 1.35–1.55 m.

These are initial design guidelines, not fixed dimensions. Before detailed modeling, coordinate the dimensions with the chosen design.

Use real-world units in Blender: meters and millimeters as needed.

All components must follow a consistent scale system.

Do not model the cab, wheels, engine, and chassis independently and then fit them together through arbitrary scaling.

---

# 2. SUBAGENT ARCHITECTURE

This is a mandatory part of the work.

The main agent serves as the technical director, integrator, lead 3D artist, and final quality controller.

Subagents carry out specialized tasks.

Use parallel work where tasks are independent, and sequential work where the output of one stage is required for the next.

Do not create subagents merely as a formality. Every subagent must carry out a specific, useful task with a verifiable result.

## Subagent A — Technical architecture

Responsible for:
- overall dimensions;
- vehicle layout;
- axle placement;
- structural logic;
- cab and hood proportions;
- wheelbase;
- mounting points;
- coordination of all major systems.

This subagent must establish the common coordinate system and dimensional constraints in advance.

## Subagent B — Wheels and running gear

Responsible for:
- rear and front tires;
- three-dimensional tread;
- wheel rims;
- hubs;
- fasteners;
- axles;
- steering tie rods;
- steering knuckles;
- necessary front axle components.

Wheel detailing is one of the highest priorities.

## Subagent C — Engine and engine compartment

Responsible for:
- engine;
- cooling systems;
- air intake;
- exhaust;
- piping;
- filters;
- mounting components;
- internal engine compartment layout.

## Subagent D — Cab and interior

Responsible for:
- cab frame;
- doors;
- glazing;
- seals;
- interior;
- seat;
- controls;
- dashboard;
- operational displays;
- internal technical details.

## Subagent E — Hydraulics and hitch systems

Responsible for:
- rear three-point hitch;
- cylinders;
- joints;
- hydraulic lines;
- hydraulic ports;
- PTO;
- attachment mechanisms;
- towing assemblies.

## Subagent F — Materials and micro-detailing

Responsible for:
- physically convincing materials;
- microscopic surface irregularities;
- markings;
- rubber;
- painted metal;
- metal fasteners;
- glass;
- plastic;
- subtle wear;
- technical lettering.

## Subagent G — Quality assurance

Independently reviews the results of the other agents.

This subagent must look for:
- incorrect dimensions;
- violations of mechanical logic;
- missing details;
- unintended intersections;
- damaged geometry;
- poor topology;
- implausible materials;
- inconsistencies between components;
- insufficient detailing.

Subagent G must not automatically approve the results. It must objectively identify shortcomings.

When errors are found, send the feedback to the responsible subagent or fix the issues through the main agent.

## Collaboration rules

1. The main agent establishes a common coordinate system.
2. Subsystems receive coordinated dimensions and mounting points.
3. Each subagent works only within its assigned area.
4. Do not allow multiple agents to make conflicting simultaneous changes to the same Blender file.
5. If Blender MCP uses a shared scene, apply changes sequentially, use separate collections, or use separate working files followed by integration.
6. Before integration, verify scale, orientation, and dependencies.
7. The main agent is responsible for the final quality of the entire machine.
8. For particularly complex systems, use additional subagent work cycles.

**Very important: subagents must actually improve the quality of geometry and detailing, not merely write recommendations.**

---

# 3. GENERAL MODELING PRINCIPLES

The work is carried out in stages.

Each stage progresses from large to small:

**Primary form → structural elements → functional components → fasteners → small details → micro-details.**

Do not start with bolts before the system they attach to is ready.

Do not model the interior before establishing the final cab shape.

Do not create hydraulic hoses before the mechanisms and connection points exist.

After each stage, you must inspect the model as a whole.

Even when working on an individual component, consider its relationship with the rest of the structure.

Do not sacrifice proportions for the sake of adding more details.

---

# STAGE 1 — OVERALL LAYOUT AND CHASSIS

Start with the overall body of the tractor.

Create:
- central load-bearing structure;
- primary transmission volumes;
- an engine block as a layout element;
- axle mounting points;
- basic engine compartment;
- space for the cab;
- main rear structure.

Initially, work only with large forms.

Do not add decorative elements.

Achieve a convincing silhouette of a real heavy-duty tractor.

Establish the correct geometric relationship between the engine compartment, central transmission, front axle, rear axle, and cab.

Keep in mind that many tractors use load-bearing engine, transmission, and rear axle housings, so do not add an arbitrary massive automotive-style frame without a structural justification.

Once the foundation is established, refine:
- load-bearing housings;
- connecting flanges;
- major functional protrusions;
- mounting surfaces;
- transmission housing;
- supports;
- axle mounts.

All forms must have carefully considered fillet radii and thicknesses.

Do not use simple intersecting cubes as a substitute for final geometry.

## Stage verification

Compare the silhouette from the front, rear, side, top, and three-quarter views.

Check the wheelbase dimensions, ride height, engine position, and future cab installation.

Do not proceed to the next stage until the structure looks convincing.

---

# STAGE 2 — WHEELS: MAXIMUM DETAIL

This is one of the most important stages of the project.

Delegate the work to a specialized subagent, with the main agent reviewing its results.

Create fully three-dimensional tires.

## Tire geometry

Each tire must have:
- a correct overall shape;
- realistic width;
- naturally curved sidewalls;
- a transition from the sidewall to the tread surface;
- three-dimensional tread lugs;
- rounded tread edges;
- a tire bead;
- a natural contact patch with the ground.

Use a characteristic agricultural V-shaped or chevron tread pattern.

The tread lugs must be actual 3D geometry, not just an image or a normal map.

Each tread lug must have:
- the correct angle;
- reasonable thickness;
- a functional contact surface;
- sidewalls;
- smooth transitions;
- correct placement relative to neighboring elements.

Pay attention to the tread orientation relative to the direction of travel.

Avoid uneven spacing, unintended overlaps, and repeated errors.

## Tire sidewalls

Add:
- raised manufacturer markings for a fictional brand;
- tire size markings;
- technical designations;
- small symbols;
- molded rings;
- subtle rubber surface relief.

Lettering must follow the sidewall surface rather than float freely in space.

Do not create meaningless random symbols.

## Wheel rims

Model:
- rim;
- center disc;
- functional openings;
- internal geometry;
- hub mounting interface;
- center caps;
- bolts;
- nuts;
- washers;
- wheel seating features.

The number and arrangement of fasteners must be consistent.

Create complete rear and front wheels with their corresponding differences.

## Micro-details

Add:
- slight manufacturing irregularities in the rubber;
- barely visible mold marks;
- subtle roughness variation;
- light dust in recessed areas;
- mild deformation in the ground contact area.

Do not make the wheels look as worn as those of old machinery.

## Verification

Create separate close-up renders of the front and rear wheels.

When zoomed in, the wheels must withstand close inspection without revealing primitive geometry.

Check the tread on all four wheels and verify their correct fit on the axles.

---

# STAGE 3 — FRONT AXLE, STEERING SYSTEM, AND RUNNING GEAR

Create a front axle that is convincing from an engineering standpoint.

Refine:
- drive axle housing;
- central differential;
- axle shaft housings;
- steering knuckles;
- steering tie rods;
- hydraulic steering cylinders;
- articulated joints;
- supports;
- fasteners;
- protective components.

If an oscillating front axle is used, its design must allow the corresponding movement.

Do not add automotive shock absorbers or springs without justification in the chosen design.

Model only mechanisms that are consistent with the tractor's overall construction.

Add the necessary geometry to transmit forces to the wheels.

All steering components must have physically plausible orientations and connection points.

## Detailing

Refine:
- flanges;
- holes;
- bolts;
- metal connections;
- dust boots;
- protective housings;
- grease fittings where appropriate;
- functional protrusions;
- housing transitions.

Check that the steering components do not intersect the wheels or body.

Check the available clearance for front wheel steering.

---

# STAGE 4 — ENGINE COMPARTMENT AND ENGINE

Create a detailed diesel engine appropriate for the class of machine.

There is no need to recreate a particular existing engine down to the last screw, but the overall construction must look realistic.

## Main components

- Cylinder block.
- Cylinder head.
- Valve cover.
- Intake system.
- Turbocharger.
- Connecting pipes.
- Exhaust system.
- Cooling system.
- Radiator.
- Fan.
- Air filter.
- Oil filter.
- Fuel lines.
- Mounting brackets.
- Electrical connections.
- Technical piping.

Use a plausible scale for each component.

Avoid meaningless tangles of pipes.

Every hose must have an identifiable beginning and end.

Add fittings, clamps, connectors, and mounting hardware.

Refine the radiator shape, frame, protective grilles, and pipe connections.

## Engine details

Add:
- flanges;
- casting protrusions;
- functional holes;
- service covers;
- auxiliary equipment mounts;
- mating surfaces;
- bolt heads;
- pipe mounts.

The engine must be consistent with the available space under the hood.

Do not model an oversized engine that cannot fit inside the engine compartment.

## Verification

Create a dedicated technical view of the engine with the hood temporarily hidden.

Check the piping system and ensure there are no unnecessary intersections.

---

# STAGE 5 — HOOD AND EXTERIOR PANELS

Create a high-quality engine compartment body.

Requirements:
- precise panel geometry;
- carefully designed functional seams;
- consistent gaps;
- realistic thickness;
- smooth, controlled fillets;
- correct light reflections;
- detailed air intakes.

Create separate components:
- main hood;
- side panels;
- front grille;
- ventilation elements;
- industrial-style trim panels;
- mounts;
- service access panels.

The panels must not look like a single melted piece of plastic.

Add actual manufacturing seam lines between them.

## Front grille

Create a three-dimensional grille structure.

It must have depth and internal space, rather than being a black plane with a texture.

Add fasteners and a frame.

Create headlights:
- with housings;
- internal reflectors;
- transparent lenses;
- separate lighting elements;
- seals.

## Verification

Make sure the hood does not intersect the engine.

Check the realism of panel gaps and the correctness of surface bevels.

---

# STAGE 6 — CAB: EXTERIOR STRUCTURE

Create a complete enclosed cab.

Start with the frame and large forms.

Then create:
- front pillars;
- side pillars;
- rear pillars;
- roof;
- door openings;
- window frames;
- door panels;
- mounts;
- sills;
- steps;
- handrails.

Carefully consider pillar thickness and glass fitment.

The glazing must not intersect the metal frame.

## Doors

Each door must have:
- the correct shape;
- a three-dimensional frame;
- hinges;
- a handle;
- a latch assembly;
- a rubber seal;
- an interior panel;
- a correct functional clearance gap.

If necessary, allow the door to open without intersecting neighboring components.

## Glass

Create:
- windshield;
- side windows;
- rear window;
- appropriate thickness;
- realistic materials;
- correct reflections.

Do not use completely black, opaque glass.

The interior must remain visible.

## Additional details

- Windshield wipers.
- Wiper shafts.
- Mirrors.
- Mirror brackets.
- Work lights.
- Turn signals.
- Rotating warning beacon.
- Antenna.
- Roof ventilation elements.
- A visibility-assistance camera, if appropriate for the design.

## Verification

Inspect the cab from the front, rear, side, top, and three-quarter views.

Check the glazing geometry and all mounting components.

---

# STAGE 7 — CAB INTERIOR: MAXIMUM DETAIL

The interior must be fully developed.

Do not limit it to a seat and steering wheel.

## Operator's seat

Create:
- base;
- seat cushion;
- backrest;
- headrest;
- side bolsters;
- armrests;
- adjustment mechanism;
- suspension base;
- mounting components.

The material must resemble fabric or professional-grade agricultural machinery upholstery.

Add stitching, seams between components, and subtle surface texture.

## Steering controls

- Steering wheel with correct rim thickness.
- Central hub.
- Spokes.
- Steering column.
- Adjustment housing.
- Steering column stalks.
- Mounts.

## Dashboard

Create:
- display;
- instrument indicators;
- buttons;
- switches;
- ventilation openings;
- plastic panels;
- bezels;
- control elements.

Buttons must protrude from the surface or be correctly recessed.

Do not substitute the entire interior with a flat texture.

## Center and side consoles

Add:
- control joystick;
- levers;
- selectors;
- primary buttons;
- additional displays;
- cup holder;
- small storage compartments;
- adjustment controls;
- functional panels.

## Additional details

- Pedals.
- Flooring.
- Rubber mats.
- Pillar trim.
- Headliner components.
- Interior lighting.
- Handles.
- Seat belt.
- Air vents.

## Verification

Check ergonomics.

A person of average height must be able to sit in the seat and reach the steering wheel and primary controls.

Create several close-up renders of the interior.

Separately check how the interior looks through the exterior glazing.

---

# STAGE 8 — REAR AXLE, TRANSMISSION, AND POWERTRAIN STRUCTURE

Refine the rear section of the chassis.

Create:
- rear axle housing;
- transmission components;
- hub connections;
- flanges;
- service covers;
- mounts;
- service points;
- protective components.

Check the position of the rear wheels relative to the cab.

Create reasonable clearances between the tires and fenders.

Do not allow the wheels to penetrate the body.

## Detailing

Add structurally justified:
- cast ribs;
- connecting flanges;
- bolts;
- plugs;
- protective housings;
- brackets.

Components must have realistic thickness and technically correct shapes.

---

# STAGE 9 — REAR THREE-POINT HITCH

This stage requires special attention.

The rear hitch must be a complete mechanical assembly.

Create:
- lower links;
- upper center link (top link);
- articulated joints;
- adjustment elements;
- lift arms;
- lift rods;
- stabilizers;
- mounting pins;
- retainers;
- connecting plates.

All components must interact logically.

Check the kinematics.

Raising and lowering the hitch must be possible within its intended operating range without obvious mechanical intersections.

## Power take-off (PTO)

Create:
- output shaft;
- protective guard;
- connection area;
- mounting components.

Do not leave the rear of the tractor empty.

---

# STAGE 10 — HYDRAULICS AND PIPING

Use a specialized subagent.

Create a realistic hydraulic system.

## Hydraulic cylinders

Each cylinder must have:
- main body;
- piston rod;
- end caps;
- sealing area;
- mounting eyes;
- articulated joints;
- hydraulic line connection points.

## Hoses

Create:
- three-dimensional flexible hoses;
- correct bends;
- fittings;
- metal end fittings;
- coupling nuts;
- mounts;
- protective components.

Hoses must not hang in the air without a reason.

Each hydraulic line must be connected to a specific assembly.

## Distribution connections

Add:
- hydraulic couplers;
- protective caps;
- mounting panel;
- distinguishable connection types;
- fasteners.

Check the routing of all lines.

Do not create meaningless tangles of hoses for the sake of visual complexity.

**The main goal is convincing engineering detail.**

---

# STAGE 11 — FENDERS, STEPS, AND EXTERNAL EQUIPMENT

Create:
- front fenders;
- rear fenders;
- fender mounts;
- steps;
- non-slip surfaces;
- handrails;
- external tanks and caps;
- rear lighting units;
- safety features;
- reflectors;
- license plate mounting areas;
- technical panels.

The steps must be conveniently positioned for climbing into the cab.

Handrails must have reasonable thickness and actual mounting hardware.

The front fenders must accommodate the ability of the wheels to turn.

## Fine detailing

- Textured steps.
- Mounting bolts.
- Rubber pads.
- Panel joints.
- Plastic plugs.
- Manufacturing seams.

---

# STAGE 12 — MICRO-DETAILING

This is a separate, full-fledged stage, not an optional refinement.

Use several subagents to analyze different parts of the tractor in parallel.

Refine the details visible in close-up views.

## Bolts and nuts

Use different types of fasteners:
- hex-head bolts;
- nuts;
- washers;
- hex socket screws;
- studs;
- locking elements.

Fastener dimensions must correspond to the scale of the components.

Do not make all bolts identical.

## Technical connections

- Flanges.
- Clamps.
- Seals.
- Articulated joints.
- Hinges.
- Brackets.
- Metal plates.
- Cable clips.

## Manufacturing details

Add where appropriate:
- characteristic cast surfaces;
- weld seams;
- manufacturing transitions;
- bevels;
- fillets;
- small seam lines;
- stamped shapes;
- component markings.

## Electrical systems

Refine:
- wiring harnesses;
- connectors;
- protective sheathing;
- wiring clips;
- lighting unit connections.

There is no need to model every hidden wire.

However, all visible cables must look purposeful.

## Micro-detail verification

Create close-up renders of:
- a wheel hub;
- one hydraulic connection;
- the steering mechanism;
- a door hinge;
- dashboard components;
- a section of the engine.

Details must remain high-quality in these views.

If a close-up reveals the primitive nature of individual elements, refine them.

---

# STAGE 13 — PHOTOREALISTIC-QUALITY MATERIALS

Use a physically based approach to materials.

Create separate, carefully designed materials for different surface types.

## Painted metal

- Realistic reflections.
- Subtle roughness variations.
- Microscopic surface irregularities.
- Minor manufacturing differences between panels.

## Cast metal

- Moderate roughness.
- Characteristic microtexture.
- Distinction from smooth painted metal.

## Rubber

- Realistic matte surface.
- Subtle microrelief.
- Different properties for the sidewalls and tread.
- Controlled signs of use.

## Glass

- Realistic transparency.
- Thickness.
- Correct refraction.
- Reflections of the surrounding scene.
- Slight variation if necessary.

## Plastic

- Convincing roughness.
- Differences between hard and soft plastics.
- Plausible microtexture.

## Interior

- Seat fabric.
- Rubber surfaces.
- Rubberized buttons.
- Matte dashboard finish.
- Glass display surfaces.

## Metal fasteners

- Steel.
- Galvanized surfaces.
- Stainless steel components where appropriate.
- Subtle differences in surface condition.

Do not use a single material for all metal components.

---

# STAGE 14 — REALISTIC SIGNS OF USE

The tractor should look like a working but well-maintained machine.

Add a small amount of:
- dust on the tires;
- dirt in deep areas of the tread;
- dust in hard-to-reach areas;
- subtle signs of use on the steps;
- very light scuffing on working surfaces;
- minor dirt around lower mechanical components.

Do not add excessive rust.

Do not cover the entire tractor with uniform noise.

Dirt accumulation must follow the logic of how the machine is used.

The upper hood surface, step area, lower chassis, and wheels should accumulate dirt differently.

Use textures and procedural materials where they genuinely improve realism.

---

# STAGE 15 — HIGH-QUALITY LIGHTING

Create a professional studio scene.

The main model is the sole primary subject of the composition.

Use Cycles if available.

Add:
- a large, soft key light;
- an additional side light;
- rim lighting;
- controlled reflections on the body;
- clearly readable glass materials;
- well-lit wheels;
- correct contact shadows.

The tractor should look like a real machine photographed for a professional advertising campaign.

Do not apply excessive cinematic color grading that obscures the colors of the materials.

## Primary camera angles

1. Front three-quarter view.
2. Rear three-quarter view.
3. Strict side view.
4. Front orthographic view.
5. Rear orthographic view.
6. Top view.
7. Low-angle view to convey the machine's mass.
8. Close-up of the cab.
9. Close-up of a wheel.
10. Close-up of the rear hydraulics.

---

# STAGE 16 — DETAILED VERIFICATION

After EVERY stage, perform a comprehensive review.

You must involve an independent QA subagent in this process.

## Verification cycle 1 — Geometry

- No damaged polygons.
- No inverted normals.
- No unintended holes.
- No incorrect smoothing.
- No clearly erroneous self-intersections.
- No overlapping duplicate surfaces.
- No inappropriate sharp edges.
- Bevels are reasonably sized.
- Technically significant components have thickness.

Distinguish acceptable engineering intersections, such as those inside enclosed assemblies, from erroneous ones.

## Verification cycle 2 — Construction

- All assemblies are consistent in scale.
- All technical components are logically connected.
- Wheel axes are correctly positioned.
- Wheels do not intersect the body.
- Hoses are connected to the correct assemblies.
- Doors fit their openings.
- The interior fits inside the cab.
- The engine fits under the hood.
- The hitch has plausible kinematics.

## Verification cycle 3 — Detailing

Inspect each major assembly separately.

Do not skip an area simply because it is not visible in the main render.

Pay particularly close attention to:
- the inner surfaces of the wheel rims;
- the rear of the cab;
- the underside of the tractor;
- engine mounting points;
- the space beneath the fenders;
- hydraulic cylinder mounts;
- the sides of the engine compartment.

## Verification cycle 4 — Materials

- Realistic rubber.
- Plausible metal.
- Good glass transparency.
- Correct roughness.
- No normal-related errors.
- No stretched textures.
- No excessive procedural noise.

## Verification cycle 5 — Camera angles

Use consistent orthographic views and the same scale when evaluating proportions.

Check the following views:
- 0°;
- 30°;
- 45°;
- 60°;
- 90°;
- 120°;
- 180°;
- top;
- bottom.

Do not consider the model high-quality simply because it looks beautiful from one side.

## Correction rule

If an error is found, fix it.

After making the correction, recheck that area and the adjacent assemblies.

Do not declare a stage complete until critical issues have been resolved.

If a defect cannot be fixed, explicitly disclose it in the report. Do not conceal shortcomings.

---

# 17. STAGED SAVING SYSTEM

After each stage, save a separate `.blend` version.

Use the following structure:

`mega_tractor/`
- `stages/`
- `components/`
- `renders/`
- `checks/`
- `final/`

The `stages` folder must contain intermediate versions of the project.

The `components` folder must contain individual working components or subagent outputs if separate modeling was used.

The `renders` folder must contain renders.

The `checks` folder must contain verification images.

The `final` folder must contain the finished result.

Do not overwrite previous high-quality versions unnecessarily.

---

# 18. FINAL STAGE — THREE COMPLETE QUALITY CONTROL CYCLES

After completing all stages, perform THREE additional comprehensive reviews of the entire model.

## First review — Technical

Check:
- topology;
- normals;
- geometry;
- materials;
- proportions;
- structural integrity;
- absence of errors in the scene.

## Second review — Detailing

Inspect the entire machine assembly by assembly.

For each assembly, assess:
- whether it is sufficiently detailed;
- whether the mounting hardware looks realistic;
- whether the engineering connections are correctly implemented;
- whether it withstands close-up inspection;
- whether it looks primitive.

Use subagents for an independent audit.

If an individual assembly looks noticeably worse than adjacent ones, refine it.

## Third review — Photorealism

Evaluate the final renders.

Ask the following questions:
- Does the object look like real machinery?
- Are the proportions natural?
- Are the materials visually convincing?
- Is the interior sufficiently detailed?
- Do the bolts and hoses look like arbitrary decorations?
- Does the model remain convincing in close-ups?
- Does it convey a sense of mass and engineering complexity?

If the result looks like a toy, identify the specific reason and fix it.

---

# 19. MANDATORY FINAL FILES

Save the following:

**Main model**
- `mega_tractor.blend`

**Additional exports, if technically possible**
- `mega_tractor.fbx`
- `mega_tractor.glb`

**Primary renders**
- `hero_front_3_4.png`
- `hero_rear_3_4.png`
- `front.png`
- `back.png`
- `left.png`
- `right.png`
- `top.png`
- `bottom.png`

**Close-ups**
- `detail_front_wheel.png`
- `detail_rear_wheel.png`
- `detail_engine.png`
- `detail_cabin_interior.png`
- `detail_dashboard.png`
- `detail_hydraulics.png`
- `detail_rear_hitch.png`
- `detail_chassis.png`

**Technical images**
- `wireframe_front.png`
- `wireframe_side.png`
- `orthographic_sheet.png`

Also save at least one verification screenshot after each major stage.

Produce the primary renders at a resolution of at least 2560×1440 if resources allow.

A resolution of 3840×2160 is preferable for the main hero render.

Do not increase resolution at the expense of unfinished geometry: model quality comes first, then render quality.

---

# 20. FINAL REPORT

Prepare a report containing:

1. What was created.
2. Which subagents participated.
3. Which assemblies they modeled or reviewed.
4. Which technical issues were identified.
5. Which corrections were made.
6. Which details received additional refinement.
7. Which stages were fully completed.
8. Which limitations remain.
9. Where the files were saved.
10. Links or paths to the final images and `.blend` file.

Do not claim that the model has been verified if the corresponding review was not actually performed.

Do not claim that nonexistent files have been created.

---

# CRITICAL REQUIREMENTS

## 1. Maximum detail

Do not limit the work to the overall silhouette.

Refine complex assemblies to a level at which they are enjoyable to inspect in close-up.

## 2. No visual shortcuts

Do not replace important three-dimensional technical components with textures.

Normal maps are acceptable for microrelief, but not for the primary forms of mechanisms, tread, or fasteners that must have actual volume.

## 3. Engineering plausibility

The tractor must look like machinery that could physically exist.

No arbitrary pipes, pointless cylinders, or decorative gears.

## 4. Correct proportions

Maintain a realistic scale for all components.

Do not enlarge small details merely to make them more noticeable if this compromises realism.

## 5. High-quality materials

No resemblance to a toy, modeling clay, cheap plastic, or an unfinished computer-generated placeholder.

## 6. Continuous quality control

Reviews are mandatory after every stage.

Errors must be corrected before finalization.

## 7. Active use of subagents

Do not attempt to carry out all complex tasks exclusively through the main agent if effective delegation is available.

Use specialized subagents for:
- independent modeling;
- technical analysis;
- in-depth reviews;
- problem-solving;
- micro-detailing;
- material refinement.

If a subagent returns a poor result, do not integrate it without correcting it.

## 8. Consistency across all subsystems

No component should look out of place.

The chassis, cab, wheels, engine, hydraulics, and hitch must form a single cohesive machine.

## 9. Do not substitute quantity for quality

Do not create 100,000 arbitrary details just to achieve a large object count.

Every detail must improve realism.

5,000 well-designed components are better than 100,000 meaningless primitives. This is an illustrative comparison, not a target object-count limit.

## 10. Primary priority

Priorities in strict order:

1. Correct construction.
2. Perfectly coordinated proportions.
3. High-quality geometry.
4. Detailing of technical assemblies.
5. Photorealistic materials.
6. Micro-detailing.
7. Lighting and rendering.
8. Additional presentation.

**Do not conceal poor modeling with attractive lighting or rendering.**

---

# SPECIAL INSTRUCTIONS FOR THE MAIN AGENT

Your task is not to perform the minimum sufficient number of actions, but to create the best technically and visually achievable result with the available tools and resources.

After completing a stage, do not mechanically proceed to the next one.

Assess whether the result is of sufficiently high quality.

If a wheel looks too simple, refine the wheel.

If the cab looks empty, refine the interior.

If the engine resembles a collection of cylinders, improve its construction.

If the hydraulic hoses lack logical connections, redo them.

If the materials look like plastic, improve them.

If any part of the machine fails to withstand close-up inspection, assign a subagent to refine it further.

Use subagents for parallel analysis and independent verification, but avoid conflicts arising from simultaneous editing of the Blender scene.

Inspect the actual results, not just the subagents' messages claiming successful completion.

**ULTIMATE GOAL:**

Create an ultra-detailed, photorealistic 3D model of a modern agricultural tractor that looks like a real, expensive industrial product.

It must be convincing from every angle, feature high-quality geometry, a complete interior, complex technical mechanisms, and numerous meticulously crafted details.

The viewer must be able to move the camera close to virtually any important part of the model and discover not a simplified placeholder, but a purposeful, beautiful, and meticulously modeled structure.

Begin with an analysis of the overall layout, distribution of tasks among subagents, and the first stage of modeling.

**Do not skip stages. Do not sacrifice quality for speed. Continue performing checks and corrections until the project is complete.**
