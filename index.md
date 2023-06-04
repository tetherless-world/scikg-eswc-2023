---
layout: default
---

Data from scientific studies are published in datasets, typically accompanied by data dictionaries and codebooks to support data understanding. The data acquisition methods may also be described in additional documentation to support reproducibility. To conduct rigorous analysis, data users need to leverage this documentation to correctly interpret the data. While this process can be burdensome for new data users, it is also prone to errors even for seasoned users. A computational formal model of the knowledge that was used to create the study can facilitate better understanding and thus improved usage of the study data. Knowledge graphs can be used effectively to capture this study knowledge.

This tutorial aims to introduce participants to the basics of knowledge graph construction using data, data dictionaries, and codebooks from scientific studies. It will use the Center for Disease Control and Prevention's (CDC) National Health and Nutrition Examination Surveys (NHANES) data as a testbed and introduce standardized terminology, novel and established techniques, and resources such as scientific/biomedical ontologies, semantic data dictionaries, and knowledge graph frameworks in both lecture and practical sessions. By the end of the tutorial, participants will have created a small knowledge graph that can be accessed to retrieve study knowledge and data.

# Contents

- [Tutorial overview](#tutorial-overview)
  * [Section 1: Studies, Data, and Documentation](#section-1--studies--data--and-documentation)
  * [Section 2: Scientific and Biomedical Ontologies](#section-2--scientific-and-biomedical-ontologies)
  * [Section 3: Semantic Data Dictionaries](#section-3--semantic-data-dictionaries)
  * [Section 4: Knowledge Graph Frameworks](#section-4--knowledge-graph-frameworks)
- [Program](#program)
- [Material](#material)
- [Organizers](#organizers)
- [Acknowledgements](#acknowledgements)

# Tutorial overview

The SciKG tutorial will be divided into four sections. It will start with an overview of how scientific study data is usually acquired, organized and published, and the current challenges (and opportunities for semantic web) involving the use of this data. Next, we introduce methods for scientific data annotation and terminology reuse. Following, we will give an overview of the state-of-the-art scientific and biomedical ontologies and provide real-world examples of their successful adoption. Finally, the tutorial will introduce knowledge graph frameworks and demonstrate how they can be used to bootstrap and manage scientific KGs.

## Section 1: Studies, Data, and Documentation

* Scientific studies and their data acquisition activities
* Scientific data organization
* Scientific data publishing
* Documentation
    * Data dictionaries
    * Codebooks
    * Methods
* National Health and Nutrition Examination Surveys (NHANES)
    * Semantics of NHANES data

## Section 2: Scientific and Biomedical Ontologies

* The role of standardized terminology in science
* Semanticscience Integrated Ontology (SIO)
* Human-Aware Science Ontology (HAScO)
* Disease Ontology (DOID)
* Chemical Elements of Biological Interest (ChEBI)

## Section 3: Semantic Data Dictionaries

* Introduction to Semantic Data Dictionaries (SDDs)
    * Structure
    * Examples
* Practical section with NHANES datasets

## Section 4: Knowledge Graph Frameworks

* The Human-Aware Data Acquisition Framework (HADatAc)
* Whyis
* Using SDDs to bootstrap Knowledge graphs
* Using SPARQL to retrieve study data

# Program

| Time (EEST/UTC+3) | Event                                        |
| ----------------- | -------------------------------------------- |
| 9:00 - 10:30      | Part 1: Studies, Data, and Documentation     |
| 10:30 - 11:00     | Break                                        |
| 11:00 - 12:30     | Part 2: Scientific and Biomedical Ontologies |
| 12:30 - 14:00     | Lunch                                        |
| 14:00 - 15:30     | Part 3: Semantic Data Dictionaries           |
| 15:30 - 16:00     | Break                                        |
| 16:00 - 18:00     | Part 4: Knowledge Graph Frameworks           |

# Material

| Slides                                                                                  |
| --------------------------------------------------------------------------------------- |
| [Intro](slides/SciKG_Tutorial_ESWC-23_Intro.pdf)                                        |
| [Part 1: Studies, Data, and Documentation](slides/SciKG_Tutorial_ESWC-23_Part1.pdf)     |
| [Part 2: Scientific and Biomedical Ontologies](slides/SciKG_Tutorial_ESWC-23_Part2.pdf)<br>[HAScO Ontology](slides/SciKG_Tutorial_ESWC-23_Part2_HAScO.pdf) |
| Part 3: Semantic Data Dictionaries                                                  |
| Part 4: Knowledge Graph Frameworks                                                  |

# Organizers

### Dr. Henrique Santos, *Rensselaer Polytechnic Institute*
Dr. Santos is the Director of Semantic Applications in the Tetherless World Constellation at Rensselaer Polytechnic Institute. His research focuses on knowledge representation, domain-specific reasoning, and explainable artificial intelligence. Dr. Santos has lectured undergraduate courses in Artificial Intelligence and Algorithms and has presented several works at renowned conferences, including the International Semantic Web Conference, and the Extended Semantic Web Conference.

### Dr. Paulo Pinheiro, *Parcela Semântica*
Dr. Pinheiro is a seasoned data scientist and software engineer managing projects at the frontier between artificial intelligence and databases. He has twenty years of hands-on experience with data and knowledge management software development, including in-depth knowledge of data standards, data policies, and information assurance. Dr. Pinheiro has extensive teaching experience including past professorship appointments.

### Dr. Jamie P. McCusker, *Rensselaer Polytechnic Institute*
Dr. McCusker works on Biomedical Semantics. Her current interests are data and provenance interoperability in life sciences. She has worked as a software developer for 11 years in bioinformatics, high-performance computing, data mining, natural language processing, and supply chain auditing. Dr. McCusker has taught numerous courses and tutorials on knowledge graphs, ontology engineering, data science, and semantic science.

### Dr. James Masters, *Icahn School of Medicine at Mount Sinai*
Dr. Masters is the Director of Research Data Services at the Icahn School of Medicine at Mount Sinai and manages the Harmonized Data Repository of the Human Health Analysis Resource Data Center. The Harmonized Data Repository is a knowledge graph built using the HADatAc platform, biomedical ontologies, and the methodologies to be discussed in this tutorial. Before joining Icahn School of Medicine, Dr. Masters developed and run several training courses on Semantic Web applications for users and other stakeholders in the financial services industry.

### Sabbir M. Rashid, *Rensselaer Polytechnic Institute*
Rashid is a Ph.D. candidate at Rensselaer Polytechnic Institute on research related to data annotation and harmonization, ontology engineering, knowledge representation, and various forms of reasoning. His graduate studies have involved research related to the semantic annotation and transformation of data using Semantic Data Dictionaries, applied to deductive and abductive inference techniques over linked health data, such as in the context of chronic diseases like diabetes.

### Prof. Deborah L. McGuinness, *Rensselaer Polytechnic Institute*
Prof. McGuinness is the Tetherless World Senior Constellation Chair and Professor of Computer and Cognitive Science. Prof. McGuinness is also widely known for her leading role in the development of the W3C Recommended Web Ontology Language (OWL), her work on earlier description logic languages and environments, including interdisciplinary semantic data resources, provenance languages, and environments, such as InferenceWeb, PML, and PROV.

# Acknowledgements

This tutorial is partially funded by the following projects:
* NIEHS-funded [Children’s Health Exposure Analysis Resource (CHEAR)](https://reporter.nih.gov/project-details/9062054), project number **1U2CES026555-01**
* NIEHS-funded [Human Health Exposure Analysis Resource (HHEAR)](https://reporter.nih.gov/search/omw727mrOEiYVmxYWQ2GnQ/project-details/10424419), project number **5U2CES026555-05**
* IBM-funded [Health Empowerment by Analytics, Learning, and Semantics (HEALS)](https://idea.rpi.edu/research/projects/heals) through the [AI Horizons Network](https://research.ibm.com/collaborate/horizons-network/) program
* DARPA-funded [Machine Common Sense](https://www.darpa.mil/program/machine-common-sense), grant number **N660011924033**
* NSF-funded [Nanomine](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1640840&HistoricalAwards=false), award number **1640840**
* NSF-funded [MaterialsMine](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1835648&HistoricalAwards=false), award number **1835648**
