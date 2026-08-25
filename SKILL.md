---
name: bigfish-ink-wash-photo
description: Reimagine a user-supplied photograph as a spacious, spontaneous contemporary Chinese expressive ink painting made with few decisive strokes, large untouched paper, and only essential identifying anchors rather than precise reconstruction. Use for 写意水墨、水墨意境画、东方水墨、宣纸留白海报, photo-to-ink transformations, or revisions that must preserve a main subject, pose, direction, composition, or approved painted element while avoiding photorealistic pasted subjects and jelly-like AI watercolor marks.
---

# Ink Wash Photo

## Workflow

1. Inspect the uploaded source photograph before writing the image prompt.
2. Read [references/generation-prompt.md](references/generation-prompt.md) in full.
3. Before generating, determine the final canvas direction from subject extension, spatial flow, visual-center distribution, and the source's key structure. Unless the user explicitly requests another ratio, lock landscape output to 16:9 or portrait output to 9:16. Near-square or unusually proportioned sources must still resolve to one of these two ratios; never preserve a nonstandard source ratio as the final canvas.
4. Use that document as the canonical prompt. Treat the photograph as compositional memory for surface detail, but as binding evidence for subject geometry. Adapt only observable source facts, the locked final canvas direction and ratio, and the user's explicit request.
5. Always perform image-to-image editing with the uploaded photograph attached as the source reference. Never generate from the text prompt alone when a source photo is available.
6. Before the tool call, internally write one source-specific identity-and-pose lock for every person: apparent gender presentation, posture, facing direction, head/torso/pelvis relationship, limb placement, support/contact point, hair silhouette, and major clothing silhouette. Include these observable facts in the tool prompt without exposing the analysis to the user. When any fact is visually ambiguous, preserve the source silhouette instead of inventing a clearer identity, costume, or action.
7. Ask the image tool for native canvas compliance: landscape means 16:9; portrait means 9:16. Tool-default dimensions are never automatically acceptable.
8. Never obtain compliance by cropping a main person, building, tree crown, mountain or ridge, key shoreline structure, boat, main focal point, or any identity-defining structure. Prefer expanding the canvas, scaling the complete subject group down, repositioning it, or reorganizing peripheral space.
9. Return the generated high-resolution image directly unless the user requests variants.

## Chinese expressive brushwork is mandatory

The result must read unmistakably as Chinese 写意水墨 painted with a Chinese calligraphy brush on raw xuan paper, never as Western watercolor, a watercolor illustration, or a photo filtered through transparent washes. Build every form from visible brush actions: center-tip structural strokes, side-brush massing, dry and reverse-brush drag, lifting and pressing, pauses and turns, broken flying-white, splashed ink, broken ink, accumulated ink, and water colliding with ink. Each mark must show a purposeful start, travel, pressure change, and release.

Use very few marks. Abbreviate boats to canopy arcs, hull direction, and a few figure silhouettes; buildings to broken dry lines and pale ink planes; water to a handful of spacious horizontal brush marks; reflections to two or three short fading strokes. Leave contours open, let structures skip or disappear, and stop as soon as the scene is recognizable.

Use color only as a restrained tint carried inside the ink. Never model forms with luminous transparent color glazing, smooth Western wash gradients, digital airbrush blending, or softly rounded watercolor patches.

Surface roughness must be the absence and breakup of ink inside a broad brush mark, never an added texture made from particles or small blobs. Build each subject with a few broad, continuous, directional strokes. Within those strokes only, let the brush dragging across raw paper create elongated fiber-aligned broken ink, dry abrasion, flying-white, torn edges, and paper showing through. These marks must follow the stroke direction and remain subordinate to the large form. From normal viewing distance, the viewer should see complete masses and brush momentum first; paper-fiber breakup should appear only on closer inspection. Keep untouched paper clean and never apply a global grain overlay.

## Artistic intent

Create the feeling of a master painter recalling the scene with a few relaxed, decisive marks. The result must read first as an original ink painting and only second as a transformation of a photograph. Recognizability comes from a few identifying anchors, not from complete contours, exhaustive objects, façade grids, repeated waves, or polished rendering.

Use calligraphic pressure, speed, pauses, dry-brush drag, splashed ink, broken ink, accumulated ink, broken strokes, and untouched paper. Let a single stroke carry structure, atmosphere, and tone. Leave forms unfinished and stop as soon as the scene is recognizable.

## Priority order

When requirements compete, resolve them in this order:

