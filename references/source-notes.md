# Source Notes

This design-reference project was distilled from three user-provided HTX Skill packages.

## `htx-brand.skill`

Contributes:
- `brand-blue` and `vip-gold` theme systems;
- brand colors and gradients;
- typography intent and weight rules;
- logo placement and safe-area rules;
- blue-white split layout logic;
- long-form / complex campaign hierarchy;
- strict anti-decoration and copy-fidelity constraints;
- background library selection rules.

## `htx-social-poster.skill`

Contributes:
- `big-number-grid` layout;
- `soft-information` layout;
- blue-grid and soft-blue-white backgrounds;
- poster-specific spacing, logo and title behavior;
- fast social-poster family routing.

## `htx-huobao-fast.skill`

Contributes:
- Huobao character identity invariants;
- character-safe composition and text-safe regions;
- reward-number yellow `#FFC800`;
- blue background normalization;
- mascot / prop / crop / logo interaction constraints.

## Derived vs source-grounded

The six family definitions are source-grounded abstractions.

`web-ui`, `ppt-pdf` and `infographic` adapters are derived extensions built from those source rules. They should be treated as design-system extrapolations, not as claims about an official HTX web or presentation standard.
