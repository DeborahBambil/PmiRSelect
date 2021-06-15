# Select Plan tMiRNAs
![name-of-you-image](https://github.com/DeborahBambil/figs/blob/main/logo2.png?raw=true)
Author: Deborah Bambil

This tool was built from a non-redundant dataset (threshold 80% similarity) of miRNAs collected in the 
miRBase of pre-miRNAs (hairpin), to search for miRNAs by homology in genomes, the tool's output 
provides both the identified miRNAs (output fasta and tabular), as the identified non-redundant miRNAs


#INSTALL DEPENDENCES Ubuntu

$ bash install.sh

#If your operating system is different from Ubuntu, install the infernal tool, depending on your operating system

#DOWNLOAD GENOME 

#Insert in "SelectionPlantMiRNAs" directory named its genome: "genome"

#Search MIRNAS

$ bash run.sh

$ press "enter" when "Extract regions from a sequence alignment"

#OUTPUT

#Identified miRNAs will be in the "miRNAsIdentified" folder, separated by miRNA family files

#Identified miRNAs output Tabular will be in the "miRNAsIdentified_Tabular" folder, separated by miRNA family files

#Select miRNAs Non Redundant threshold 80% "miRNAsIdentify_NonRedundant", separated by miRNA family files

#Select miRNAs Redundant "miRNAsIdentify_Redundant", separated by miRNA family files
