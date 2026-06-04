# Universiti Sains Malaysia (usm)

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
