---
name: architectural-isometric-diorama
description: Transform a reference travel, architecture, landmark, streetscape, waterfront, plaza, mountain, or city photograph into a collectible architectural diorama poster using strict orthographic isometric projection, faithful scene reconstruction, miniature-model materials, a cut-out base, and restrained editorial typography. Use when the user uploads a location photo and asks for an isometric architectural model, miniature city diorama, axonometric poster, travel architecture archive, or a result matching this repository's style.
---

# Architectural Isometric Diorama

Turn a single reference photograph into a collectible architectural archive poster: a structurally faithful miniature scene rendered with **strict orthographic isometric / axonometric projection**, mounted on a clean cut-out base, with restrained editorial typography on a warm off-white background.

## Core rule

Do **not** treat the task as “make the photo look like a cute miniature.” Treat it as:

**reference-photo analysis → structural extraction → scene simplification → orthographic axonometric reconstruction → miniature materialization → editorial composition**

Structural fidelity is more important than decorative invention.

## 1. Read the reference image

Identify and rank the visible scene elements:

1. landmark or main architectural subject;
2. supporting buildings and spatial boundaries;
3. foreground elements that define the place, such as water, roads, stairs, plazas, lawns, walls, bridges, docks, railings, trees or promenades;
4. small but highly recognizable details, such as exposed pipes, towers, domes, roof silhouettes, signs, lighting bands, boats, flags, colonnades, windows, balconies or retaining walls;
5. irrelevant distant clutter.

Preserve the first four groups when they materially help recognition. Remove or compress the fifth group.

Never invent a large landmark that is absent from the reference.

## 2. Projection is a hard constraint

The output must use **strict orthographic isometric projection**.

Use these concepts together:

- orthographic camera;
- parallel projection;
- true axonometric architectural view;
- zero perspective distortion;
- zero vanishing points;
- equal scale regardless of depth;
- all parallel architectural edges remain parallel;
- approximately 30-degree isometric axes;
- rectangular bases keep opposite edges perfectly parallel;
- rear edges must not become shorter than front edges.

The image should resemble a precise architectural axonometric drawing transformed into a physical miniature model.

Avoid:

- perspective camera;
- wide-angle lens;
- three-quarter perspective photography;
- near-large/far-small scaling;
- converging parallel lines;
- cinematic lens distortion.

## 3. Scene reconstruction

Rebuild the visible scene as a coherent miniature architectural model, not as a flat cutout of the photograph.

Preserve:

- major massing and height hierarchy;
- relative positions of buildings;
- number and direction of major stairs, bridges, roof ridges, terraces and walls where visible;
- iconic facade rhythms and window proportions;
- dominant vegetation masses;
- water/road/plaza orientation;
- original time-of-day character where useful;
- the reference image's dominant palette.

If the photograph is a frontal elevation, infer only the minimum side depth required to create a plausible axonometric object. Do not overbuild unseen architecture.

## 4. Simplification

Delete or simplify:

- sky;
- remote skyline that does not define the subject;
- visual clutter;
- excessive vehicles and pedestrians;
- temporary construction noise unless it is important to the scene;
- random signage and unreadable brand graphics.

Keep a few tiny people, vehicles or boats only when they improve scale and place identity.

## 5. Diorama base

Place the reconstructed scene on a thin, clean architectural model base.

Preferred base:

- square or rectangular;
- dark charcoal, graphite or muted stone edge;
- enough thickness to read as a physical model;
- scene clipped cleanly at the perimeter;
- water, road, lawn or plaza can continue to the base edge;
- no oversized plinth.

The base itself must obey the same orthographic projection.

## 6. Material language

Render as a premium architectural miniature, between model-making, architectural visualization and editorial illustration.

Materials should be:

- matte;
- slightly desaturated;
- physically plausible;
- simplified but recognizable;
- finely detailed without becoming hyper-real.

Preserve the source material identity: red brick stays red brick, dark metal stays dark metal, limestone stays limestone, water remains water, vegetation stays natural.

Avoid:

- LEGO look;
- clay toy look;
- cute chibi miniature style;
- glossy plastic;
- fantasy architecture;
- excessive rounded geometry;
- over-saturated colors.

## 7. Lighting

Use soft studio-like global illumination while preserving the reference atmosphere.

Day scenes:

