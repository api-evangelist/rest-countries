# REST Countries (rest-countries)

REST Countries is a free, open-source RESTful API that returns rich country reference data — ISO 3166-1 codes (cca2, cca3, ccn3, cioc), common/official and native names, translations, capitals, regions and subregions, continents, currencies, languages, calling codes, top-level domains, timezones, geographic coordinates, borders, area, population, demonyms, flags and coats of arms, postal code formats, Gini index, FIFA code, independence and UN membership status, driving side, and start of week. The canonical hosted instance runs at restcountries.com (v3.1) and the source is community-maintained at github.com/apilayer/restcountries (mirror of gitlab.com/restcountries/restcountries), licensed under MPL-2.0. The hosted API is unauthenticated and free; for production use the project encourages self-hosting from source.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/rest-countries/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/rest-countries/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** Public

## Tags

- Countries
- Geocoding
- Geography
- ISO 3166
- Open Source
- Public APIs
- Reference Data
- Currencies
- Languages
- Capitals
- Regions
- Subregions
- Translations

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### REST Countries

Free, unauthenticated, read-only REST API for country reference data. Provides endpoints for bulk listing and for lookups by name, ISO alpha code (cca2/cca3/ccn3/cioc), currency, language, capital, region, subregion, translation, demonym, and independence status. Response payloads can be trimmed with the `fields` query parameter (required on `/all`).

- **Human URL:** [https://restcountries.com](https://restcountries.com)
- **Base URL:** `https://restcountries.com/v3.1`

#### Tags

- Countries
- Geography
- ISO 3166
- Reference Data
- REST

#### Properties

- [Documentation](https://restcountries.com)
- [GitHub Repository](https://github.com/apilayer/restcountries)
- [Source Repository](https://gitlab.com/restcountries/restcountries)
- [OpenAPI](openapi/rest-countries-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rest-countries.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rest-countries.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/rest-countries-country-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/rest-countries-country-structure.json)
- [J S O N- L D](json-ld/rest-countries-context.jsonld)
- [Example](examples/rest-countries-country-example.json)
- [Example](examples/rest-countries-by-region-example.json)
- [Plans](plans/rest-countries-plans-pricing.yml)
- [Rate Limits](rate-limits/rest-countries-rate-limits.yml)

## Common Properties

- [Website](https://restcountries.com)
- [Documentation](https://restcountries.com)
- [GitHub Repository](https://github.com/apilayer/restcountries)
- [Source Repository](https://gitlab.com/restcountries/restcountries)
- [Mirror](https://github.com/restcountries/restcountries)
- [License](https://www.mozilla.org/en-US/MPL/2.0/)
- [Spectral Rules](rules/rest-countries-rules.yml)
- [Vocabulary](vocabulary/rest-countries-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
