 ![name-of-you-image](https://github.com/DeborahBambil/figs/blob/main/Fig1.png?raw=true)

# PmiR Select (Plant MiRNAs Selection)
Author: Deborah Bambil

This tool was built from a non-redundant dataset (threshold 80% similarity) of miRNAs collected in the 
miRBase of pre-miRNAs (hairpin V.22.1), to search for miRNAs by homology in organism genomes and transcripts as DNA, cDNA, mRNA in Fasta format. 

# Unzip the directory with the tool: PmiRSelect.rar

# Install Dependences Ubuntu

$ bash install.sh

If your operating system is different from Ubuntu, install the infernal tool, depending on your operating system

# Insert Organism FOR search of homologs miRNAs

#Insert in "PmiRSelect" directory named "organism.fa" (genome, cDNA, mRNA...) 

# miRNAs Prediction (START SEARCH)

$ bash run.sh

$ press "enter" when "Extract regions from a sequence alignment"

# OUTPUT

The tool's output provides both the miRNAs prediction:

> Predicted = all predicted sequences
> AlignmentBlast = Match between predicted and dataset  e-value 0.00001
> Curated = sequences predicted and compared with data plant miRNA families in the Blastn tool
> CuratedIdendical = Separate the repeated sequences 
> CuratedNonIdentical = Separate the repeated sequences 

>To repeat the experiment, use these empty folders, but never empty the cmbuild_calibrate directory, because there is the dataset

>Reference implemented Infernal tool: Nawrocki, E. P. (2014). Annotating functional RNAs in genomes using Infernal. In RNA sequence, structure, and function: computational and bioinformatic methods (pp. 163-197). Humana Press, Totowa, NJ.
