# A Safe Bet: framework development

Development of the A Safe Bet framework: a scoping review and structured taxonomy of responsible gambling (RG) tools, the Responsible Gambling Intervention Framework built from it, and regulatory implementation architectures for the United Kingdom and the Netherlands. The framework provides the design basis for the whole programme: a standardised reference library of RG tools, and jurisdiction-specific specifications for deploying them on live gambling platforms. The review covered peer-reviewed, English-language studies of adult gambling populations, searched in three rounds between May 2021 and May 2024. The taxonomy and the Intervention Framework were developed independently of the collaborating operators. For the implementation architectures, the research team applied all selection filters; operator product and compliance teams provided the feasibility information used at the final filter and reviewed the policy rule sets.

## Programme and status

Part of [A Safe Bet](https://github.com/a-safe-bet-research), a research programme on player-tailored responsible gambling led by Erasmus University Rotterdam and the University of Amsterdam.

**Status:** under revision 

## Preregistration

Not preregistered. The review was an iterative, evidence-organising process rather than a test of a pre-specified question.

## Preprint

None at present.

## Publication

Not yet published. Citation to be added on acceptance.

## Repository contents

The numbered subfolders match the Open Science Framework deposit cited in the manuscript, so appendix references (e.g. Appendix 01.1) resolve in both places.

| Folder | Contents |
|---|---|
| `protocol/01_review_protocol/` | Search strategy, eligibility criteria, PRISMA-ScR checklist, detailed PRISMA flow, screening and exclusion record |
| `protocol/02_extraction_framework/` | 45-field inventory, extraction codebook, tool codes and domains, evidence direction and sample size, evidence quality and readiness |
| `materials/03_rg_taxonomy/` | Taxonomy dataset of 410 tool records, convergent evidence set, structural patterns |
| `materials/04_rg_intervention_framework/` | The Responsible Gambling Intervention Framework (210 tools across 15 domains), its codebook, framework-to-architecture translation |
| `materials/05_implementation_architectures/` | UK and Netherlands implementation architectures, architecture codebook, architecture methodology |
| `code/` | Scripts used to produce the taxonomy analyses and figures, where applicable |
| `outputs/` | Figures and tables as submitted |

## Data availability

| Category | What | Where |
|---|---|---|
| Open | All review, extraction, taxonomy, framework and architecture files | This repository; the deposit cited in the manuscript at https://doi.org/10.17605/OSF.IO/SWRKT |
| Derived or aggregated only | None | |
| Controlled access | None | |
| Not shareable | None. No participant data were collected for this study | |

## Reproducing the analysis

The study is a literature-based synthesis. Where scripts exist in `code/`, they run in numbered order from the repository root; see `code/README.md`.

## Ethics and governance

The study synthesised published literature and involved no human participants; formal ethics approval was therefore not required. Programme-level governance documents are in [`common/governance/`](https://github.com/a-safe-bet-research/common).

## Funding and partners

See the [organisation profile](https://github.com/a-safe-bet-research). The collaborating gambling operators were not involved in the design of the taxonomy or the Responsible Gambling Intervention Framework. Both operators participated as project partners under the collaboration agreement; for the implementation architectures their product and compliance teams provided feasibility information and reviewed the policy rule sets, with confirmation status recorded per rule in the architecture codebook (Appendix 05.3).

## Authors and contributions

Harriet R. Galvin (ORCID 0000-0003-0698-5093; Erasmus University Rotterdam), Leroy Snippe (no ORCID; University of Amsterdam), Michael J. A. Wohl (ORCID 0000-0001-6945-5562; Carleton University), Reinout W. Wiers (ORCID 0000-0002-4312-9766; University of Amsterdam), Marilisa Boffo (ORCID 0000-0003-4730-7838; Erasmus University Rotterdam). CRediT roles as stated in the publication.

## Licences

Code: PolyForm Noncommercial 1.0.0, see `LICENSE-code.md`. Materials, documentation and outputs: CC BY-NC-SA 4.0, see `LICENSE-materials.md`. Copyright Erasmus University Rotterdam. Commercial licences on request: gamblingresearch@essb.eur.nl.

## How to cite this repository

Zenodo DOI to be added at the first release. Until then cite the OSF deposit: https://doi.org/10.17605/OSF.IO/SWRKT.

## Related repositories

- [`common`](https://github.com/a-safe-bet-research/common): shared programme materials, governance, data documentation
- [`poc`](https://github.com/a-safe-bet-research/poc): the proof-of-concept evaluation that implemented the UK architecture
