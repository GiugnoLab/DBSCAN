# DBSCAN
> Enhancing density-basedclustering, parameter reduction and outlier detection



### Description:
Clustering is a widely used unsupervised data mining technique. In density-based clustering, a cluster is defined as a connected dense component and grows in the direction driven by the density. The basic structure of density-based clustering presents some common drawbacks: (i) parameters have to be set; (ii) the behavior of the algorithm is sensitive to the density of the starting object; and (iii) adjacent clusters of different densities could be not properly identified. In this paper, we address all the above problems.
Our method, based on the concept of space stratification, efficiently identifies the different densities in the dataset and, accordingly, ranks the objects of the original space. Next, it exploits such a knowledge by projecting the original data into a space with one more dimension. It performs a density based clustering taking into account the reverse-nearest-neighbor of the objects. Our method also reduces the number of input parameters by giving a guideline to set them in a suitable way. Experimental results indicate that our algorithm is able to deal with clusters of different densities and outperforms the most popular algorithms DBSCAN and OPTICS in all the standard benchmark datasets. DBStrata is a software system that implements the density-based clustering architecture together with several extensions able to boost the clustering performances and to efficiently identify outliers.
