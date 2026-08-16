# Screenshot manifest

Every image is captured by the knowledge pipeline's shots flow (Playwright
against a live supervisor UI) with sensitive values — supervisor/node/user
names, CIDRs/IPs, LUN WWIDs — blurred in-browser before capture. The UI
route and platform version enable drift-driven retakes.

| Image | Page | UI route | Version | Captured |
| --- | --- | --- | --- | --- |
| platform-health/onboarding-wizard-status.png | platform-health/overview | /s/{supervisor}/onboarding | v1.47.0 | 2026-08-16 |
| platform-health/infrastructure-board.png | platform-health/infrastructure | /s/{supervisor}/infrastructure (composite: SAN board + GPU inventory from a GPU supervisor) | v1.47.0 | 2026-08-16 |
| networking/networking-overview.png | networking/overview | /s/{supervisor}/networking | v1.47.0 | 2026-08-16 |
| supervisor-overview.png | concepts/supervisors-and-clusters | /s/{supervisor} | pre-manifest (Pencil render) | 2026-08-12 |
| supervisor-infrastructure.png | concepts/supervisors-and-clusters | /s/{supervisor}/infrastructure | pre-manifest (Pencil render) | 2026-08-12 |
| projects-list.png | concepts/projects | /s/{supervisor}/projects | pre-manifest (Pencil render) | 2026-08-12 |
