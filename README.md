# Coast Capital Savings (coast-capital)

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
