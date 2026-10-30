# HappyOrNot

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

HappyOrNot is a Finnish customer-experience feedback company known for its Smiley Terminal, Smiley Touch and Smiley Digital feedback devices used across retail, airports, healthcare, public sector and workplaces. Its read-only Customer API v2 lets applications and BI tools pull raw feedback data — button (smiley/NPS) ratings, follow-up selections, freeform text, AI demographics, contact-request details and metadata — together with the experience points, groups, surveys, questions, smileys, users and alerts that produce it. Authentication is a package-scoped API token (X-HON-API-Token header or auth query parameter); responses are JSON or CSV, paged with offset/limit and an X-More-Available header. The API is documented with an OpenAPI 3.1 specification and integrates with Power BI, Tableau, Salesforce, Medallia, Qualtrics and Zapier.

**Areas:** Company · Enterprise · Customer Experience · Customer Feedback · Surveys · Analytics · Voice of Customer · Retail · Feedback

## HappyOrNot on APIs.io

Everything profiled for HappyOrNot is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/happyornot/](https://apis.io/providers/happyornot/)** — or go straight to one of the APIs or properties below.

### APIs (21)

- [HappyOrNot Alert Comments API](https://apis.io/apis/happyornot/happyornot-alert-comments-api/) — Endpoints and data definitions related to alert comments which have been written for alerts
- [HappyOrNot Alert Specifications API](https://apis.io/apis/happyornot/happyornot-alert-specifications-api/) — Endpoints and data definitions related to alert specifications based on which alerts are triggered
- [HappyOrNot Alerts API](https://apis.io/apis/happyornot/happyornot-alerts-api/) — Endpoints and data definitions related to alerts which have been triggered by incoming feedback, based on alert specfications
- [HappyOrNot Button Feedbacks API](https://apis.io/apis/happyornot/happyornot-button-feedbacks-api/) — Button feedback related endpoints and data definitions
- [HappyOrNot Contact Details API](https://apis.io/apis/happyornot/happyornot-contact-details-api/) — Contact details data endpoints and data definitions
- [HappyOrNot Custom Data Fields API](https://apis.io/apis/happyornot/happyornot-custom-data-fields-api/) — Endpoints and data definitions related to custom data fields
- [HappyOrNot Demographics API](https://apis.io/apis/happyornot/happyornot-demographics-api/) — Demographics data endpoints and data definitions
- [HappyOrNot Experience Points API](https://apis.io/apis/happyornot/happyornot-experience-points-api/) — Experience points and groups related endpoints and data definitions
- [HappyOrNot Follow Up Feedbacks API](https://apis.io/apis/happyornot/happyornot-follow-up-feedbacks-api/) — Follow-up feedback related endpoints and data definitions
- [HappyOrNot Follow Up Option Localizations API](https://apis.io/apis/happyornot/happyornot-follow-up-option-localizations-api/) — Endpoints and data definitions related to localizations for selectable options for follow ups in surveys
- [HappyOrNot Follow Up Options API](https://apis.io/apis/happyornot/happyornot-follow-up-options-api/) — Endpoints and data definitions related to selectable options for follow ups in surveys
- [HappyOrNot Follow Up Question Localizations API](https://apis.io/apis/happyornot/happyornot-follow-up-question-localizations-api/) — Endpoints and data definitions related to localizations for questions used for follow ups in surveys
- [HappyOrNot Follow Up Questions API](https://apis.io/apis/happyornot/happyornot-follow-up-questions-api/) — Endpoints and data definitions related to questions used for follow ups in surveys
- [HappyOrNot Metadata API](https://apis.io/apis/happyornot/happyornot-metadata-api/) — Metadata related endpoints and daa definitions
- [HappyOrNot Question Localizations API](https://apis.io/apis/happyornot/happyornot-question-localizations-api/) — Endpoints and data definitions related to localizations for question used in surveys
- [HappyOrNot Questions API](https://apis.io/apis/happyornot/happyornot-questions-api/) — Endpoints and data definitions related to questions used in surveys
- [HappyOrNot Smileys API](https://apis.io/apis/happyornot/happyornot-smileys-api/) — Endpoints and data definitions related to smileys
- [HappyOrNot Surveys API](https://apis.io/apis/happyornot/happyornot-surveys-api/) — Surveys related endpoints and data definitions
- [HappyOrNot Text Feedbacks API](https://apis.io/apis/happyornot/happyornot-text-feedbacks-api/) — Text feedback related endpoints and data definitions
- [HappyOrNot Token Introspection API](https://apis.io/apis/happyornot/happyornot-token-introspection-api/) — Token introspection including token scopes
- [HappyOrNot Users API](https://apis.io/apis/happyornot/happyornot-users-api/) — Endpoints and data definitions related to users

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (2)

Multi-step workflows that chain operations into a business task.

- [Resolve an experience point and fetch its button feedback](https://apis.io/arazzos/happyornot/happyornot-fetch-feedback/)
- [Monitor HappyOrNot alerts](https://apis.io/arazzos/happyornot/happyornot-monitor-alerts/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [happyornot](https://apis.io/servers/happyornot/happyornot/)

#### Collections (21)

Postman and Open Collection request collections.

- [HappyOrNot Customer API v2 alert-comments API](https://apis.io/collections/happyornot/open-happyornot-alert-comments-api/)
- [HappyOrNot Customer API v2 alert-comments alert-specifications API](https://apis.io/collections/happyornot/open-happyornot-alert-specifications-api/)
- [HappyOrNot Customer API v2 alert-comments alerts API](https://apis.io/collections/happyornot/open-happyornot-alerts-api/)
- [HappyOrNot Customer API v2 alert-comments button-feedbacks API](https://apis.io/collections/happyornot/open-happyornot-button-feedbacks-api/)
- [HappyOrNot Customer API v2 alert-comments contact-details API](https://apis.io/collections/happyornot/open-happyornot-contact-details-api/)
- [HappyOrNot Customer API v2 alert-comments custom-data-fields API](https://apis.io/collections/happyornot/open-happyornot-custom-data-fields-api/)
- [HappyOrNot Customer API v2 alert-comments demographics API](https://apis.io/collections/happyornot/open-happyornot-demographics-api/)
- [HappyOrNot Customer API v2 alert-comments experience-points API](https://apis.io/collections/happyornot/open-happyornot-experience-points-api/)
- [HappyOrNot Customer API v2 alert-comments follow-up-feedbacks API](https://apis.io/collections/happyornot/open-happyornot-follow-up-feedbacks-api/)
- [HappyOrNot Customer API v2 alert-comments follow-up-option-localizations API](https://apis.io/collections/happyornot/open-happyornot-follow-up-option-localizations-api/)
- [HappyOrNot Customer API v2 alert-comments follow-up-options API](https://apis.io/collections/happyornot/open-happyornot-follow-up-options-api/)
- [HappyOrNot Customer API v2 alert-comments follow-up-question-localizations API](https://apis.io/collections/happyornot/open-happyornot-follow-up-question-localizations-api/)
- [HappyOrNot Customer API v2 alert-comments follow-up-questions API](https://apis.io/collections/happyornot/open-happyornot-follow-up-questions-api/)
- [HappyOrNot Customer API v2 alert-comments metadata API](https://apis.io/collections/happyornot/open-happyornot-metadata-api/)
- [HappyOrNot Customer API v2 alert-comments question-localizations API](https://apis.io/collections/happyornot/open-happyornot-question-localizations-api/)
- [HappyOrNot Customer API v2 alert-comments questions API](https://apis.io/collections/happyornot/open-happyornot-questions-api/)
- [HappyOrNot Customer API v2 alert-comments smileys API](https://apis.io/collections/happyornot/open-happyornot-smileys-api/)
- [HappyOrNot Customer API v2 alert-comments surveys API](https://apis.io/collections/happyornot/open-happyornot-surveys-api/)
- [HappyOrNot Customer API v2 alert-comments text-feedbacks API](https://apis.io/collections/happyornot/open-happyornot-text-feedbacks-api/)
- [HappyOrNot Customer API v2 alert-comments token-introspection API](https://apis.io/collections/happyornot/open-happyornot-token-introspection-api/)
- [HappyOrNot Customer API v2 alert-comments users API](https://apis.io/collections/happyornot/open-happyornot-users-api/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Happyornot Openapi Overlay](https://apis.io/overlays/happyornot/happyornot-openapi-overlay/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Happyornot Authentication](https://apis.io/security/happyornot/happyornot-authentication/)
- [Happyornot Domain Security](https://apis.io/security/happyornot/happyornot-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.happy-or-not.com)
- [Documentation](https://happyornot.github.io/docs/)
- [Getting started](https://happyornot.github.io/docs/)
- [API reference](https://api.happy-or-not.com/v2/)
- [Pricing](https://www.happy-or-not.com/en/pricing/)
- [Sign up](https://reporting.happy-or-not.com/)
- [Support](https://support.happy-or-not.com/)
- [Blog](https://www.happy-or-not.com/en/resources/blog/)
- [Terms of service](https://www.happy-or-not.com/en/terms/)
- [Privacy policy](https://www.happy-or-not.com/en/privacy-policy/)
- [GitHub](https://github.com/happyornot)

## API Evangelist rating

**Kin Score 43.2** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 49.6 |
| Contract governance | 4.5 |
| Operational transparency | 26.3 |
| Developer ergonomics | 58.9 |
| Access clarity | 31.6 |

**Agent readiness 20.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 24.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/happyornot/](https://apis.io/providers/happyornot/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for HappyOrNot: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/happyornot/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
