# Alzheimer's Disease Classification  

This repository contains the implementation of a project focused on classifying MRI and fMRI images into three categories:  
- **Alzheimer's Disease (AD)**  
- **Mild Cognitive Impairment (MCI)**  
- **Normal Control (NC)**  

The dataset used for this project is sourced from the **Alzheimer's Disease Neuroimaging Initiative (ADNI)**.  

## Key Contributions  

### 1. **Preprocessing of MRI and fMRI Images**  
- Performed **image registration**, **segmentation**, and **skull stripping** to enhance data quality.  
- Applied **normalization**, **motion correction**, and **noise reduction** techniques for consistent image analysis.  

### 2. **Feature Extraction**  
- Extracted features from **MRI** images, including image histograms and 3D representations.  
- Processed **fMRI** data using histograms, connectivity matrices, and spatio-temporal features.  

### 3. **Model Development and Classification**  
- Developed and ensembled the following models for optimal classification:  
  - **Classical Machine Learning (ML) Models**  
  - **Multilayer Perceptrons (MLPs)**  
  - **2D Convolutional Neural Networks (CNNs)**  
  - **3D Convolutional Neural Networks (CNNs)**  
  - **Eidetic 3D Long Short-Term Memory (LSTM) Models**  

## Results  
This approach provided effective classification performance by leveraging advanced preprocessing techniques and combining multiple machine learning and deep learning architectures.  

## Usage  
For a detailed walkthrough of the code, datasets, and implementation, refer to the files and scripts in this repository
