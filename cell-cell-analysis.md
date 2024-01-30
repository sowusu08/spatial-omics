## Calculating cell-cell associations with distance
1. pearson's correlation of cell counts in whole area
2. then determine if highly correlated cell pairs are interacting with each other or spread apart  
  a. get straight line distance from cell type A to cell type B  
  b. then use __permutation testing__ to establish permuted null distribution (when labels of cells are randomly shuffled multiple times)  
  c. then overlay permuted null distribution and observed distribution to see if there is difference in medians or means of the two distributions  

## Multi-cellular neighborhood associations
1. Unsupervised clustering of cells using K-means clustering  
  a. usually 1000 permutations but test first on 10 permutations to make sure code works
