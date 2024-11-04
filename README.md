# Welcome! 

This repository is a showcase of representative samples of my work in R to share as examples of my R scripting and data analysis skills during the graduate school application process.

Please note that any unpublished data, including raw data and labels, has been obscured and/or edited to protect our group's unpublished findings. I've done my best to make it clear when this is the case. Any documents with nonsense or generic labels have been edited and do not represent real-world data. For that reason, **please do not consider any data in this repository, regardless of how it is labeled, to be reflective of any real-world biology.** This is just a display case for the code itself!

## Guide to this repository

**ELISA** is a generic example of code used to process raw data from a competitive ELISA assay.

**enzyme_activity_assay** is a generic example of code used to process raw absorbance data over time from a colorimetric enzyme activity assay into a plot. 

**gel_contraction** is a generic example of code used to process collagen gel contraction measurements into a plot showing contractive response to different stimuli.

**IMR90_cellcount_to_protein** is a quick tool I made to easily convert a user-input number of IMR-90 cells and lysis buffer volume into an estimation of the total protein mass contained in those cells. This was used in an assay in which the assay's lysis buffer was incompatible with any accessible total protein estimation assay.

**proteinCHKr** is a tool to calculate the percent of an annotated protein's total amino acid content which is either cysteine, histidine, or lysine. The user can input the gene symbols, ENSGs, or ENSTs of the genes of interest. The proteinCHKr sends a query to BioMart and calculates and returns the percent C/H/K content and an indication of whether the gene of interest is within two standard deviations of the population mean. I use this as a crude screening tool to support early exploration experiments with 4-hydroxynonenal (4-HNE). 4-HNE forms adducts with C, H, and K, so it's helpful to know if a potential target protein has an unusually high or low content of these amino acids.

**qPCR** is a generic example of code which processes qRT-PCR raw data into plots of Cq and log fold change.

**RIP-seq** is the RIP-seq analysis I performed in the Mukherjee lab and presented at the 2021 RNA Society meeting.
