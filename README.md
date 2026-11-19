# Wine Ontology

An OWL 2 ontology for the wine domain, covering wines, grape varieties, producers, regions, vintages and styles. It is built in Protégé and checked with a reasoner.

> Status: in progress (Project 1 of my ontology portfolio)

## Scope

**In scope:**

**Out of scope:**

**Intended users and uses:**

## Competency questions

The ontology must be able to answer the questions in [competency-questions.md](competency-questions.md). Each question has a matching SPARQL query in [`queries/`](queries/).

## How to use it

1. Install [Protégé Desktop](https://protege.stanford.edu/).
2. Open `ontology/wine.ttl`.
3. Run a reasoner (Reasoner → HermiT → Start reasoner) and check the inferred hierarchy.
4. Run the queries in `queries/` with Protégé's SPARQL tab or Apache Jena.

## Repository layout

| Path | Contents |
| --- | --- |
| `ontology/wine.ttl` | The ontology, in Turtle |
| `competency-questions.md` | What the ontology must answer |
| `examples/` | Example individuals (specific wines) |
| `queries/` | SPARQL queries, one per competency question |
| `docs/design-decisions.md` | Modelling choices and the reasons for them |

## Reused vocabularies

List any external ontologies or vocabularies reused here (for example schema.org, Dublin Core, FOAF) and what each is used for.

## License

To be decided (CC BY 4.0 is common for ontologies).
