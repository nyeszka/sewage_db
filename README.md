# sewage_db
A multi-layered dataset from sewage across five European cities in an SQL database.

## About the dataset

We present a comprehensive dataset originating from our longitudinal sewage surveillance in five European cities: Copenhagen, Rotterdam, Budapest, Rome and Bologna over 9-19 months with variable time frames between the cities (2019-2021). This includes the data from shotgun metagenomic sequencing and qPCR (for pathogens) done on 230 samples (qpcr.csv, qpcr_primers.csv), as well as Hi-C sequencing and analysis results for 24 samples (proximeta-csv).

The metadata (meta_location.csv) provided comprises GPS coordinates, the names of the sewage treatment plants, and, for some cities, temperature and pH measurements etc.

The dataset incorporates outputs of bioinformatic analyses of short-read metagenomic sequencing, including abundances of ARGs on gene and class level (resfinder_gene_abundance.csv, resfinder_class_abundance.csv), along with tables containing which gene belongs to which AMR class (resfinder_gene_class.csv) and phenotype (resfinder_gene_phenotype.csv). Abundances of different taxa obtained through reference-based classification of sequencing reads (genomic_phylum_abundance.csv, genomic_class_abundance.csv, genomic_order_abundance.csv, genomic_family_abundance.csv, genomic_genus_abundance.csv, genomic_species_abundance.csv) are also available. Metagenomic assemblies are presented in the form of binned contigs with basic information and potential source (binned_contigs.csv), abundances in each sample for each contig (numbases_bins_derepMAGs_allcities_with_repl.csv), and metagenome-assembled genomes (MAGs), accompanied by relevant quality assessments (mag_checkm2.csv) and annotations (gene_annotation.csv).


Link to the SQL interface: https://k8plex-veo.vo.elte.hu/notebook/report/ezc9v9-sqlinterface/ 
