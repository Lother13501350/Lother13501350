# Lother

**Product / Full-stack Engineer**

I build web products and Windows automation tools, with a focus on application workflows, data integration, and recovery from failed operations. My public work uses TypeScript, React, Next.js, PostgreSQL, PowerShell, Python, and C#.

## Featured work

### [PalRelay](https://github.com/Lother13501350/palrelay)

A Windows toolkit that lets friends take turns hosting one Palworld world, with saves synchronized through Google Drive.

- **Work I maintain:** the PowerShell session protocol, C# WPF interface, save versioning, and migration/recovery tooling.
- **Engineering evidence:** nonce-based advisory locks, SHA-256 download checks, publish-before-unlock ordering, and offline cloud tests. The last source CI run recorded **65 passing checks**; downloadable **v0.6.1** is available.
- **Stack:** PowerShell · C# / WPF · Python · rclone · GitHub Actions.
- [Source and architecture](https://github.com/Lother13501350/palrelay) · [Windows releases](https://github.com/Lother13501350/palrelay/releases).

### [TBTI Affiliate Agent](https://github.com/Lother13501350/tbti-affiliate-agent)

An affiliate operations MVP for managing product links, attributing clicks, importing order reports, and reviewing AI optimization proposals.

- **Work I maintain:** admin workflows, PostgreSQL records, affiliate-platform adapters, CSV imports, and constrained AI proposal execution.
- **Engineering evidence:** imports deduplicate files and platform/order IDs; the optimizer submits proposals for human review. Typecheck, lint, and production build passed locally on October 6, 2026. Automated domain tests remain a gap.
- **Stack:** TypeScript · Next.js · React · Neon PostgreSQL · OpenAI / Claude integrations.
- [Source, local setup, and offline screenshot](https://github.com/Lother13501350/tbti-affiliate-agent). The hosted instance is an operations service with protected administration.

### [ChillOut Marketing Dashboard](https://github.com/Lother13501350/TREKX_Marketing)

A static workspace for campaign planning, editable metrics, content schedules, and JSON/CSV handoffs.

- **Work I maintain:** browser-side editing and persistence, data exports, generated travel tools, and static validation.
- **Engineering evidence:** local validation checked **256 HTML pages** on October 6, 2026. Edits stay in the current browser; there is no shared backend.
- **Stack:** JavaScript · HTML / CSS · localStorage · GitHub Actions.
- [Source](https://github.com/Lother13501350/TREKX_Marketing) · [Interactive workspace](https://chillout-marketing-dashboard.vercel.app/ops.html).

## Technical stack

| Area | Technologies used in these repositories |
| --- | --- |
| Languages | TypeScript, JavaScript, PowerShell, Python, C# |
| Web | React, Next.js App Router, Vite, Tailwind CSS |
| Data and integration | PostgreSQL / Neon, CSV imports, affiliate adapters, Google Drive via rclone |
| Desktop and automation | WPF, PowerShell, save migration tooling |
| AI | API-backed classification and advisory agents with application-controlled writes |
| Delivery | Git, GitHub Actions, Vercel |

## Current focus

Making product workflows reproducible: explicit setup, constrained automation, useful verification, and documented failure/recovery behavior. I use AI-assisted development and verify the resulting behavior against source code and executable checks.

## Contact

For project questions or technical discussions, open an issue in the relevant repository. Code, limitations, and setup instructions are linked above.
