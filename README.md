# Classifying Google Street View House Numbers

### Project Description
An exploration of supervised classification models and image thresholding techniques to classify house numbers within Google street view images.

### Data Source

* Street View House Numbers (SVHN) Dataset 
  * [Standford - Google SVHN Datasets](http://ufldl.stanford.edu/housenumbers/ "Google SVHN Dataset") 
  
  Ref: Yuval Netzer, Tao Wang, Adam Coates, Alessandro Bissacco, Bo Wu, Andrew Y. Ng 
  <strong>Reading Digits in Natural Images with Unsupervised Feature Learning</strong> 
  <em>NIPS Workshop on Deep Learning and Unsupervised Feature Learning 2011</em>

### Tools Used
  * Scipy - Load images from .mat format (MATLAB)
  * OpenCV - Image manipulation (grayscale, thresholds)
  * Sckit-Learn - Estimator models
  
### Process
  1. Crop images to reduce secondary digits either side of main digit being classified
  2. Convert to grayscale to reduce feature space (RGB colors)
  3. Apply threshold to further reduce feature space (binning based on grascale shades)
  4. Convert multi-dimensional image array to one-dimensional array (image array flatted to 1D, end result is 2D array - stack of 1D image arrays)
  5. Train models using 2D image array
  6. Test models and evaluate performace
  
### Results
(TBC)
