# TheSportsDB (sportsdb)

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

TheSportsDB is an open, crowd-sourced database of sports artwork and metadata with a free REST API in JSON. It provides data on leagues, teams, players, events, venues, schedules, and season standings across soccer, basketball, baseball, American football, hockey, tennis, and many other sports worldwide, with premium V2 livescores and video highlights for supporters.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sportsdb/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sportsdb/refs/heads/main/apis.yml)

## Tags

- Sports
- Sports Data
- Teams
- Players
- Events

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### TheSportsDB Search API

Search across teams, players, events, venues, and filenames by name, with the API key supplied as a path segment.

- **Human URL:** [https://www.thesportsdb.com/documentation](https://www.thesportsdb.com/documentation)
- **Base URL:** `https://www.thesportsdb.com/api/v1/json`

#### Tags

- Search
- Teams
- Players

#### Properties

- [Documentation](https://www.thesportsdb.com/documentation)
- [API Reference](https://www.thesportsdb.com/free-api-documentation)
- [OpenAPI](openapi/sportsdb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sportsdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sportsdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TheSportsDB Lookups API

Look up full details by ID for leagues, teams, players, events, venues, equipment, honours, contracts, lineups, timelines, and stats.

- **Human URL:** [https://www.thesportsdb.com/documentation](https://www.thesportsdb.com/documentation)
- **Base URL:** `https://www.thesportsdb.com/api/v1/json`

#### Tags

- Lookup
- Details
- Metadata

#### Properties

- [Documentation](https://www.thesportsdb.com/documentation)
- [API Reference](https://www.thesportsdb.com/free-api-documentation)
- [OpenAPI](openapi/sportsdb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sportsdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sportsdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TheSportsDB Leagues API

List sports, countries, leagues, and seasons, and retrieve league tables (standings) for a given league and season.

- **Human URL:** [https://www.thesportsdb.com/documentation](https://www.thesportsdb.com/documentation)
- **Base URL:** `https://www.thesportsdb.com/api/v1/json`

#### Tags

- Leagues
- Seasons
- Standings

#### Properties

- [Documentation](https://www.thesportsdb.com/documentation)
- [API Reference](https://www.thesportsdb.com/free-api-documentation)
- [OpenAPI](openapi/sportsdb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sportsdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sportsdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TheSportsDB Events & Schedules API

Retrieve past and upcoming events by team or league, events by date, season schedules, TV schedules, and video highlights.

- **Human URL:** [https://www.thesportsdb.com/documentation](https://www.thesportsdb.com/documentation)
- **Base URL:** `https://www.thesportsdb.com/api/v1/json`

#### Tags

- Events
- Schedules
- Fixtures

#### Properties

- [Documentation](https://www.thesportsdb.com/documentation)
- [API Reference](https://www.thesportsdb.com/free-api-documentation)
- [OpenAPI](openapi/sportsdb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sportsdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sportsdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TheSportsDB Livescores API

Premium V2 livescores updated every 2 minutes by sport, league, or all, authenticated with an API key in the X-API-KEY header.

- **Human URL:** [https://www.thesportsdb.com/documentation](https://www.thesportsdb.com/documentation)
- **Base URL:** `https://www.thesportsdb.com/api/v2/json`

#### Tags

- Livescores
- Realtime
- Premium

#### Properties

- [Documentation](https://www.thesportsdb.com/documentation)
- [API Reference](https://www.thesportsdb.com/free-api-documentation)
- [OpenAPI](openapi/sportsdb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sportsdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sportsdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TheSportsDB Players & Teams API

List all teams in a league or sport/country and all players on a team, plus per-player results, statistics, and career history.

- **Human URL:** [https://www.thesportsdb.com/documentation](https://www.thesportsdb.com/documentation)
- **Base URL:** `https://www.thesportsdb.com/api/v1/json`

#### Tags

- Players
- Teams
- Rosters

#### Properties

- [Documentation](https://www.thesportsdb.com/documentation)
- [API Reference](https://www.thesportsdb.com/free-api-documentation)
- [OpenAPI](openapi/sportsdb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sportsdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sportsdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/thesportsdb)
- [Website](https://www.thesportsdb.com)
- [Documentation](https://www.thesportsdb.com/documentation)
- [Plans](plans/sportsdb-plans-pricing.yml)
- [Rate Limits](rate-limits/sportsdb-rate-limits.yml)
- [Fin Ops](finops/sportsdb-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
