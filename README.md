# Universiti Sains Malaysia (usm)

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

Universiti Sains Malaysia (USM) is a public research university founded in 1969 in Penang, Malaysia, holding APEX status and ranked #146 in the QS World University Rankings 2025. This repository catalogs USM's public developer/API footprint as an [APIs.json](http://apisjson.org) provider profile.

- APIs.json: <https://raw.githubusercontent.com/api-evangelist/usm/refs/heads/main/apis.yml>
- Run with Naftiko: <https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=usm-api-evangelist&utm_content=repo>

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Access, OAI-PMH, Malaysia

## APIs

- **USM Repository OAI-PMH** — Live OAI-PMH 2.0 metadata-harvesting endpoint for the EPrints 3.3.16 institutional repository (Repository@USM). Docs: <https://eprints.usm.my/> · Base: `https://eprints.usm.my/cgi/oai2`
- **API@USM Developer Portal (Gated)** — Institutional API portal operated by PPKT; catalog and documentation are behind login, no public endpoints exposed. Docs: <https://api.usm.my/>

## Plans

See [plans/usm-plans-pricing.yml](plans/usm-plans-pricing.yml).

## Rate Limits

See [rate-limits/usm-rate-limits.yml](rate-limits/usm-rate-limits.yml).

## FinOps

See [finops/usm-finops.yml](finops/usm-finops.yml).

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: <https://www.usm.my/en/>
- Developer Portal: <https://api.usm.my/>
- LinkedIn: <https://www.linkedin.com/school/universiti-sains-malaysia-official/>

## Notes

Only live-verified surfaces are cataloged; no endpoints were fabricated. The EPrints OAI-PMH endpoint returns a valid Identify response. The api.usm.my developer portal is real (HTTP 200) but gated behind login with no public catalog. No official USM GitHub organization was found (github.com/usm-my returns 404), and no `data.usm.my` or `developer.usm.my` subdomain resolves. The official website (www.usm.my) blocks automated requests (HTTP 403) but is the live institutional site.

## Maintainers

- Kin Lane — <kin@apievangelist.com>
