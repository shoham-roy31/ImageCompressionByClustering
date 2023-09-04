# ImageCompressionByClustering
This repository is about the process of image compression utilizing Unsupervised Machine Learning Algorithm. 

Compression of an image is necessary for Computer Vision. Thereby reducing the unecessary details of an image and processing it to such an extent so it yields only the minimal neccesary features of the image sufficient for Computer Vision. Otherwise, it will increase both space and time complexity for processing an image.

An Unsupervised Machine Learning Algorithm is implemented for clustering purpose. By the name itself, one can guess what type of clustering algorithm can be implement!
Yes, KMeans Clustering Algorithm is employed for this job.

The Mechanics of Image Compression is the reduced the pixel clarity as much as possible, but with a condition of keeping the image's charaterstics and features indentical to the original one.

Let us, understand the clustering algorthim, KMeans. 
KMeans Clustering Algorithm, clusters datasets into respective groups depending upon their Eculidian/Manhatan Distances, so is a stream of datapoints different random points are selected in the stream.
After rigorous, evaluation centroids of the respective clusters of datapoints are evaluated. This centroids delegate the respective cluster.

Hence, if this single centroid help us to represent as an unified cluster, we will implement this logic to reduce the image quality. 
