---
name: htx-design-refer
description: "Apply a reusable HTX-inspired brand design reference system derived from user-supplied HTX brand, social-poster and Huobao skills. Includes six source-grounded visual families, medium routing, brand tokens, layout rules, quality gates and optional Huobao character guidance."
---

# HTX Design Refer

This Skill converts the supplied HTX production rules into a reusable **Design Reference / Style Router**.

It is intended for brand-consistent design work such as posters, long-form operation graphics, PPT/PDF, landing pages, information cards, campaign visuals and review tasks.

## 1. Source boundary

The source material for v0.1.0 is limited to three user-supplied skills:

- `htx-brand.skill`
- `htx-social-poster.skill`
- `htx-huobao-fast.skill`

The six visual families below are grounded in those source rules. Web/PPT adapters are derived extensions and should preserve the same tokens and hierarchy rather than inventing a separate HTX identity.

## 2. Brand equation

`clear commercial hierarchy + disciplined brand blue + high legibility + controlled campaign emphasis + strict asset placement`

In practice:

- communicate the business point before decoration;
- keep title, value, body and auxiliary information clearly separated;
- use HTX blue as a real brand field, not generic neon atmosphere;
- use yellow only for explicit Huobao reward-number emphasis;
- use white/black text according to actual background contrast;
- do not add visual ornaments the brief did not require.

## 3. Choose one primary family

Read `references/visual-families.md`.

1. `brand-blue-field`
2. `blue-grid-reward`
3. `soft-blue-information`
4. `blue-white-hero`
5. `vip-gold`
6. `huobao-character`

Do not average all families together.

## 4. Choose the medium

Source-grounded:
- `poster-social`
- `longform-operation`
- `huobao-fast`
- `review-only`

Derived adapters:
- `web-ui`
- `ppt-pdf`
- `infographic`

Read `references/medium-router.md` before using a derived adapter.

## 5. Core tokens

Read `references/brand-dna.md` and `tokens/htx.tokens.json`.

Key tokens:

- brand blue: `#0066FF`
- brand blue gradient: `#0066FF → #2692FF`, top to bottom
- VIP gold gradient: `#DEC48A → #F5ECD7`, top to bottom
- reward yellow in Huobao titles: `#FFC800`
- body black on white/light fields: `#000000`
- standard divider: `#E8E8E8`

Typography intent:
- Latin: Urbanist
- Chinese: HarmonyOS Sans SC
- maximum weight: 700
- use scale, spacing and position before heavier weight.

Font binaries are intentionally not redistributed in this repository. Use licensed/local copies in production environments.

## 6. Composition rules

Always:

- preserve the user's copy; do not invent promotional text unless asked;
- establish semantic hierarchy before layout;
- preserve safe margins and the top-right logo exclusion zone;
- prefer left-aligned title systems for campaign work;
- do not stretch background assets;
- do not recolor official supplied brand assets;
- use one primary visual system per output;
- remove empty illustration placeholders when no illustration is provided;
- use background partition, scale, spacing and rules before decorative graphics.

## 7. Logo discipline

For 1080×1080 social posters, source rules use:

- logo: 100×100
- top: 60 px
- right: 60 px

Other dimensions should preserve the same proportional safe-area logic.

Use supplied SVG assets directly. Do not redraw, filter, recolor or distort them.

## 8. Huobao rules

When `huobao-character` is active, also read `references/huobao-character.md`.

Huobao is a character system, not a generic decorative mascot. Preserve identity, blue T-shirt with white flame mark, clean text-safe region, theme-prop integrity and official logo separation.

Do not add Huobao to institutional/VIP or information-heavy work unless the content actually benefits from a mascot-led campaign.

## 9. Quality gate

Read `references/quality-gate.md`.

A strong result must pass:

1. brand-token fidelity;
2. semantic hierarchy;
3. copy fidelity;
4. readable typography;
5. logo and safe-area discipline;
6. correct family selection;
7. correct background treatment;
8. no unsupported decorative additions;
9. correct asset geometry and crop;
10. original composition without drifting into generic crypto/neon styling.

## 10. Originality and brand boundary

This is a user-created design reference built from user-supplied HTX skills and assets. It should not be presented as an official public brand manual unless the user confirms that status.

Preserve the supplied brand rules and visual assets; do not infer unsupported corporate policy, legal approval, or new brand standards.
