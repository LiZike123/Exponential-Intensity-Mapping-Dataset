
# Exponential Intensity Mapping

## Project Overview
This repository contains the code for the paper **"Exponential Intensity Mapping: Enhancing Grayscale Stability in High-Temperature Forging Images"** published in *The Visual Computer*. 

## Dependencies
This project requires the following dependencies:

- Python
- numpy
- opencv-python
## Installation

Follow the steps below to set up the environment and run the code:

1.  **Clone the Repository**
    ```bash
    git clone https://github.com/LiZike123/Exponential-Intensity-Mapping-Dataset.git
    cd Exponential-Intensity-Mapping-Dataset
2.  **Install Dependencies**
    ```bash
    pip install -r requirements.txt
3.  **Download Large Files**
    Due to GitHub file size limits, the dataset and additional resources are hosted on Zenodo:
    
    All figures are available on Zenodo with DOI: https://doi.org/10.5281/zenodo.18593835
    
The Zenodo package includes the following folders:

allp: Contains all images used in the paper.

calib: 30 experimental images for extracting parameters m and c.

code: All code files associated with the project.

Label: Manually annotated contours of 79 images (for region-growing coverage and Canny edge detection analysis).

Val: 79 validation images for quantitative analysis.
    
After downloading, extract the files and place them in the project directory to ensure the notebooks can access the data correctly.
## Files and Folders
The core code files in this repository (GitHub) are:

FunctionImplementationAndComparison.ipynb: Compares images before/after mapping, visualizing the preprocessing performance.

ParamsMandC.ipynb: Extracts parameters m and c from 30 experimental images based on the proposed formula.

validation.ipynb: Validates the method on 79 images for quantitative analysis.

## Downloading Large Files
Due to size limitations on GitHub, the following dataset files are hosted on Zenodo. You can download them from the link below:
https://doi.org/10.5281/zenodo.18593835
The total size of the files is approximately 1.6 GB.

## Usage
After downloading the necessary files, you can use the following Jupyter notebooks to explore and analyze the dataset:

FunctionImplementationAndComparison.ipynb: Use this notebook to compare images before and after applying the intensity mapping technique.

ParamsMandC.ipynb: This notebook will allow you to extract the parameters m and c from 30 images.

validation.ipynb: This notebook is for validating the results on 79 images to perform quantitative analysis.

## License
The project is licensed under the terms provided in the LICENSE file.

## Contributing
Contributions to this project are welcome! Please fork the repository and submit a pull request with your changes.

## Contact
If you have any questions about our work or code, please email niuliqun111@126.com .

## Citation
If you find this work useful in your research, please consider citing our paper:
```bash
    @article{niu2026exponential,
    author    = {Liqun Niu and Zike Li and Xuming Wang and Bingzheng Wang and Zhenglong Liang},
    title     = {Exponential Intensity Mapping: Enhancing Grayscale Stability in High-Temperature Forging Images},
    journal   = {The Visual Computer},
    year      = {2026},
    publisher = {Springer}
}



