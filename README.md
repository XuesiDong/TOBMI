# TOBMI is an imputation method used for "blocking missing" dataset. 
# For the convenience of attempt, example datasets for users are subsets from our study (without data conversion).
# In our study, abnormal samples, as well as samples missing either transcriptomic or epigenomic data were excluded!
# We propose a k-nearest neighbor (kNN) weighted imputation method for trans-omics block missing data (TOBMIkNN) to handle gene-absence     individuals in RNA-seq datasets using external information obtained from DNA methylation probe datasets.
# We recommond mahalanobis distance for this method. Notably, if you prepare to handle a high-order autocorrelation matrix (Like Us),       using generalized inverse matrix in mahalanobis distance or euclidean distance directly may be convenient.
# If you have any question, please do not hesitate to contact us: dxsbiostatistics@163.com  /  230179785@seu.edu.cn
