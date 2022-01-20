# Build a bridge between transcriptome and lipidome in Arabidopsis

**Author: Yu Song** <br/>
**Semester: Spring 2020** <br/>
**Project area: Biochemistry** <br/>
**Updated date: 5/4/2020**


# Introduction
## Objective
Write a python function to automate the calculation of correlation value from transcriptome data and phenotypic data (climate data and lipid data) in Arabidopsis. Visualize the results using linear regression curve and heatmap, save and export the outputs in csv. file.

## Inputs
The inputs are two separate csv. files with many columns – accession ID, CS number, accession name, gene ID, lipid ID, RNAseq value, and phenotype value.<br/>
The first csv. file is "RNAseq value_climate value.csv" with accession information, gene expression data and climate data of origin.<br/>
The second csv. file is "RNAseq value_lipid value.csv" with accession information, gene expression data and lipid values.

## Outcomes
The output is a regression curve between latitude and climate data as well as some statistical parameters.<br/>
The output is a heatmap with gene ID, phenotype, and coorelation level.<br/>
The output file is a .csv file with three columns: gene ID, phenotype, and correlation level.
    
## Rationale
*Arabidopsis thaliana* is an excellent model to study genetic, cellular, and molecular biology of plants because of its small genome size, well-sequenced genomes. Genome wide association study (GWAS) is a powerful tool to dissect the genetic architecture of complex traits in plant. Our previous GWAS analysis based on lipidomic data of 320 natural Arabidopsis accessions revealed some candidate genes along with causative SNPs for lipid metabolism. Some SNPs are located in intron or intergenic region which may influence the gene expression level. We know there are some associations between transcriptome variation and lipid variation in natural Arabidopsis accessions. Kawakatsu et al. analyzed the transcriptomes from 727 accessions grown at 22°C. Exposito-Alonso et al. collected climate variables of origin for 517 natural accession which are potential indicator for cold tolerance of Arabidopsis. We hypothesized that with high correlation value calculated from RNAseq values of specific gene and lipid values, it is possible the gene is responsible for lipid metabolism. Also, if we find strong correlation between RNAseq values and climate values, it is possible the gene is related to cold tolerance.

## Sketch

<img src="sketch.png" alt="sketch_image" width="2000"/>


## References
1. Kawakatsu, Taiji, et al. "Epigenomic diversity in a global collection of Arabidopsis thaliana accessions." *Cell* 166.2 (2016): 492-505.<br/>
2. Exposito-Alonso, Moises, et al. "Natural selection on the Arabidopsis thaliana genome in present and future climates." Nature 573.7772 (2019): 126-129.