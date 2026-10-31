# OpenStack

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Open source cloud computing platform for building and managing public and private clouds, providing infrastructure as a service (IaaS) through a set of interrelated services including Compute (Nova), Object Storage (Swift), Block Storage (Cinder), Networking (Neutron), Identity (Keystone), Image (Glance), Orchestration (Heat), Database (Trove), DNS (Designate), and Load Balancer (Octavia). Each service exposes its own REST API; clients authenticate against Keystone and use the returned service catalog to discover per-region endpoints for the remaining services.

**Areas:** OpenStack · Cloud Platform · Infrastructure-as-a-Service · Open Source · Virtualization · Linux Foundation

## OpenStack on APIs.io

Everything profiled for OpenStack is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/openstack/](https://apis.io/providers/openstack/)** — or go straight to one of the APIs or properties below.

### APIs (22)

- [OpenStack Networking (Neutron) API](https://apis.io/apis/openstack/neutron/) — Neutron provides networking as a service, exposing endpoints for networks, subnets, ports, routers, floating IPs, security groups, load balancers,…
- [OpenStack Block Storage (Cinder) API](https://apis.io/apis/openstack/cinder/) — Cinder provides persistent block-level storage volumes that can be attached to Nova instances. The v3 API exposes endpoints for volumes, snapshots, backups,…
- [OpenStack Object Storage (Swift) API](https://apis.io/apis/openstack/swift/) — Swift is the OpenStack object storage service. The API exposes endpoints for accounts, containers, and objects with eventual- consistency replication,…
- [OpenStack Image (Glance) API](https://apis.io/apis/openstack/glance/) — Glance manages disk and server images. The v2 API exposes endpoints for images, image members, image tags, image data upload/download, tasks, schemas, and…
- [OpenStack Orchestration (Heat) API](https://apis.io/apis/openstack/heat/) — Heat is the OpenStack orchestration service that manages infrastructure-as-code deployments via HOT (Heat Orchestration Template) and AWS…
- [OpenStack Load Balancer (Octavia) API](https://apis.io/apis/openstack/octavia/) — Octavia provides Load Balancing as a Service. The v2 API exposes endpoints for load balancers, listeners, pools, members, health monitors, L7 policies and…
- [OpenStack DNS (Designate) API](https://apis.io/apis/openstack/designate/) — Designate is the OpenStack DNS-as-a-Service. The v2 API exposes endpoints for zones, recordsets, pools, transfers, and TSIG keys.
- [OpenStack Database (Trove) API](https://apis.io/apis/openstack/trove/) — Trove is the OpenStack Database-as-a-Service that provisions and manages database instances (MySQL, PostgreSQL, MongoDB, Redis, MariaDB, Cassandra, etc.) on…
- [OpenStack Domains API](https://apis.io/apis/openstack/openstack-domains-api/) — Domain management for multi-tenancy.
- [OpenStack Endpoints API](https://apis.io/apis/openstack/openstack-endpoints-api/) — Service endpoint URLs per region and interface.
- [OpenStack Flavors API](https://apis.io/apis/openstack/openstack-flavors-api/) — Compute instance flavors.
- [OpenStack Groups API](https://apis.io/apis/openstack/openstack-groups-api/) — Group management.
- [OpenStack Images API](https://apis.io/apis/openstack/openstack-images-api/) — Image references.
- [OpenStack Keypairs API](https://apis.io/apis/openstack/openstack-keypairs-api/) — SSH key pair management.
- [OpenStack Projects API](https://apis.io/apis/openstack/openstack-projects-api/) — Project (tenant) management.
- [OpenStack Roles API](https://apis.io/apis/openstack/openstack-roles-api/) — Role definitions and assignments.
- [OpenStack Server Actions API](https://apis.io/apis/openstack/openstack-server-actions-api/) — Lifecycle actions on servers.
- [OpenStack Servers API](https://apis.io/apis/openstack/openstack-servers-api/) — Compute instance management.
- [OpenStack Services API](https://apis.io/apis/openstack/openstack-services-api/) — Service catalog entries.
- [OpenStack Tokens API](https://apis.io/apis/openstack/openstack-tokens-api/) — Issue and validate authentication tokens.
- [OpenStack Users API](https://apis.io/apis/openstack/openstack-users-api/) — User management.
- [OpenStack Versions API](https://apis.io/apis/openstack/openstack-versions-api/) — API version discovery.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Openstack Agentic Access](https://apis.io/agentic-access/openstack/openstack-agentic-access/)

#### JSON Schema (1)

The data models the API reads and writes.

- [OpenStack Nova Server](https://apis.io/schemas/openstack/openstack-server/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Openstack Context](https://apis.io/jsonld/openstack/openstack-context/)

#### Collections (16)

Postman and Open Collection request collections.

- [OpenStack Identity (Keystone) API v3 Domains API](https://apis.io/collections/openstack/open-openstack-domains-api/)
- [OpenStack Identity (Keystone) API v3 Domains Endpoints API](https://apis.io/collections/openstack/open-openstack-endpoints-api/)
- [OpenStack Identity (Keystone) API v3 Domains Flavors API](https://apis.io/collections/openstack/open-openstack-flavors-api/)
- [OpenStack Identity (Keystone) API v3 Domains Groups API](https://apis.io/collections/openstack/open-openstack-groups-api/)
- [OpenStack Identity (Keystone) API v3 Domains Images API](https://apis.io/collections/openstack/open-openstack-images-api/)
- [OpenStack Identity (Keystone) API v3 Domains Keypairs API](https://apis.io/collections/openstack/open-openstack-keypairs-api/)
- [OpenStack Identity (Keystone) API v3](https://apis.io/collections/openstack/open-openstack-keystone/)
- [OpenStack Compute (Nova) API](https://apis.io/collections/openstack/open-openstack-nova/)
- [OpenStack Identity (Keystone) API v3 Domains Projects API](https://apis.io/collections/openstack/open-openstack-projects-api/)
- [OpenStack Identity (Keystone) API v3 Domains Roles API](https://apis.io/collections/openstack/open-openstack-roles-api/)
- [OpenStack Identity (Keystone) API v3 Domains Server Actions API](https://apis.io/collections/openstack/open-openstack-server-actions-api/)
- [OpenStack Identity (Keystone) API v3 Domains Servers API](https://apis.io/collections/openstack/open-openstack-servers-api/)
- [OpenStack Identity (Keystone) API v3 Domains Services API](https://apis.io/collections/openstack/open-openstack-services-api/)
- [OpenStack Identity (Keystone) API v3 Domains Tokens API](https://apis.io/collections/openstack/open-openstack-tokens-api/)
- [OpenStack Identity (Keystone) API v3 Domains Users API](https://apis.io/collections/openstack/open-openstack-users-api/)
- [OpenStack Identity (Keystone) API v3 Domains Versions API](https://apis.io/collections/openstack/open-openstack-versions-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [OpenStack — jsonschema rules](https://apis.io/rules/openstack/openstack-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Openstack Authentication](https://apis.io/security/openstack/openstack-authentication/)
- [Openstack Domain Security](https://apis.io/security/openstack/openstack-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Openstack Plans Pricing](https://apis.io/plans/openstack/openstack-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Openstack Rate Limits](https://apis.io/rate-limits/openstack/openstack-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Openstack Finops](https://apis.io/finops/openstack/openstack-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.openstack.org/)
- [Documentation](https://docs.openstack.org/api-ref/)
- [Getting started](https://docs.openstack.org/api-quick-start/)
- [Blog](https://www.openstack.org/blog/)
- [Terms of service](https://www.openstack.org/legal/)
- [GitHub](https://github.com/openstack)

## API Evangelist rating

**Kin Score 36.1** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 54.7 |
| Contract governance | 9.8 |
| Operational transparency | 10.5 |
| Developer ergonomics | 50.0 |
| Access clarity | 15.8 |

**Agent readiness 17.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 20.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/openstack/](https://apis.io/providers/openstack/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for OpenStack: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/openstack/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
