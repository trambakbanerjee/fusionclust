<!-- README.md is generated from README.Rmd. Please edit that file -->
fusionclust
===========
[![Build Status](https://travis-ci.org/trambakbanerjee/fusionclust.svg?branch=master)](https://travis-ci.org/trambakbanerjee/fusionclust)
[![CRAN_Status_Badge](http://www.r-pkg.org/badges/version/fusionclust)](https://cran.r-project.org/package=fusionclust)

The goal of `fusionclust` is to conduct clustering and feature screening in large scale cluster analysis problems. In particular, `fusionclust` provides the Big Merge Tracker (BMT) and COSCI algorithms for convex clustering and feature screening using an ℓ1 fusion penalty.  

BMT is a computationally efficient path algorithm that relies on a convex relaxation of the k-means clustering criterion and is useful for determining the number of clusters / modes in an univariate problem. COSCI (COnvex Screening for Cluster Information), on the other hand, is a non-parametric method for ranking and screening non-informative features in large scale cluster analysis problems and enjoys a perfect screening property in the sense that under mild regularity conditions on the densities of the features, COSCI screens out all the non-informative features with high probability. See the two references for more details around these algorithms.

Installation
-----------
You can:

1. install the release version of `fusionclust` from [CRAN](https://CRAN.R-project.org/package=fusionclust) with `install.packages("fusionclust")`.

2. install the development version of `fusionclust`

 ```R
   devtools::install_github("trambakbanerjee/fusionclust")
   ```

Example
-------

Check out the included vignette [`demo-fusionclust`](https://cran.r-project.org/web/packages/fusionclust/vignettes/demo-fusionclust.html) for illustrative examples.

References
--------
[1.] [Feature Screening in Large Scale Cluster Analysis](http://www.sciencedirect.com/science/article/pii/S0047259X17300271)    
Banerjee, T., Mukherjee, G. and Radchenko P.  *Journal of Multivariate Analysis, Volume 161, 2017, Pages 191-212

[2.] [Convex clustering via ℓ1 fusion penalization](http://onlinelibrary.wiley.com/doi/10.1111/rssb.12226/abstract)   
Radchenko P., Mukherjee G.   *J. R. Stat. Soc. Ser. B Stat. Methodol. (2017)*

