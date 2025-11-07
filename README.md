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
| -------- | ---------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- | --------------------------------------------------------------- |
| **1**    | **What Is Applied Ontology?**<br>Disciplinary origins and philosophical foundations | Keet Ch. 1; Smith (2015)               | Install Protégé |
| **2**    | **Ontology vs. Conceptual Modeling**<br>Realism, universals, particulars, information artifacts.                             | Keet Ch. 2; Smith & Ceusters (2010)                                                               | Diagram: conceptual vs. ontological model of a simple domain.   |
| **3**    | **BFO and the Ontological Realist Framework**                                                                                | BFO 2.0 Spec; Smith (2018) *“BFO and Scientific Ontologies”*                                      | Model: create a small BFO-aligned domain ontology.              |
| **4**    | **Logic Foundations**<br>FOL, DL, OWL 2 syntax and semantics.                                                                | Keet Ch. 3 & 4; Beverley *“Logic for Ontologists” notes*                                          | Lab: express a BFO fragment in OWL; test with reasoner.         |
| **5**    | **Ontological Categories and Relations**<br>Dependent continuants, realizable entities, roles, qualities.                    | Keet Ch. 5; CCO documentation excerpts                                                            | Exercise: classify 15 terms under BFO hierarchy.                |
| **6**    | **Competency Questions and Ontology Design Patterns**                                                                        | Keet Ch. 6; Beverley (2025) *“Design Patterns for Systematic Disambiguation”*                     | Draft 5 CQs and a DOLCE/BFO design-pattern example.             |
| **7**    | **Ontology Reuse and Modularization**<br>Upper, core, domain, and application modules.                                       | Keet Ch. 7; Smith & Maly (2023) *“Ontology Modules and Interoperability”*                         | Create an import hierarchy using ROBOT.                         |
| **8**    | **Midterm Workshop: Building a Mini-Ontology**<br>From CQs to OWL.                                                           | Review prior chapters                                                                             | **Midterm:** 20-term ontology + reasoning demo.                 |
| **9**    | **Ontology Evaluation and Quality Assurance**<br>Consistency, competency coverage, and SHACL constraints.                    | Keet Ch. 8; Beverley (2024) *“Automated Ontology QC Pipelines”*                                   | Lab: run SHACL validation on a sample ontology.                 |
| **10**   | **Ontology and AI Integration**<br>Knowledge graphs, embeddings, and LLM alignment.                                          | Keet Ch. 9; Smith (2024) *“Ontologies and AI: Towards Explainable Systems”*                       | Experiment: create RDF graph + SPARQL queries.                  |
| **11**   | **Ontology Governance and Version Control**<br>Community workflows, GitHub, CI/CD for ontologies.                            | Keet Ch. 10; NCOR *Ontology Tradecraft* repo                                                      | Set up GitHub repo; configure ROBOT + GitHub Actions.           |
| **12**   | **Applied Ontology in Science and Industry**<br>Biomedicine, Defense, Manufacturing, Policy.                                 | Smith (2022) *“Ontology in Biomedicine”*; Beverley (2024) *“Ontologies in Intelligence Analysis”* | Case study: analyze ontology integration in your field.         |
| **13**   | **Ethics, Interoperability, and Open Science**<br>Licensing, data sharing, FAIR principles.                                  | Keet Ch. 11; Smith (2023) *“Ontology and Open Science”*                                           | Draft metadata + license for your ontology project.             |
| **14**   | **Student Project Consultations and Peer Review**                                                                            | No new readings                                                                                   | Present preliminary final projects; peer feedback.              |
| **15**   | **Final Project Presentations & Future of Applied Ontology**                                                                 | Beverley (2025) *“Systematic Disambiguation as a Methodology.”*                                   | Submit final ontology project + reflection paper.               |




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
