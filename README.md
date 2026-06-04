# École des Ponts ParisTech (ecole-des-ponts-paristech)

École des Ponts ParisTech (École nationale des ponts et chaussées, ENPC) is a leading French public engineering grande école based in Champs-sur-Marne, ranked #205 in the QS World University Rankings 2025. This repository catalogs the institution's public developer/API footprint as an APIs.json provider profile for the api-evangelist organization. ENPC's verifiable public API footprint is research- and library-oriented: an institutional open-access repository exposed as the ENPC collection on the national HAL platform (harvestable via the HAL Search API and OAI-PMH), plus a small public GitHub organization.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/ecole-des-ponts-paristech/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ecole-des-ponts-paristech-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Engineering, Research, Open Access, Open Data, Library, OAI-PMH, France

## APIs

- **HAL Search API (ENPC collection)** — Solr-backed publication metadata for the ENPC institutional open-access collection on the national HAL platform. Docs: https://api.archives-ouvertes.fr/docs/search · Base: https://api.archives-ouvertes.fr/search/ENPC/
- **HAL OAI-PMH Endpoint** — OAI-PMH 2.0 metadata harvesting for the ENPC collection on HAL. Docs: https://api.archives-ouvertes.fr/docs/oai · Base: https://api.archives-ouvertes.fr/oai/hal/
- **OAI-PMH Repository Plugin (Omeka)** — Open-source PHP plugin on the official GitHub org for exposing the school's digital heritage library metadata to Gallica/Europeana. Repo: https://github.com/EcoleDesPontsParisTech/OaiPmhRepository

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/ecole-des-ponts-paristech-plans-pricing.yml](plans/ecole-des-ponts-paristech-plans-pricing.yml)
- Rate Limits: [rate-limits/ecole-des-ponts-paristech-rate-limits.yml](rate-limits/ecole-des-ponts-paristech-rate-limits.yml)
- FinOps: [finops/ecole-des-ponts-paristech-finops.yml](finops/ecole-des-ponts-paristech-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://ecoledesponts.fr/
- GitHub: https://github.com/EcoleDesPontsParisTech
- LinkedIn: https://www.linkedin.com/school/ecole-des-ponts-paristech/
- Twitter/X: https://twitter.com/EcoledesPonts
- Library: https://lib.enpc.fr/
- Repository (HAL ENPC): https://enpc.hal.science/

## Notes

- ENPC does not publish a general-purpose, self-service developer portal. The cataloged APIs are research/library interfaces, not a commercial developer program.
- The HAL Search API and OAI-PMH endpoint are national CCSD/HAL infrastructure scoped to the institution's ENPC collection (verified live: 43,726 ENPC records; OAI-PMH Identify returned valid XML), not endpoints hosted on ENPC's own domains.
- No course/timetable/SIS, identity/SSO, research-data, or mobile-backend APIs were found publicly documented; none were invented.
- The espacechercheurs.enpc.fr open-science portal did not resolve from the review environment; LinkedIn returned an anti-bot 999 rather than a confirmed status.

## Maintainers

- Kin Lane — kin@apievangelist.com
