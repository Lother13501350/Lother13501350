# Profile assets

These assets belong to the Lother Lab GitHub profile. Visual maintenance guidance is in [DESIGN.md](../DESIGN.md).

| Asset | Source and purpose |
| --- | --- |
| `hero.webp` | AI-generated pixel-art Taiwanese night studio, with the lettering “Lother” and “WEB PRODUCTS × AUTOMATION.” Generated with the built-in ImageGen tool, then faithfully converted from the original PNG with `cwebp` for delivery. |
| `hero.prompt.txt` | Exact generation prompt, including composition, wording, palette, and constraints. |
| `hero.webp.json` | Companion generation provenance: the exact prompt and creation timestamp. |
| `workflow.svg` | Authored horizontal idea → build → ship diagram (1000 × 118). |
| `workflow-mobile.svg` | Authored vertical equivalent (420 × 258), selected by the README's `<picture>` at `max-width: 600px`. |
| `tech/*.svg` | Local, consistently styled technology badges. Icon origins are recorded below and in `origins.json`. |

## Hero provenance

The unmodified generated PNG is preserved in the author's local design archive, outside this repository. `hero.webp` is the shipping conversion, not a separately generated variant. Keep the original and companion prompt/provenance files when replacing or re-encoding the banner; record any new generation or material edit explicitly.

## Icon provenance

TypeScript, React, Next.js, PostgreSQL, Python, and GitHub Actions glyphs come from **Simple Icons**, licensed **CC0-1.0**, pinned to commit `4ba19240849175ab4b855a732ab98c0f87cfb714`. [origins.json](origins.json) contains each exact source URL. Badge backgrounds, borders, labels, placement, and palette are authored locally. Brand trademark rights are separate from the icon-source license.

The PowerShell badge uses a locally authored terminal glyph; it is not a Simple Icons asset. Both process diagrams are authored SVGs.

## Maintenance

- Keep assets local to avoid third-party widget dependencies.
- Preserve SVG titles and descriptions, README alternative text, and equivalent process labels in both layouts.
- Keep only one decorative pulse in the selected process asset. Both variants stop and hide it under `prefers-reduced-motion: reduce`; the process remains understandable without motion.
- Verify the README on desktop and mobile, in GitHub light and dark themes, after changing dimensions, lettering, disclosure structure, or assets.
