# Genetic and geographical delineation of zoonotic vector borne helminths of canids
Several zoonotic vector-borne helminths (VBHs) infesting canids cause serious veterinary and medical diseases worldwide. Increasing the knowledge about their genetic structures is pivotal to identify them and therefore to settle effective surveillance and control measures. To overcome the limitation due to the heterogeneity of large DNA sequence datasets used for their genetic characterization, we provide here a pipline for phylogenetic analysis on large sequence datasets (i.e., all available cox1 and 12S  from GenBank at January 2022) from public database.

# Key input and output files used in the present study

Three folders are provided for the 12S, cox1 and MLST phylogenitic analysis. Each of them containing the following:

# Files used to generate the ML phylogeny and phylogenitic placement

> REFMSA--12S.fasta: Multi-sequence alignement on selected reference sequences

> Query--12S.fasta: Multi-sequence alignement on all query sequences available from GenBank at January 2022.

> TREE features.txt: iqtree output file

> epa_result--cox1.jplace: EPA-ng output file for phylogenitic placement of query sequences.

[![Conda install](https://anaconda.org/bioconda/epa-ng/badges/installer/conda.svg)](https://anaconda.org/bioconda/epa-ng)
[![Conda install](https://anaconda.org/bioconda/epa-ng/badges/downloads.svg)](https://anaconda.org/bioconda/epa-ng)
[![ubuntu CI status](https://github.com/Pbdas/epa-ng/workflows/build&test_ubuntu/badge.svg)](https://github.com/Pbdas/epa-ng/actions)
[![macOS CI status](https://github.com/Pbdas/epa-ng/workflows/build&test_macos/badge.svg)](https://github.com/Pbdas/epa-ng/actions)
[![Softwipe Score](https://img.shields.io/badge/softwipe-e8.0-blue)](https://github.com/adrianzap/softwipe/wiki/Code-Quality-Benchmark)
[![Gitter chat](https://badges.gitter.im/Pbdas/epa-ng.png)](https://gitter.im/epa-ng/Lobby)

# Annotation files used to annotate the tree within iTOL software

> Labels.txt: Sequence labels 

> Species delimitation.txt: Result of species deliitations algorithms

> alignement.txt: alignement of informative sites

> epidemio_multibar.txt: descreptive statistics showing the distribution of sequences according to the isolation source


# Jplace file used in the paper are available from the following links:

> cox1 tree: https://itol.embl.de/tree/1095222034364991637522955 

> 12S tree: https://itol.embl.de/tree/1095222034318181637538254 

> MLST tree: https://itol.embl.de/tree/109522205480771637547090


# Citation
If you use the above data, please cite the following paper:

Younes Laidoudi, Samia Bedjaoui, Maria Stefania Latrofa, Angela Fanelli, Filipe Dantas-Torres, Domenico Otranto. Genetic and geographical delineation of zoonotic vector-borne helminths of canids. Scientific Repport Journal


