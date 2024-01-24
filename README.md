# Trajectory_Analysis

This repository contains codes for the trajectory analsysis performed in the thesis by Herrera-Foessel, SA (Link DIVA).

The codes are divided in two parts. 

File: 23_12_06_SublateralOrgan_Monocle_Spruce_SHF_Part1.Rmd Part1 includes codes for:

1) Pre-trajectory analysis: Subsetting using STUtility, cluster analysis with Seurat (including SCTransform, batch correcting with Harmony, dimensionality reductions with PCA and UMAP, cluster analysis (Louvain).

2) Trajectory Analysis with Monocle 3:
Convertion of Seurat object to cds Monocle 3 object, integration of cluster and UMAP cell embeddings from Seurat, construction of trajectory analysis, order cells based on initial root, saving pseudotime values to Seurat Object, finding significant genes along trajectory (graph_test with Morans I Statistic).

4) Visualization of cluster and tissue on brightfield images using STUtility/Seurat.


File: 23_12_06_SublateralOrgan_Monocle_Spruce_SHF_Part1.Rmd Part2 includes codes for:
1) FindAllmarkers in Seurat and merging with annotated marker list by inner join.

2) Visualization of clusters and genes with heatmaps, dimplots, featureplots, Vlnplots etc.

3) Regression plots with Expression against pseudotime.

4) Result tables of number spots per cluster. 
