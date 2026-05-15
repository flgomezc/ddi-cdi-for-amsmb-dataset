# DDI-CDI Metadata Model for the AMSMB HTR Dataset

> **Work in progress — first draft.** The complete repository will be published on BSC GitLab when the model is finished.

This repository shares the first draft of a [DDI-CDI 1.0](https://ddi-cdi.github.io/ddi-cdi_v1.0/) metadata model for the **AMSMB HTR Dataset** — 100 digitized medieval notarial charters on parchment (1208–1499), published by the Barcelona Supercomputing Center (BSC):

> Coll Ardanuy, M.; Cuadrada, C.; Sarobe, R. (2025). *Dataset for handwritten text recognition in medieval notarial charters written on parchment (1208–1499)*. BSC Dataverse. https://dataverse.bsc.es/citation?persistentId=perma:BSC/0VB0MC

## Files

| File | Description |
|---|---|
| `amsmb_ddi_cdi_model.jsonld` | DDI-CDI model — process provenance, agents, variable descriptions, controlled vocabularies |
| `amsmb_charters_instances.jsonld` | 100 `InstanceValue` nodes with archival metadata and links to dataset files |
| `amsmb_charters_summaries.jsonld` | 100 contemporary Catalan summaries (`dcterms:abstract`), one per charter |

The three files are linked by shared `@id` values and together form a complete machine-actionable description of the dataset.

## Status

- [x] Process model (11 steps, full provenance chain)
- [x] Agents (9 persons with ORCID, 4 organizations)
- [x] Variable descriptions (10 variables, full ConceptualVariable → RepresentedVariable → InstanceVariable cascade)
- [x] Controlled vocabularies (29 document types, material, split, archive)
- [ ] PermaID to DOI
- [ ] Ontological alignment of 29 document types to Getty AAT / CIDOC-CRM
- [ ] Per-parchment DDI-CDI files with PageXML qualitative data

## License
DDI-CDI Model: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) 
Dataset: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
