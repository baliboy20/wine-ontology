# Competency questions

Competency questions are the questions the ontology must be able to answer. They set its scope and serve as its test cases. Aim for 15–25, written in plain English before you model anything.

Tips:

- Write real questions a sommelier, buyer, importer or wine student would ask.
- Mix simple lookups ("Which grapes…") with questions that need reasoning ("Which wines count as…").
- Each question should lead to a SPARQL query in `queries/`.

## Questions

| # | Question | Needs reasoning? | Query |
| --- | --- | --- | --- |
| CQ1 | Which grape varieties is this wine made from? | No | `queries/cq01.rq` |
| CQ2 | Which wines come from a given region, including its sub-regions? | Yes (transitive part-of) | `queries/cq02.rq` |
| CQ3 | Which wines are single-varietal? | Yes (cardinality) | `queries/cq03.rq` |
| CQ4 |  |  |  |
| CQ5 |  |  |  |
| CQ6 |  |  |  |
| CQ7 |  |  |  |
| CQ8 |  |  |  |
| CQ9 |  |  |  |
| CQ10 |  |  |  |
| CQ11 |  |  |  |
| CQ12 |  |  |  |
| CQ13 |  |  |  |
| CQ14 |  |  |  |
| CQ15 |  |  |  |

CQ1–CQ3 are examples to show the format. Keep them, change them or replace them.
