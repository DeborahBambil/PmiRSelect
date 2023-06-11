 ![name-of-you-image](https://github.com/DeborahBambil/figs/blob/main/Fig1.png?raw=true)

# PmiR-Select (Plant MiRNAs Selection)
Authors: Deborah Bambil, Lúcio Flávio de Alencar Figueiredo, Mirele Carolina Souza Ferreira da Costa

This tool was built from update criteria for pre-miRNAs of plants and non-redundant dataset of pre-miRNAs collected in the miRBase of pre-miRNAs (hairpin V.22.1), to search for pre-miRNAs by homology in organism genomes.

# Unzip the directory with the tool: PmiRSelect.rar

# Install Dependences Ubuntu

$ bash install.bin

If your operating system is different from Ubuntu, install the infernal tool, depending on your operating system

# Insert Organism FOR search of homologs miRNAs

#Insert in "PmiRSelect" directory named "genome.fa" (Genome)

# miRNAs Prediction (START SEARCH)

$ bash run.bin

$ press "enter" when "Extract regions from a sequence alignment"

# OUTPUT

The tool's output provides both the miRNAs prediction:

> PredictedCurated = all predicted sequences and all miRNAs sequences only file NT count

> PredictedCuratedIdendical = Separate the repeated sequences 

> PredictedCuratedNonIdentical = Separate the repeated sequences 

> AlignmentBlastHairpin = Match between predicted and Hairpin plants dataset e-value 0.00001

> AlignmentBlastMature = Match between predicted and Mature plants dataset e-value 0.00001

> To repeat the experiment, use these empty folders, but never empty the cmbuild_calibrate directory, because there is the dataset



OtherThresholdDatasets

Reference implemented:

> Infernal tool: Nawrocki, E. P. (2014). Annotating functional RNAs in genomes using Infernal. In RNA sequence, structure, and function: computational and bioinformatic methods (pp. 163-197). Humana Press, Totowa, NJ.

> Emboss tool: Rice P., Longden I. and Bleasby A. EMBOSS: The European Molecular Biology Open Software Suite. Trends in Genetics. 2000 16(6):276-277.

> Genome tool: Gremme, G., Steinbiss, S., and Kurtz, S. (2013). GenomeTools: a comprehensive software library for efficient processing of structured genome annotations. IEEE/ACM transactions on computational biology and bioinformatics, 10(3), 645-656.

> Blastn: Chen, Y., Ye, W., Zhang, Y., and Xu, Y. (2015). High speed BLASTN: an accelerated MegaBLAST search tool. Nucleic acids research, 43(16), 7762-7768.

>Bedtools: Quinlan, Aaron R., and Ira M. Hall. "The BEDTools manual." Genome.