- soft daylight from upper-left or upper-side;
- gentle ambient occlusion;
- subtle contact shadows;
- restrained long shadow toward the rear-right;
- no dramatic cinematic contrast.

Night scenes:

- keep architectural illumination and reflections from the source;
- use dark but readable water/ground;
- preserve warm/cool light contrast;
- keep the overall poster background warm and light rather than turning the whole canvas black.

## 8. Editorial layout

Background: warm ivory, cream or very light beige with a subtle paper texture.

Composition:

- diorama occupies about 55–68% of the canvas;
- place model center-right or lower-right;
- maintain generous negative space;
- keep text small and restrained;
- use blue-gray, indigo-gray or another dark tone derived from the image palette.

Typography should feel like a Japanese architecture/design magazine: clean sans serif, generous tracking, quiet hierarchy.

Recommended text system:

- upper-left: 2–4 line English title;
- below title: one slash “/” as a small divider;
- below divider: 3–5 short lines of restrained poetic copy;
- lower-left: three-digit issue number, then city/place and country;
- lower-right: coordinates when known.

Never let typography dominate the model.

## 9. Copy generation

Generate titles that are short, atmospheric and place-specific. Avoid clichés and tourist-ad language.

Good patterns:

- `BETWEEN WALLS, / A BREATH`
- `CITY LIGHTS, / RIVER WHISPERS`
- `RIVER OF TIME, / LIGHT OF SHANGHAI`
- `SUMMER PALACE, / ECHOES OF / DYNASTIES`

Body copy should be 12–28 English words, calm and observational.

## 10. Place metadata

If the user provides the place, use it exactly unless clearly misspelled.

If coordinates are confidently known, include them. If not, omit them rather than fabricate precision.

Issue numbers may continue a user-defined series. If no sequence exists, use a neutral placeholder such as `001`.

## 11. Prompt template

Use the following template when generating the image:

> Transform the supplied reference photograph into a structurally faithful **architectural isometric diorama poster**. Reconstruct the visible landmark and its immediate environment as a physical miniature architectural model. Preserve the main massing, facade rhythm, roof silhouettes, important stairs, walls, bridges, water, roads, vegetation and distinctive small details that make the place recognizable. Simplify only irrelevant distant clutter and do not invent major architecture absent from the reference.
>
> Use **strict orthographic isometric projection / true axonometric architectural view**, orthographic camera, parallel projection, zero perspective distortion, zero vanishing points, equal scale regardless of depth, approximately 30-degree isometric axes. All parallel architectural edges must remain perfectly parallel. The rectangular model base must obey the same orthographic projection; opposite edges remain parallel and the rear edge must not become shorter than the front edge.
>
> Place the scene on a thin charcoal architectural model base. Render it as a premium physical miniature with matte materials, simplified but recognizable textures, subtle ambient occlusion, refined contact shadows and soft studio global illumination. Preserve the dominant colors and time-of-day atmosphere of the source image. Avoid cartoon, LEGO, clay, glossy plastic, exaggerated proportions, fantasy structures and photographic perspective.
>
> Use a warm ivory paper-textured background with generous negative space. Place the diorama center-right or lower-right, occupying about 55–68% of the image. Add restrained blue-gray editorial typography on the left: a short 2–4 line English title, a slash divider, a brief poetic description, a three-digit issue number, place/city and country. Place coordinates in the lower-right only when known. The final piece should feel like a collectible Japanese architectural design magazine plate: quiet, precise, refined and spatially faithful to the reference photograph.

## 12. Negative constraints

Always reinforce these when the model drifts:

`no perspective camera, no vanishing points, no wide-angle distortion, no near-large far-small scaling, no random architecture, no fantasy reconstruction, no cute toy style, no LEGO, no clay, no glossy plastic, no excessive vegetation, no oversized typography, no dramatic cinema lighting, no black poster background unless explicitly requested`

## 13. Quality check before finalizing

Verify:

- Can the place still be recognized from the original photograph?
- Is the main landmark shape faithful?
- Are the base edges parallel rather than perspective-converging?
- Are distant objects the same scale system as near objects?
- Did the model invent unseen large structures?
- Is the scene simplified without losing identity?
- Does the palette still come from the source?
- Is the poster calm, spacious and editorial rather than toy-like?

If any answer is no, regenerate with stronger structural and orthographic constraints.
