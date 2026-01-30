# Fly Circadian Cell Atlas

This repository contains Jupyter notebooks and scripts used for the analyses in our study:
["A Time-Resolved Single-Nucleus Atlas of Circadian Transcription in the Drosophila Head"](https://doi.org/10.xxxx/xxxxx).

Read alignment and generation of gene and exon count matrices were performed using the [EasySci](https://github.com/JunyueCaoLab/EasySci.git) pipeline.


## Environment (key packages)
Tested with:
- Python 3.10.18
- R 4.3.3

### Python / Jupyter
- jupyterlab 4.0.13
- notebook 7.0.6
- ipykernel 6.29.3
- ipython 8.24.0

### Core scientific stack
- numpy 1.24.4
- pandas 2.2.3
- scipy 1.13.0
- scikit-learn 1.4.2
- statsmodels 0.14.5
- h5py 3.11.0

### Single-cell / omics analysis
- anndata 0.10.7
- scanpy 1.9.3
- scrublet 0.2.3
- umap-learn 0.5.3
- leidenalg 0.10.2
- python-igraph 0.11.9
- bbknn 1.6.0
- harmonypy 0.0.10
- scanorama 1.7.4
- loompy 3.0.7

### Gene regulatory network / SCENIC
- pyscenic 0.12.1
- arboreto 0.1.6
- ctxcore 0.2.0

### Enrichment / annotation
- gseapy 1.1.10
- goatools 1.2.3
- mygene 3.2.2
- biopython 1.85

### Plotting / visualization
- matplotlib 3.8.4
- seaborn 0.13.2
- bokeh 2.4.3
- plotly (R) 4.10.4
- ComplexHeatmap (R/Bioconductor) 2.18.0
- circlize (R) 0.4.16

### R / Bioconductor (selected)
- Seurat 5.3.0
- monocle 2.30.0
- limma 3.58.1
- edgeR 4.0.16
- scran 1.30.0
- scuttle 1.12.0
- SingleCellExperiment 1.24.0
- SummarizedExperiment 1.32.0

## Computing environment
All analyses were run on The Rockefeller University high-performance computing (HPC) cluster (Linux). Jobs were executed on compute nodes equipped with NVIDIA A100 Tensor Core GPUs.

