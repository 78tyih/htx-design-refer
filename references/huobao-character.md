# Huobao Character System

This file preserves only the source-grounded character rules needed for design-reference work.

## Identity invariants

From the supplied Huobao Skill:

- blue T-shirt;
- official white flame mark on the chest;
- blue horn / recognizable Huobao face and character identity;
- bare hands and bare feet in source generation;
- no gloves;
- no shoes;
- no shorts;
- normal compact body / T-shirt proportions;
- preserve hands, face, horn and campaign props.

## Poster composition

- keep the left ~50% low-detail and text-safe when generating a character scene;
- place Huobao primarily center-right / lower-right;
- keep upper-right official-logo area clean;
- final social composition usually crops to upper body naturally from the bottom;
- do not simulate crop by erasing, masking or making limbs disappear.

## Background

Normalize the independent background layer to:

- top: `#0066FF`
- bottom: `#2692FF`

Do not globally recolor the character, props or logo to force brand matching.

## Reward emphasis

If the user copy contains a literal `$`, the source skill permits 1–2 metallic gold dollar coins in the character scene and uses `#FFC800` for core reward expressions in the final title.

Do not add coins merely to fill empty space when the content does not warrant them.

## Avoid

- glowing network lines;
- trajectory/orbit lines;
- floating UI badges;
- random decorative icons;
- generated text inside the character scene;
- extra logos;
- character costume changes unsupported by source material;
- props crossing into the text-safe or logo-safe regions.
