# Alzheimer Detection Model using CNN and ANN

## Project Overview
This project aims to develop an Alzheimer’s detection model using Convolutional Neural Networks (CNN) and Artificial Neural Networks (ANN). It includes advanced preprocessing and image segmentation techniques to isolate brain regions and optimize model predictions. An interactive interface was created using Streamlit for real-time prediction.

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Model Architecture](#model-architecture)
4. [Preprocessing and Segmentation](#preprocessing-and-segmentation)
5. [Hyperparameter Optimization](#hyperparameter-optimization)
6. [Streamlit Interface](#streamlit-interface)
7. [Results](#results)
8. [Installation](#installation)
9. [Usage](#usage)
10. [Future Work](#future-work)
11. [Contributing](#contributing)
12. [License](#license)

## Introduction
This project was conducted as part of an internship at ASM in Sfax, Tunisia. The objective was to create a model capable of detecting Alzheimer’s through image analysis. The CNN and ANN models were trained to predict Alzheimer’s status based on brain scans.

## Dataset
The dataset consists of MRI scans labeled for Alzheimer’s. Preprocessing was conducted to normalize and segment relevant brain areas for accurate prediction.

## Model Architecture
- **Convolutional Neural Network (CNN)**: Extracts features from brain images.
- **Artificial Neural Network (ANN)**: Complements the CNN model for classification.

## Preprocessing and Segmentation
Detailed preprocessing steps were applied, including normalization and segmentation to isolate critical brain regions.

## Hyperparameter Optimization
Hyperparameters were tuned to improve model accuracy and reduce overfitting.

## Streamlit Interface
An interactive interface using Streamlit allows users to upload MRI scans and receive predictions in real-time.

## Results
The optimized model achieved high accuracy, with the Streamlit interface providing accessible predictions.

## Installation
```bash
git clone https://github.com/your-username/Alzheimer-Detection-Model.git
cd Alzheimer-Detection-Model
pip install -r requirements.txt
