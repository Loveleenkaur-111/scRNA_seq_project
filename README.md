# GSE279086 Single-Cell RNA-Seq Analysis

## Project Overview

This project presents a comprehensive single-cell RNA sequencing (scRNA-seq) analysis of the public dataset GSE279086 to investigate cell type-specific alterations in kidney oxidative metabolism associated with Type 1 Diabetes in young adults.

## Objectives

* Process and analyze kidney scRNA-seq data
* Perform quality control and batch correction
* Annotate cell populations using CellTypist
* Identify differentially expressed genes (DEGs)
* Conduct pathway enrichment analysis using Reactome
* Explore metabolic alterations linked to Type 1 Diabetes

## Workflow

1. Download and preprocess GEO data
2. Create Seurat objects
3. Quality control filtering
4. Batch correction and integration
5. Cell type annotation
6. Differential expression analysis
7. Pathway enrichment analysis
8. Visualization and interpretation

## Tools and Packages

* R
* Seurat
* Harmony
* CellTypist
* clusterProfiler
* ReactomePA

## Key Results

* Identification of major kidney cell populations
* Cell type-specific transcriptional changes
* Differentially expressed genes associated with diabetic pathology
* Reactome pathway enrichment highlighting altered oxidative metabolism

## Repository Structure

* 01_download.sh
* 02_cleanup_geo_files.sh
* 03_10XtoSeurat.Rmd
* 04_qc_batchcorrection_GSE279086.Rmd
* 05_celltypist_GSE279086.ipynb
* 06_DEGs_Pathways_GSE279086.Rmd

## Author

Loveleen Kaur
M.Sc. Biochemistry and Molecular Biology
