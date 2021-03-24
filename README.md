# spleen_scrna_data_exploration
This a demo of exploring single cell RNA seq data using Scanpy
Data used are the filtered and unfiltered spleen single cell RNA seq datasets available from the Murine Aging Cell Atlas (https://mca.research.calicolabs.com/data)
  https://storage.googleapis.com/calico-website-mca-storage/spleen.h5ad (filtered dataset)
mca_spleen_scrna_filtered.ipynb explores the filtered dataset - outputs include the following:
  mca_spleen_filtered_mean_expression_by_celltype.csv (lists gene expression by cell type)
  mca_spleen_filtered_variance_by_celltype.csv (lists variance in gene expression by cell type)
  mca_spleen_filtered_top25_rank_genes_celltype.csv (lists the top 25 expressed genes by cell type)
  mca_spleen_filtered_mean_expression_by_celltype_age.csv (lists gene expression by cell type and mouse age)
  mca_spleen_filtered_variance_by_celltype_age.csv (lists variance in gene expression by cell type and mouse age)
  mca_spleen_filtered_top25_rank_genes_celltype_age.csv (lists gene expression by cell type and mouse age)
  mca_spleen_filtered_rank_celltype.png (plot of top 25 expressed genes by cell type)
  mca_spleen_filtered_rank_celltype_age.png  (plot of top 25 expressed genes by cell type and mouse age)
