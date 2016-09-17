# Enrich2-Example

This repository contains an example dataset for the [Enrich2](https://github.com/FowlerLab/Enrich2) software package.

The dataset is a small subset of a deep mutational scan of BRCA1 testing for E3 ubiquitin ligase activity ([Starita *et al.* 2015](http://dx.doi.org/10.1534/genetics.115.175802)). Two replicates each with three time points are included. The FASTQ files contain barcode sequences mapping to single amino acid variants and synonymous variants from the first 30 residues of the mutagenized regions, as well as wild type.

[Enrich2](https://github.com/FowlerLab/Enrich2) is required for analysis. The expected run time is approximately 5 minutes.

To perform the analysis:

1. [Download this repository](https://github.com/FowlerLab/Enrich2-Example/archive/master.zip) and unzip it to wherever you like.
2. Using the terminal, navigate to your new "Enrich2-Example-master" directory. (This step is required for the example because its configuration file contains relative path names.)
3. Run Enrich2:
    * To use the command line mode, type: ``enrich_cmd BRCA1_example.json WLS wt``
    * To use the graphical user interface, type: ``enrich_gui`` and open "BRCA1_example.json" using the File menu. Once the configuration has loaded, click the "Run Analysis" button.
4. Explore the "Enrich2-Example-master/Results/plots" directory to see visualizations of the dataset.

For more information, please refer to the [Enrich2 manuscript](http://biorxiv.org/) and [Enrich2 documentation](https://readthedocs.org) or contact [Alan F Rubin](mailto:alan.rubin@wehi.edu.au).
