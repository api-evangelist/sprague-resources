# Sprague Resources

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
