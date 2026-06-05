# Cisco Expressway (cisco-expressway)

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
