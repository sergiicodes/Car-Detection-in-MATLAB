This MATLAB program detects and counts cars in a video sequence using a foreground detector based on Gaussian mixture models (GMMs).
A Gaussian mixture model is a probabilistic model that bears that all the data points are generated from a mixture of a finite number of Gaussian distributions with unknown parameters. 
One can think of mixture models as generalizing k-means clustering to incorporate information about the covariance structure of the data as well as the centers of the latent Gaussians.

An essential use of this model is in analyzing traffic patterns. For instance, detection is the first step before performing more sophisticated tasks, such as tracking or categorizing vehicles by type. This example shows how foreground and blob analysis can detect and count cars in a video sequence, assuming the camera is stationary. The model focuses on detecting objects.
