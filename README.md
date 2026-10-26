# Cisco Expressway (cisco-expressway)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

API definitions for Cisco Expressway, a session border controller and firewall traversal solution for Unified Communications that provides secure remote and mobile access for collaboration workloads including video, voice, content, and presence. Programmatic access spans a REST API for configuration (/api/provisioning), a REST API for status and observability (/api/status), an SNMP MIB for metrics, and a legacy XML API for systems still in transition.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cisco-expressway/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cisco-expressway/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Collaboration
- Firewall Traversal
- H.323
- Session Border Controller
- SIP
- Unified Communications
- Video Conferencing

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Cisco Expressway Configuration API

RESTful API for configuring and managing Cisco Expressway systems including zones, search rules, transforms, DNS, NTP, and system settings. Uses JSON Schema version 4 for request and response schemas.

- **Human URL:** [https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/expressway/admin_guide/X14-2/rest-api/exwy_b_cisco-expressway-rest-api-summary-guide--x142/exwy_m_using-the-expressway-rest-api.html](https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/expressway/admin_guide/X14-2/rest-api/exwy_b_cisco-expressway-rest-api-summary-guide--x142/exwy_m_using-the-expressway-rest-api.html)
- **Base URL:** `https://expressway.example.com/api/provisioning`

#### Tags

- Configuration
- Management
- Provisioning
- REST
- Unified Communications

#### Properties

- [Documentation](https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/expressway/admin_guide/X14-2/rest-api/exwy_b_cisco-expressway-rest-api-summary-guide--x142/exwy_m_using-the-expressway-rest-api.html)
- [Reference](https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-programming-reference-guides-list.html)
- [Authentication](https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/expressway/admin_guide/X14-2/rest-api/exwy_b_cisco-expressway-rest-api-summary-guide--x142/exwy_m_using-the-expressway-rest-api.html)
- [Getting Started](https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-installation-and-configuration-guides-list.html)
- [Changelog](https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-release-notes-list.html)
- [OpenAPI](openapi/cisco-expressway-configuration-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-expressway-configuration-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-expressway-configuration-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/cisco-expressway-zone-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cisco-expressway-search-rule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cisco-expressway-transform-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cisco-expressway-system-status-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/cisco-expressway-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Cisco Expressway Status API

RESTful API for retrieving status information, alarms, call history, licensing status, upgrade status, and system health metrics from Cisco Expressway. Endpoints follow the pattern /api/status/common/ for items common between Expressway-E and Expressway-C.

- **Human URL:** [https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/expressway/admin_guide/X14-2/rest-api/exwy_b_cisco-expressway-rest-api-summary-guide--x142/exwy_m_using-the-expressway-rest-api.html](https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/expressway/admin_guide/X14-2/rest-api/exwy_b_cisco-expressway-rest-api-summary-guide--x142/exwy_m_using-the-expressway-rest-api.html)
- **Base URL:** `https://expressway.example.com/api/status`

#### Tags

- Alarms
- Health Check
- Licensing
- Monitoring
- Status

#### Properties

- [Documentation](https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/expressway/admin_guide/X14-2/rest-api/exwy_b_cisco-expressway-rest-api-summary-guide--x142/exwy_m_using-the-expressway-rest-api.html)
- [Reference](https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-programming-reference-guides-list.html)
- [Getting Started](https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-installation-and-configuration-guides-list.html)
- [Changelog](https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-release-notes-list.html)
- [OpenAPI](openapi/cisco-expressway-status-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-expressway-status-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-expressway-status-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/cisco-expressway-alarm-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cisco-expressway-call-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cisco-expressway-registration-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cisco-expressway-system-status-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/cisco-expressway-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Cisco Expressway SNMP API

SNMP-based monitoring and management interface for Cisco Expressway providing access to system metrics, alarms, and configuration data. Supports SNMP versions v2c and v3 for secure network management integration.

- **Human URL:** [https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-technical-reference-list.html](https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-technical-reference-list.html)
- **Base URL:** `snmp://expressway.example.com:161`

#### Tags

- Metrics
- Monitoring
- Network Management
- SNMP

#### Properties

- [Documentation](https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-technical-reference-list.html)
- [Reference](https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-technical-reference-list.html)
- [Changelog](https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-release-notes-list.html)
- [Postman Collection](collections/cisco-expressway-configuration-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-expressway-configuration-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/cisco-expressway-status-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-expressway-status-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco Expressway XML API

Legacy XML-based API for configuration and status retrieval on Cisco Expressway systems. Uses HTTP Basic Authentication over HTTPS for secure access to system configuration and management functions.

- **Human URL:** [https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-programming-reference-guides-list.html](https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-programming-reference-guides-list.html)
- **Base URL:** `https://expressway.example.com/xmlapi`

#### Tags

- Configuration
- Legacy
- Management
- XML

#### Properties

- [Documentation](https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-programming-reference-guides-list.html)
- [Authentication](https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/expressway/admin_guide/X14-0/exwy_b_cisco-expressway-administrator-guide/exwy_m_managing-security.html)
- [Changelog](https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-release-notes-list.html)
- [Postman Collection](collections/cisco-expressway-configuration-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-expressway-configuration-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/cisco-expressway-status-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-expressway-status-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://developer.cisco.com/)
- [Documentation](https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-programming-reference-guides-list.html)
- [Getting Started](https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-installation-and-configuration-guides-list.html)
- [Authentication](https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/expressway/admin_guide/X14-2/rest-api/exwy_b_cisco-expressway-rest-api-summary-guide--x142/exwy_m_using-the-expressway-rest-api.html)
- [Blog](https://blogs.cisco.com/collaboration)
- [Status Page](https://www.cisco.com/c/en/us/support/web/cloud-status.html)
- [Support](https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/tsd-products-support-series-home.html)
- [Terms of Service](https://www.cisco.com/c/en/us/about/legal/terms-conditions.html)
- [Privacy Policy](https://www.cisco.com/c/en/us/about/legal/privacy-full.html)
- [GitHub Organization](https://github.com/CiscoDevNet)
- [Community](https://community.cisco.com/t5/devnet/ct-p/4409j-developer-home)
- [Website](https://www.cisco.com/c/en/us/products/unified-communications/expressway-series/index.html)
- [Login](https://developer.cisco.com/)
- [Sign Up](https://developer.cisco.com/)
- [Changelog](https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-release-notes-list.html)
- [Downloads](https://software.cisco.com/download/home/286282896)
- [Compatibility](https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-device-support-tables-list.html)
- [Spectral Rules](rules/cisco-expressway-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
