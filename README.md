# Lother

**Product / Full-stack Engineer**

I build web and native products, plus Windows automation tools, with a focus on application workflows, account data, and recovery from failed operations. My portfolio combines public source with a documented private product case study.

## Featured work

### [Classmate](case-studies/classmate/README.md)

A camera-based social game with a native iOS app, web client, and shared account, media, and AI services.

- **Work I maintain:** SwiftUI capture and room flows, shared APIs, mobile authentication, private media lifecycle, and AI quota/spend controls.
- **Engineering evidence:** transactional session rotation, retryable media cleanup, and server-owned capabilities. The October 6, 2026 local audit recorded **462 passing tests, 23 skips, and a passing typecheck**; the native physical-device target compiled with signing disabled.
- **Stack:** Swift / SwiftUI · AVFoundation · Vision · SpriteKit · TypeScript / Next.js · PostgreSQL · private Blob storage.
- [Public case study: screenshots, architecture, and three technical decisions](case-studies/classmate/README.md) · [Hosted sign-in entrance](https://classmate-you-look-a-little-handsom.vercel.app/). Active development; application source is private.

### [TBTI Affiliate Agent](https://github.com/Lother13501350/tbti-affiliate-agent)

An affiliate operations MVP for managing product links, attributing clicks, importing order reports, and reviewing AI optimization proposals.

- **Work I maintain:** admin workflows, PostgreSQL records, affiliate-platform adapters, CSV imports, and constrained AI proposal execution.
- **Engineering evidence:** imports deduplicate files and platform/order IDs; the optimizer submits proposals for human review. Typecheck, lint, and production build passed locally on October 6, 2026. Automated domain tests remain a gap.
- **Stack:** TypeScript · Next.js · React · Neon PostgreSQL · OpenAI / Claude integrations.
- [Source, local setup, and offline screenshot](https://github.com/Lother13501350/tbti-affiliate-agent). The hosted instance is an operations service with protected administration.

### [PalRelay](https://github.com/Lother13501350/palrelay)

A Windows toolkit that lets friends take turns hosting one Palworld world, with saves synchronized through Google Drive.

- **Work I maintain:** the PowerShell session protocol, C# WPF interface, save versioning, and migration/recovery tooling.
- **Engineering evidence:** nonce-based advisory locks, SHA-256 download checks, publish-before-unlock ordering, and offline cloud tests. The last source CI run recorded **65 passing checks**; downloadable **v0.6.1** is available.
- **Stack:** PowerShell · C# / WPF · Python · rclone · GitHub Actions.
- [Source and architecture](https://github.com/Lother13501350/palrelay) · [Windows releases](https://github.com/Lother13501350/palrelay/releases).

## Technical stack

| Area | Technologies used in the featured work |
| --- | --- |
| Languages | Swift, TypeScript, JavaScript, PowerShell, Python, C# |
| Web | React, Next.js App Router, Auth.js |
| Native | SwiftUI, AVFoundation, Vision, SpriteKit, Keychain, StoreKit |
| Data and integration | PostgreSQL / Neon, private Blob media, CSV imports, affiliate adapters, Google Drive via rclone |
| Desktop and automation | WPF, PowerShell, save migration tooling |
| AI | API-backed classification and advisory agents with application-controlled writes |
| Delivery | Git, GitHub Actions, Vercel |

## Current focus

Making product workflows reproducible: explicit setup, constrained automation, useful verification, and documented failure/recovery behavior. I use AI-assisted development and verify the resulting behavior against source code and executable checks.

## Contact

For Classmate or portfolio questions, [open a profile issue](https://github.com/Lother13501350/Lother13501350/issues). For public-source projects, use their repository issues. Implementation scope, verification limits, and source or case-study links are listed above.
