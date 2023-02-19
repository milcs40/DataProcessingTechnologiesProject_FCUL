# Data Processing Technologies Project @FCUL

Group project for the Data Processing Technologies course, with the aim of starting, planing, implementing and using a Data warehouse for analysis.
We proposed to create a Data Warehouse, using genomic data from the "1000 Genomes Project" and "NHGRI-EBI Catalog of published genome-wide associations studies" (or GWAS). The genomic data, containing information about genomic variants, will be enriched with datasets containing info about population-specific demographics, about SNPs (e.g. chromosomes, localization relative to genes) and diseases (using the Human Disease Ontology (DOID)).
HuGS-DW Human GWAS-SNP Cross-Reference Data Warehouse - Group project for the Data Processing Technologies course (Data Warehouse)

## Phase 1
Plan the DW, describing the original datasets and relevant information, facts tables, the granularity of the DW, possible dimensions, how many data marts are planned and the proposed star schema.
Includes the initial report ([`TPD_1920_Project_Phase1_Group20.pdf`](TPD_1920_Project_Phase1_Group20.pdf)) for the HuGS-DW.

## Phase 2
Make a Python notebook containing the following sections:
- Dimensions and facts tables of the DW
- Define an ETL workflow
- Do a critical assessment of the work

Includes the Jupyter Notebook ([`TPD_1920_Project_Phase2_Group20_V3.ipynb`](TPD_1920_Project_Phase2_Group20_V3.ipynb)) and the star schema ([`HuGs_Star_Schema.png`](HuGs_Star_Schema.png)) for the HuGS-DW.

## Phase 3
Make a Python notebook containing the following sections:
- OLAP queries
- Bottlenecks
- Do a critical assessment of the full project

Includes the Jupyter Notebook ([`TPD_1920_Project_Phase3_Group20.ipynb`](TPD_1920_Project_Phase3_Group20.ipynb)) for the HuGS-DW.
