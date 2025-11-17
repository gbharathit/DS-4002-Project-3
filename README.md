# DS-4002-Project-3

This repository contains a dataset of images of different dog breeds, as well as scripts and outputs to accurately classify what breed a dog image is classified. Our project uses a CNN (Convolutional Neural Network) model, a type of deep learning model, to see how an image is classified as being a part of 7 different dog breeds. All images used, exploratory analyses, and model predictions are included to enable reproduction of all results. 

## Contents of this repository

This repository contains everything needed to reproduce the analyses and results for this project: image data for 7 different dog breeds, Jupyter notebooks for preprocessing and analysis, output plots, and model accuracy metrics. The sections below outline software requirements, repository structure, and step-by-step instructions to reproduce the results.


---

## Section 1: Software and Platform

*Software Used:*

* Python (version 3.8 or higher) for preprocessing, training, and evaluation of CNN models.
* Jupyter Notebook for scripting and interactive analysis.
* Git for version control and GitHub for hosting.

*Python Packages Required (install via pip or conda):*

* pytorch (for CNN modeling)
* numpy (numerical operations)
* pandas (data handling)
* matplotlib and seaborn (visualizations)
* scikit-learn (train/test splitting, metrics)
* opencv-python (image preprocessing)


## Section 2: Map of Documentation

*1. DATA Folder*

* Beagle/, FrenchBulldog/, GermanShepherd/, GoldenRetriever/, MiniaturePoodle/, Schnauzer/, ShihTzu/, SiberianHusky/ – Each folder contains PNG images of the corresponding breed.
* metadata.csv – CSV file containing image IDs and corresponding breed labels for reproducibility.

*2. OUTPUT Folder*

* classdistributionplot.jpg – Plot showing the number of images per breed.
* heightplot.png – Histogram of image heights across all images.
* widthplot.png – Histogram of image widths across all images.

*3. SCRIPTSFolder*

* ClassDistributionPlot.Rmd – Script used to create the class distribution plot.
* Histograms of Image Width and Height.ipynb – Script used to create the histograms of image height and widths.
* MI3_Modelupdated.ipynb – Notebook for building, training, and evaluating the CNN model.



## Section 3 – How to Reproduce Our Results

*Step 1: Get the Repository*

* Clone the repository using Git:

  bash
  git clone https://github.com/gbharathit/DS-4002-Project-3.git
  
* Or download it as a ZIP file and extract it.
* Open Jupyter Notebook and set your working directory to the project folder.

*Step 2: Make Sure the Data Files Are There*

* Ensure that all breed folders (Beagle/, FrenchBulldog/, etc.) and metadata.csv are in the same folder as the notebooks.
* These files are included in the repository, so no additional downloads are needed.

*Step 3: Install Python and Packages*

* Install Python (version 3.8 or higher) if not already installed.
* Install required packages:

  bash
  pip install tensorflow numpy pandas matplotlib seaborn scikit-learn opencv-python
  
*Step 4: Run the Analysis*

* Open ClassDistributionPlot.Rmd in R and Histograms of Image Width and Height.ipynb in Jupyter Notebook or Google Colab to explore the dataset.
* Open MI3_Modelupdated.ipynb to train the CNN model and evaluate predictions.
* Generated outputs include plots, metrics, and confusion matrices for model performance.

*Step 5: Troubleshooting*

* Make sure your working directory is set to the project folder.
* Ensure all image folders and metadata.csv are present.
* If issues occur, check your Python environment and package versions with:

  python
  !pip list

