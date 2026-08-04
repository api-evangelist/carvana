# Carvana (carvana)

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

Carvana is an e-commerce platform for buying, selling, and financing used cars online, featuring home delivery or pickup at its distinctive car vending machines. Its primary developer-facing integration surface is the Carvana Partner REST API (published on Azure API Management at api-developer.carvana.com) which enables authorized rental companies, wholesalers, and fleet partners to post, update, and manage inventory in Carvana's catalog. A Carvana Collective API (api.collective.carvana.com) supports partner-collective workflows, and Carvana also distributes inventory data via AWS Data Exchange.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/carvana/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** Partner

## Tags

 - Automotive, E-Commerce, Used Cars, Inventory, Partner API, Fortune 500

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-04-23

## APIs

### Carvana Partner API

REST API that enables deep integration between Carvana and authorized partners (car rental companies, wholesalers, and fleet operators) for posting, updating, and managing used-vehicle inventory. Requires Carvana LLC authorization; the developer portal runs on Microsoft Azure API Management.

**Human URL:** [https://api-developer.carvana.com/](https://api-developer.carvana.com/)

#### Tags

 - Partner, Inventory, Authorized Access

#### Properties

- [Portal](https://api-developer.carvana.com/)
- [Login](https://api-developer.carvana.com/signin)
- [Documentation](https://api-developer.carvana.com/)

### Carvana Collective API

API surface supporting Carvana Collective partner-collaborative workflows; access is restricted to authorized Carvana partners.

**Human URL:** [https://api.collective.carvana.com/](https://api.collective.carvana.com/)

#### Tags

 - Partner, Collective

### Carvana Car Sales Data (AWS Data Exchange)

Carvana's used-car inventory and sales data product published on AWS Data Exchange for direct subscription and data-warehouse delivery to analytics, pricing, and market-research consumers.

**Human URL:** [AWS Marketplace Listing](https://aws.amazon.com/marketplace/pp/prodview-y77x3t6zisn4w)

#### Tags

 - Data Product, AWS Data Exchange, Inventory

### Carvana Partner Inventory Help Center

Consumer-facing explainer describing how Carvana sources partner inventory (rental fleets and other partners) into the buyer catalog.

**Human URL:** [Where is Partner Inventory](https://www.carvana.com/help/carvana-inventory/where-is-partner-inventory)

#### Tags

 - Partner, Inventory, Consumer

## Use Cases

- Rental and fleet partners programmatically posting end-of-service vehicles into Carvana's inventory with VIN, photos, condition, and price through the Partner API.
- Bulk updates of partner inventory status (available, reserved, sold, reconditioning) from a partner's fleet-management system.
- Data-driven used-car analytics via subscription to Carvana's AWS Data Exchange product, joined with macro demand signals in BigQuery/Redshift/Snowflake.
- Consumer-facing experiences on carvana.com (browsing, financing, delivery scheduling, vending-machine pickup) consuming internal services not publicly exposed as APIs.
- Investor and analyst workflows via the IR site (earnings, filings, press releases).

## Common Properties

- [Website](https://www.carvana.com)
- [Developer Portal](https://api-developer.carvana.com/)
- [Login](https://api-developer.carvana.com/signin)
- [Help Center](https://www.carvana.com/help)
- [Sell a Car](https://www.carvana.com/sell-car)
- [Finance](https://www.carvana.com/finance)
- [Vending Machine Locations](https://www.carvana.com/vending-machine-locations)
- [About](https://www.carvana.com/company/about_us)
- [Investor Relations](https://investors.carvana.com)
- [Careers](https://www.carvana.com/careers)
- [Contact](https://www.carvana.com/help/contact-us)
- [Terms of Service](https://www.carvana.com/terms-of-use)
- [Privacy Policy](https://www.carvana.com/privacy-policy)
- [JSON-LD Context](json-ld/carvana-context.jsonld)
- [Vocabulary Definition](vocabulary.yml)
- [Spectral Rules](spectral/carvana.spectral.yml)

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
