# ADT (adt)

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

ADT is a provider of monitored security, interactive home and business automation, and related monitoring services for residential and small business customers across the United States and Canada. ADT offers smart home security systems, professional monitoring, video surveillance, access control, and automation integrations with Google Nest, Amazon Alexa, and Z-Wave smart home devices through the ADT+ platform.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/adt/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/adt/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Access Control
- Automation
- Home Security
- IoT
- Monitoring
- Security
- Smart Home

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### ADT+ Platform API

The ADT+ Platform API provides programmatic access to ADT's smart home security platform, enabling management of security devices, sensors, cameras, locks, and automation rules. Supports real-time status monitoring, arming and disarming, video clip retrieval, and alert management for residential and commercial security systems.

- **Human URL:** [https://www.adt.com/smart-home](https://www.adt.com/smart-home)
- **Base URL:** `https://api.adt.com/v1`

#### Tags

- Automation
- Monitoring
- Security
- Smart Home

#### Properties

- [Documentation](https://www.adt.com/smart-home)
- [OpenAPI](openapi/adt-platform-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/adt-platform-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adt-platform-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/)
- [JSON-LD](json-ld/adt-platform-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/adt-spectral-rules.yml)
- [Vocabulary](vocabulary/adt-vocabulary.yaml)

### ADT Business API

The ADT Business API provides commercial security management capabilities including multi-site access control, commercial alarm management, video surveillance integration, and security event monitoring for small to enterprise business customers.

- **Human URL:** [https://www.adt.com/business](https://www.adt.com/business)
- **Base URL:** `https://api.adt.com/business/v1`

#### Tags

- Access Control
- Business Security
- Commercial
- Video Surveillance

#### Properties

- [Documentation](https://www.adt.com/business)
- [OpenAPI](openapi/adt-business-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/adt-business-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adt-business-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/)
- [JSON-LD](json-ld/adt-business-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/adt-spectral-rules.yml)
- [Vocabulary](vocabulary/adt-vocabulary.yaml)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/adt)
- [Website](https://www.adt.com)
- [Portal](https://www.adt.com/smart-home)
- [Support](https://www.adt.com/support)
- [Blog](https://www.adt.com/about-adt/news)
- [Terms of Service](https://www.adt.com/terms-of-service)
- [Privacy Policy](https://www.adt.com/privacy-policy)
- [Login](https://www.adt.com/login)
- [Sign Up](https://www.adt.com/get-a-quote)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Integrations](https://www.adt.com/apps)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
