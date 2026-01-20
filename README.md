# scRNA-seq Analysis using Seurat (PBMC)

## Objective
To perform a basic single-cell RNA-seq analysis using Seurat, including
quality control, clustering, and marker gene identification.

## Dataset
PBMC (Peripheral Blood Mononuclear Cells) single-cell RNA-seq dataset
provided by the SeuratData package.

## Tools
- R
- Seurat

## Scope and Note
This project is an academic learning exercise focused on understanding
the basic concepts and standard workflow of single-cell RNA-seq analysis
using Seurat. The analysis is intended for educational and demonstration
purposes.

## Status
## Status
- Quality control completed (mitochondrial filtering applied)
- Data normalized using LogNormalize (scale factor = 10,000)
- Highly variable genes identified (2,000 features, VST method)
- Data scaled for downstream analysis
- Dimensionality reduction performed using PCA
- Graph-based clustering completed (9 clusters identified)
- UMAP visualization generated for cluster interpretation


