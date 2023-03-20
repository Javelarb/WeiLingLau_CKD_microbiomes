# WeiLingLau_CKD_microbiomes

This repository includes the R code for analysis of 16S data obtained from mice under a chronic kidney disease model.
16S taxonomic assignments were produced from Qiime2.

Additionally, there are the following files are included:
* Lau_microbiome_analysis.Rmd - R markdown document of analysis code.
* metadata.tsv - The metadata pertaining to each sample in tab separated format.
* taxonomy.tsv - Contains the taxonomic assignment of amplicon sequence variants ID's produced from Qiime2.
* Filtered_ASV_table.tsv - A count by samples matrix at the Amplicon Sequence Variant (ASV) level with chloroplasts and mitrochondria removed.
* Filtered_species_table.tsv - A count by samples matrix at the species level with chloroplasts and mitrochondria removed.
* Filtered_Genus_table.tsv - A count by samples matrix at the Genus level with chloroplasts and mitrochondria removed.
* Filtered_rarefied_4300_ASV_table.tsv - The same file as Filtered_ASV_table.tsv but rarfied to 4300 reads.
* Filtered_rarefied_1700_species_table.tsv - The same file as Filtered_species_table.tsv but rarfied to 1700 reads.
* Filtered_rarefied_3700_genus_table.tsv - The same file as Filtered_Genus_table.tsv but rarfied to 3700 reads.
* feature-table.biom - The raw ASV table produced from Qiime2.
