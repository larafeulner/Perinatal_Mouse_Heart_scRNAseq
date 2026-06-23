This repository contains codes and analysis files related to the publication "Transcriptional dynamics of the murine heart during perinatal development at single-cell resolution" (Feulner et. al). Data was derived from a single-cell RNA-seq (Drop-seq) dataset of mouse hearts covering E14.5, E16.5, E18.5, P0, P4 and P7 timepoints.

Referenced files not hosted on this repository should be available instead on Zenodo (DOI: 10.5281/zenodo.20650169, https://zenodo.org/records/20650169). These include Perinatal_clusterannot.Rds object and folders for FilteredCounts, subset_mats_pusupertime, subset_meta_psupertime and psupertime_results.

Overall order of analysis should be Clustering_and_DiffExp.Rmd, Figure1_plots.Rmd, Subclustering.Rmd, psupertime.R, Figure3_plots.Rmd and Figure6_plots.Rmd.

Clustering_and_DiffExp.Rmd: Final clustering and generation of Seurat object (Perinatal_clusterannot.Rds) corresponding to Figure 1.

Subclustering.Rmd: Isolation of main cardiac cell types from Perinatal_clusterannot.Rds, reclustering, final filtering for cell type purity, and generation of raw matrices for downstream analysis including psupertime. 

psupertime.R: psupertime_analysis, corresponding to Figure 3A.

plot_dt and sceptic_pseudotime folders contain files used for supplemental sceptic analysis in Python (sceptic_ipynb).

R_package_versions.txt includes returns from SessionInfo() command in R and represent versions used during time of analysis. 
