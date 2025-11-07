# Introduction to Applied Ontology
The content contained in this repository introduces the theory and practice of applied ontology - the systematic representation of reality for computational reasoning, data integration, and AI interoperability. Topics covered include modeling domains with widely-used formal ontologies - such as the Basic Formal Ontology and the Common Core Ontologies suite - and applying semantic technologies (OWL, RDF, SPARQL, SHACL). 

## Learning Outcomes

Using the material below, you should be able to:
- Explain the philosophical and logical foundations of applied ontology,
- Build, document, and validate ontologies using OWL and Protégé,
- Apply BFO and CCO principles to domain-specific modeling,
- Solicit and design competency questions,
- Evaluate ontology quality using reasoning, constraints, and validation tools.



| **Week** | **Topics**                                                                                                          | **Resources**                                                                          | **Assignment**                                       |
| -------- | ---------------------------------------------------------------------------------------------------------------------------- | ----------- | ---------------------- |
| **1**    | **What Is Applied Ontology?**                                          | Arp, et. al. Chapter 1               | **Project 1:** Environment Setup |
| **2**    | **Applied Ontology and its Discontents**                               | Keet, Chapter 1                      |    |
| **3**    | **Competency Questions and Engagement**                                | Beverley                             |    |
| **4**    | **Top-Down, Bottom-Up, Middle-Ins**                                    | Arp, Chapter 3                       | **Project 2:** Deliver Competency Questions |
| **5**    | **Basic Formal Ontology 1**                                            | Arp, Chapter 5, 6                    |    |
| **6**    | **Basic Formal Ontology 2**                                            | Arp, Chapter 6, 7                    |    |
| **7**    | **Common Core Ontologies**                                             | Jensen                               |  **Project 3:** BFO/CCO Design Patterns     |
| **8**    | **Midterm Workshop: Building a Mini-Ontology**                         | Review prior readings                |    |
| **9**    | **RDF, RDFs, and OWL**                                                 |                                      |    |
| **10**   | **Ontology and AI Integration**                    | Keet Ch. 9; Smith (2024) *“Ontologies and AI: Towards Explainable Systems”*  | Experiment: create RDF graph + SPARQL queries.           |
| **11**   | **Ontology Governance and Version Control**     | Keet Ch. 10; NCOR *Ontology Tradecraft* repo   | Set up GitHub repo; configure ROBOT + GitHub Actions.           |
| **12**   | **Applied Ontology in Science and Industry** | Smith (2022) *“Ontology in Biomedicine”* | Case study: analyze ontology integration in your field.         |
| **13**   | **Ethics, Interoperability, and Open Science** | Keet Ch. 11; Smith (2023) *“Ontology and Open Science”*    | Draft metadata + license for your ontology project.             |
| **14**   | **Student Project Consultations and Peer Review**             |         | Present preliminary final projects; peer feedback.              |
| **15**   | **Final Project Presentations & Future of Applied Ontology**  | Beverley (2025) *“Systematic Disambiguation as a Methodology.”*      | Submit final ontology project + reflection paper.               |




