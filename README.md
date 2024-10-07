# Computer Vision Lab - Image Thresholding and Augmentation with OpenCV
This repository contains a notebook for performing various image processing tasks using OpenCV and NumPy in Python. It includes thresholding, image augmentation, denoising, and histogram equalization techniques.

## Project Overview
The project covers the following tasks:

Convert RGB Image to Grayscale: The original image is converted to grayscale.

Minimum and Maximum Pixel Intensity: The notebook computes the minimum and maximum pixel intensity values in the grayscale image.

Image Augmentation: Techniques such as flipping, rotating, or scaling the image to create variations.

Adjusted Image: The image is adjusted for brightness or contrast based on specific parameters.

Denoising the Image: Applying filters to remove noise and smooth the image.

Histogram of the Pixel Values: A histogram is generated to display the distribution of pixel intensities.

Equalized Image: Histogram equalization is applied to improve contrast.

Histogram for Equalized Image: The histogram of the equalized image is displayed.

CLAHE Image: Contrast Limited Adaptive Histogram Equalization (CLAHE) is applied to enhance image contrast.

Histogram for CLAHE Image: A histogram for the CLAHE image is generated.

Histogram for Denoised Image: The histogram of the denoised image is computed.

## Libraries Used
OpenCV for image manipulation and processing.

NumPy for efficient numerical operations.

Matplotlib for plotting histograms and visualizing images.

## Steps to Run the Notebook
Install the required libraries:

`!pip install opencv-python-headless numpy matplotlib`

Run the notebook in Jupyter or a compatible environment.
## Detailed Workflow
Image Loading: An RGB image is loaded using OpenCV.

Grayscale Conversion: The image is converted to grayscale for further processing.

Image Augmentation: Various transformations are applied to create multiple variations of the image.

Image Denoising: Noise is reduced using Gaussian filters.

Histogram Equalization: Applied to improve the contrast of the image.

CLAHE: Adaptive histogram equalization is applied to enhance local contrast while limiting noise amplification.

Histogram Visualization: Histograms are plotted for each image to visualize pixel intensity distributions.

## Results
### The notebook outputs the following images:

Original grayscale image.

Augmented image.

Denoised image.

Histogram equalized image.

CLAHE image.

## Usage
This notebook serves as a foundation for exploring basic and advanced image processing techniques such as thresholding, noise removal, and contrast enhancement. 
The code can be extended for more sophisticated computer vision tasks.

## Future Enhancements
Incorporate edge detection (e.g., using the Canny edge detector).

Add more complex image augmentations such as zoom, shear, and blur.

Implement adaptive thresholding techniques to automate the selection of threshold values.