1. Preserve every person's source identity cues and geometry exactly: count, apparent gender presentation, posture, facing direction, body axis, joint arrangement, limb placement, support/contact, hair shape, clothing silhouette, and major outer silhouette. Never trade these facts for style, blank space, or a more poetic composition.
2. Preserve the primary non-human identifying anchors: subject type, dominant silhouette, direction, placement, and essential spatial relation.
3. Reserve one large, continuous, completely unpainted field of warm paper covering strictly 55–65% of the entire canvas. Treat this as a protected blank mask: no wash, mist, shadow, reflection, distant scenery, decorative grain, or stray mark may enter it.
4. Preserve the living quality of expressive brushwork, omission, rhythm, and untouched paper while simplifying only internal surface detail.
5. Keep people, boats, buildings, vegetation, water, and ground in one shared ink-and-paper material layer.
6. Merge, abbreviate, or omit secondary objects and internal structures whenever they make the image feel reconstructed, polished, or photographic.

Source fidelity never means contour tracing. Do not recreate every building, window, boat, wave, leaf, garment fold, or background object. For a city, a distinctive tower silhouette and skyline rhythm may be enough. For a sunset, the sun, horizon, reflection axis, and broad water mass may be enough.

This freedom never applies to human identity cues or pose. Simplify the paint inside the person, not the person's geometry. A standing person must remain standing; a walking person must retain the same step and weight-bearing leg; a seated person must retain the same seat, orientation, and limb arrangement. Preserve visible gender presentation and hair/clothing silhouette without adding facial detail. Never masculinize or feminize the subject, and never invent sitting, kneeling, cross-legged poses, hats, robes, or historical styling.

## Build complex dense forms as unified masses

Treat every complex, dense, or repetitive subject—including tree crowns, shrubs, mountains, rocks, water ripples, reflections, roof tiles, window grids, fish schools, crowds, flower beds, and boat groups—as a unified large shape, volume, value structure, and overall rhythm before adding only a few necessary structural cues. Never construct or fill these subjects by accumulating many repeated units.

Local marks must serve the large volume rather than becoming uniform, mechanical, dense texture. Any roughness must stay inside a broad parent stroke as fiber-aligned missing ink; it must never become independent dots, cells, scales, foam, sponge marks, or repeated patches. Vary edges through clarity, interruption, and dissolution; let paper and air enter the form. Reduce structure, contrast, boundaries, and surface breakup with distance and decreasing importance until they merge into blank paper.

If an area starts becoming fragmented, dense, or repetitively textured, stop adding detail and reorganize it with larger continuous forms, connected ink masses, and broad value relationships. The governing rule is: unified shaping, not unit accumulation; volume, not surface filling; hierarchical abbreviation, not detail stacking.

## Interpret vegetation by its real morphology

Do not force every plant into the same generic foliage recipe.

- Treat dense rounded crowns as three to five connected large ink masses made with broad side-brush strokes.
- Treat willow through a few long hanging directional strokes and restrained pale ink.
- Treat poplar, metasequoia, and other upright tree rows through vertical trunk rhythm and restrained crown masses.
- Treat bamboo through sparse poles, joints, and quick blade-like strokes.
- Merge distant woodland into mist, terrain, and tonal bands.

Preserve the source crown's outer silhouette, overall volume, season, and growth state—not its internal leaf count or leaf density. Simplification must not turn a thriving tree into a dead or sparse tree.

For a thriving tree, the large foliage masses must visually dominate the exposed branch network. Keep most secondary branches concealed; reveal only the trunk and a few structurally necessary branch turns. Express abundance through crown volume and ink weight, never by adding leaf units.

## Do not over-engineer the prompt

- Do not invent extra numeric detail-retention ratios, automatic style-reference selection, or hard checks beyond the canonical prompt. The canonical 55–65% protected blank area and 35–45% painted area are mandatory and must not be softened or reinterpreted.
- Do not repeat long negative lists several times. Keep positive artistic direction dominant and place the concise prohibitions at the end.
- Do not translate source fidelity into complete rendering. Preserve structure, then deliberately stop.
- Do not describe the result as precise, highly detailed, polished, refined, photorealistic, or an accurate reconstruction.
- Do not use a watercolor-photo filter look, uniform paper overlay, embossed texture, repeated digital dabs, or neatly completed edges.
- Do not invent ancient costumes, monks, fishermen, temples, mountains, red suns, birds, calligraphy, seals, or decorative frames unless they exist in the photograph or the user asks for them.

## Revisions

If the user approves the painted content and only asks for more blank space, outpaint the canvas: preserve the approved image as one locked visual unit, scale or reposition it, and extend only quiet warm paper. Do not regenerate the subject.

For a local defect such as a face, hand, foliage patch, or pasted-looking boat, perform a local edit while locking the rest of the approved image. Do not rerender the full scene unless the user asks.
