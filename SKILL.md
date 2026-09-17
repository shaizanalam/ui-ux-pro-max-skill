---
name: ui-ux-pro-max
description: >-
  UI/UX design intelligence for web, mobile, and desktop. This skill should be used when designing, building, reviewing, or fixing interfaces, including pages, components, design systems, accessibility, interaction, responsive layout, typography, color, charts, and stack-specific UI implementation. Searchable local data: 79 searchable styles (50 active), 192 product palettes and reasoning profiles, 74 font pairings, 119 UX guidelines, 105 icons, 17 GSAP presets, 25 chart types, and 22 stacks.
---

# UI/UX Pro Max Skill

Comprehensive UI/UX design intelligence for web, mobile, and desktop applications.

## Sub-skills

This skill bundles several sub-skills located in `cli/assets/skills/`:

| Sub-skill | SKILL.md Location | Purpose |
|-----------|-------------------|---------|
| **design** | `cli/assets/skills/design/SKILL.md` | Unified design: brand, tokens, UI, logo, CIP, slides, banners, social photos, icons |
| **brand** | `cli/assets/skills/brand/SKILL.md` | Brand identity, voice, assets |
| **ui-styling** | `cli/assets/skills/ui-styling/SKILL.md` | UI components, Tailwind, shadcn/ui styling |
| **design-system** | `cli/assets/skills/design-system/SKILL.md` | Design system tokens and specs |
| **slides** | `cli/assets/skills/slides/SKILL.md` | HTML presentations and pitch decks |
| **banner-design** | `cli/assets/skills/banner-design/SKILL.md` | Banner design for social, ads, web, print |

## Local Data

The `src/ui-ux-pro-max/data/` directory contains searchable design data:

- `styles.csv` – 79 searchable UI styles (50 active)
- `colors.csv` / `products.csv` – 192 product palettes and reasoning profiles
- `typography.csv` – 74 font pairings
- `ux-guidelines.csv` – 119 UX guidelines
- `icons.csv` – 105 icon references
- `motion.csv` – 17 GSAP animation presets
- `charts.csv` – 25 chart types
- `stacks/` – 22 stack-specific guides

## Search Script

Use `src/ui-ux-pro-max/scripts/search.py` to query the local CSV data:

```
python search.py --query "glassmorphism" --file styles.csv
```

## When to Use

Activate this skill when:
- Designing or building any user interface
- Choosing color palettes, fonts, or typography
- Implementing responsive layouts
- Creating design systems or component libraries
- Building accessible, modern web UIs
- Adding animations or micro-interactions
- Reviewing or fixing UI/UX issues
