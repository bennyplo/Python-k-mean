# Python-k-mean
Python implementation of k-means clustering (Jupyter notebook)

This is an example code for k-means clustering implemented in python (Jupyter notebook).<br/>
This simple program was designed to perform image segmentation.<br/>
<p align="justify">It needs a training image (i.e. pyramid2.jpeg), a labelled image (pyramid2_label.jpeg), and a test image (pyramid1.jpeg). The 3 example images are also included in this repository.</p>
As you can see in the example labelled image, areas of the image are labelled with 3 different colors (namely Red, Green Blue).<br/>
The program will read the labels based on these 3 colors. <br/>
The program defines 5 clusters (k=5) and intialise the means(centroids) of the 5 clusters into random locations in the R,G,B space.
1000 samples are randomly picked from the training set to form the training data.
Each sample in Based on the Euclidean distances from the centroids
The program goes through pixel by pixel and segment the image accordingly.<br/>
