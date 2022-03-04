# Genetic and geographical delineation of zoonotic vector borne helminths of canids


1. **[Introduction](#Introduction)**
2. **[Data](#Key-input-and-output-files-used-in-the-present-study)**
3. **[Results](#Final-*.jplace-Files-are-Available-as-Pre-edited-Trees-in)**
5. **[Softwares](#Softwares)**
6. **[Citing this repository](#Citation)**



# Introduction
Several zoonotic vector-borne helminths (VBHs) infesting canids cause serious veterinary and medical diseases worldwide. Increasing the knowledge about their genetic structures is pivotal to identify them and therefore to settle effective surveillance and control measures. To overcome the limitation due to the heterogeneity of large DNA sequence datasets used for their genetic characterization, we provide here a pipline for phylogenetic analysis on large sequence datasets (i.e., all available cox1 and 12S  from GenBank at January 2022) from public database.




# Key input/output files used in the present study

Three folders (i.e., 12S, cox1 and MLST) are provided. Each of them containing the following:

## Files used to generate the ML phylogeny and phylogenitic placement

> REFMSA.fasta: Multi-sequence alignement on selected reference sequences

> Query.fasta: Multi-sequence alignement on all query sequences available from GenBank at January 2022.

> TREE features.txt: iqtree output file

> epa_result.jplace: EPA-ng output file for phylogenitic placement of query sequences.




## Annotation files used to annotate the tree within iTOL software

> Labels.txt: Sequence labels 

> Species delimitation.txt: Result of species deliitations algorithms

> alignement.txt: alignement of informative sites

> epidemio_multibar.txt: descreptive statistics showing the distribution of sequences according to the isolation source



# Final *.jplace Files are Available as Pre-edited Trees in

> cox1 tree: https://itol.embl.de/tree/1095222034364991637522955 

> 12S tree: https://itol.embl.de/tree/1095222034318181637538254 

> MLST tree: https://itol.embl.de/tree/109522205480771637547090

# Softwares

1. [Sequence Retrival: [MSA-Viewer](https://www.ncbi.nlm.nih.gov/projects/msaviewer/)]
2. [A-A-A Sequence Comparison: [TaxI2 tool](https://github.com/iTaxoTools/TaxI2.git)] 
3. [Reference Sequence Alignement: [MAFFT](https://github.com/GSLBiotech/mafft.git)] 
4. [ML Phylogeny: [Iqtree2](https://github.com/iqtree/iqtree2.git)] 
5. [Query Sequence Alignement: [HMMER](https://github.com/EddyRivasLab/hmmer.git)] 
6. [Phylogenitic placement: [EPA-ng](https://github.com/Pbdas/epa-ng.git)]
7. [Tree Editing: [iTOL](https://github.com/iBiology/iTOL.git)]

# Citation
If you use the above data, please cite the following paper:

Younes Laidoudi, Samia Bedjaoui, Maria Stefania Latrofa, Angela Fanelli, Filipe Dantas-Torres, Domenico Otranto. Genetic and geographical delineation of zoonotic vector-borne helminths of canids. Scientific Repport Journal


