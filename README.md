# scRNA-seq
#scRNAseq_analysis/
#├── data/  
 
  │   ├── raw_data/          # Raw feature-barcode matrices
  
  │   └── processed_data/    # Processed Seurat objects
  
  ├── results/
  
  │   ├── figures/           # All output plots
  
  │   ├── markers/           # Marker gene lists
  
  │   └── DE_results/        # Differential expression results
  
  ├── scripts/
  
  │   ├── 1_quality_control.R
  
  │   ├── 2_normalization.R
  
  │   ├── 3_feature_selection.R
  
  
  │   ├── 4_dimensionality_reduction.R
  
  │   ├── 5_clustering.R
  
  │   ├── 6_celltype_annotation.R
  
  │   ├── 7_differential_expression.R
  
  │   └── utils.R            # Helper functions
  
  ├── docs/
  
  │   ├── README.md          # Project overview
  
  │   └── requirements.md     # Software/dependency info
  
  └── scRNAseq_analysis.Rproj # R project file
