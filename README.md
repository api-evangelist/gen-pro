# GEN

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

GEN is an AI‑powered content engine that automates video creation for TikTok, Instagram and YouTube. It scans millions of short‑form videos to identify trending topics, generates scripts, visuals and captions, and auto‑posts to the platforms. Subscription plans are offered via Stripe.

**Areas:** AI · VideoGeneration · SocialMedia · Automation · ContentCreation · Company

## GEN on APIs.io

Everything profiled for GEN is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/gen-pro/](https://apis.io/providers/gen-pro/)** — or go straight to one of the APIs or properties below.

### APIs (27)

- [GEN Agent Chat API](https://apis.io/apis/gen-pro/gen-pro-agent-chat-api/) — Conversational AI agent interface. All endpoints use base URL `https://agent.gen.pro/v1`.
- [GEN Agent Core API](https://apis.io/apis/gen-pro/gen-pro-agent-core-api/) — **Preferred** single-endpoint read/write for the agent setup canvas. One flat PATCH updates every brand field, personality, and default voice in a single…
- [GEN Agent Profile API](https://apis.io/apis/gen-pro/gen-pro-agent-profile-api/) — (Legacy) Manage the agent's identity, voice, and brand profile. Prefer Agent Core for new work.
- [GEN Agent Voice API](https://apis.io/apis/gen-pro/gen-pro-agent-voice-api/) — Voice library, ElevenLabs integration, prompt-based design (4-step flow), audio-sample cloning, async TTS preview.
- [GEN Agents API](https://apis.io/apis/gen-pro/gen-pro-agents-api/) — Create, read, update, and delete agents and their avatars.
- [GEN API Keys API](https://apis.io/apis/gen-pro/gen-pro-api-keys-api/) — Create and manage Personal Access Tokens (PATs) for API authentication.
- [GEN Asset Libraries API](https://apis.io/apis/gen-pro/gen-pro-asset-libraries-api/) — Browse asset libraries and manage asset folders.
- [GEN Billing API](https://apis.io/apis/gen-pro/gen-pro-billing-api/) — Credit balance, plans, transactions, and credit purchase flows.
- [GEN Cells API](https://apis.io/apis/gen-pro/gen-pro-cells-api/) — Read and update individual cells.
- [GEN Characters API](https://apis.io/apis/gen-pro/gen-pro-characters-api/) — A person the agent can appear as, with looks (images) and talking characters (talking videos). Characters were called avatars; the /v1/avatars routes still…
- [GEN Columns API](https://apis.io/apis/gen-pro/gen-pro-columns-api/) — Manage columns within a sheet.
- [GEN Content Monitoring API](https://apis.io/apis/gen-pro/gen-pro-content-monitoring-api/) — Monitor and discover social media content across multiple platforms.
- [GEN Content Resources API](https://apis.io/apis/gen-pro/gen-pro-content-resources-api/) — Upload and manage content resources (images, videos, audio).
- [GEN Direct Upload API](https://apis.io/apis/gen-pro/gen-pro-direct-upload-api/) — Get pre-signed S3 URLs for large file uploads.
- [GEN Discovery API](https://apis.io/apis/gen-pro/gen-pro-discovery-api/) — Identify the authenticated user, their workspaces, and agents.
- [GEN Generations API](https://apis.io/apis/gen-pro/gen-pro-generations-api/) — Trigger AI content generation on cells and layers.
- [GEN Layers API](https://apis.io/apis/gen-pro/gen-pro-layers-api/) — Manage video layers within cells.
- [GEN Organizations API](https://apis.io/apis/gen-pro/gen-pro-organizations-api/) — Manage organizations (workspaces).
- [GEN Proof of Genesis API](https://apis.io/apis/gen-pro/gen-pro-proof-of-genesis-api/) — Back up GEN assets to Walrus with verifiable hashes. Base URL `https://agent-core.gen.pro/v1`. Public assets may be uploaded raw; private assets must be…
- [GEN Publishing API](https://apis.io/apis/gen-pro/gen-pro-publishing-api/) — Post and schedule content to social media platforms.
- [GEN Recurring Jobs API](https://apis.io/apis/gen-pro/gen-pro-recurring-jobs-api/) — Scheduled agent runs ("daily tasks"). Base URL `https://agent.gen.pro/v1`. Each scheduled run is gated by available credits: a job remains configured if…
- [GEN Rows API](https://apis.io/apis/gen-pro/gen-pro-rows-api/) — Manage rows within a sheet.
- [GEN Sheets API](https://apis.io/apis/gen-pro/gen-pro-sheets-api/) — Create and retrieve Auto Content Engine sheets (vidsheets).
- [GEN Song Mixes API](https://apis.io/apis/gen-pro/gen-pro-song-mixes-api/) — Backend/API-first DJ-style song mixing. Base URL `https://agent.gen.pro/v1`.
- [GEN Templates API](https://apis.io/apis/gen-pro/gen-pro-templates-api/) — Browse and clone pre-configured engine templates.
- [GEN Variables API](https://apis.io/apis/gen-pro/gen-pro-variables-api/) — Global variables for template substitution.
- [GEN Watchlists API](https://apis.io/apis/gen-pro/gen-pro-watchlists-api/) — Named collections of monitoring sources (accounts, hashtags, keywords) per agent. Base URL `https://agent-core.gen.pro/v1`. Scraped data feeds back into…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Gen Pro Webhooks](https://apis.io/asyncapis/gen-pro/gen-pro-webhooks/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [GEN Agentic Access](https://apis.io/agentic-access/gen-pro/gen-pro-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [AgentCore](https://apis.io/schemas/gen-pro/gen-pro-agent-core/)
- [AgentCorePatch](https://apis.io/schemas/gen-pro/gen-pro-agent-core-patch/)
- [AgentCorePatchResult](https://apis.io/schemas/gen-pro/gen-pro-agent-core-patch-result/)
- [ProofOfGenesisBackup](https://apis.io/schemas/gen-pro/gen-pro-proof-of-genesis-backup/)
- [ProofOfGenesisBackupCreate](https://apis.io/schemas/gen-pro/gen-pro-proof-of-genesis-backup-create/)
- [PublishedPostUpdate](https://apis.io/schemas/gen-pro/gen-pro-published-post-update/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Gen Pro Context](https://apis.io/jsonld/gen-pro/gen-pro-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [GEN API Rules](https://apis.io/rules/gen-pro/gen-pro-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [GEN Authentication](https://apis.io/security/gen-pro/gen-pro-authentication/)
- [GEN Domain Security](https://apis.io/security/gen-pro/gen-pro-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://gen.pro/)
- [Documentation](https://help.gen.pro/)
- [API reference](https://gen.pro/docs)
- [Pricing](https://gen.pro/pricing)
- [Sign up](https://gen.pro/signupnow)
- [Blog](https://gen.pro/blog/)
- [Terms of service](https://gen.pro/terms-of-use/)
- [Privacy policy](https://gen.pro/privacy-policy/)
- [Status](https://status.gen.pro/)

## API Evangelist rating

**Kin Score 53.8** — developing · rubric 0.27.0 · scored 2026-11-09

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 68.1 |
| Contract governance | 79.1 |
| Operational transparency | 23.7 |
| Developer ergonomics | 37.4 |
| Access clarity | 44.7 |

**Agent readiness 48.1** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | verified |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | — |
| Event Surface Described | unknown |
| Agent Skills | unknown |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | mostly (partial credit) |
| MCP Tool Quality | na |

**Regulatory alignment 22.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/gen-pro/](https://apis.io/providers/gen-pro/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for GEN: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/gen-pro/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
