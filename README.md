# synCHOP target nomination

Bioinformatics pipeline integrating temporal scRNA-seq data from retinal ganglion cells (RGCs) in a mouse model of optic nerve crush (GSE137398), cell-type specific markers for RGCs (GSE199317), and TF-driven chromatin accessibility changes (GSE184547).

To replicate this analysis, follow the notebooks in order from step 1 (memory-intensive: data download and creating a single AnnData matrix with all temporal scRNA-seq RGC data), to step 2 (creating pseudobulk profiles for each timepoint, identifying DEGs, classifying temporal profiles in scRNA-seq data, identifying RGC-specific markers that are not upregulated in other glial subtypes), to step 3 (integrating transcription factors highly expressed post-optic nerve crush whose motifs are enriched in chromatin regions that are more accessible). 
