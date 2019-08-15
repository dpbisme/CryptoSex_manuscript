# Overview of this repo

> This repo houses all of the code and analysis conducted for the manuscript "Lifecycle Progression and Sexual Development of the Apicomplexan Parasite Cryptosporidium parvum". A link to the raw fastq file data hosted on GEO is provided [here](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE129267). The abstract for the manuscript is copied below:

## Abstract
The apicomplexan parasite *Cryptosporidium* is a leading global cause of severe diarrheal disease and an important contributor to early childhood mortality. Currently there are no fully effective treatments or vaccines available. Transmission of the disease occurs through ingestion of oocysts, through direct contact or contaminated water or food. Oocysts are meiotic spores and the product of parasite sex. *Cryptosporidium* has a single host lifecycle where both asexual and sexual processes unfold in the intestine of infected hosts. Here we use the new-found ability to genetically engineer *Cryptosporidium* to make life cycle progression and parasite sex tractable. We derive reporter strains to follow parasite development in culture and infected mice and define the genes that orchestrate sex and oocyst formation through mRNA sequencing of sorted cells. After two days, parasites in cell culture show pronounced sexualization, but productive fertilization does not occur and infection falters. In contrast in infected mice, male gametes successfully fertilize females, leading to meiotic division and sporulation. To rigorously test for fertilization, we devised a two-component genetic crossing assay employing a Cre recombinase activated reporter. Our findings suggest obligate developmental progression towards sex in *Cryptosporidium*, which has important implications for the treatment and prevention of the infection.

> The locations of the core components of this repo are outlined in the file system map below. In short, there are the following main directories:

 - /ANALYSIS/code - contains the Rmarkdown (.rmd) file the combines all code and outputs and was used to generate the supplementary code file included in the manuscript.  In addition, code for manuscript figures based on RNAseq data are included in this document.  Also contain the study design file that describes each sample.
 - /ANALYSIS/functionalEnrichmentAnalysis - includes text files used for running Gene Set Enrichment Analysis.
 - /ANALYSIS/images - includes individual images and adobe illustrator file for constructing figure 3 from the manuscript.  Also contains [DataGraph](http://www.visualdatatools.com/DataGraph/) file for making annotated enrichment plots.
 - /ANALYSIS/readmapping - includes Kallisto outputs and log files
 - /QA/fastqc - includes outputs from running [fastqc](https://www.bioinformatics.babraham.ac.uk/projects/fastqc/) on all raw fastq files.  
 - /QA/multiqc_report.html - [multiqc](https://multiqc.info/) html summary report that summarizes fastqc and kallisto results for each sample.

```
