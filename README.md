# Python-k-mean
Python implementation of k-means clustering (Jupyter notebook)

This is an example code for k-means clustering implemented in python (Jupyter notebook).<br/>
This simple program was designed to perform image segmentation.<br/>
<h3>Dataset</h3>
<p align="justify">It needs a training image (i.e. pyramid2.jpeg), a labelled image (pyramid2_label.jpeg), and a test image (pyramid1.jpeg). The 3 example images are also included in this repository.</p>
As you can see in the example labelled image, areas of the image are labelled with 3 different colors (namely Red, Green Blue).<br/>
The program will read the labels based on these 3 colors. <br/>
The program defines 5 clusters (k=5) and intialise the means(centroids) of the 5 clusters into random locations in the R,G,B space.
<h3>Training of the k-means cluster method:</h3>
<ul><li>1000 samples are randomly picked from the training set to form the training data.</li>
  <li>For each sample, find the nearest centroid (i.e. cluster).</li>
  <li> Assign the sample to the cluster</li>
  <li>Update the centroids -> mean of the cluster of samples</li>
  <li>report until the centroids locations no longer changes<.li>
 </ul>
    <h4>Label the clusters</h4>
    <ul><li>For each cluster, find the label where most samples are of the same label</li>
      <li>Assign the label to the cluster</li>
    </ul>
    <h3>Inferencing</h3>
  <li>The program goes through pixel by pixel</li>
  <li>Find the nearest centroid</li>
  <li>label/segment the pixel with the label of the cluster</li>
  </ul>
