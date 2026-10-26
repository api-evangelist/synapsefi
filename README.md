# Synapse

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

Synapse Financial Technologies was a San Francisco banking-as-a-service platform, founded
2014-04-14 by Sankaet Pathak and Bryan Keltner, that sold a REST API letting fintech companies
open and operate deposit accounts, move money over ACH and wires, issue cards and run KYC/CIP
checks through partner banks. At its peak it served roughly 100 fintech platforms.

**This company is defunct and its API is permanently gone.** Synapse filed for Chapter 11
bankruptcy on 2024-04-22, the sale of its technology assets drew no qualified bids, and the case
was later dismissed. As of 2026-08-29 every `synapsefi.com` host — including `api.synapsefi.com`
and `docs.synapsefi.com` — returns NXDOMAIN. There is no successor API.

## What this profile records

| Artifact | What it holds |
| --- | --- |
| [`packages/`](packages/synapsefi-packages.yml) | The first-party SDKs that survive on npm, PyPI, RubyGems and the Go module proxy, with versions and publish dates. Newest release in any registry: `synapsenode` 2.0.0-beta.11, 2023-06-28. |
| [`lifecycle/`](lifecycle/synapsefi-lifecycle.yml) | The retirement record — last known version (REST v3.1), the bankruptcy timeline, and the confirmation that no deprecation policy, status page or successor exists. |
| [`well-known/`](well-known/synapsefi-well-known.yml) | The `.well-known` and contract-discovery probe, recording a confirmed absence with statuses. |
| [`plans/`](plans/synapsefi-plans-pricing.yml) | Zero published plans, with probe evidence. |
| [`rate-limits/`](rate-limits/synapsefi-rate-limits.yml) | Zero published limits, with probe evidence. |
| [`llms/`](llms/synapsefi-llms.txt) | A generated `llms.txt` telling an agent, plainly, not to attempt an integration. |

No OpenAPI, Swagger, GraphQL SDL, AsyncAPI, protobuf, WSDL, MCP server or agent card exists. The
public GitHub organization <https://github.com/SynapseFI> is still live with 11 repositories, all
client libraries; the full git tree of every one was walked and none contains a machine-readable
contract.
