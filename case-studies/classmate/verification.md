# Classmate verification notes

Recorded October 6, 2026. This is a summarized local verification record for a private application checkout. Raw build logs and application source are not included in the public portfolio.

| Check | Recorded result | What it establishes |
| --- | --- | --- |
| `npm run typecheck` | Passed | TypeScript checking of the audited checkout |
| `npm test` | 485 tests: 462 passed, 23 skipped, 0 failed | Credential-free Node checks, including domain behavior, test doubles, and source/contract assertions |
| Native build | Build succeeded for a physical iPhone 17 target, signing disabled | Native compilation; no installation or runtime acceptance |
| Hosted web entrance | Opened and captured while signed out | Public entrance renders; authenticated product flows were not exercised |
| Archived native screenshots | Reviewed before publication | Earlier app UI in empty preview states; no personal photos, messages, or account records |

The Node run used no production database or paid AI credentials. Database-dependent skips are not passing integration tests. The commands require the private checkout and its dependencies; this portfolio repository contains documentation and images only.

## Decision-specific evidence

- **Identity:** reviewed provider-to-account mapping, opaque-token hashing, transaction/row-lock refresh rotation, and token/identity tests. Real database refresh races were not exercised in the credential-free run.
- **Media:** reviewed asset validation and registry checks, live-reference authorization, deletion tombstones, transactional reference revocation, and durable external cleanup scheduling. Production storage deletion/retry was not exercised.
- **AI:** reviewed server-side gates and the spend wrapper. Mocked-provider and deterministic-store tests cover budget rejection and conservative settlement after provider failures. Actual provider costs and database contention were not measured.

## Release limits

Browser end-to-end and XCTest targets exist, but were not run in this audit. Signed installation, live authentication, StoreKit purchase/restoration, APNs delivery, and account-deletion acceptance require an available physical iPhone and isolated test services. No iOS Simulator was used.

The latest hosted CI jobs observed during the audit did not start because of an account execution limit; local results are separate from hosted CI. Dependency advisories still need review and regression checks before a release-readiness claim.

[Return to the case study](README.md).
