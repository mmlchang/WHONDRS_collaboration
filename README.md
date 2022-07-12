# WHONDRS_collaboration

This is a private git repo for SUTS WHONDRS_collaboration

The folder structure is as follows:

--Readme

--Dataset
---- sediment
---- water

--EDA (exploratory data analysis)
---- EDAJaccard.ipynb
Site clustering using the water dataset where sample_id as rows and Jaccard indices as columns for the clustering (PCA followed by kMeans). The initial assumptions would be to identify which sites are similar / different from each other in terms of Jaccard diversity indices, then from there we look at the CF composition (top CF per cluster) and the differences in meta data (boxplot). Then, Flo’s model could investigate what’re the important features that drive such differences, assuming the CF composition (DOM clusters) are related to sites.
    
--Model
    
--Results