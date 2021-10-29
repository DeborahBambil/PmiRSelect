 ![name-of-you-image](https://github.com/DeborahBambil/figs/blob/main/Fig1.png?raw=true)

# PmiR Select (Plant MiRNAs Selection)
Author: Deborah Bambil

This tool was built from a non-redundant dataset (threshold 80% similarity) of miRNAs collected in the 
miRBase of pre-miRNAs (hairpin), to search for miRNAs by homology in organism genomes and transcripts as DNA, cDNA, mRNA etc in fasta format, the tool's output 
provides both the identified miRNAs (output fasta and tabular), as the identified non-redundant miRNAs.

Here, the 80% threshold database in fasta is also available. Corresponding to version 22.1 from miRBase.

> DatasetThreshold80Percent.fa

> Tool and Dataset updates will be made as by database file harpin miRBase updates

Start search miRNAs:

#Unzip the directory with the tool: SelectPlantMiRNAs.rar

# Install Dependences Ubuntu

$ bash install.sh

If your operating system is different from Ubuntu, install the infernal tool, depending on your operating system

# Download Organism

#Insert in "SelectionPlantMiRNAs" directory named its genome, cDNA, mRNA etc... as: "organism.fa"

# Search miRNAs

$ bash run.sh

$ press "enter" when "Extract regions from a sequence alignment"

# OUTPUT

"miRNAsIdentified" folder: Identified miRNAs will be in the, separated by miRNA family files

"miRNAsIdentified_Tabular" folder: Identified miRNAs output Tabular, separated by miRNA family files

"miRNAsIdentify_NonRedundant" folder: Select miRNAs Non Redundant threshold 80%, separated by miRNA family files

"miRNAsIdentify_Redundant" folder: Select miRNAs Redundant, separated by miRNA family files

"MSA" folder: multiple sequence alignment of identified miRNAs

"MSA_FASTA" folder: multiple sequence alignment of identified miRNAs, in fast format

>To repeat the experiment, use these empty folders, but never empty the cmbuild_calibrate directory, because there is the dataset

>Reference implemented Infernal tool: Nawrocki, E. P. (2014). Annotating functional RNAs in genomes using Infernal. In RNA sequence, structure, and function: computational and bioinformatic methods (pp. 163-197). Humana Press, Totowa, NJ.
