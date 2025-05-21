# Hyperspectral Image Classification with Deep Learning

This repository contains the implementation of hyperspectral image classification using deep learning models combined with feature selection and extraction techniques. The study evaluates the performance of Fast-3D Convolutional Neural Networks (CNN) and Residual Neural Networks (ResNet) on Indian Pines and Salinas datasets.

## Objective

To enhance the accuracy and computational efficiency of hyperspectral image classification by applying advanced feature engineering methods within deep learning architectures.

## Methods

The project involves the following key components:

* Feature Selection Methods: CFS, MIFS, LDA, RFE
* Feature Extraction Methods: PCA, IPCA, QDA, NMF
* Deep Learning Models: Fast-3D CNN and ResNet
* Evaluation Datasets: Indian Pines and Salinas Hyperspectral Datasets

## Folder Structure

* src/: Contains the Google Colab Notebook .
* datasets/: Provides instructions for downloading datasets.
* figure/: Contains the Methodology diagram .
* results/: Includes accuracy , computational time comparisons graphs , and an Excel summary file.
* requirements.txt: Lists Python libraries required to run the notebook.

## Datasets

This project uses the following publicly available hyperspectral datasets:

* Indian Pines
* Salinas

Download the .mat files and place them in your working directory before running the notebook.

## How to Run

1.  Install dependencies
2.  Open and run the notebook
3.  Ensure that the datasets are available in the expected path.

## Results

- Accuracy & Compuational Time Comparison graphs results are saved in the results/ folder.
- A comparison across CNN and ResNet architectures with 8 feature engineering techniques is provided in accuracy_summary.xlsx.
