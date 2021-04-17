# CRISPR_Asgard

This repository is divided in 4 directories: arCOGs, PSI-BLAST, neighborhood_analysis, Result analysis. Each directory contains a .ipynb script that executed the code for each stage of the project.

arCOGs: The CRISPR_arCOGs.ipynb script eliminated the arCOGs that were not annotated as CRISPR-related, leaving only the CRISPR-related arCOGs. The CRISPR arCOG profiles are located under the ali-ar14/ directory.

PSI-BLAST: The PSI-BLAST.ipynb script executes the PSI-BLAST search based on the arCOGs as queries and asgard_proteomes.fasta as database.

neighborhood_analysis: the hit_neighborhoods.ipynb script retrieves the region neighboring each hit.

Result analysis: The Result_analysis.ipynb analyzes results and generates plots and diagrams.

![alt text](Result analysis/CRISPR_systems.png?raw=true)
