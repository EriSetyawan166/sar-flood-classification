# SAR Flood Classification with SAR Image Analysis and Conversion

This repository contains code and notebooks for SAR (Synthetic Aperture Radar) flood classification. It includes a Jupyter Notebook for SAR image analysis and classification using a 3D convolutional neural network (CNN), as well as a notebook for converting BMP images to NIfTI format.

## SAR Image Analysis and Classification

The `SAR_3D_CNN.ipynb` notebook demonstrates how to preprocess SAR images, build a 3D CNN model, train the model using flood and non-flood images, and evaluate its performance. It provides a step-by-step guide to understand and apply SAR image classification techniques.

## BMP to NIfTI Conversion

The `convert_into_nii.ipynb` notebook showcases the conversion of BMP images to NIfTI format. It utilizes the PIL (Python Imaging Library) and nibabel libraries to read BMP images, create 3D NIfTI volumes, and save them in the output directory. This conversion process is useful for integrating BMP image data into SAR analysis workflows.

## Usage

1. Download the respective Jupyter Notebook files (`SAR_3D_CNN.ipynb` and `convert_into_nii.ipynb`) from this repository.
2. Open the notebooks in your preferred Jupyter Notebook environment (e.g., Jupyter Notebook, JupyterLab).
3. Follow the instructions and run the code cells in the notebooks to understand the SAR flood classification techniques and BMP to NIfTI conversion process.
