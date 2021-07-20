# Tree-Visualization


Order to create an anaconda environment and install the correct packages.

1. conda create -n treeEnv python=3.6
2. conda activate treeEnv
3. conda install -c etetoolkit ete3
4. ete3 build check
5. conda install -c etetoolkit ete_toolchain
6. conda install -c bioconda pyvcf
7. conda install -c conda-forge argparse

Positional arguments must be provided in the following order: Filename where newick string is being stored, CSV file where cancerous genes are being stored, csv file containing the cell states for each cell, filename for the annotated vcf file (file provided by SnpEff)
