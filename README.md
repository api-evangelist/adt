# ADT (adt)
ADT is a provider of monitored security, interactive home and business automation, and related monitoring services for residential and small business customers across the United States and Canada. ADT offers smart home security systems, professional monitoring, video surveillance, access control, and automation integrations with Google Nest, Amazon Alexa, and Z-Wave smart home devices through the ADT+ platform.

**URL:** [Visit ADT](https://www.adt.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Access Control, Automation, Home Security, IoT, Monitoring, Security, Smart Home

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### ADT+ Platform API
The ADT+ Platform API provides programmatic access to ADT's smart home security platform, enabling management of security devices, sensors, cameras, locks, and automation rules. Supports real-time status monitoring, arming and disarming, video clip retrieval, and alert management for residential and commercial security systems.

**Human URL:** [https://www.adt.com/smart-home](https://www.adt.com/smart-home)

#### Tags:

 - Automation, Monitoring, Security, Smart Home

#### Properties

- [Documentation](https://www.adt.com/smart-home)
- [OpenAPI](openapi/adt-platform-api-openapi.yml)
- [JSONSchema](json-schema/)
- [JSONStructure](json-structure/)
- [JSONLD](json-ld/adt-platform-api-context.jsonld)
- [SpectralRules](rules/adt-spectral-rules.yml)
- [NaftikoCapability](capabilities/shared/platform-api.yaml)
- [Vocabulary](vocabulary/adt-vocabulary.yaml)

### ADT Business API
The ADT Business API provides commercial security management capabilities including multi-site access control, commercial alarm management, video surveillance integration, and security event monitoring for small to enterprise business customers.

**Human URL:** [https://www.adt.com/business](https://www.adt.com/business)

#### Tags:

 - Access Control, Business Security, Commercial, Video Surveillance

#### Properties

- [Documentation](https://www.adt.com/business)
- [OpenAPI](openapi/adt-business-api-openapi.yml)
- [JSONSchema](json-schema/)
- [JSONStructure](json-structure/)
- [JSONLD](json-ld/adt-business-api-context.jsonld)
- [SpectralRules](rules/adt-spectral-rules.yml)
- [NaftikoCapability](capabilities/home-security-management.yaml)
- [Vocabulary](vocabulary/adt-vocabulary.yaml)

## Common Properties

- [Website](https://www.adt.com)
- [Portal](https://www.adt.com/smart-home)
- [Support](https://www.adt.com/support)
- [Blog](https://www.adt.com/about-adt/news)
- [TermsOfService](https://www.adt.com/terms-of-service)
- [PrivacyPolicy](https://www.adt.com/privacy-policy)
- [Login](https://www.adt.com/login)
- [SignUp](https://www.adt.com/get-a-quote)

## Features

| Name | Description |
|------|-------------|
| Professional Security Monitoring | 24/7 professional monitoring center that responds to alarms, contacts emergency services, and alerts homeowners. |
| Smart Home Automation | Programmatic control of lights, locks, thermostats, and smart plugs integrated with the ADT+ security platform. |
| Video Surveillance and Clips | Access and retrieve recorded video clips from indoor, outdoor, and doorbell cameras via API. |
| Remote Arm and Disarm | Remotely arm and disarm security systems and zones through authenticated API calls. |
| Sensor and Device Status | Real-time status monitoring of door sensors, motion detectors, smoke detectors, and flood sensors. |
| Access Control Management | Manage smart locks, access codes, and entry permissions for residential and commercial properties. |
| Alarm Event Notifications | Receive real-time webhook notifications for alarm events, zone violations, and system status changes. |
| Multi-Site Management | Manage multiple properties and security systems from a single API integration for commercial customers. |

## Use Cases

| Name | Description |
|------|-------------|
| Home Automation Integration | Integrate ADT security with third-party home automation platforms like Google Home, Amazon Alexa, and Apple HomeKit. |
| Property Management | Manage access codes and security schedules for rental properties, vacation homes, and commercial buildings. |
| Insurance Integration | Share security monitoring data with insurance providers for smart home insurance discount programs. |
| Emergency Response Automation | Trigger automated emergency responses, notifications, and camera recordings when alarms are triggered. |
| Business Intelligence | Analyze security events, access patterns, and alarm history for business operational insights. |
| Contractor Access Management | Issue temporary access codes for service contractors with time-limited entry permissions. |

## Integrations

| Name | Description |
|------|-------------|
| Google Nest | Integration with Google Nest thermostats, cameras, and smart displays through ADT+ with Google partnership. |
| Amazon Alexa | Voice control of ADT security system including arm, disarm, and status queries via Amazon Alexa. |
| Google Assistant | Voice control and smart home automation via Google Assistant and Nest Hub displays. |
| Z-Wave | Z-Wave wireless protocol support for smart locks, lights, thermostats, and other smart home devices. |
| Apple HomeKit | HomeKit-compatible devices that integrate with ADT security ecosystem. |
| Ring | Integration with Ring video doorbells and cameras as complementary security devices. |
| Lutron | Smart lighting control integration with Lutron Caseta and RadioRA systems. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [ADT Platform API](openapi/adt-platform-api-openapi.yml)
- [ADT Business API](openapi/adt-business-api-openapi.yml)

### JSON Schema

- 25 schema files in [json-schema/](json-schema/)

### JSON Structure

- 25 structure files in [json-structure/](json-structure/)

### JSON-LD

- [ADT Platform API Context](json-ld/adt-platform-api-context.jsonld)
- [ADT Business API Context](json-ld/adt-business-api-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [ADT Platform API](capabilities/shared/platform-api.yaml) — 9 operations for security system management, device monitoring, event retrieval, access codes, and video clips

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Home Security Management](capabilities/home-security-management.yaml) | ADT Platform API | 10 | Homeowners, Property Managers |

## Vocabulary

- [ADT Vocabulary](vocabulary/adt-vocabulary.yaml) — Unified taxonomy mapping 10 resources, 6 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [ADT Spectral Rules](rules/adt-spectral-rules.yml) — 30 rules across 12 categories enforcing ADT API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
