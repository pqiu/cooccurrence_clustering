# cooccurrence_clustering

One primary reason that makes the analysis of single-cell RNA-seq data challenging is the dropouts, where the data only captures a small fraction of the transcriptome of each cell. Many computational algorithms have been developed to address the dropouts. Here, an opposite view is explored. Instead of treating dropout as a problem to be fixed, we embrace it as a useful signal for defining cell types. We present an iterative co-occurrence clustering algorithm that works with binarized single-cell RNA-seq count data, and is able to effectively identify cell populations, as well as cell-type specific pathways and signatures. 

# Manual

Download and unzip the cooccurence_clustering_repo.zip file. Among the three resulting folders, source code is under the "tools" folder, and the other two folders are two example datasets. 

In each example folder, run the step_01, 02, 03, ... matlab scripts sequentially. 

In addition to the co-occurrence clustering algorthim, we also provide a matlab implementation of Seurat clustering.

System requirements for running the code:  Matlab 2017b and Windonws 10 
