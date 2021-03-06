# awesome-single-cell

List of software packages (and the people developing these methods) for single-cell data analysis, including RNA-seq, ATAC-seq, etc. [Contributions welcome](https://github.com/seandavi/awesome-single-cell/blob/master/CONTRIBUTE.md)...

## Software packages

### RNA-seq

- [anchor](https://github.com/yeolab/anchor) - [Python] - ⚓ Find bimodal, unimodal, and multimodal features in your data
- [BackSPIN](https://github.com/linnarsson-lab/BackSPIN) - [Python] - Biclustering algorithm developed taking into account intrinsic features of single-cell RNA-seq experiments.
- [BASiCs](https://github.com/catavallejos/BASiCS) - [R] - Bayesian Analysis of single-cell RNA-seq data. Estimates cell-specific normalization constants. Technical variability is quantified based on spike-in genes. The total variability of the expression counts is decomposed into technical and biological components.
- [bonvoyage](https://github.com/yeolab/bonvoyage) - [Python] - 📐 Transform percentage-based units into a 2d space to evaluate changes in distribution with both magnitude and direction.
- [BPSC](https://github.com/nghiavtr/BPSC) - [R] - Beta-Poisson model for single-cell RNA-seq data analyses
- [Cellity](https://github.com/teichlab/cellity) - [R] - Classification of low quality cells in scRNA-seq data using R
- [cellTree](https://www.bioconductor.org/packages/3.3/bioc/html/cellTree.html) - [R] - Cell population analysis and visualization from single cell RNA-seq data using a Latent Dirichlet Allocation model.
- [clusterExperiment](https://github.com/epurdom/clusterExperiment) - [R] - Functions for running and comparing many different clusterings of single-cell sequencing data. Meant to work with SCONE and slingshot.
- [ECLAIR](https://github.com/GGiecold/ECLAIR) - [python] - ECLAIR stands for Ensemble Clustering for Lineage Analysis, Inference and Robustness. Robust and scalable inference of cell lineages from gene expression data.
- [Falco](https://github.com/VCCRI/Falco/) - [AWS cloud] - [Falco: A quick and flexible single-cell RNA-seq processing framework on the cloud](http://www.biorxiv.org/content/early/2016/07/15/064006.abstract).
- [FastProject](https://github.com/yoseflab/fastproject) - [Python] - Signature analysis on low-dimensional projections of single-cell expression data.
- [flotilla](https://github.com/yeolab/flotilla) - [Python] Reproducible machine learning analysis of gene expression and alternative splicing data
- [HocusPocus](https://github.com/joeburns06/hocuspocus) - [R] - Basic PCA-based workflow for analysis and plotting of single cell RNA-seq data.
- [MAST](https://github.com/RGLab/MAST) - [R] - Model-based Analysis of Single-cell Transcriptomics
(MAST) fits a two-part, generalized linear models that are specially adapted for bimodal and/or zero-inflated single cell gene expression data.
- [Monocle](http://cole-trapnell-lab.github.io/monocle-release/) - [R] - Differential expression and time-series analysis for single-cell RNA-Seq.
- [OEFinder](https://github.com/lengning/OEFinder) - [R] - Identify ordering effect genes in single cell RNA-seq data. OEFinder shiny impelemention depends on packages shiny, shinyFiles, gdata, and EBSeq.
- [Ouija](https://github.com/kieranrcampbell/ouija) - [R] - Incorporate prior information into single-cell trajectory (pseudotime) analyses using Bayesian nonlinear factor analysis.
- [outrigger](https://github.com/YeoLab/outrigger) - [Python] - Outrigger is a program to calculate alternative splicing scores of RNA-Seq data based on junction reads and a *de novo*, custom annotation created with a graph database, especially made for single-cell analyses.
- [SC3](https://github.com/hemberg-lab/sc3) - [R] - SC3 is an interactive tool for the unsupervised clustering of cells from single cell RNA-Seq experiments.
- [scater](bioconductor.org/packages/scater) - [R] - Scater places an emphasis on tools for quality control, visualisation and pre-processing of data before further downstream analysis, filling a useful niche between raw RNA-sequencing count or transcripts-per-million data and more focused downstream modelling tools such as monocle, scLVM, SCDE, edgeR, limma and so on.
- [scDD](https://github.com/kdkorthauer/scDD) - [R] - scDD (Single-Cell Differential Distributions) is a framework to identify genes with different expression patterns between biological groups of interest.  In addition to traditional differential expression, it can detect differences that are more complex and subtle than a mean shift.
- [SCDE](https://github.com/hms-dbmi/scde) - [R] - Differential expression using error models and overdispersion-based identification of important gene sets.
- [SCell](https://github.com/diazlab/SCell) - [matlab] - SCell is an integrated software tool for quality filtering, normalization, feature selection, iterative dimensionality reduction, clustering and the estimation of gene-expression gradients from large ensembles of single-cell RNA-seq datasets. SCell is open source, and implemented with an intuitive graphical interface.
- [scLVM](https://github.com/PMBio/scLVM) - [R] - scLVM is a modelling framework for single-cell RNA-seq data that can be used to dissect the observed heterogeneity into different sources, thereby allowing for the correction of confounding sources of variation.  scLVM was primarily designed to account for cell-cycle induced variations in single-cell RNA-seq data where cell cycle is the primary soure of variability. 
- [SCONE](https://github.com/YosefLab/scone) - [R] - SCONE (Single-Cell Overview of Normalized Expression), a package for single-cell RNA-seq data quality control (QC) and normalization. This data-driven framework uses summaries of expression data to assess the efficacy of normalization workflows.
- [SCOUP](https://github.com/hmatsu1226/SCOUP) - [C++] - Uses probabilistic model based on the Ornstein-Uhlenbeck process to analyze single-cell expression data during differentiation. 
- [scran](http://bioconductor.org/packages/scran) - [R] - This package implements a variety of low-level analyses of single-cell RNA-seq data. Methods are provided for normalization of cell-specific biases, pool-based norms to estimate size factors, assignment of cell cycle phase, and detection of highly variable and significantly correlated genes.
- [SCRAT](https://github.com/zji90/SCRAT) - [R] - SCRAT provides essential tools for users to read in single-cell regolome data (ChIP-seq, ATAC-seq, DNase-seq) and summarize into different types of features. It also allows users to visualize the features, cluster samples and identify key features.
- [SEPA](https://github.com/zji90/SEPA) - [R] - SEPA provides convenient functions for users to assign genes into different gene expression patterns such as constant, monotone increasing and increasing then decreasing. SEPA then performs GO enrichment analysis to analysis the functional roles of genes with same or similar patterns.
- [scTCRseq](https://github.com/ElementoLab/scTCRseq) - [python] - Map T-cell receptor (TCR) repertoires from single cell RNAseq.
- [Seurat](http://www.satijalab.org/seurat.html) - [R] - It contains easy-to-use implementations of commonly used analytical techniques, including the identification of highly variable genes, dimensionality reduction (PCA, ICA, t-SNE), standard unsupervised clustering algorithms (density clustering, hierarchical clustering, k-means), and the discovery of differentially expressed genes and markers.
- [sincell](http://bioconductor.org/packages/sincell) - [R] - Existing computational approaches for the assessment of cell-state hierarchies from single-cell data might be formalized under a general workflow composed of i) a metric to assess cell-to-cell similarities (combined or not with a dimensionality reduction step), and ii) a graph-building algorithm (optionally making use of a cells-clustering step). Sincell R package implements a methodological toolbox allowing flexible workflows under such framework.
- [sincera](https://research.cchmc.org/pbge/sincera.html) - [R] - R-based pipeline for single-cell analysis including clustering and visualization.
- [SinQC](http://www.morgridge.net/SinQC.html) - [R] - A Method and Tool to Control Single-cell RNA-seq Data Quality.
- [SLICER](https://github.com/jw156605/SLICER) - [R] - Selective Locally linear Inference of Cellular Expression Relationships (SLICER) algorithm for inferring cell trajectories.
- [slingshot](https://github.com/kstreet13/slingshot) - [R] - Functions for identifying and characterizing continuous developmental trajectories in single-cell sequencing data.
- [SPADE](http://www.nature.com/nprot/journal/v11/n7/full/nprot.2016.066.html) - [R] - Visualization and cellular hierarchy inference of single-cell data using SPADE.
- [switchde](http://github.com/kieranrcampbell/switchde) - [R] - Differential expression analysis across pseudotime. Identify genes that exhibit switch-like up or down regulation along single-cell trajectories along with where in the trajectory the regulation occurs.
- [TraCeR](http://github.com/teichlab/tracer) - [python] - Reconstruction of T-Cell receptor sequences from single-cell RNA-seq data.
- [TRAPeS](https://github.com/yoseflab/trapes) - [python, C++] - TRAPeS (TCR Reconstruction Algorithm for Paired-End Single-cell), a software for reconstruction of T cell receptors (TCR) using short, paired-end single-cell RNA-sequencing.
- [TSCAN](https://github.com/zji90/TSCAN) - [R] - Pseudo-time reconstruction and evaluation in single-cell RNA-seq analysis.

### Copy number analysis

- [Gingko](https://github.com/robertaboukhalil/ginkgo) - [R, C] - Gingko is a cloud-based web app single-cell copy-number variation analysis tool.

## Tutorials and workflows
 
- [Aaron Lun's Single Cell workflow on Bioconductor](http://bioconductor.org/help/workflows/simpleSingleCell/) - [R] - This article describes a computational workflow for basic analysis of scRNA-seq data using software packages from the open-source Bioconductor project.
- [Bioconductor2016 Single-cell-RNA-sequencing workshop by Sandrine Dudoit lab](https://github.com/drisso/bioc2016singlecell) - [R] - SCONE, clusterExperiment, and slingshot tutorial.
- [BiomedCentral Single Cell Omics collectin](http://www.biomedcentral.com/collections/singlecellomics) - collection of papers describing techniques for single-cell analysis and protocols.
- [CSHL Single Cell Analysis - Bioinformatics](https://github.com/YeoLab/single-cell-bioinformatics/) course materials - Uses Shalek 2013 and Macaulay 2016 datasets to teach machine learning to biologists
- [Gilad Lab Single Cell Data Exploration](http://jdblischak.github.io/singleCellSeq/analysis/) - R-based exploration of single cell sequence data. Lots of experimentation. 
- [Harvard STEM Cell Institute Single Cell Workshop 2015](http://hms-dbmi.github.io/scw/) - workshop on common computational analysis techniques for scRNA-seq data from differential expression to subpopulation identification and network analysis. [See course description for more information](http://scholar.harvard.edu/jeanfan/classes/single-cell-workshop-2015) 
- [Hemberg Lab scRNA-seq course materials](http://hemberg-lab.github.io/scRNA.seq.course/index.html) 
- [Using Seurat for unsupervised clustering and biomarker discovery](http://www.satijalab.org/seurat-intro.html) - 301 single cells across diverse tissues from (Pollen et al., Nature Biotechnology, 2014)
- [Using Seurat for spatial inference in single-cell data](http://www.satijalab.org/seurat-intro.html) - 851 single cells from Zebrafish embryogenesis (Satija*, Farrell* et al., Nature Biotechnology, 2015)

## Web portals and apps

- [conquer](http://imlspenticton.uzh.ch:3838/conquer/) - A repository of consistently processed, analysis-ready single-cell RNA-seq data sets.
- [Neuro Single Cell Expression Portal at the Broad](https://portals.broadinstitute.org/single_cell) - The Single-Cell RNA-Seq Portal for Brain Research was developed to facilitate sharing scientific results, and disseminate datasets resulting from the NIH's BRAIN initiative.

## Journal articles of general interest

### Paper collections

- [Mendeley Single Cell Sequencing Analysis](https://www.mendeley.com/groups/9329461/single-cell-sequencing-analysis/papers/)

### Experimental design

- [Design and computational analysis of single-cell RNA-sequencing experiments](http://genomebiology.biomedcentral.com/articles/10.1186/s13059-016-0927-y)

### Methods comparisons

- [Comparative analysis of single-cell RNA sequencing methods](http://biorxiv.org/content/early/2016/06/29/035758) - a comparison of wet lab protocols for scRNA sequencing.

## Similar lists and collections

- [CrazyHotTommy's RNA-seq analysis list](https://github.com/crazyhottommy/RNA-seq-analysis#single-cell-rna-seq) - Very broad list that includes some single cell RNA-seq packages and papers.
- [lazappi's Single-cell Software table](https://github.com/lazappi/awesome-single-cell) - Table of single cell software and it's functions. Live version [here](https://goo.gl/4wcVwn).

## People

Gender bias at conferences is a well known problem ([http://www.sciencemag.org/careers/2015/07/countering-gender-bias-conferences](http://www.sciencemag.org/careers/2015/07/countering-gender-bias-conferences)). Creating a list of potential speakers can help mitigate this bias and a community of people developing and maintaining helps to further diversify this list beyond smaller networks. 

### Female

- [Christina Kendziorski (University of Wisconsin–Madison, USA)](https://www.biostat.wisc.edu/~kendzior/) 
- [Sandrine Dudoit (UC Berkeley, USA)](http://www.stat.berkeley.edu/~sandrine/)
- [Keegan Korthauer (Dana Farber Cancer Institute, USA)](http://bcb.dfci.harvard.edu/~keegan/)
- [Stephanie Hicks (Dana Farber Cancer Institute, USA)](http://www.stephaniehicks.com/)
- [Dana Pe'er (Columbia University, USA](http://www.c2b2.columbia.edu/danapeerlab/html/)
- [Aviv Regev (Broad Institute, USA)](https://www.broadinstitute.org/scientific-community/science/core-faculty-labs/regev-lab/regev-lab-home)
- [Catalina Vallejos (MRC Biostatistics Unit and EMBL-EBI, UK)](http://www.mrc-bsu.cam.ac.uk/people/in-alphabetical-order/t-to-z/catalina-vallejos-menesses/)
- [Sarah Teichmann (Wellcome Trust Sanger Institute, UK)](http://www.teichlab.org/)
- [Emma Pierson (Stanford University, USA)](http://cs.stanford.edu/people/emmap1/)
- [Ning Leng (Morgridge Institute for Research, USA)](https://www.biostat.wisc.edu/~ningleng/)
- [Laleh Haghverdi (Institute of Computational Biology, Germany)](https://www.helmholtz-muenchen.de/icb/institute/staff/staff/ma/2453/-Haghverdi/index.html)

### Male

- [Raphael Gottardo (Fred Hutchinson Cancer Research Center, USA)](https://www.fredhutch.org/en/labs/profiles/gottardo-raphael.html)
- [John Marioni (EBI, UK)](http://www.ebi.ac.uk/research/marioni)
- [Oliver Stegle (EBI, UK)](http://www.ebi.ac.uk/research/stegle)
- [Davis McCarthy (EBI, UK)](https://sites.google.com/site/davismcc/)
- [Aaron Lun (Cancer Research UK, UK)](http://www.cruk.cam.ac.uk/users/aaron-lun)
- [Cole Trapnell (University of Washington, Department of Genome Sciences)](http://cole-trapnell-lab.github.io/)
- [Rahul Satija (New York Genome Center)](http://satijalab.org/)
