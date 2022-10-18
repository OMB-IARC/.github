## Welcome to the Github page of the Onco-Metabolomics Team at IARC-WHO

The Onco-Metabolomics Team (OMB) is part of the [Nutrition and Metabolism Branch](https://www.iarc.who.int/branches-nme/) (NME), at the [International Agency for Research on Cancer](https://www.iarc.who.int/) (IARC) as the cancer research branch of the World Health Organisation (WHO).


The OMB is a multidisciplinary team that fosters close collaboration between analytical chemists, epidemiologists, bioinformaticians, and statisticians to conceptualize and implement metabolic–nutrition–cancer epidemiology studies. OMB studies metabolic perturbations, nutritional and dietary factors, and the exposome in cancer development by implementing modern liquid chromatography–mass spectrometry (LC-MS)-based analytical techniques to measure and identify metabolites in various biospecimens and to study metabolite variations associated with cancer outcomes.
OMB also undertakes studies to identify novel biomarkers of dietary, lifestyle, and environmental exposures for cancer risk factors along with studies to explore the underlying metabolic mechanisms of cancer development. To enable this, OMB develops and implements new laboratory- and bioinformatics-based methodologies, emphasizing annotation and biological interpretation of the metabolome, metabolomic data management tools, and computational metabolomics methods.
Areas of major research interest are the identification of novel biomarkers of the gut bacterial exposome and diet, including exogenous and endogenous exposures (e.g. glycation products and dicarbonyl stress, tryptophan metabolism), as well as the exploration of the role of the gut–liver axis (e.g. functionality of the protective colonic mucosal barrier, microbiome metabolism, compositional changes and dysbiosis, and bile acid metabolism) in cancer development.
OMB collaborates closely with other teams in NME, with untargeted metabolomics groups worldwide, and with a large international network of cancer and metabolic epidemiology research groups.

You can find on this page some of the tools and code developped as part of the bioinformatics and computational activities in the OMB team.

Note: some of the tools and code are developed as part of the ANR and DFG funded [MetClassNet consortium](http://www.metclassnet.org/), some of the repositories forked here from the MetClassNet consortium are modified to fit the internal need at OMB but the source code and up to date versions are available on the [MetClassNet Github page](https://github.com/MetClassNet).


#######
### CanGraph - Knowledge graphs for cancer-associated metabolites
[CanGraph](https://omb-iarc.github.io/CanGraph/) is a Python program that allows you to extract information about a newly discovered or existing metabolite from the multiple databases: [Exposome Explorer](http://exposome-explorer.iarc.fr/) (a curated database of metabolites associated to exposures developped by IARC), [DrugBank](https://go.drugbank.com/) (a drug database, you need to apply for a paid commercial or an academic license to use it), [HMDB](https://hmdb.ca/metabolites) (Human Metabolome Database), [SMPDB](https://smpdb.ca/) (Small Molecule Pathway Database), WikiData. The database metabolites are unified by the MetaNetX and MeSH ontologies. 
Author: @[MarionMoseby](https://github.com/orgs/OMB-IARC/people/MarionMoseby)

########
### MetaboPipeline - Metabolomics data bioinformatics pipeline and data science notebooks

**MetaboPipeline_bioinfo** is an ensemble of scripts and pipeline tools to analyze metabolomics data from human cohort studies. 
The metabolomics data processing and annotation part is derived from the Nextflow pipeline [MetaboIgniter](https://nf-co.re/metaboigniter) used to process, analyze, and annotate raw LC-MS metabolomics data. 

**MetaboPipeline_notebooks** is an ensemble of notebooks to apply a "data science" approach to the metabolomics data outputs from the MetaboPipeline_bioinfo pipeline or from the vendor softwares (e.g., Agilent MassHunter). These notebooks allow a number of statistical and machine learning methods to be applied to analyze the metabolomics datasets, including metadata from the EPIC cohort studies.
Author: @[maxvincent24](https://github.com/maxvincent24)

########
### MetClassNet - Multilayers networks for metabolomics data annotation and interpretation
Tools and repositories related to the MetClassNet consortium and their application to human cancer cohort studies can be found in this repository (private and public repos). The original code is are available on the [MetClassNet Github page](https://github.com/MetClassNet).
**MetClassNetR** - R code to create and analyze networks from metabolomics data

**MetNet** - R package adapted for MetClassNet of the MetNet used to infer metabolic networks from untargeted high-resolution mass spectrometry data
Please visit the Bioconductor page of [MetNet](https://bioconductor.org/packages/release/bioc/html/MetNet.html) for further information.
This depency is necessary to run MetClassNetR R vignettes

**Neo4MetClassNet** - Neo4J graph database environment for MetClassNet tools

**gml2cypher** - Generate cypher commands to import a graph in a GML file into a Neo4J database

**MetClassNet_IARCdata** - repo contain code needed to work directly related to the MetClassNet tool development and its applications to IARC metabolomics data

**MCN-HumanNet** - Human Metabolic Network 


For any requests feel free to contact: amaraa@iarc.who.int


![](https://www.iarc.who.int/config/logo.svg) 
