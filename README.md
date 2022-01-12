# CRISPR_Asgard

This is a Bioinformatics Project carried out by me (Javier Marchena Hurtado) during my Master's in Bioinformatics in Copenhagen, 2021. The full project report is available in the pdf "CRISPR-Cas in Asgard Archaea.pdf". 

This repository is divided in 4 directories: arCOGs, PSI-BLAST, neighborhood_analysis, Result analysis. Each directory contains a .ipynb script that executed the code for each stage of the project.

arCOGs: The CRISPR_arCOGs.ipynb script eliminated the arCOGs that were not annotated as CRISPR-related, leaving only the CRISPR-related arCOGs. The CRISPR arCOG profiles are located under the ali-ar14/ directory.

PSI-BLAST: The PSI-BLAST.ipynb script executes the PSI-BLAST search based on the arCOGs as queries and asgard_proteomes.fasta as database.

neighborhood_analysis: the hit_neighborhoods.ipynb script retrieves the region neighboring each hit.

Result analysis: The Result_analysis.ipynb analyzes results and generates plots and diagrams.

![CRISPR_systems](https://user-images.githubusercontent.com/54844846/115114279-bb364300-9f8e-11eb-8643-d2c31543ee48.png)
