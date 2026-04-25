# Cisco Expressway (cisco-expressway)

API definitions for Cisco Expressway, a session border controller and firewall traversal solution for Unified Communications that provides secure remote and mobile access for collaboration workloads including video, voice, content, and presence. Programmatic access spans a REST API for configuration (`/api/provisioning`), a REST API for status and observability (`/api/status`), an SNMP MIB for metrics, and a legacy XML API for systems still in transition.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cisco-expressway/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
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
- **Modified:** 2026-04-23

## APIs

### Cisco Expressway Configuration API
RESTful API for configuring and managing Cisco Expressway systems including zones, search rules, transforms, DNS, NTP, and system settings. Uses JSON Schema Draft-04 for request and response shapes.

**Human URL:** [REST API Summary Guide (X14.2)](https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/expressway/admin_guide/X14-2/rest-api/exwy_b_cisco-expressway-rest-api-summary-guide--x142/exwy_m_using-the-expressway-rest-api.html)

#### Tags

- Configuration, Management, Provisioning, REST, Unified Communications

#### Properties

- [Documentation](https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/expressway/admin_guide/X14-2/rest-api/exwy_b_cisco-expressway-rest-api-summary-guide--x142/exwy_m_using-the-expressway-rest-api.html)
- [Reference](https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-programming-reference-guides-list.html)
- [Authentication](https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/expressway/admin_guide/X14-2/rest-api/exwy_b_cisco-expressway-rest-api-summary-guide--x142/exwy_m_using-the-expressway-rest-api.html)
- [OpenAPI](openapi/cisco-expressway-configuration-api-openapi.yml)
- [Zone JSON Schema](json-schema/cisco-expressway-zone-schema.json)
- [Search Rule JSON Schema](json-schema/cisco-expressway-search-rule-schema.json)
- [Transform JSON Schema](json-schema/cisco-expressway-transform-schema.json)
- [System Status JSON Schema](json-schema/cisco-expressway-system-status-schema.json)
- [JSON-LD Context](json-ld/cisco-expressway-context.jsonld)

### Cisco Expressway Status API
RESTful API for retrieving status information, alarms, call history, licensing status, upgrade status, and system health metrics. Endpoints follow the pattern `/api/status/common/` for items shared by Expressway-E and Expressway-C.

**Human URL:** [REST API Summary Guide (X14.2)](https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/expressway/admin_guide/X14-2/rest-api/exwy_b_cisco-expressway-rest-api-summary-guide--x142/exwy_m_using-the-expressway-rest-api.html)

#### Tags

- Alarms, Health Check, Licensing, Monitoring, Status

#### Properties

- [Documentation](https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/expressway/admin_guide/X14-2/rest-api/exwy_b_cisco-expressway-rest-api-summary-guide--x142/exwy_m_using-the-expressway-rest-api.html)
- [OpenAPI](openapi/cisco-expressway-status-api-openapi.yml)
- [Alarm JSON Schema](json-schema/cisco-expressway-alarm-schema.json)
- [Call JSON Schema](json-schema/cisco-expressway-call-schema.json)
- [Registration JSON Schema](json-schema/cisco-expressway-registration-schema.json)
- [System Status JSON Schema](json-schema/cisco-expressway-system-status-schema.json)
- [JSON-LD Context](json-ld/cisco-expressway-context.jsonld)

### Cisco Expressway SNMP API
SNMP-based monitoring and management interface providing access to system metrics, alarms, and configuration data. Supports SNMP v2c and v3 for secure network management integration.

**Human URL:** [SNMP Reference](https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-technical-reference-list.html)

#### Tags

- Metrics, Monitoring, Network Management, SNMP

### Cisco Expressway XML API
Legacy XML-based API for configuration and status retrieval. Uses HTTP Basic authentication over HTTPS.

**Human URL:** [Programming Reference Guides](https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-programming-reference-guides-list.html)

#### Tags

- Configuration, Legacy, Management, XML

## Common Properties

- [Cisco DevNet Portal](https://developer.cisco.com/)
- [Documentation](https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-programming-reference-guides-list.html)
- [Getting Started](https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-installation-and-configuration-guides-list.html)
- [Authentication](https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/expressway/admin_guide/X14-2/rest-api/exwy_b_cisco-expressway-rest-api-summary-guide--x142/exwy_m_using-the-expressway-rest-api.html)
- [Blog](https://blogs.cisco.com/collaboration)
- [Status](https://www.cisco.com/c/en/us/support/web/cloud-status.html)
- [Support](https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/tsd-products-support-series-home.html)
- [Terms of Service](https://www.cisco.com/c/en/us/about/legal/terms-conditions.html)
- [Privacy Policy](https://www.cisco.com/c/en/us/about/legal/privacy-full.html)
- [GitHub (CiscoDevNet)](https://github.com/CiscoDevNet)
- [Community](https://community.cisco.com/t5/devnet/ct-p/4409j-developer-home)
- [Website](https://www.cisco.com/c/en/us/products/unified-communications/expressway-series/index.html)
- [Change Log](https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-release-notes-list.html)
- [Downloads](https://software.cisco.com/download/home/286282896)
- [Compatibility](https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-device-support-tables-list.html)
- [Spectral Ruleset](rules/cisco-expressway-rules.yml)
- [Naftiko Capabilities](capabilities/cisco-expressway-capabilities.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
