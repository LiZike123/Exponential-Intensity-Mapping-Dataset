# Exponential-Intensity-Mapping-Dataset
# Exponential-Intensity-Mapping-Dataset

## Project Overview
This repository contains the code for the paper **"Exponential Intensity Mapping: Enhancing Grayscale Stability in High-Temperature Forging Images"** published in *The Visual Computer*. The project aims to improve grayscale stability in high-temperature forging images through exponential intensity mapping techniques.

## Dependencies
This project requires the following dependencies:

- Python
- numpy
- opencv-python

You can install the required dependencies using pip:

```bash
pip install -r requirements.txt

Files and Folders

The repository contains the following files and folders:

FunctionImplementationAndComparison.ipynb: Compares images before and after mapping, visually demonstrating the performance of the preprocessing technique.

ParamsMandC.ipynb: Extracts the parameters m and c from 30 images based on the formula.

validation.ipynb: Performs validation on 79 images for quantitative analysis.

Additionally, large files are hosted on Baidu Netdisk:

allp folder: Contains all images.

calib folder: Contains 30 experimental images used for extracting m and c.

code folder: Contains all the code files.

Label folder: Contains the manually annotated contours of 79 images to assist in analyzing region-growing coverage and Canny edge detection.

Val folder: Contains the 79 validation images.

Downloading Large Files

Due to size limitations on GitHub, the following dataset files are hosted on Baidu Netdisk. You can download them from the link below:

Download Link: Exponential-Intensity-Mapping-Dataset.zip

Extract Code: eimm

The total size of the files is approximately 1.46 GB.

Usage

After downloading the necessary files, you can use the following Jupyter notebooks to explore and analyze the dataset:

FunctionImplementationAndComparison.ipynb: Use this notebook to compare images before and after applying the intensity mapping technique.

ParamsMandC.ipynb: This notebook will allow you to extract the parameters m and c from 30 images.

validation.ipynb: This notebook is for validating the results on 79 images to perform quantitative analysis.

License

The project is licensed under the terms provided in the LICENSE file.

Contributing

Contributions to this project are welcome! Please fork the repository and submit a pull request with your changes.


This `README.md` file provides an overview of the project, installation instructions, file descriptions, and usage instructions for the notebooks. Let me know if you'd like to make any changes or additions!
