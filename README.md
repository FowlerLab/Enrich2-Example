# Enrich2-Example

This repository contains an example dataset for the [Enrich2](https://github.com/FowlerLab/Enrich2) software package.

The dataset is a small subset of a deep mutational scan of BRCA1 testing for E3 ubiquitin ligase activity ([Starita *et al.* 2015](http://dx.doi.org/10.1534/genetics.115.175802)). Two replicates each with three time points are included. The FASTQ files contain barcode sequences mapping to single amino acid variants and synonymous variants from the first 30 residues of the mutagenized regions, as well as wild type.

To perform the example analysis:

1. [Download Enrich2](https://github.com/FowlerLab/Enrich2/archive/master.zip) from the [Enrich2 GitHub repository](https://github.com/FowlerLab/Enrich2).
2. Install the Enrich2 software and its dependencies as described in the [Enrich2 documentation](https://readthedocs.org/). We recommend using [Anaconda](https://www.continuum.io/downloads) to manage dependencies.
3. [Download this repository](https://github.com/FowlerLab/Enrich2-Example/archive/master.zip) and unzip it to wherever you like.
4. Using the terminal, navigate to your new "Enrich2-Example-master" directory.
5. To analyze the example dataset:
    * If using the Enrich2 command line mode, type: ``enrich_cmd BRCA1_example.json WLS wt``
    * If using the Enrich2 graphical user interface, type: ``enrich_gui`` and open "BRCA1_example.json" using the File menu. After the configuration has loaded, click the "Run Analysis" button.
6. Explore the "Enrich2-Example-master/Results/plots" directory to see visualizations from the dataset.

For more information, please refer to the [Enrich2 manuscript](http://biorxiv.org/) or contact [Alan F Rubin](mailto:alan.rubin@wehi.edu.au).
