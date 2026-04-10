# Linear Representations of Hierarchical Concepts in Language Models

**Paper:** [Sakata et al., Linear Representations of Hierarchical Concepts in Language Models](https://arxiv.org/abs/2604.07886)

This repository releases the dataset used for analyzing hierarchical concept representations in language models.

## Status

This repository currently provides **dataset files only**.

- **Data:** released in this repository
- **Code:** not yet released
- **Paper:** see citation information below

Code for preprocessing, experiments, and analysis is being prepared and will be added in a future update.

## Overview

This dataset is designed for studying how hierarchical relations are represented in language models.

Examples of hierarchical relations include:

- `Osaka ⊂ Japan ⊂ Eastern Asia ⊂ Asia`
- `Lionel Messi ⊂ Soccer player ⊂ Athlete`
- `Google ⊂ Technology company ⊂ Company`
- `Dog ⊂ Carnivora ⊂ Mammal`
- `Explainable Artificial Intelligence ⊂ Artificial Intelligence ⊂ Computer Science`

The dataset covers multiple domains and organizes concepts into parent-child hierarchies.

## Repository Contents

A typical repository structure is as follows:

```text
.
├── README.md
├── DATA_LICENSE.md
└── hierarchical_data/
    ├── location/
    ├── person/
    ├── organization/
    ├── organism/
    └── researchTopic/
````

Depending on the final release format, file names and directory structure may change slightly.

## Limitations

* This dataset is assembled from multiple third-party and derived sources.
* Licensing and redistribution conditions may differ by source.
* Users should not assume that all dataset components are covered by a single permissive license.
* Some parts of the dataset may reflect source-specific conventions, filtering decisions, or hierarchy design choices.

## Data License and Reuse

This repository contains data derived from multiple sources.

Please read [`DATA_LICENSE.md`](./DATA_LICENSE.md) carefully before reusing, redistributing, or modifying the dataset.


## Citation

If you use this repository, please cite the associated paper.

```bibtex
@misc{sakata2026linearrepresentationshierarchicalconcepts,
      title={Linear Representations of Hierarchical Concepts in Language Models}, 
      author={Masaki Sakata and Benjamin Heinzerling and Takumi Ito and Sho Yokoi and Kentaro Inui},
      year={2026},
      eprint={2604.07886},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2604.07886}, 
}
```

Update this entry with the final publication venue and bibliographic information when available.


## Contact

For questions about the dataset, please contact:

* [sakata.masaki.s5@dc.tohoku.ac.jp](mailto:sakata.masaki.s5@dc.tohoku.ac.jp)
