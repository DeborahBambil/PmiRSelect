 ![name-of-you-image](https://github.com/DeborahBambil/figs/blob/main/logoa_selection-removebg-preview.png?raw=true)

# Selection Plant MiRNAs
Author: Deborah Bambil

This tool was built from a non-redundant dataset (threshold 80% similarity) of miRNAs collected in the 
miRBase of pre-miRNAs (hairpin), to search for miRNAs by homology in genomes, the tool's output 
provides both the identified miRNAs (output fasta and tabular), as the identified non-redundant miRNAs

#Unzip the directory with the tool: SelectPlantMiRNAs.rar

#INSTALL DEPENDENCES Ubuntu

$ bash install.sh

#If your operating system is different from Ubuntu, install the infernal tool, depending on your operating system

#DOWNLOAD GENOME 

#Insert in "SelectionPlantMiRNAs" directory named its genome: "genome"

#Search MIRNAS

$ bash run.sh

$ press "enter" when "Extract regions from a sequence alignment"

#OUTPUT

#"miRNAsIdentified" folder: Identified miRNAs will be in the, separated by miRNA family files

#"miRNAsIdentified_Tabular" folder: Identified miRNAs output Tabular, separated by miRNA family files

#"miRNAsIdentify_NonRedundant" folder: Select miRNAs Non Redundant threshold 80%, separated by miRNA family files

#"miRNAsIdentify_Redundant" folder: Select miRNAs Redundant, separated by miRNA family files

#"MSA" folder: multiple sequence alignment of identified miRNAs

#"MSA_FASTA" folder: multiple sequence alignment of identified miRNAs, in fast format

>To repeat the experiment, use these empty folders, but never empty the cmbuild_calibrate directory, because there is the dataset

