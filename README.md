# PCA-K-Means

## Introduction

This project computes the Principal Component Analysis and K-Means algorithms and use them on a dataset. The dataset is the set of images from MNIST database corresponding to the handwritten digit $7$. Each image is $28px\times 28px$. The set is divided in a training set and a testing set of respective size $3133$ and $3132$.

### Comparison <a href='#comparison'>Starts here</a>
<b><a href='#q8'>Question 8 (5%)</a></b> After the implementation of both algorithm a comparison of the results from PCA to the results of K-means on the <b>test set</b> by plotting on the same graph the reconstruction error $E(D)$ for $D = 3,4,5,10,50,100$ and the distortion cost you just computed (remark that the two measures are simply $L_2$ norms thus the comparison is valid). To be clear, the first one measure the error in the reconstructed image from the projection on the components of PCA, the second measure the error between each image and the centroid of the cluster it is assigned to. Both correpond to the error made when approximating the original image to either its projection or its cluster's centroid.