* **Week 1** Course structure, VS Code, GitHub, rdflib, Jupyter
  - [Lecture on Setting up Environments](https://www.youtube.com/watch?v=ia8dkizLzfY)
  - [Due: Project 1 - Environment Setup](projects/project-1/README.md)

* **Week 2** Competency questions, hub-and-spoke, reuse, design patterns
  - [Lecture on Modeling using Basic Formal Ontology](https://www.youtube.com/watch?v=eQzBrRKe68E)
  - [Lecture on Ontology Engineering Methodology](https://www.youtube.com/watch?v=eQzBrRKe68E)
  - [Challenging Modeling Exercises & Solutions](https://www.youtube.com/watch?v=rXEsc0dDdsA)

* **Week 3** RDF, RDFs, OWL, & Linked Data Best Practices
  - [Lecture on the Semantic Stack](https://www.youtube.com/watch?v=jQbXhtJhs4E&list=PLDpLIEgKNGbOVAAfiD_28PH18wcktXy3M&index=2)

* **Week 4** The Protocol Language SPARQL
  - [Lecture on SPARQL](https://youtu.be/8Dd2jmw6yzc?list=PLDpLIEgKNGbOVAAfiD_28PH18wcktXy3M&t=1917)
  - [ROBOT Tutorial - James Overton & Becky Jackson](https://ontodev.github.io/robot-tutorial/#/title-slide)
  - [Due: Project 2 - Modeling Bottlenecks](projects/project-2/README.md)

* **Week 5** OWL2 reasoning, reasoners (HermiT, ELK), ROBOT, Jupyter
  - [Lecture on OWL2 Reasoning](https://www.youtube.com/watch?v=5Ae5FNqk6ro&list=PLDpLIEgKNGbOVAAfiD_28PH18wcktXy3M&index=3)
  - [Zebra Logic](https://www.youtube.com/watch?v=cOtpB-moIRA)

* **Week 6** SHACL basics, node and property shapes, constraint definitions
  - [Lecture on SHACL Validation](https://www.youtube.com/watch?v=alVaKWmiqtU&list=PLDpLIEgKNGbOVAAfiD_28PH18wcktXy3M&index=9)
  - [Lecture on Ontology Mappings](https://youtu.be/4MPBavNBgnU)
  - [Due: Project 3 - Ontology Mappings](projects/project-3/README.md)

* **Week 7** Pillars of Ontology Engineering: interoperability and quality
  - [Lecture on Ontology Engineering Tradecraft](https://youtu.be/gPPKDdli-4Y)
  - [Late Night Debugging Session](https://youtu.be/TkwIPS-QJQQ)

* **Week 8** Fall break; making sure folks caught up on projects

* **Week 9** Midterm: Semantic Pipeline Part 1
  - [Lecture Semantic Pipelines 1](https://youtu.be/sScyvhhnKAY)

* **Week 10** Midterm: Semantic Pipeline Part 2
  - [Lecture Semantic Pipelines 2](https://youtu.be/9KI013aD-oY)
  - [Due: Project 4 - ETL + Validation Midterm](projects/project-4/README.md)

* **Week 11** Link prediction, classification, evaluation of ontology-based ML
  - [Lecture on ML and Ontologies]() 

* **Week 12** Embeddings and semantic similarity
  - [Lecture on Embeddings with MOWL]() 

* **Week 13** Prompting for ontology building, SPARQL generation
  - [Lecture on LLMs in Ontology Engineering 1]() 
  - [Due: Project 5 - ML + LLM Pipelines](projects/project-5/README.md)

* **Week 14** LLM risk analysis, evaluating logic and the boundaries of use
  - [Lecture on LLMs in Ontology Engineering 2]() 

* **Week 15** Student Presentations
  - [Student Presentation 1]()
  - [Student Presentation 2]()
  - [Student Presentation 3]()
  - [Student Presentation 4]()
  
* **Week 16** Student Presentations
  - [Student Presentation 5]()
  - [Student Presentation 6]()
  - [Student Presentation 7]()
  - [Student Presentation 8]()
  - [Due: Project 6 - Cradle-to-Grave Pipeline](projects/project-6/README.md)


## Meeting Time

In person 1-3:50 on Mondays. Zoom for attending remotely is here (https://buffalo.zoom.us/j/9795922981?pwd=RGVGSTNvQ3BDNjUvTERaU1hobXduUT09).

## Extra Content

  - [MOWL Tutorial](https://github.com/bio-ontology-research-group/MOWL)
  - [FAIR Cookbook – RDF Conversion](https://faircookbook.elixir-europe.org/content/recipes/interoperability/rdf-conversion.html)
  - [SHACL by Example](https://labra.github.io/SHACL/)

## Repository Content
This repository contains the following directories: 

* **presentations** - Slides for presentations given by participants in the course. 
* **documentation** - Directory where etiquette and collaboration guidance is provided.
* **projects** - Directory where course projects and supplementary material are described. 


This course trains students to build semantically interoperable systems using the full Semantic Web stack, automated reasoning, and ontology-based machine learning workflows. Each week blends theoretical grounding with hands-on practice. Final projects will demonstrate students’ ability to model, query, validate, and augment knowledge using formal ontologies and AI.
