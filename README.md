# getphylo_benchmarking
A repository for data and tools used to benchmark getphylo.

# Contents
This repository contains the following directories and subdirectories:

## benchmarking
This directory contains information for the performance benchmarking of getphylo.
### accessions
This directory contains text files containing the NBCI accessions for the *Streptomyces* genomes that comprise each of the six benchmarking datasets.
### trees
This directory contains the trees produced during benchmarking by getphylo, autoMLST and gtdb-tk.

## case_studies
This directory contains data from four case studies used to demonstrate the utility of getphylo.
### case_study_1
This directory contains data relevent to case study one - a bacterial phylogeny. It includes the input genbank files and the output alignment, partition and tree.
### case_study_2
This directory contains data relevent to case study two - a phylogeny of a gene clusters related to [resorculin biosynthesis](https://pubmed.ncbi.nlm.nih.gov/36876905/). It includes a list of the input MiBiG accessions and the resorculin BGC as a genbank file. It also includes the output alignment, partition and tree.
### case_study_3
This directory contains data relevent to case study two - a phylogeny of a primates. It contains a list of NCBI accessions used as input and the output alignment, partition and tree.
### case_study_4
This directory contains data relevent to case study two - a phylogeny of a Eurotiomycete fungi. It contains a list of strains used as input and the output alignment, partition and tree.

## scripts
This directory contains three scripts used during benchmark:
- alignment_information.py - prints information, such as the number of informative sites, about the supplied alignment
- gtdbtk_unrooted.bash - runs the first two modules of gtdb-tk de novo workflow to produce an unrooted tree
- treesum.py - prints information, such as average branch support, about the supplied newick tree

# Citation
Coming soon...

# TODO
1. add primate partition
2. add gtdb-tk unrooted script

