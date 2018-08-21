---
title: "Interoperable"
teaching: 0
exercises: 0
questions:
- "Key question"
objectives:
- "First objective."
keypoints:
- "First key point."
---



For scientists and repositories
provide machine-readable (meta)data with a well-established formalism 
structured, using discipline-established vocabularies / ontologies / thesauri (RDF extensible knowledge representation model, OWL, JSON LD, schema.org)
support referencing metadata fields between datasets via a  schema (relatedIdentifer, relationType)
offer (meta)data ingest from relevant sources (Document Information Dictionary or Extensible Metadata Platform from PDF)
provide as precise & complete metadata as possible
look for metrics to evaluate the FAIRness of a controlled vocabulary / ontology / thesaurus 
often do not (yet) exist
assist in their development
clearly identify relationships between datasets in the metadata (e.g. “is new version of”, “is supplement to”, “relates to”, etc.)
request support regarding these tasks from the repositories in your field of study
for software: follow established code style guides (thanks to @npch!)

Vision: Research will move from document- to knowledge-based information flows
semantic descriptions of research data & their structures
aggregation, development & teaching of subject-specific vocabularies, ontologies & knowledge graphs
several TIB groups are working towards this
Data Science and Digital Libraries => (research) knowledge graph(s)
Scientific Data Management
Visual Analytics to expose information within videos as keywords => av.tib.eu
Scientific Knowledge Engineering => ontologies

Example:
→ Automatic ORCID profile update when DOI is minted
DataCite – CrossRef – ORCID
  collaboration
→ PID of choice for RDM: Here: The Digital Object Identifier (DOI)

Detour: Replication / Reproducibility Crisis
doi.org/10.1073/pnas.1708272114
doi.org/10.1371/journal.pbio.1002165
doi.org/10.12688/f1000research.11334.1 
Examples of science failing due to software errors/bugs: 
figshare.com/authors/Neil_Chue_Hong/96503 


“[...] around 70% of research relies on software [...] if almost a half of that software is untested, this is a huge risk to the reliability of research results.”
Results from a US survey about Research Software Engineers
URSSI.us/blog/2018/06/21/results-from-a-us-survey-about-research-software-engineers (Daniel S. Katz, Sandra Gesing, Olivier Philippe, and Simon Hettrick)
Olivier Philippe, Martin Hammitzsch, Stephan Janosch, Anelda van der Walt, Ben van Werkhoven, Simon Hettrick, Daniel S. Katz, Katrin Leinweber, Sandra Gesing, Stephan Druskat. 2018. doi.org/10.5281/zenodo.1194669 

Code style guides & formatters (thanks to Neil Chu Hong)
faster than manual/menial formatting
code looks the same, regardless of author
can be automated enforced to keep diffs focussed
PyPI.org/project/pycodestyle, /black, etc.
ROpenSci packaging guide
style.tidyverse.org
Google.GitHub.io/styleguide 


If others can use your code, convey the meaning of updates with SemVer.org (CC BY 3.0)
“version number[ changes] convey meaning about the underlying code” (Tom Preston-Werner)


Exercise
Python & R Carpentries lessons


Linked data example
Triples - RDF - SPARQL
Wikidata exercise

Standards: https://fairsharing.org/standards/
schema.org: http://schema.org/

ISA framework: 'Investigation' (the project context), 'Study' (a unit of research) and 'Assay' (analytical measurement) - https://isa-tools.github.io/

Example of schema.org: rOpenSci/codemetar

Modularity
http://bioschemas.org 

codemeta croswalks to other standards
https://codemeta.github.io/crosswalk/

DCAT
https://www.w3.org/TR/vocab-dcat/

Using community accepted code style guidelines such as PEP 8 for Python (PEP 8 itself is FAIR)

Scholix - related indentifiers - Zenodo example linking data/software to papers 
https://dliservice.research-infrastructures.eu/#/
https://authorcarpentry.github.io/dois-citation-data/01-register-doi.html

Should vocabularies from reusable episode be moved here?