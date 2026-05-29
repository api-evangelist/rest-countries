# REST Countries (rest-countries)

REST Countries is a free, open-source RESTful API that returns rich country reference data — ISO 3166-1 codes (cca2, cca3, ccn3, cioc), common/official and native names, translations, capitals, regions and subregions, continents, currencies, languages, calling codes, top-level domains, timezones, geographic coordinates, borders, area, population, demonyms, flags and coats of arms, postal code formats, Gini index, FIFA code, independence and UN membership status, driving side, and start of week. The canonical hosted instance runs at restcountries.com (v3.1) and the source is community-maintained at github.com/apilayer/restcountries (mirror of gitlab.com/restcountries/restcountries), licensed under MPL-2.0. The hosted API is unauthenticated and free; for production use the project encourages self-hosting from source.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/rest-countries/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Countries, Geocoding, Geography, ISO 3166, Open Source, Public APIs, Reference Data, Currencies, Languages, Capitals, Regions, Subregions, Translations

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### REST Countries
Free, unauthenticated, read-only REST API for country reference data. Provides endpoints for bulk listing and for lookups by name, ISO alpha code (cca2/cca3/ccn3/cioc), currency, language, capital, region, subregion, translation, demonym, and independence status. Response payloads can be trimmed with the `fields` query parameter (required on `/all`).

**Human URL:** [https://restcountries.com](https://restcountries.com)

#### Tags:

 - Countries, Geography, ISO 3166, Reference Data, REST

#### Properties

- [Documentation](https://restcountries.com)
- [GitHubRepository](https://github.com/apilayer/restcountries)
- [SourceRepository](https://gitlab.com/restcountries/restcountries)
- [OpenAPI](openapi/rest-countries-openapi.yml)
- [JSONSchema](json-schema/rest-countries-country-schema.json)
- [JSONStructure](json-structure/rest-countries-country-structure.json)
- [JSON-LD](json-ld/rest-countries-context.jsonld)
- [Example](examples/rest-countries-country-example.json)
- [Example](examples/rest-countries-by-region-example.json)
- [NaftikoCapability](capabilities/rest-countries-lookup.yaml)
- [Plans](plans/rest-countries-plans-pricing.yml)
- [RateLimits](rate-limits/rest-countries-rate-limits.yml)

## Common Properties

- [Website](https://restcountries.com)
- [Documentation](https://restcountries.com)
- [GitHubRepository](https://github.com/apilayer/restcountries)
- [SourceRepository](https://gitlab.com/restcountries/restcountries)
- [Mirror](https://github.com/restcountries/restcountries)
- [License](https://www.mozilla.org/en-US/MPL/2.0/)
- [SpectralRules](rules/rest-countries-rules.yml)
- [Vocabulary](vocabulary/rest-countries-vocabulary.yml)

## Features

| Name | Description |
|------|-------------|
| Bulk Country Listing | Retrieve the complete country dataset via `/all` with a required `fields` selector. |
| Multi-Key Lookups | Search by name, ISO 3166-1 alpha-2/alpha-3/numeric/CIOC code, currency, language, capital, region, subregion, translation, demonym, or independence status. |
| Sparse Fieldsets | Use the `fields` query parameter to request only the fields you need (up to 10), shrinking payload size. |
| Rich Country Metadata | Each country exposes 30+ fields including flags, coat of arms, IDD calling codes, postal code regex, Gini index, FIFA code, timezones, driving side, and start of week. |
| Image Assets | PNG and SVG flag and coat of arms images plus Unicode flag emoji are served directly in the payload. |
| Map Service Links | Each country includes deep links to Google Maps and OpenStreetMap. |
| Open Source | Mozilla Public License 2.0; the full Java/Maven source is available on GitHub and GitLab for self-hosting. |

## Use Cases

| Name | Description |
|------|-------------|
| Country Dropdowns and Selectors | Populate UI country pickers with localized names, flags, and ISO codes. |
| Address and Postal Validation | Validate postal codes against per-country format and regex patterns. |
| Phone Number Country Detection | Match international dialing prefixes to country names and flags. |
| Currency and Language Reference | Resolve ISO 4217 currency codes and ISO 639 language codes against country metadata. |
| Geographic Filtering | Group countries by UN region, subregion, or continent for reporting and segmentation. |
| Educational and Trivia Apps | Drive quizzes, learning content, and atlases with structured country data. |
| Data Enrichment | Enrich CRM, analytics, and logistics records with consistent country reference data. |

## Integrations

| Name | Description |
|------|-------------|
| Java SDK | Reference Java client embedded in the upstream Maven project. |
| Community SDKs | Community-published clients exist for JavaScript, Python, PHP, Ruby, Go, and Swift; none are official. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [REST Countries OpenAPI](openapi/rest-countries-openapi.yml)

### JSON Schema

- [Country](json-schema/rest-countries-country-schema.json)

### JSON Structure

- [Country](json-structure/rest-countries-country-structure.json)

### JSON-LD

- [REST Countries Context](json-ld/rest-countries-context.jsonld)

### Examples

- [Country (Germany)](examples/rest-countries-country-example.json)
- [Countries By Region (Western Europe)](examples/rest-countries-by-region-example.json)

## Capabilities

Naftiko capabilities organized as customer-facing workflows over the REST Countries v3.1 API.

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|---------------|-------|---------|
| [REST Countries Lookup](capabilities/rest-countries-lookup.yaml) | REST Countries | 10 | Developer / Data Consumer |

## Plans & Pricing

- [REST Countries Plans](plans/rest-countries-plans-pricing.yml) — Free hosted tier plus self-hosted (MPL-2.0) option

## Rate Limits

- [REST Countries Rate Limits](rate-limits/rest-countries-rate-limits.yml) — Soft fair-use limits on the hosted API; unlimited when self-hosted

## Vocabulary

- [REST Countries Vocabulary](vocabulary/rest-countries-vocabulary.yml) — Controlled vocabulary covering country reference concepts and 30+ resource attributes

## Rules

- [REST Countries Rules](rules/rest-countries-rules.yml) — 9 Spectral rules enforcing REST Countries v3.1 API conventions

## License

Source code is licensed under the [Mozilla Public License 2.0](https://www.mozilla.org/en-US/MPL/2.0/). The hosted REST Countries v3.1 API is provided free of charge by the community.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
