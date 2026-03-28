# Transcriptomics analysis

This repository contains cleaned and annotated R scripts for the paper "COMPARATIVE TRANSCRIPTOMICS OF EARLY CLUBROOT INFECTION REVEALS DISTINCT HOST REPROGRAMMING IN BROCCOLI, BROCCOLINI AND GAI-LAN".

This repository contains cleaned code only. Raw sequencing/count files and large external annotation resources are not included.

## Script map

- `00_stage_timeline_panel.R` — build the stage-alignment timeline figure panel.
- `01_host_deseq_within_genotype.R` — main host DESeq2 workflow within genotype against control.
- `02_host_pca_publication_plots.R` — publication-style host PCA plots.
- `03_host_pca_with_ellipses.R` — host PCA plots with 95% ellipses.
- `04_deg_burden_plot.R` — DEG burden summary figure.
- `05_compile_supplementary_table_S3.R` — compile host DESeq2 results for Supplementary Table S3.
- `06_overlap_membership_tables.R` — build shared/unique DEG membership tables.
- `07_custom_upset_plots.R` — custom UpSet plots for overlap patterns.
- `08_go_mapping_master_tables.R` — build XP/LOC/GO mapping tables.
- `09_go_mapping_extend_with_ensembl.R` — extend the mapping with Ensembl downloads.
- `10_deg_annotation_join_and_conversion_tables.R` — join DEG tables to annotation/conversion tables.
- `11_go_bp_enrichment.R` — GO biological-process enrichment and dotplot.
- `12_targeted_pathway_candidates.R` — keyword-based targeted pathway candidate selection.
- `13_targeted_pathway_heatmap_final.R` — final targeted pathway heatmap.
- `14_compile_supplementary_tables_S4_S5.R` — compile S4 and S5 supplementary tables.
- `15_pathogen_exploratory_analysis.R` — exploratory pathogen-side transcript analysis.
- `16_pathogen_publication_plots.R` — publication-style pathogen PCA and heatmap figures.
- `17_compile_pathogen_supplementary_tables.R` — compile pathogen supplementary tables.


