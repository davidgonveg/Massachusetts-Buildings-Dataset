# Massachusetts Buildings Dataset - Image Segmentation

## Overview
This notebook demonstrates the use of a U-Net deep learning model to perform image segmentation on the Massachusetts Buildings Dataset. The primary goal is to identify and segment buildings in satellite images. Two main approaches are detailed:
1. Using whole images directly.
2. Using crops of images to increase dataset size and potentially improve model performance by avoiding large blank spaces.

## Requirements
- Ensure that all images are located in a working directory under a folder named `images`.

## Solution Summary
- **Resizing Images**: The model has been adapted to handle various image sizes to compare performance, with larger images generally yielding better results.
- **Cropping Strategy**: Instead of resizing images, crops of the desired size are made to create a larger dataset. This approach helps to handle images with large blank areas more effectively.
- **One Hot Encoding**: Applied to the images to facilitate model processing.

## How to Use
- The notebook is fully executed with results visible directly. Re-execution is not required to view the outcomes unless modifications are made.

## Visualization
- Visual comparisons of images from different dataset splits are provided to understand the variations in image types and quality.

## Additional Notes
- The solution includes a detailed step-by-step implementation of the U-Net model, from data preparation to training and evaluating the model.
