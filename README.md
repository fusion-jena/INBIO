# INBIO Ontology

This repository is used to summarize and report the methodology and results of "INBIO: An Ontology for Argumentation in Invasion
Biology". This study will be submitted to  23rd International Conference on Knowledge Engineering and Knowledge Management (EKAW2022) (https://ekaw2022.inf.unibz.it/): Poster and Demo track.

In INAS project, we aim to develop an argumentation machine that supports the end users (especially young scientists) during the argumentation process in the invasion biology domain. To this end, 
we focus on a particular phase of scientific argumentation process, namely the development of claims (hypotheses). A core step to achieve this goal is the formal and semantic representation of claim statements (hypotheses). The \textit{INBIO} ontology is considered a first outcome. In this poster paper, we introduce the overview design and description of the new ontology

# Paper availability
The accepted version can be accesed vis the [publisher web site](if it get accepted)

# Repository folders
This repository includes almost the material related to the development of a core ontology for HoH. It includes the following:
* Original hypotheses; this foloder includes the source set of twelves hypotheses [Hypotheses_v0.doc](https://github.com/fusion-jena/HoH_Core_Ontology/blob/master/original%20hypotheses/Hypotheses_v0.docx) as well as a number of hand crafted trial to develop the ontology
* OntologyTerms; this folder includes the set of extracted terms from the input hypotheses along with the set of ontologies from [BioPortal](http://bioportal.bioontology.org/) containing these terms.

* The code folder has the [termSerach](https://github.com/fusionjena/HoH_Core_Ontology/tree/master/code/code%20python%20search%20terms) source code used to lookup which ontologies from BioPortal containing the set of terms as well as the [module extractor](https://github.com/fusion-jena/HoH_Core_Ontology/tree/master/code/ModuleExtractor)  used to extract a module from the the selected ontology 
* The preliminary outcome of the ontology deveoplemnt is stored in the [ontologHoH](https://github.com/fusion-jena/HoH_Core_Ontology/tree/master/ontologyHoH) folder.
# Usage

Acknowledgments: This work has been mostly funded by the Deutsche Forschungsgemeinschaft (DFG) as part of the CRC 1076 AquaDiva [http://www.aquadiva.uni-jena.de/]