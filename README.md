# 0 Abstract of the paper

The vast neuronal diversity in the human neocortex is vital for high-order brain functions, necessitating elucidation of the regulatory mechanisms underlying such unparalleled diversity. However, recent studies have yet to comprehensively reveal the diversity of [neurons](https://www.sciencedirect.com/topics/biochemistry-genetics-and-molecular-biology/neurod1) and the molecular logic of neocortical origin in humans at single-cell resolution through profiling [transcriptomic](https://www.sciencedirect.com/topics/neuroscience/transcriptomics) or [epigenomic](https://www.sciencedirect.com/topics/biochemistry-genetics-and-molecular-biology/epigenomics) landscapes, owing to the application of unimodal data alone to depict exceedingly heterogeneous populations of [neurons](https://www.sciencedirect.com/topics/neuroscience/neurod1). In this study, we generated a comprehensive compendium of the developing human neocortex by simultaneously [profiling gene expression](https://www.sciencedirect.com/topics/biochemistry-genetics-and-molecular-biology/gene-expression-profiling) and open chromatin from the same cell. We computationally reconstructed the differentiation trajectories of excitatory projection neurons of cortical origin and inferred the regulatory logic governing lineage bifurcation decisions for neuronal diversification. We demonstrated that neuronal diversity arises from [progenitor cell](https://www.sciencedirect.com/topics/biochemistry-genetics-and-molecular-biology/progenitor-cell) lineage specificity and postmitotic differentiation at distinct stages. Our data paves the way for understanding the primarily coordinated regulatory logic for neuronal diversification in the neocortex.

# 1 Processing of scMultiome-seq datasets and annotation of cell types

pwd:/data3/yuhan/Project/Neuron/scMultiome/scMultiome_library
run.4_GW20B1_FU_scMultiome_ATAC_GEX_B1.R
run.8_GW15B1_301_scMultiome_ATAC_GEX_B1.R
run.9_GW11B3_FU_scMultiome_ATAC_GEX_B1.R

# 2 Data integration and cell type annotation
pwd:/data3/yuhan/Project/Neuron/scMultiome/Run_Harmony/scMultiome_data_integration/peaksCombine_CFpvalue20
run.peaksCombine_CFpvalue20.R
/data3/yuhan/Project/Neuron/scMultiome/2_cell_annotation_newVersion
run.obj.integratedATAC_HarmonyRNA_combine.cell_annotation_newVersion.cleanedcell.final.R

# 3 Inference of RNA velocity
/data3/yuhan/Project/Neuron/scMultiome/4_developmental_trajectories.newVersion.cleanedcell/scVelo
run.developmental_trajectories.scVelo.py

# 4 Inference of branching trajectory tree
pwd:/data3/yuhan/Project/Neuron/scMultiome/4_developmental_trajectories.newVersion.cleanedcell/1_URDTree
run.step0.URDobj.R
run.step1.URDtree.R
run.step2.TREEdescription.R
run.step3.HistogramPlot.R

# 5 paper

Tian Y, Wu X, Luo S, et al. A multi-omic single-cell landscape of cellular diversification in the developing human cerebral cortex[J]. Computational and Structural Biotechnology Journal, 2024, 23: 2173-2189.

