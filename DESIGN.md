---
name: Lother Lab
description: A mint-accented pixel-art Taiwanese night studio for web products and automation.
colors:
  ink: "#101b28"
  petrol: "#152d39"
  outline: "#385565"
  mint: "#82cecb"
  amber: "#efbb76"
  ivory: "#f4eee2"
  muted: "#a2bdc8"
typography:
  badge-label:
    fontFamily: "Arial, Helvetica, sans-serif"
    fontSize: "13px"
    fontWeight: 600
  process-title:
    fontFamily: "Arial, Helvetica, sans-serif"
    fontSize: "24px"
    fontWeight: 600
rounded:
  badge: "5px"
  process: "8px"
components:
  tech-badge:
    backgroundColor: "{colors.petrol}"
    textColor: "{colors.ivory}"
    typography: "{typography.badge-label}"
    rounded: "{rounded.badge}"
    height: "36px"
---

# Design System: Lother Lab

## Overview

**Creative North Star: "Lother Lab — the Taiwanese night studio."**

This GitHub profile extends the existing mint avatar through a quiet pixel-art workstation, travel maps, and a Taiwanese city at night. Ivory lettering, a mint monitor, and warm lamplight frame the focus on web products and automation.

The surface mode is **Experience**: the banner leads, then native GitHub Markdown supports reading and repository discovery. This document governs this GitHub profile repository and its visual assets.

## Colors

The frontmatter records the exact authored SVG palette. The generated illustration uses related tonal variation rather than flat token fills.

- **Primary — Mint:** technology glyphs and process nodes; carries the avatar identity into local assets.
- **Secondary — Amber:** the single decorative process pulse and the banner's warm-light character.
- **Neutral — Ink:** process background and the banner's dark visual anchor.
- **Neutral — Petrol:** technology badge surfaces.
- **Neutral — Outline:** badge borders and process connectors.
- **Neutral — Ivory:** SVG labels and the banner's prominent lettering.
- **Neutral — Muted:** supporting process captions.

GitHub owns the surrounding light or dark shell, body text, and links. Keep authored labels legible within their own dark asset surfaces in either theme.

## Typography

GitHub controls the README's body, headings, links, and inline code. Do not introduce a webfont or promise custom Markdown typography.

The hero's large ivory **Lother** lettering and mint **WEB PRODUCTS × AUTOMATION** subtitle are part of the image. They are authored lettering, not a reusable installed font. Keep both lines clear of illustration detail and retain equivalent text in the image alternative.

SVG labels use the Arial/Helvetica sans-serif stack recorded above. Process captions are regular weight, with a smaller desktop size (15px) and a larger mobile size (19px).

## Layout

The hero fills the README width and keeps its wide composition: lettering on the left, studio and city on the right. Native headings and paragraphs supply the remaining spacing; no external stylesheet is involved.

The reading order is banner → short bilingual introduction → two rows of local technology badges → **From the lab** → **How I build**. TBTI Affiliate Agent and PalRelay are the two visible featured projects. Native `<details>` discloses pc-steward, Travel Agency Website, and ChillOut Marketing Dashboard under **More from the lab**. Preserve this distinction when maintaining the profile's current hierarchy.

The process uses a responsive `<picture>`: `workflow.svg` is horizontal (1000 × 118); `workflow-mobile.svg` is vertical (420 × 258), selected at `max-width: 600px`. Both share the same three labels and captions. The image scales to the available README width. Technology badges stay at a height of 36px and wrap naturally on narrow screens.

## Elevation & Depth

Authored SVGs are flat, with tonal surfaces and fine borders rather than shadows. Depth belongs to the hero's pixel-art scene: layered city silhouettes, window reflections, and desk lighting. GitHub supplies its native page and disclosure treatments.

## Shapes

The banner has a full-bleed rectangular silhouette. Badges have modest curved corners (5px); the process panel uses slightly larger curves (8px). Mint circular nodes and thin connectors keep the process diagram simple and readable.

## Components

- **Hero:** local `assets/hero.webp`, with informative alternative text. Preserve the night-studio composition and both lettering lines. Generation and conversion provenance are documented in [assets/README.md](assets/README.md).
- **Technology badges:** local SVGs with mint glyphs, ivory labels, petrol fills, and outline borders. They name TypeScript, React, Next.js, PostgreSQL, PowerShell, Python, and GitHub Actions; they imply neither proficiency scores nor certifications. Each SVG includes a title and accessible image label.
- **Project entries:** native headings, linked repository names, short descriptions, and inline-code technology lists. Keep descriptions grounded in the linked source and use the native disclosure for the additional projects.
- **Process:** one amber pulse moves through idea → build → ship over a seven-second cycle using `cubic-bezier(.16,1,.3,1)`. Its direction changes between horizontal and vertical assets. It illustrates an approach and is not live status. Static labels and nodes carry the full meaning. `prefers-reduced-motion: reduce` removes the animation and hides the pulse.

## Do's and Don'ts

- **Do** preserve the mint avatar connection, Taiwanese night-studio imagery, and readable native GitHub content.
- **Do** maintain alt text, SVG titles/descriptions, equivalent process copy at both sizes, and the reduced-motion rule.
- **Do** keep asset origins and the exact hero prompt alongside the shipping files.
- **Don't** add invented metrics, unsupported project claims, external statistics widgets, or additional competing motion.
- **Don't** treat the decorative pulse as a service-health or deployment indicator.
