# TOBMI
# TOBMI is an imputation method used for "blocking missing" dataset. 
# We propose a k-nearest neighbor (kNN) weighted imputation method for trans-omics block missing data (TOBMIkNN) to handle gene-absence     individuals in RNA-seq datasets using external information obtained from DNA methylation probe datasets.
# We recommond mahalanobis distance for this method. Notably, if you prepare to handle a high-order autocorrelation matrix, using           generalized inverse matrix in mahalanobis distance or use euclidean distance directly may be more convenient.
