# Sprague Resources

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

Sprague Resources (operating as Sprague Energy) is one of the largest independent suppliers of energy products and related services in the northeastern United States and Quebec, founded in 1870. The company distributes refined fuel products (heating oil, diesel, gasoline, kerosene, biofuels), natural gas, and electricity to commercial and industrial customers, and operates 20+ port terminal facilities for materials handling. Sprague was acquired by Hartree Partners in 2024.

- **Website:** https://www.spragueenergy.com
- **Customer Portal:** https://mysprague.com

## Business Overview

Sprague serves 25,000+ customers across the Northeast with:
- **Refined Petroleum Products:** Heating oil, diesel (ULSD), gasoline, kerosene, biofuels, bunker fuel
- **Natural Gas Supply:** Commodity procurement with customized plans for commercial and industrial customers
- **Electricity Procurement:** Energy brokerage services (expanded via 2026 Global Companies acquisition)
- **Materials Handling:** Port terminal operations, bulk cargo, wind turbine components
- **Terminal Network:** 20+ port facilities across the northeastern US and Quebec

## Digital Platforms

### SpraguePORT
Electronic customer portal providing:
- Account management and order history
- Real-time market data and pricing
- Invoice access and reporting
- Available for refined products and natural gas customers

### Sprague Real-time
Online pricing tool for resellers and brokers to access current market pricing for petroleum products.

**Note:** Sprague Energy does not publish a public developer API. The SpraguePORT portal is a closed business-to-business system accessible only to Sprague customers and partners.

## Artifacts

### JSON Schema

| Schema | Description |
|---|---|
| [sprague-fuel-order-schema.json](json-schema/sprague-fuel-order-schema.json) | Fuel delivery order schema with product type, quantity, pricing, and delivery details |

### JSON Structure

| Structure | Description |
|---|---|
| [sprague-fuel-order-structure.json](json-structure/sprague-fuel-order-structure.json) | Hierarchical field map for fuel delivery orders |

### JSON-LD Context

| Context | Description |
|---|---|
| [sprague-resources-context.jsonld](json-ld/sprague-resources-context.jsonld) | Linked data context mapping Sprague vocabulary to schema.org |

### Vocabulary

| Vocabulary | Description |
|---|---|
| [sprague-resources-vocabulary.yml](vocabulary/sprague-resources-vocabulary.yml) | Energy distribution vocabulary covering fuel types, pricing models, and service offerings |

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
