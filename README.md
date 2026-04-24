# Carvana (carvana)

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
