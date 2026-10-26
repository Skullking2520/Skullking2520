# My Contributions · MoongCheap AI

[Back to profile](../README.md) · [Team repository](https://github.com/V-MoongCheap/MoongCheap-AI/tree/develop)

## Context & Role

The AI component of a team capstone in the kt cloud TECH UP program. As **AI team lead**, I coordinated delivery and cross-team communication. My technical work focused on the data foundation, facet taxonomy, and natural-language demand labeling (Part A).

| Area | My work |
| --- | --- |
| Team coordination | Coordinated schedules, collaboration with other teams, and project progress updates |
| Data foundation | Collected and preprocessed product data and consumer expressions; documented their intended use |
| Facets & taxonomy | Organized attribute, value, and alias candidates with evidence validation and human review |
| Demand labeling | Connected natural-language requirements to the taxonomy using a rule-first hybrid approach and validation |
| Integration | Connected Part A outputs to downstream processing and improved batch and database persistence paths |

Demand clustering, seller matching, and seller analytics were primarily owned by other AI teammates. My coordination responsibilities are distinct from my direct implementation work in Part A.

## Explore the Technical Work

1. [Document status and current baseline](https://github.com/V-MoongCheap/MoongCheap-AI/blob/develop/docs/DOCUMENT_STATUS.md)
2. [Data lineage](https://github.com/V-MoongCheap/MoongCheap-AI/blob/develop/docs/DATA_LINEAGE.md)
3. [Model and method selection](https://github.com/V-MoongCheap/MoongCheap-AI/blob/develop/docs/MODEL_SELECTION_FINAL_V1.md)
4. [Part A runtime validation policy](https://github.com/V-MoongCheap/MoongCheap-AI/blob/develop/docs/A_RUNTIME_VALIDATION_POLICY.md)
5. [Part A execution and deployment checks](https://github.com/V-MoongCheap/MoongCheap-AI/blob/develop/docs/A_LABELING_SMOKE_TEST.md)
6. [Part A–B integration contract](https://github.com/V-MoongCheap/MoongCheap-AI/blob/develop/docs/PART_B_V22_INTEGRATION.md)

## Design & Evaluation Scope

Model-generated candidates were checked against the taxonomy and source evidence, with human review kept as a separate step. Labeling applied clear rules first and used a model selectively for unresolved requests.

Historical comparisons, current persistence policies, and deployment checks are different records. Scores from earlier experiments are not presented as the accuracy of later code. The scope of submitted deliverables and remaining improvements follows the [current baseline documentation](https://github.com/V-MoongCheap/MoongCheap-AI/blob/develop/docs/DOCUMENT_STATUS.md).
