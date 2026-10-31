# Open (open.money)

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

Open is one of India's leading SMB neobanks, pioneering "connected banking" - a unified business finance platform that layers payments, automated reconciliation, accounting, payroll, expense management, vendor payouts, and GST-compliant invoicing on top of partner-bank current accounts (ICICI, SBI, Axis Bank, Yes Bank and 20+ others). Beyond its SMB application, Open also ships an embedded-finance / Banking-as-a-Service stack branded as Zwitch (zwitch.io), which exposes the same connected-banking primitives - virtual accounts, payouts via NEFT/IMPS/RTGS, UPI collect and intent flows, the Layer hosted payment gateway, beneficiary management, PAN/bank/VPA verification, webhooks, and split settlements - as REST APIs for fintechs and platforms that want to embed account-to-account payments and Indian payment rails into their own products. Open's broader portfolio also includes BankingStack (white-label connected banking for partner banks), the Open Capital lending product, and a suite of e-commerce plugins (WooCommerce, Magento, OpenCart, PrestaShop, CS-Cart, WHMCS) plus PHP, Java, Node.js, iOS, and Android SDKs for the Layer payment gateway.

**Areas:** Connected Banking · Neobank · Small Business · Embedded Finance · Banking as a Service · Payments · Payouts · UPI · Accounting · Payroll · Expense Management · India

## Open (open.money) on APIs.io

Everything profiled for Open (open.money) is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/open-financial/](https://apis.io/providers/open-financial/)** — or go straight to one of the APIs or properties below.

### APIs (20)

- [Open Zwitch Virtual Accounts API](https://apis.io/apis/open-financial/virtual-accounts/) — Programmatic creation and management of virtual accounts used as transfer wallets, collection wallets, and collection tools on top of partner-bank…
- [Open Zwitch Transfers API](https://apis.io/apis/open-financial/transfers/) — Initiate single or bulk fund transfers from a virtual account to bank beneficiaries over NEFT, IMPS, or RTGS, and inspect transfer status, UTR, and…
- [Open Zwitch Beneficiaries API](https://apis.io/apis/open-financial/beneficiaries/) — Manage the set of bank-account beneficiaries that can be paid from a virtual account. Supports creating beneficiaries, listing, retrieving, updating, and…
- [Open Zwitch UPI API](https://apis.io/apis/open-financial/upi/) — UPI collect requests, UPI Intent strings, and dynamic UPI QR codes for accepting customer-initiated payments on India's Unified Payments Interface rails.…
- [Open Layer Payment Gateway API](https://apis.io/apis/open-financial/layer/) — Layer is Zwitch's hosted payment gateway. A few lines of layer.js render a fully PCI-compliant checkout pop-up that accepts net banking, UPI, credit/debit…
- [Open Zwitch Verification API](https://apis.io/apis/open-financial/verification/) — Identity and account-validation suite used during merchant onboarding, KYB, and pre-payout checks. Endpoints cover PAN verification, name matching,…
- [Open Zwitch Split Settlements API](https://apis.io/apis/open-financial/settlements/) — Configure split-settlement rules so that incoming payments are automatically apportioned across multiple beneficiary accounts at settlement time. Used by…
- [Open Zwitch Webhooks](https://apis.io/apis/open-financial/webhooks/) — Real-time event delivery for payment, transfer, refund, settlement, virtual-account, and verification lifecycle events, with HMAC signature verification and…
- [Open Zwitch Payment Pages API](https://apis.io/apis/open-financial/payment-pages/) — No-code hosted payment pages and payment links that small businesses can share over email, SMS, or WhatsApp to collect one-time or recurring payments…
- [Open Connected Banking Platform](https://apis.io/apis/open-financial/connected-banking/) — Open's flagship SMB neobanking application. Connects one or more partner-bank current accounts (ICICI, SBI, Axis Bank, Yes Bank, and others) and layers on…
- [Open (open.money) Accounts API](https://apis.io/apis/open-financial/open-financial-accounts-api/) — The Accounts API from Open (open.money) — 8 operation(s) for accounts.
- [Open (open.money) Constants API](https://apis.io/apis/open-financial/open-financial-constants-api/) — The Constants API from Open (open.money) — 4 operation(s) for constants.
- [Open (open.money) Events API](https://apis.io/apis/open-financial/open-financial-events-api/) — The Events API from Open (open.money) — 1 operation(s) for events.
- [Open (open.money) Icp API](https://apis.io/apis/open-financial/open-financial-icp-api/) — The Icp API from Open (open.money) — 1 operation(s) for icp.
- [Open (open.money) Kycs API](https://apis.io/apis/open-financial/open-financial-kycs-api/) — The Kycs API from Open (open.money) — 4 operation(s) for kycs.
- [Open (open.money) Pg API](https://apis.io/apis/open-financial/open-financial-pg-api/) — The Pg API from Open (open.money) — 2 operation(s) for pg.
- [Open (open.money) Pg Settlements API](https://apis.io/apis/open-financial/open-financial-pg-settlements-api/) — The Pg Settlements API from Open (open.money) — 2 operation(s) for pg settlements.
- [Open (open.money) Refund API](https://apis.io/apis/open-financial/open-financial-refund-api/) — The Refund API from Open (open.money) — 2 operation(s) for refund.
- [Open (open.money) Transfers API](https://apis.io/apis/open-financial/open-financial-transfers-api/) — The Transfers API from Open (open.money) — 4 operation(s) for transfers.
- [Open (open.money) Verifications API](https://apis.io/apis/open-financial/open-financial-verifications-api/) — The Verifications API from Open (open.money) — 1 operation(s) for verifications.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [open-financial-mcp.yml](https://apis.io/servers/open-financial/open-financial-mcp-yml/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Open Financial Agentic Access](https://apis.io/agentic-access/open-financial/open-financial-agentic-access/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Open (open.money) API Rules](https://apis.io/rules/open-financial/open-financial-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Open Financial Authentication](https://apis.io/security/open-financial/open-financial-authentication/)
- [Open Financial Domain Security](https://apis.io/security/open-financial/open-financial-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://open.money/)
- [Documentation](https://developers.zwitch.io/)
- [Getting started](https://developers.zwitch.io/reference/introduction)
- [Pricing](https://open.money/pricing)
- [Support](https://help.open.money/support/home)
- [Blog](https://open.money/blog)
- [Terms of service](https://open.money/terms)
- [Privacy policy](https://open.money/privacy)

## API Evangelist rating

**Kin Score 42.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 76.8 |
| Contract quality | 50.7 |
| Contract governance | 18.2 |
| Operational transparency | 5.3 |
| Developer ergonomics | 54.8 |
| Access clarity | 44.7 |

**Agent readiness 46.9** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | verified |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | distinct |

**Regulatory alignment 19.7** — Banking & Open Finance

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/open-financial/](https://apis.io/providers/open-financial/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Open (open.money): the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/open-financial/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
