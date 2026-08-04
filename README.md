# Uptime.com (uptime-com)

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

Uptime.com is a website, application, and infrastructure monitoring platform providing uptime checks, transaction and API monitoring, page speed checks, SLA reporting, status pages, and alerting from a global network of probe servers. Its REST API at https://uptime.com/api/v1 (Token authentication) lets customers programmatically manage checks, outages, SLA reports, status pages, contacts, integrations, and tags.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/uptime-com/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/uptime-com/refs/heads/main/apis.yml)

## Tags

- Monitoring
- Uptime
- Website Monitoring
- Status Pages
- SLA

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Uptime.com Checks & Monitors API

Create, list, retrieve, update, pause, resume, and delete monitoring checks including HTTP(S), API/transaction, DNS, TCP, SMTP, SSH, ping, blacklist, malware, and group checks, plus probe-server location management.

- **Human URL:** [https://uptime.com/api/v1/docs/](https://uptime.com/api/v1/docs/)
- **Base URL:** `https://uptime.com/api/v1`

#### Tags

- Checks
- Monitors
- Uptime

#### Properties

- [Documentation](https://support.uptime.com/hc/en-us/articles/360009681280-Getting-Started-with-the-Uptime-com-REST-API)
- [API Reference](https://uptime.com/api/v1/docs/)
- [OpenAPI](openapi/uptime-com-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/uptime-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uptime-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Uptime.com Outages API

List and retrieve detected outage records produced by checks, including start/end timestamps, duration, the originating check, and resolution state.

- **Human URL:** [https://uptime.com/api/v1/docs/](https://uptime.com/api/v1/docs/)
- **Base URL:** `https://uptime.com/api/v1`

#### Tags

- Outages
- Incidents
- Downtime

#### Properties

- [Documentation](https://support.uptime.com/hc/en-us/articles/360009681280-Getting-Started-with-the-Uptime-com-REST-API)
- [API Reference](https://uptime.com/api/v1/docs/)
- [OpenAPI](openapi/uptime-com-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/uptime-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uptime-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Uptime.com SLA Reports API

Create, list, retrieve, update, and delete SLA reports that summarize uptime, response time, and outage performance across selected checks and tags over a default or custom reporting period.

- **Human URL:** [https://uptime.com/api/v1/docs/](https://uptime.com/api/v1/docs/)
- **Base URL:** `https://uptime.com/api/v1`

#### Tags

- SLA
- Reports
- Reporting

#### Properties

- [Documentation](https://support.uptime.com/hc/en-us/articles/360009681280-Getting-Started-with-the-Uptime-com-REST-API)
- [API Reference](https://uptime.com/api/v1/docs/)
- [OpenAPI](openapi/uptime-com-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/uptime-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uptime-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Uptime.com Status Pages API

Create, list, retrieve, update, and delete public and private status pages along with their components and incidents for communicating service health to users.

- **Human URL:** [https://uptime.com/api/v1/docs/](https://uptime.com/api/v1/docs/)
- **Base URL:** `https://uptime.com/api/v1`

#### Tags

- Status Pages
- Incidents
- Components

#### Properties

- [Documentation](https://support.uptime.com/hc/en-us/articles/360009681280-Getting-Started-with-the-Uptime-com-REST-API)
- [API Reference](https://uptime.com/api/v1/docs/)
- [OpenAPI](openapi/uptime-com-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/uptime-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uptime-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Uptime.com Contacts & Integrations API

Manage contact groups (email, SMS, voice, on-call schedules) and notification integrations (Slack, PagerDuty, Opsgenie, webhooks, and more) used to route check and outage alerts.

- **Human URL:** [https://uptime.com/api/v1/docs/](https://uptime.com/api/v1/docs/)
- **Base URL:** `https://uptime.com/api/v1`

#### Tags

- Contacts
- Integrations
- Alerting

#### Properties

- [Documentation](https://support.uptime.com/hc/en-us/articles/360009681280-Getting-Started-with-the-Uptime-com-REST-API)
- [API Reference](https://uptime.com/api/v1/docs/)
- [OpenAPI](openapi/uptime-com-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/uptime-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uptime-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Uptime.com Tags API

Create, list, retrieve, update, and delete color-coded check tags used to group and filter checks, SLA reports, and status pages across the account.

- **Human URL:** [https://uptime.com/api/v1/docs/](https://uptime.com/api/v1/docs/)
- **Base URL:** `https://uptime.com/api/v1`

#### Tags

- Tags
- Labels
- Organization

#### Properties

- [Documentation](https://support.uptime.com/hc/en-us/articles/360009681280-Getting-Started-with-the-Uptime-com-REST-API)
- [API Reference](https://uptime.com/api/v1/docs/)
- [OpenAPI](openapi/uptime-com-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/uptime-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uptime-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/uptime-com)
- [LinkedIn](https://www.linkedin.com/company/uptime-com)
- [Website](https://uptime.com/)
- [Documentation](https://uptime.com/api/v1/docs/)
- [Plans](plans/uptime-com-plans-pricing.yml)
- [Rate Limits](rate-limits/uptime-com-rate-limits.yml)
- [Fin Ops](finops/uptime-com-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
