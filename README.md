# Genetic and geographical delineation of zoonotic vector borne helminths of canids


**[1. Introduction](#Introduction)**

**[2. Data](#Key-input-and-output-files-used-in-the-present-study)**

**[3. Results](#Final-*.jplace-Files-are-Available-as-Pre-edited-Trees)**

**[4. Softwares](#Softwares)**

**[5. Citing this repository](#Citation)**



# Introduction
Several zoonotic vector-borne helminths (VBHs) infesting canids cause serious veterinary and medical diseases worldwide. Increasing the knowledge about their genetic structures is pivotal to identify them and therefore to settle effective surveillance and control measures. To overcome the limitation due to the heterogeneity of large DNA sequence datasets used for their genetic characterization, we provide here a pipline for phylogenetic analysis on large sequence datasets (i.e., all available cox1 and 12S  from GenBank at January 2022) from public database.

![Fifure 4](https://user-images.githubusercontent.com/68795566/189247008-58ca4161-7096-4a57-b566-ef7775304109.png)



# Key input/output files used in the present study

Three folders (i.e., 12S, cox1 and MLST) are provided. Each of them containing the following


## Files used to generate the ML phylogeny and phylogenitic placement

> REFMSA.fasta: Multi-sequence alignement on selected reference sequences

> Query.fasta: Multi-sequence alignement on all query sequences available from GenBank at January 2022

> TREE features.txt: iqtree output file

> epa_result.jplace: EPA-ng output. (phylogenitic placement of query sequences)




## Files used to annotate the tree

> Labels.txt: Species name and GanBank accession number

> Species delimitation.txt: Result of species clustering 

> alignement.txt: alignement of informative sites

> epidemio_multibar.txt: descreptive statistics showing the distribution of sequences according to the isolation source



# Final *.jplace Files are Available as Pre-edited Trees



![Figure 1](https://user-images.githubusercontent.com/68795566/189246815-40a89bcc-8da8-4148-8125-970c843f954b.JPEG)

> [Fig. 1: [cox1](https://itol.embl.de/tree/1095222034364991637522955)]



![Figure 2](https://user-images.githubusercontent.com/68795566/189246901-475c72de-339a-4eff-b3ad-63b35417ee8b.JPEG)

> [Fig. 2: [12S](https://itol.embl.de/tree/1095222034318181637538254)]

 

![Figure 3](https://user-images.githubusercontent.com/68795566/189246918-09121221-b43b-4e01-8ac3-c7d04b99972f.JPEG)

> [Fig. 3: [MLST](https://itol.embl.de/tree/109522205480771637547090)]

# Softwares

1. [Sequence Retrival: [MSA-Viewer](https://www.ncbi.nlm.nih.gov/projects/msaviewer/)]
2. [A-A-A Sequence Comparison: [TaxI2 tool](https://github.com/iTaxoTools/TaxI2.git)] 
3. [Reference Sequence Alignement: [MAFFT](https://github.com/GSLBiotech/mafft.git)]
4. [Sequence Concatenation: [SeaView](http://doua.prabi.fr/software/seaview)] 
5. [ML Phylogeny: [Iqtree2](https://github.com/iqtree/iqtree2.git)] 
6. [Query Sequence Alignement: [HMMER](https://github.com/EddyRivasLab/hmmer.git)] 
7. [Phylogenitic Placement: [EPA-ng](https://github.com/Pbdas/epa-ng.git)]
8. [Tree Editing: [iTOL-v5](https://github.com/iBiology/iTOL.git)]
9. [Chat: [Gitter](https://matrix.to/#/#Pipline:matrix.org)]


# Citation
If you use the above data, please cite the following paper:

[Laidoudi et al., 2022: [Genetic and geographical delineation of zoonotic vector-borne helminths of canids](https://doi.org/10.1038/s41598-022-10553-w)]

