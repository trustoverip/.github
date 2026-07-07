# Trust Over IP (ToIP)

[#trust-over-ip-toip](#trust-over-ip-toip)
> A digital trust project of the [Linux Foundation Decentralized Trust](https://www.lfdecentralizedtrust.org), defining a robust, common standard and complete architecture for Internet-scale digital trust.
---

## Table of Content

[#table-of-content](#table-of-content)

- [Latest Updates](#latest-updates)
- [About This Repository](#about-this-repository)
- [ToIP Overview](#toip-overview)
- [ToIP Architecture](#toip-architecture)
- [What ToIP Enables](#what-toip-enables)
- [Working Group Repositories and Discussions](#working-group-repositories-and-discussions)
- [Resources](#resources)
- [How to Participate](#how-to-participate)
- [Licensing](#licensing)

---


<!-- TODO: Populate with recent deliverable/document updates, similar to DTGWG's Latest Updates table. -->

## About This Repository

[#about-this-repository](#about-this-repository)

This is the umbrella repository for **Trust Over IP (ToIP)**. It is designed to serve as an entry point to our work and a guide to all our resources.

It links to the individual repositories maintained by each ToIP Working Group and Task Force, where corresponding specifications, deliverables, and discussions live.

ToIP was founded in May 2022 to develop a protocol stack (the ToIP stack) modeled after the same four layers as the TCP/IP stack. The repos hosted here represent three generations of evolution of ToIP deliverables:

1. Repos started before 2023 contain deliverables produced by the first generation of Working Groups and Task Forces — largely exploratory or advisory.
2. Repos dating from ~2023 transitioned into deliverables intended to become full ToIP Approved Deliverables, using the first standard ToIP specification template (based on the ISO spec model).
3. Repos created in 2026 mostly represent deliverables intended to become full ToIP Approved Deliverables, with technical specifications using the new ToIP specification template (based on the IETF RFC model).

[↑ Back to top](#trust-over-ip-toip)

---

## ToIP Overview

[#toip-overview](#toip-overview)

Trust Over IP defines an architecture for Internet-scale digital trust. It combines cryptographic assurance at the machine layers with human accountability at the business, legal, and social layers.

ToIP combines two complementary halves:

- **Technology protocols** — Cryptographic and technical mechanisms that support trustworthy digital interactions.
- **Governance controls** — Business, legal, policy, and social rules that make trust ecosystems accountable and interoperable.

Together, these two halves form a four-layer architecture for decentralized digital trust infrastructure.

[↑ Back to top](#trust-over-ip-toip)

---

## ToIP Architecture

[#toip-architecture](#toip-architecture)

Trust Over IP is organized around a four-layer, dual-stack architecture:

- **Layer 1: Utility Layer** — Foundational infrastructure such as networks, ledgers, identifiers, cryptographic utilities, and registries.
- **Layer 2: Agent Layer** — Software agents, wallets, services, and endpoints that exchange trusted data and messages.
- **Layer 3: Credential Exchange Layer** — Protocols and workflows for issuing, holding, presenting, verifying, and revoking credentials and other trustworthy data.
- **Layer 4: Ecosystem Layer** — Governance frameworks, trust registries, business rules, policies, and ecosystem-specific controls.

Each layer has both a technology side and a governance side because technical interoperability alone is not enough to establish trust at Internet scale.

[↑ Back to top](#trust-over-ip-toip)

---

## What ToIP Enables

[#what-toip-enables](#what-toip-enables)

Trust Over IP helps communities, organizations, and ecosystems:

- Define digital trust architectures
- Create interoperable trust frameworks
- Develop technical specifications for trusted digital interactions
- Connect decentralized identifiers, verifiable credentials, wallets, agents, and trust registries
- Establish governance frameworks for digital trust ecosystems
- Support trusted data exchange across organizations and jurisdictions
- Build reusable standards, protocols, and implementation guidance
- Improve security, privacy, and accountability in digital interactions

Example use cases include digital identity ecosystems, verifiable credential networks, trust registries and trust lists, digital wallets and credential exchange, supply chain trust, regulatory technology and compliance workflows, agent-to-agent digital trust, and cross-border/cross-sector trust frameworks.

[↑ Back to top](#trust-over-ip-toip)

---

## Working Group Repositories and Discussions

[#working-group-repositories-and-discussions](#working-group-repositories-and-discussions)

Each ToIP Working Group operates its own repositories and discussion forums. Please feel free to cross-link discussions that cross more than one Working Group or Task Force.

<!--TODO: check if descriptions and WG groupings are accurate-->

| Working Group | Focus Area | Repository | Discussions |
|---|---|---|---|
| **Keri Stack (KSWG)** | DID method specification for `did:webs`. | [kswg-did-method-webs-specification](https://github.com/trustoverip/kswg-did-method-webs-specification) | [Discussions](https://github.com/trustoverip/kswg-did-method-webs-specification/discussions) |
| **Keri Stack (KSWG)** | Key Event Receipt Infrastructure specification work. | [kswg-keri-specification](https://github.com/trustoverip/kswg-keri-specification) | [Discussions](https://github.com/trustoverip/kswg-keri-specification/discussions) |
| **Keri Stack (KSWG)** | Authentic Chained Data Containers specification work. | [kswg-acdc-specification](https://github.com/trustoverip/kswg-acdc-specification) | [Discussions](https://github.com/trustoverip/kswg-acdc-specification/discussions) |
| **Keri Stack (KSWG)** | Composable Event Streaming Representation specification work. | [kswg-cesr-specification](https://github.com/trustoverip/kswg-cesr-specification) | [Discussions](https://github.com/trustoverip/kswg-cesr-specification/discussions) |
| **Technical Stack (TSWG)** | DID method specification work related to X.509. | [tswg-did-x509-method-specification](https://github.com/trustoverip/tswg-did-x509-method-specification) | [Discussions](https://github.com/trustoverip/tswg-did-x509-method-specification/discussions) |
| **Technical Stack (TSWG)** | Trust Spanning Protocol specification. | [tswg-tsp-specification](https://github.com/trustoverip/tswg-tsp-specification) | [Discussions](https://github.com/trustoverip/tswg-tsp-specification/discussions) |
| **Technical Stack (TSWG)** | Trust Registry Query Protocol specification work. | [tswg-trust-registry-protocol](https://github.com/trustoverip/tswg-trust-registry-protocol) | [Discussions](https://github.com/trustoverip/tswg-trust-registry-protocol/discussions) |
| **Decentralized Trust Graph (DTGWG)** | Trust Tasks work for transport-agnostic task management. | [dtgwg-trust-tasks-tf](https://github.com/trustoverip/dtgwg-trust-tasks-tf) | [Discussions](https://github.com/trustoverip/dtgwg-trust-tasks-tf/discussions) |
| **AI & Agentic Identity (AIMWG)** | TSP-enabled AI agent protocols specification work. | [aimwg-tsp-enabled-ai-agent-protocols](https://github.com/trustoverip/aimwg-tsp-enabled-ai-agent-protocols) | [Discussions](https://github.com/trustoverip/aimwg-tsp-enabled-ai-agent-protocols/discussions) |

<!-- TODO: Confirm which repositories should be highlighted as official first-starting points for new contributors. -->

> For the full umbrella view of the Decentralized Trust Graph Working Group specifically, see [dtgwg-general](https://github.com/trustoverip/dtgwg-general).

[↑ Back to top](#trust-over-ip-toip)

---

## Resources

[#resources](#resources)

- The [Trust Over IP project page](https://www.lfdecentralizedtrust.org/projects/trust-over-ip) gives an overview of the project, architecture, objectives, benefits, and community links.
- The [Trust Over IP website](https://www.trustoverip.org/) describes ToIP's mission, model, work, design principles, events, and working groups.
- The [Trust Over IP wiki](https://lf-toip.atlassian.net/wiki/) contains working group materials, meeting notes, deliverable information, and community documentation.
- The [ToIP Technology Architecture](https://trustoverip.org/our-work/technology-architecture/) describes the technical architecture work of the project.
- The [Trust Over IP model](https://trustoverip.org/toip-model/) explains the four-layer model that combines cryptographic trust and governance.
- The [Trust Over IP deliverables page](https://trustoverip.org/our-work/deliverables/) provides access to ToIP deliverables and specification work.
- The [Trust Over IP working group activity page](https://trustoverip.org/our-work/working-group-activity/) describes active working groups and participation areas.
- Watch Trust Over IP videos through the [LFDT YouTube playlists page](https://www.youtube.com/c/Hyperledger/playlists), which includes a Trust Over IP playlist.
- Watch the Trust Over IP 5th Anniversary Virtual Symposium: [Day 1](https://www.youtube.com/watch?v=1bOR7aEiz6k) and [Day 2](https://www.youtube.com/watch?v=MwnBALA8ygs).
- Our [Code of Conduct](https://www.lfdecentralizedtrust.org/code-of-conduct) describes expected behavior across the LFDT community.
- For security related issues, please follow the LFDT security reporting process. Do not post security related content, issues, or discussions publicly in any repository.

[↑ Back to top](#trust-over-ip-toip)

---

## How to Participate

[#how-to-participate](#how-to-participate)

1. Review the [Trust Over IP GitHub organization](https://github.com/trustoverip).
2. Explore the [Trust Over IP website](https://www.trustoverip.org/) and [wiki](https://lf-toip.atlassian.net/wiki/).
3. Join community discussions on [LFDT Discord](https://discord.lfdecentralizedtrust.org) — channel `#toip-general`.
4. Attend community meetings — ToIP community calls and working group meetings are open to all interested participants. See the [meeting calendar](https://zoom-lfx.platform.linuxfoundation.org/meetings/ToIP?view=month).
5. Choose a working group, task force, or repository that matches your area of interest from the table above.
6. Open issues for bugs, documentation gaps, specification questions, or feature ideas.
7. Submit pull requests with clear descriptions and links to related issues or working group discussions.

Past meeting recordings and presentations can be accessed through the [LFX Individual Dashboard](https://openprofile.dev/), the [LFDT Meeting Calendar](https://zoom-lfx.platform.linuxfoundation.org/meetings/lf-decentralized-trust), and the [LFDT YouTube playlists](https://www.youtube.com/c/Hyperledger/playlists).

For larger changes, please open an issue first so the community can discuss the design before implementation.

[↑ Back to top](#trust-over-ip-toip)

---

## Licensing

[#licensing](#licensing)

Trust Over IP repositories may contain specifications, governance materials, documentation, templates, and code. Licenses may vary by repository — please check the license file in each repository before reuse.

Further information is available on the [Trust Over IP wiki](https://lf-toip.atlassian.net/wiki/).

[↑ Back to top](#trust-over-ip-toip)

---

*This repository is the umbrella index for Trust Over IP. Specifications and deliverables
live in the Working Group and Task Force repositories linked in the table above.*