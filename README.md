# SPREE

![license](https://img.shields.io/badge/license-license-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-online_retail-lightgrey)

> Anticloud-hardened packaging of the upstream project `SPREE` in category **ONLINE RETAIL**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** ONLINE RETAIL · **Upstream:** https://github.com/spree/spree · **Upstream pin:** `4ca24b80ddff9b85aa0502757275f2b526a95268` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

<p>
  <a href="https://spreecommerce.org">
    <img src="https://spreecommerce.org/wp-content/themes/spree/images/logo.svg" alt="Spree Commerce open source headless eCommerce platform for B2B, Multi-seller Marketplace, cross-border eCommerce, multi-tenant eCommerce" width="250" />
  </a>
</p>

[Website](https://spreecommerce.org)
·
[Next.js Storefront](https://github.com/spree/storefront)
·
[Documentation](https://spreecommerce.org/docs/)
·
[API](https://spreecommerce.org/docs/api-reference/)
·
[Roadmap](https://github.com/spree/spree/milestones?direction=asc&sort=due_date&state=open)
·
[Discord](https://discord.spreecommerce.org)

[![Gem Total Downloads](https://img.shields.io/gem/dt/spree)](https://rubygems.org/gems/spree)
[![codecov](https://codecov.io/gh/spree/spree/graph/badge.svg?token=DPFc7HbJvU)](https://codecov.io/gh/spree/spree)
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

**Build commerce the way you want it.** Spree is an open-source commerce platform with a complete REST API, TypeScript SDKs, a React admin dashboard, and a production-ready Next.js storefront. BSD 3-Clause licensed — keep full ownership of your code, data, and infrastructure.

Teams use Spree to build **multi-vendor marketplaces** and **B2B and wholesale** channels, as well as headless DTC, cross-border and omnichannel selling — all from one set of commerce primitives, and all alongside the ERP, PIM, and payment systems you already run.

## Use Cases

Spree ships commerce primitives, so the same core serves very different businesses.

### [Multi-vendor Marketplace](https://spreecommerce.org/docs/developer/how-to/build-a-marketplace)

Seller onboarding with configurable requirement checklists, orders split per seller at completion, a flexible [commission engine](https://spreecommerce.org/docs/developer/core-concepts/commissions), a payout ledger with Stripe Connect, and a dedicated Seller Panel. All in the open-source core.

<img alt="Spree Commerce - Multi-vendor Marketplace eCommerce" src="https://github.com/spree/spree/assets/12614496/c4ddd118-df4c-464e-b1fe-d43862e5cf25" width="600" >

### [B2B & Wholesale](https://spreecommerce.org/docs/developer/how-to/build-a-b2b-store)

[Price lists](https://spreecommerce.org/docs/developer/core-concepts/pricing) with volume tiers, [customer groups](https://spreecommerce.org/docs/user/customers/customer-groups), [companies](https://spreecommerce.org/docs/developer/core-concepts/companies) with locations, contacts and tax exemptions, [catalogs](https://spreecommerce.org/docs/developer/core-concepts/catalogs) for per-segment assortments, and storefronts gated to approved buyers.

<img src="https://github.com/spree/spree/assets/12614496/bac1e551-f629-47d6-a983-b385aa65b1bd" alt="Spree Commerce - Wholesale eCommerce Platform" width="600" >

### [Headless & Omnichannel](https://spreecommerce.org/docs/developer/core-concepts/channels)

Run web storefronts, mobile apps, points of sale, B2B panels and marketplaces off one backend. [Channels](https://spreecommerce.org/docs/developer/core-concepts/channels) give each surface its own catalog, pricing, payment methods and order attribution.

The [Next.js storefront](https://github.com/spree/storefront) is one such surface — production-ready, open source, built with Next.js 16, React 19 and TypeScript. Fork it, customize it, deploy it. [Try the live demo](https://demo.spreecommerce.org/)

<table>
  <tr>
    <td><a href="https://demo.spreecommerce.org/"><img src="https://spreecommerce.org/wp-content/uploads/2026/04/Spree-Commerce-Next.js-Storefront-Homepage.webp" alt="Spree Commerce - Next.js Storefront - Home" width="400" /></a></td>
    <td><a href="https://demo.spreecommerce.org/"><img src="https://spreecommerce.org/wp-content/uploads/2026/04/Spree-Commerce-Next.js-Storefront-Product-Detail-Page-PDP.webp" alt="Spree Commerce - Next.js Storefront - Product" width="400" /></a></td>
    <td><a href="https://demo.spreecommerce.org/"><img src="https://spreecommerce.org/wp-content/uploads/2026/04/Spree-Commerce-Next.js-Storefront-PageSpeed-Lighthouse.webp" alt="Spree Commerce - Next.js Storefront - Lighthouse" width="400" /></a></td>
  </tr>
</table>

### [Cross-border Commerce](https://spreecommerce.org/docs/developer/core-concepts/markets)

[Markets](https://spreecommerce.org/docs/developer/core-concepts/markets) bundle currency, language, payment methods and shipping per region, so each customer sees a localized storefront from a single platform. [Translations](https://spreecommerce.org/docs/developer/core-concepts/translations) for product content, EU Omnibus price history and customs duties are built in.

<img alt="Spree Commerce - Cross-border eCommerce" src="https://spreecommerce.org/wp-content/uploads/2024/07/multi-region-country-shopping-1024x575.webp" width="600" >

### [Multi-tenant SaaS](https://spreecommerce.org/docs/developer/multi-tenant/quickstart) <sup>Enterprise</sup>

Run a SaaS platform where each tenant gets its own isolated store — catalog, orders, customers, payment methods and branding — with staff able to manage several tenants. Requires the [Enterprise Edition](https://spreecommerce.org/pricing).

## Getting Started

Copy and paste the following command to your terminal to set up Spree locally in 5 minutes:

```bash
npx create-spree-app@latest my-store
```

This sets up the Spree backend, the React Admin Dashboard, and optionally the [Next.js storefront](https://github.com/spree/storefront) in a single project. The storefront is built with Next.js 16, React 19, Tailwind CSS 4, and TypeScript.

You need Node.js 24+ installed and Docker running. Learn more in the [installation docs](https://spreecommerce.org/docs/developer/getting-started/quickstart).

If you like what you see, consider giving Spree a GitHub star ⭐

Thank you for supporting Spree open-source ❤️

### Agentic Development

Building with an AI coding agent? Install the [Sp

*(excerpt; full text in `UPSTREAM_CLONE/`)*

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Node.js / npm** (manifests: package.json, pnpm-lock.yaml; scanned in UPSTREAM_CLONE)
- Top-level source layout: `packages/`, `scripts/`, `spree/`
- Snapshot size: **7569 files**, **570101 lines of code** (measured; see Benchmarks)
- Primary languages: `.rb` (3420), `.ts` (1675), `.png` (641), `.mdx` (580), `.tsx` (576), `.md` (150)
- Upstream commit pinned for this packaging: `4ca24b80ddff9b85aa0502757275f2b526a95268`

---

## Installation

Teams use Spree to build **multi-vendor marketplaces** and **B2B and wholesale** channels, as well as headless DTC, cross-border and omnichannel selling — all from one set of commerce primitives, and all alongside the ERP, PIM, and payment systems you already run.

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

Teams use Spree to build **multi-vendor marketplaces** and **B2B and wholesale** channels, as well as headless DTC, cross-border and omnichannel selling — all from one set of commerce primitives, and all alongside the ERP, PIM, and payment systems you already run.

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

·
[API](https://spreecommerce.org/docs/api-reference/)
·
[Roadmap](https://github.com/spree/spree/milestones?direction=asc&sort=due_date&state=open)
·
[Discord](https://discord.spreecommerce.org)

[![Gem Total Downloads](https://img.shields.io/gem/dt/spree)](https://rubygems.org/gems/spree)
[![codecov](https://codecov.io/gh/spree/spree/graph/badge.svg?token=DPFc7HbJvU)](https://codecov.io/gh/spree/spree)
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

**Build commerce the way you want it.** Spree is an open-source commerce platform with a complete REST API, TypeScript SDKs, a React admin dashboard, and a production-ready Next.js storefront. BSD 3-Clause licensed — keep full ownership of your code, data, and infrastructure.

Teams use Spree to build **multi-vendor marketplaces** and **B2B and wholesale** channels, as well as headless DTC, cross-border and omnichannel selling — all from one set of commerce primitives, and all alongside the ERP, PIM, and payment systems you already run.

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Node.js / npm |
| Manifests detected | package.json, pnpm-lock.yaml |
| Files in snapshot | 7569 |
| Lines of code | 570101 |
| Dependency references | 277 |
| Dependencies by ecosystem | npm: 277 |
| Upstream license | BSD-3-Clause |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| npm | @base-ui/react | 1.8.0 | package.json |
| npm | @spree/cli | workspace:* | package.json |
| npm | @biomejs/biome | ^2.4.14 | package.json |
| npm | turbo | ^2.9.14 | package.json |
| npm | @changesets/cli | ^2.31.0 | package.json |
| npm | @changesets/changelog-github | ^0.7.0 | package.json |
| npm | @spree/sdk-core | workspace:* | packages/seller-sdk/package.json |
| npm | @types/node | ^25.6.0 | packages/seller-sdk/package.json |
| npm | @vitest/coverage-v8 | ^4.1.5 | packages/seller-sdk/package.json |
| npm | msw | ^2.14.3 | packages/seller-sdk/package.json |
| npm | tsup | ^8.0.0 | packages/seller-sdk/package.json |
| npm | tsx | ^4.0.0 | packages/seller-sdk/package.json |
| npm | typescript | ^6.0.3 | packages/seller-sdk/package.json |
| npm | vitest | ^4.1.5 | packages/seller-sdk/package.json |
| npm | yaml | ^2.8.4 | packages/seller-sdk/package.json |
| ... | (262 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

<img alt="Spree Commerce - Multi-vendor Marketplace eCommerce" src="https://github.com/spree/spree/assets/12614496/c4ddd118-df4c-464e-b1fe-d43862e5cf25" width="600" >

*Section quoted from the upstream readme.*
Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `.github/CONTRIBUTING.md`:*

# Contributing

Thank you for your interest in contributing to Spree! This guide will help you get started.

Please read our [Code of Conduct](../CODE_OF_CONDUCT.md) before contributing.

## Table of Contents

- [Getting Started](#getting-started)
  - [Cloning the project](#cloning-the-project)
  - [Prerequisites](#prerequisites)
  - [Spree codebase](#spree-codebase)
  - [Setup](#setup)
  - [Running server day-to-day](#running-server-day-to-day)
  - [Emails in development](#emails-in-development)
  - [Native Ruby (advanced)](#native-ruby-advanced)
- [Backend Development (Ruby)](#backend-development-ruby)
  - [Engines overview](#engines-overview)
  - [Spree namespace](#spree-namespace)
  - [Running engine tests](#running-engine-tests)
  - [Running tests in parallel](#running-tests-in-parallel)
  - [Performance in development mode](#performance-in-development-mode)
- [TypeScript Development](#typescript-development)
  - [Packages](#packages)
  - [Common commands](#common-commands)
  - [Package-specific commands](#package-specific-commands)
  - [Working on the React dashboard](#working-on-the-react-dashboard)
  - [Working on the storefront](#working-on-the-storefront)
  - [Dashboard E2E tests](#dashboard-e2e-tests)
  - [Type generation](#type-generation)
  - [Releasing packages](#releasing-packages)
- [Code Style](#code-style)
- [Making Changes](#making-changes)
  - [Branch naming](#branch-naming)
  - [Commit messages](#commit-messages)
- [Submitting Changes](#submitting-changes)
  - [Pull request guidelines](#pull-request-guidelines)
- [Reporting Bugs](#reporting-bugs)
- [Using AI Tools for Development](#using-ai-tools-for-development)

## Getting Started

### Cloning the project

Spree is a big monorepo. For a faster source, use a **partial source** which downloads file contents on demand while keeping full commit history for `git log` and `git blame`:

```bash
git source --filter=blob:none https://github.com/spree/spree.git
```

### Prerequisites

- Docker (eg. [Docker Desktop for MacOS](https://www.docker.com/products/docker-desktop/))
- Node 24 ([Install instructions](https://nodejs.org/en/download))

`pnpm` is provisioned automatically via [Corepack](https://nodejs.org/api/corepack.html) (bundled with Node) — the project pins its version in `package.json`, and the first `pnpm` command will fetch the matching release. If Corepack is disabled in your environment, run `corepack enable` once.

### Spree codebase

Spree is a monorepo with three main

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: BSD-3-Clause** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
BSD 3-Clause License

Copyright (c) 2024-present, Vendo Sp. z o.o., Vendo Connect Inc.
Copyright (c) 2015-2024, Spark Solutions Sp. z o.o.
Copyright (c) 2007-2015, Spree Commerce Inc.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice,
   this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its
   contributors may be used to endorse or promote products derived from
   this software without specific prior written permission.

```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original BSD-3-Clause terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `BSD-3-Clause` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `SPREE` (category: ONLINE RETAIL)
- **Upstream URL:** https://github.com/spree/spree
- **Pinned commit (SHA):** `4ca24b80ddff9b85aa0502757275f2b526a95268`
- **Branch:** main
- **Pin provenance:** GitHub API commits/main. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`98e9eb8b578bb5e29b4cd849a605f41d89e296c64db710c64c1a26dd10812b01`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

