# BioSys_Project

This repository contains the vignettes and methods developed for the BioSys course.

To access the course final report please click [Portuguese]: [Final report](https://flaviogckessler.github.io/BioSys_Project/Relatorio_FlavioKessler_BioSys.html)

Or download the final report PDF [Portuguese]: `Relatorio_FlavioKessler_BioSys.pdf`

You can also download the project presentation PDF [Portuguese]: `Apresentacao_FlavioKessler_BioSys.pdf`

## Rendered vignettes

The framework of this project followed three steps:

(i) Process the `stxbrain` dataset from `Seurat` and save it as a normalized GraphSpace object, see [Setup vignette](https://flaviogckessler.github.io/BioSys_Project/Setup_GraphSpaceObj_stxbrain.html)

(ii) Compute cell-cell communication using CellChat package and store spot-to-spot ligand-receptor pairs, see [CellChat vignette](https://flaviogckessler.github.io/BioSys_Project/CellChat_vignette.html)

(iii) With `stxbrain` and all ligand-receptor pairs datasets, the visualization of cell-cell communication in spatial transcriptomics data were performed using PathwaySpace. Please, see [PathwaySpace cell communication vignette](https://flaviogckessler.github.io/BioSys_Project/CellChat_ProximityNetwork_PathwaySpace.html)

## Description

The vignette demonstrates the use of R for spatial transcriptomics analysis and visualization, focusing in cell-cell communication.

## Repository structure

\- `CellChat_ProximityNetwork_PathwaySpace.Rmd`: main R Markdown file.

\- `bibliography.bib`: references cited in the vignette.

\- `CellChat_ProximityNetwork_PathwaySpace.html`: rendered vignette

\- `spot-spot_commu_Allbrain.rds`: data with all spot-spot cell communications, retrieved from CellChat

\- `stxbrain_Normalized_GraphSpace.RData`: Normalized GraphSpace object of `stxbrain`

## Requirements

The analysis was written in R and requires the following packages: ggplot2, igraph, CellChat, Seurat, RGraphSpace and PathwaySpace

