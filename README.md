# Image Processing App

This project consist of the implementation of image processing projects **without** the use of any image processing library (such as opencv). It was implemented with ​[Qt development software](https://wiki.qt.io/Main) on a Linux platform and the used language is C++. The projects implemented so far are:  

1. **Object Detection and Classification based on Geometric Invariant Moment.**  
2. **Line and Circle detection based on Hough Transform.**
<p align="center">
  <img src="Test_images/documentation_Images/Fig3.png" title="App" alt="App">
</p>

## Project 1: Object Detection and Classification based on Geometric Invariant Moment

This project consist of the implementation of objects detection and classification program which detects and classifies objects (such as rice, beans, etc.) based on their geometric shape. The processes that are implemented in this project are:

* Noise Elimination
	* Mean Filtering
* Image Segmentation
	* OTSU Thresholding
  	* K-Means Cluster Binary Thresholding
* Morphological Image Processing
  	* Dilation
  	* Erosion
  	* Opening
  	* Closing
  	* Boundary Extraction
* Labeling and Bounding
	* Connected-component Analysis (CCA)
	* Drawing Bound Boxes
* RST-invariant moment-based feature extraction and feature analysis 
* Distance based supervised learning for image classification



## Project 2: Line and Circle detection based on Hough Transform

This project consist of the implementation of lines and circles detection program using Hough Transform. This project is the extension of the Object detecting and classifying application’s components. The processes that are implemented in this project are:

* Smoothing
	* Gaussian Blur(Gaussian Smoothing)
* Edge Detection
  	* Sobel Edge Detection
  	* Canny Edge Detection
  		* Non-maximum Suppression
  		* Hysteresis thresholding
* Hough Line Transform
* Hough Circle Transform


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
Linux Machine with QT5 Creator.

### Downloading
Cloning The GitHub Repository

```
git clone https://github.com/RajeshDgowda/App-Image-Processing.git
```

