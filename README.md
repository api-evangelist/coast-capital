# Coast Capital Savings (coast-capital)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Coast Capital Savings is a member-owned financial co-operative headquartered in Surrey, British Columbia, serving over 600,000 members across roughly 45 branches with approximately $21.9 billion CAD in total assets. On November 1, 2018 it became Canada's first British Columbia-based federal credit union (federally regulated), and in May 2026 it completed a merger with Prospera Credit Union — making it one of Canada's largest credit unions.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/coast-capital/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/coast-capital/refs/heads/main/apis.yml)

## Open-Finance Posture

As a cooperative credit union (not a Schedule I/II chartered bank), Coast Capital operates within Canada's voluntary and still-fragmented open-finance landscape. Canada has **no operational open-banking mandate**: the federal Consumer-Driven Banking framework legislated under Budget 2024 and the Fall Economic Statement 2024 — with the Financial Consumer Agency of Canada (FCAC) as overseer — is legislated but not yet live.

- **First-party developer portal:** None found. Probing `developer.coastcapitalsavings.com`, `developers.coastcapitalsavings.com`, and `api.coastcapitalsavings.com` returned no live host (DNS/connection failure). No public OpenAPI/Swagger is published.
- **Consumer data access:** Aggregator-mediated only. Coast Capital accounts are reachable through third-party aggregators such as Plaid via credential-based/screen-scraping connections, not a documented first-party API.
- **Consumer-Driven Banking (CDB):** No published first-party CDB/FDX API. The Canadian framework is not yet operational.
- **Rails:** As a Canadian financial institution it participates in shared payment infrastructure (Interac e-Transfer, Payments Canada), but exposes no public API around it.

## APIs

None. Coast Capital Savings does not publish a public first-party developer API. This is an identity-only (built-stub) record; consumer financial-data access is aggregator-mediated (e.g. Plaid).

## Tags

- Financial Services
- Banking
- Canada
- Credit Union
- Cooperative
- Consumer-Driven Banking
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## Common Properties

- [Website](https://www.coastcapitalsavings.com/)
- [LinkedIn](https://www.linkedin.com/company/coast-capital-savings)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
