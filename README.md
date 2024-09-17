# CopyNumberDistribution
Datasets and code for copy number distribution research in prokaryotes.  See Distribution Patterns of rRNA Copy Number Repeats in Prokaryotic Genomes (Williamson, 2024) for more details.

Datasets:
1) operon_distribution_prokaryote_2023_master_1way.xlsx -> raw dataset that includes data on individual rRNA genome locations and distance calculations
2) M1.csv -> base dataset that includes calculated distribuiton variables for each accession
3) M1_gens.csv -> includes genome size for accessions found in M1
4) M4.csv -> includes clear taxonomy for accessions found in M1
5) GC_content_gene_number_finale_2024.csv -> includes GC content and gene numbers for accessions found in M1
6) Archaea_2023_CN_1plus_16S_rRNA_NORMRANGE.nwk -> phylogenetic tree of archaeal accessions
7) Bacteria_2023_CN_1plus_16S_rRNA_rarified_NORMRANGE.nwk -> phylogentic tree of subest of bacterial accessions

Code:
1) CN_Distribution_Part_1.html -> R Markdown File of the analysis
