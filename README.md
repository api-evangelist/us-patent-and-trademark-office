# US Patent and Trademark Office (us-patent-and-trademark-office)

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

The US Patent and Trademark Office (USPTO) is responsible for granting patents and registering trademarks to protect intellectual property in the United States. The USPTO examines patent applications to determine if an invention is new, non-obvious, and useful, and grants patents to those that meet the criteria. They also register trademarks, which are words, phrases, symbols, or designs that distinguish goods or services of one entity from another. The USPTO Open Data Portal provides free programmatic access to patent applications, PTAB trial proceedings, petition decisions, trademark status, and bulk datasets.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/us-patent-and-trademark-office/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/us-patent-and-trademark-office/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Federal Government
- Patents
- Trademarks
- Intellectual Property
- Open Data

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-05-19

## APIs

### USPTO Open Data Portal API

The USPTO Open Data Portal (ODP) API allows public users to discover, search, and extract USPTO patent, trademark, PTAB trial, petition decision, and bulk dataset information at no cost. Requires an ODP API key passed via the X-API-KEY header.

- **Human URL:** [https://data.uspto.gov/apis/getting-started](https://data.uspto.gov/apis/getting-started)

#### Tags

- Patents
- Trademarks
- Intellectual Property
- Federal Government
- Open Data

#### Properties

- [Documentation](https://data.uspto.gov/apis/getting-started)
- [OpenAPI](https://data.uspto.gov/swagger/swagger.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/us-patent-and-trademark-office/refs/heads/main/openapi/uspto-open-data-portal-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/uspto-open-data-portal.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uspto-open-data-portal.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/uspto-tsdr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uspto-tsdr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USPTO Trademark Status and Document Retrieval API

The Trademark Status and Document Retrieval (TSDR) REST API provides programmatic access to trademark case status, documents, case images, and related metadata. Requires an API key for bulk data downloads.

- **Human URL:** [https://developer.uspto.gov/api-catalog/tsdr-data-api](https://developer.uspto.gov/api-catalog/tsdr-data-api)

#### Tags

- Trademarks
- Intellectual Property
- Federal Government
- Open Data

#### Properties

- [Documentation](https://developer.uspto.gov/api-catalog/tsdr-data-api)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/us-patent-and-trademark-office/refs/heads/main/openapi/uspto-tsdr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/uspto-open-data-portal.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uspto-open-data-portal.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/uspto-tsdr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uspto-tsdr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/USPTO)
- [LinkedIn](https://www.linkedin.com/company/uspto)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
