# Screenshot manifest

Every image is captured by the knowledge pipeline's shots flow (Playwright
against a live supervisor UI). Captures are FULL-PAGE scrolls (sticky
chrome hidden), taken after hydration with a double blur pass — sensitive
values (supervisor/node/user names, CIDRs/IPs, MACs, LUN WWIDs) are
blurred in-browser before capture; late-rendered rows get a second sweep.
The UI route and platform version enable drift-driven retakes.

| Image | Page | UI route | Version | Captured |
| --- | --- | --- | --- | --- |
| platform-health/onboarding-wizard-status.png | platform-health/overview | /s/{supervisor}/onboarding (full page) | v1.47.0 | 2026-08-16 |
| platform-health/infrastructure-board.png | platform-health/infrastructure | /s/{supervisor}/infrastructure (full-page composite: SAN + hosts with live load + GPU inventory from a GPU supervisor) | v1.47.0 | 2026-08-16 |
| networking/networking-overview.png | networking/overview | /s/{supervisor}/networking (full page) | v1.47.0 | 2026-08-16 |
| supervisor-overview.png | concepts/supervisors-and-clusters | /s/{supervisor} | pre-manifest (Pencil render) | 2026-08-12 |
| supervisor-infrastructure.png | concepts/supervisors-and-clusters | /s/{supervisor}/infrastructure | pre-manifest (Pencil render) | 2026-08-12 |
| projects-list.png | concepts/projects | /s/{supervisor}/projects | pre-manifest (Pencil render) | 2026-08-12 |
