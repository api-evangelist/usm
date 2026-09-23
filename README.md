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

Universiti Sains Malaysia (USM) is a public research university founded in 1969 in Penang, Malaysia, holding APEX status. This repository catalogs USM's public developer/API footprint as an [APIs.json](http://apisjson.org) provider profile, profiled under the API Evangelist **university pipeline** — which settles *who operates* each surface before crediting it to the institution.

- APIs.json: <https://raw.githubusercontent.com/api-evangelist/usm/refs/heads/main/apis.yml>
- Run with Naftiko: <https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=usm-api-evangelist&utm_content=repo>

## Type

- university / Public Research University
- Index
- Consumer
- 3rd-Party

## Tags

University, Higher Education, Education, Public Research University, Malaysia, Southeast Asia, Research, Open Access, Institutional Repository, OAI-PMH, EPrints, Identity Federation, Shibboleth, SAML, Crossref

## Surfaces, by who operates them

USM runs **no developer programme** — no catalog, no documentation, no terms, no status page, no changelog, no GitHub organization. Everything below is a by-product of software the institution runs, and each entry names its operator.

**institution** — USM's own host, USM's own deployment:

- **USM Repository OAI-PMH** — OAI-PMH 2.0 harvesting for Repository@USM (EPrints 3.3.16). Six metadata prefixes; anonymous read. Base: `https://eprints.usm.my/cgi/oai2` · [OpenAPI](openapi/usm-repository-oai-pmh-openapi.yml)
- **USM Repository EPrints REST and Export** — `/rest/` dataset tree, EP2 data XML per record, single-field plain-text access, and seventeen verified export serializations. Base: `https://eprints.usm.my` · [OpenAPI](openapi/usm-repository-eprints-rest-openapi.yml)
- **e-Learning@USM Moodle Web Services** — self-hosted Moodle with the REST web service enabled and token-gated. The deployment is USM's; the contract is Moodle's and is deliberately not reproduced here.

**federation** — shared by definition, and the identity provider behind it is USM's:

- **USM Shibboleth Identity Provider** — `https://shibsso.usm.my/idp/shibboleth`, scope `usm.my`, registered in the SIFULAN Malaysian Access Federation on 2021-10-30 and exported to eduGAIN, carrying the REFEDS Research and Scholarship entity category. In live production use.

**registry** — facts about USM recorded in a registry other institutions also use:

- **Crossref member 8963** — DOI prefixes 10.21315 and 10.36777, 4,955 registered DOIs.
- **ROR `02rgb2k63`** — the join key ORCID and Crossref use to attribute USM's research output.

## Artifacts

| Artifact | What it holds |
|---|---|
| [openapi/](openapi/) | Two derived contracts for the repository surfaces, with pristine copies in [`openapi/_original/`](openapi/_original/) |
| [json-schema/](json-schema/usm-eprint-record.json) | Shape of an EPrints record from the live JSON export |
| [examples/](examples/) | Unedited live captures — OAI Identify, ListMetadataFormats, one full record |
| [errors/](errors/usm-repository-oai-pmh-errors.yml) | All five OAI-PMH error conditions, provoked and observed |
| [authentication/](authentication/usm-authentication.yml) | Per-surface auth posture, every line from a probe |
| [conformance/](conformance/usm-education-standards-conformance.yml) | Education-regime standards: oai-pmh, shibboleth, saml, crossref verified; datacite absent |
| [vocabulary/](vocabulary/usm-repository-vocabulary.yml) | Terms and formats actually observed, including the hex-encoded OAI setSpecs |
| [lifecycle/](lifecycle/usm-repository-lifecycle.yml) | Versioning and change posture — and the policies USM has not declared |
| [rules/](rules/usm-rules.yml) | Spectral ruleset, including the host check that keeps a vendor's contract out |

## Timestamps

- Created: 2026-06-03
- Modified: 2026-09-01

## Common Properties

- Website: <https://www.usm.my/en/>
- Research Repository: <https://eprints.usm.my/>
- Identity Federation: <https://shibsso.usm.my/idp/shibboleth>
- Library: <https://lib.usm.my/>
- Developer Portal: <https://api.usm.my/>
- News: <https://news.usm.my/>
- IT Support (PPKT): <https://ppkt.usm.my/>
- LinkedIn: <https://www.linkedin.com/school/universiti-sains-malaysia-official/>
- AI Policy (see note): the Ministry of Higher Education's national generative-AI guideline, republished by USM's Centre for Development of Academic Excellence at <https://cdae.usm.my/>

## Notes

Only live-verified surfaces are cataloged; no endpoints were fabricated. Three corrections were made on 2026-09-01 against the June 2026 profile:

1. **`api.usm.my` is not a gated API catalog.** It is an unmodified TemplateMo "Chain App Dev" HTML template — lorem ipsum body copy, `info@company.co` as the contact address, every navigation link an in-page anchor, and `/docs`, `/openapi.json` and `/swagger-ui` all 404. The login modal is scaffolding, not a gate in front of an API programme. It has been removed from `apis[]` and kept only as a Developer Portal pointer.
2. **`www.usm.my` is not dead.** The recorded HTTP 403 was a bot challenge; the site returns 200 to a browser User-Agent.
3. **The repository surface is much larger than one OAI-PMH endpoint**, and USM's Shibboleth IdP — the strongest machine-readable thing the institution operates — was missing entirely.

Two defects in USM's own configuration are worth reporting upstream to <eprints@usm.my>: the repository still advertises the EPrints default `repositoryIdentifier` `generic.eprints.org` instead of `usm.my`, so its OAI identifiers are not globally distinguishable; and it still ships the default "this server has not yet been fully configured" metadata, data and submission policy text, leaving harvesters with no declared rights over the metadata.

On the AI axis, no USM-authored AI policy was found in English or Malay. The only guidance on a USM host is the Ministry of Higher Education's national guideline, *Garis Panduan Penggunaan Teknologi Kecerdasan Buatan Generatif (KBG) dalam Pengajaran dan Pembelajaran Pendidikan Tinggi*, republished as a PDF by USM's Centre for Development of Academic Excellence — it is recorded as the `AIPolicy` pointer because it is the operative guidance, but it is MOHE's document, not USM's.

No `data.usm.my` or `developer.usm.my` subdomain resolves, and no official USM GitHub organization was found (`github.com/usm-my` returns 404). USM is not a DataCite provider or client.

## Maintainers

- Kin Lane — <kin@apievangelist.com>
