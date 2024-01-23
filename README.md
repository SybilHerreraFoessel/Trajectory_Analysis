# Trajectory_Analysis
This repository contains codes for the trajectory analsysis performed in the thesis by Herrera-Foessel, SA (Link DIVA).
The codes are divided in parts. 

File: 23_12_06_SublateralOrgan_Monocle_Spruce_SHF_Part1.Rmd
Part1 includes:

1) Pre-trajectory analysis:
Subsetting, cluster analysis (including SCTransform, batch correcting with Harmony, dimensionality reductions with PCA and UMAP, cluster analysis.

2) Trajectory Analysis with Monocle 3:
Integration of cluster and UMAP cell embeddings from Seurat, construction of trajectory analysis, order cells, 
save pseudotime values to Seurat Object, finding significant genes along trajectory.

3) Visualization of cluster and tissue on STUtility/Seurat. 
