# ATP019 — FluxCD

An Astrona **training path**: a course track that groups training series
(`ATSxxx`) as its domains. Each stage in `path.yaml` is one domain and points
at the repository that teaches it. There is no official Flux certification
exam, so the domains and weights are Astrona's own and `examPreparation` is
off.

| Stage | Domain | Weight | Content | Status |
| --- | --- | --- | --- | --- |
| STG001 | Fundamentals & GitOps Toolkit Architecture | 10 % | [ATS094](https://github.com/astrona-io/ATS094) | Draft, written, not yet run |
| STG002 | Source Controller & Repository Management | 20 % | [ATS095](https://github.com/astrona-io/ATS095) | Draft, written, not yet run |
| STG003 | Kustomize & Helm Controller Reconciliation | 25 % | [ATS096](https://github.com/astrona-io/ATS096) | Draft, written, not yet run |
| STG004 | Secret Management, SOPS & Webhook Receivers | 15 % | [ATS097](https://github.com/astrona-io/ATS097) | Draft, written, not yet run |
| STG005 | Image Automation & Progressive Delivery | 15 % | [ATS098](https://github.com/astrona-io/ATS098) | Draft, written, not yet run |
| STG006 | Multi-Tenancy, Enterprise Operations & Cluster Management | 15 % | [ATS099](https://github.com/astrona-io/ATS099) | Draft, written, not yet run |

The site picks it up through [astrona-content](https://github.com/astrona-io/astrona-content):
a file in `courses/` that points at this repository, and the content sync
builds the course — one section per stage, with the readings, playgrounds and
labs each stage repository lists in its `astrona.yaml`. That course file does
not exist yet; add it when the first stage is ready to show.
