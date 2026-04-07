# Data License

## Important

This repository contains dataset files and metadata derived from multiple named sources.

These materials are not automatically covered by a single permissive license.
Reuse, redistribution, and modification may depend on the original source of each subset.

If you use any data from this repository, you are responsible for checking and following
the terms of the original source materials, as well as the repository-specific notes below.

## Scope of this file

This file applies to:

- dataset files under `hierarchical_data/`
- processed metadata distributed with this repository
- repository-authored generated labels, prompts, and lightweight metadata, where explicitly stated below

This file does not grant broader rights than those available from the original sources.

## Explicit source list

The dataset in this repository is constructed from the following sources:

1. Locations
   - Luke Duncalfe, *ISO-3166-Countries-with-Regional-Codes* (2024)
   - Wes Gurnee and Max Tegmark, *Language Models Represent Space and Time* (ICLR 2024)

2. Persons
   - candidate entities generated using GPT-5
   - filtered against Wikidata
   - references:
     - OpenAI, *GPT-5 System Card* (2025)
     - Denny Vrandečić and Markus Krötzsch, *Wikidata: A Free Collaborative Knowledgebase* (2014)

3. Organizations
   - candidate entities generated using GPT-5
   - filtered against Wikidata
   - references:
     - OpenAI, *GPT-5 System Card* (2025)
     - Denny Vrandečić and Markus Krötzsch, *Wikidata: A Free Collaborative Knowledgebase* (2014)

4. Organisms
   - Kiho Park, Yo Joong Choe, Yibo Jiang, and Victor Veitch,
     *The Geometry of Categorical and Hierarchical Concepts in Large Language Models* (ICLR 2025)

5. Research Topics
   - OpenAlex Topics
   - Justin Barrett, *OpenAlex Topic Classification v1 Model Artifacts and Training Data* (2024)

## Source-by-source notes

### 1. Locations

The location subset of this repository is derived from:

- Luke Duncalfe, *ISO-3166-Countries-with-Regional-Codes* (2024), which provides
  ISO 3166-1 country data with regional classification based on the United Nations geoscheme
- the geographic data used in Wes Gurnee and Max Tegmark,
  *Language Models Represent Space and Time* (ICLR 2024)

#### Repository processing
Repository processing for the location subset may include:

- hierarchy alignment
- filtering
- formatting

#### Redistribution guidance
This repository does not claim to relicense the underlying location source data.
If you redistribute location-derived files, you should follow the terms of the original
source materials and preserve any required attribution, notices, and source-specific obligations.

### 2. Persons

The person subset of this repository was created by:

- generating candidate entities using GPT-5
- filtering those candidates to retain only entries that exist in Wikidata

#### Repository processing
Repository processing for the person subset may include:

- candidate generation
- filtering against Wikidata
- formatting
- hierarchy assignment
- conversion into parent-child hierarchical examples

#### Redistribution guidance
This repository does not claim exclusive rights over the underlying source material
used for person entities. Rights in repository-authored curation, formatting, and generated
metadata are limited to the extent stated in this file and do not override any upstream terms.

### 3. Organizations

The organization subset of this repository was created by:

- generating candidate entities using GPT-5
- filtering those candidates to retain only entries that exist in Wikidata

#### Repository processing
Repository processing for the organization subset may include:

- candidate generation
- filtering against Wikidata
- formatting
- hierarchy assignment
- conversion into parent-child hierarchical examples

#### Redistribution guidance
This repository does not claim exclusive rights over the underlying source material
used for organization entities. Rights in repository-authored curation, formatting, and generated
metadata are limited to the extent stated in this file and do not override any upstream terms.

### 4. Organisms

The organism subset of this repository is derived from:

- Kiho Park, Yo Joong Choe, Yibo Jiang, and Victor Veitch,
  *The Geometry of Categorical and Hierarchical Concepts in Large Language Models* (ICLR 2025)

and is reorganized in this repository according to a Linnaean-style taxonomic hierarchy.

#### Repository processing
Repository processing for the organism subset may include:

- reorganization into Linnaean hierarchy levels
- filtering
- formatting
- conversion into parent-child hierarchical examples

#### Redistribution guidance
This repository does not claim to relicense the underlying organism source data.

Reuse, redistribution, and modification of this subset may be subject to the
terms of the original source material. Users should consult the original source
and its applicable terms before redistributing organism-derived files.

### 5. Research Topics

The research topic subset of this repository is derived from:

- OpenAlex Topics
- Justin Barrett, *OpenAlex Topic Classification v1 Model Artifacts and Training Data* (2024)

#### Repository processing
Repository processing for the research topic subset may include:

- topic extraction
- hierarchy restructuring
- filtering
- formatting
- conversion into parent-child hierarchical examples

#### Redistribution guidance
This repository does not claim to relicense the underlying OpenAlex source data
beyond the rights, if any, granted by the original source.
If you reuse this subset, keep a notice that it is derived from OpenAlex Topics.

## Repository-authored generated content

Some files or fields in this repository may contain repository-authored generated content,
such as:

- candidate labels
- prompt templates
- synthetic helper metadata
- lightweight textual descriptions
- small manually curated mapping files

Unless otherwise noted in a specific file, such repository-authored generated content
is released under:

Creative Commons Attribution 4.0 International (CC BY 4.0)

This applies only to repository-authored generated content and does not override
restrictions or obligations attached to upstream third-party data.

## What users may generally do

Subject to the source-specific notes above, users may generally:

- use the dataset for research
- inspect and analyze the included files
- reuse repository-authored generated metadata under the terms stated above
- create their own derived files, provided they comply with upstream source terms

## What users should not assume

Users should not assume that:

- all files in `hierarchical_data/` are available under MIT
- all files in `hierarchical_data/` are available under CC BY 4.0
- all files in `hierarchical_data/` are freely redistributable without source review
- repository formatting or curation automatically removes upstream obligations

## Attribution

If you use this repository, please provide:

1. citation to the associated paper
2. attribution to the original upstream data sources where appropriate
3. a note that this repository contains mixed-origin data with source-specific conditions

## No warranty

This dataset is provided as is, without warranty of any kind, to the extent permitted by law.

The authors and maintainers make no representation that all files are error-free,
complete, authoritative, or suitable for any particular purpose.

## Contact

For questions about dataset reuse, please contact:

- sakata.masaki.s5@dc.tohoku.ac.jp