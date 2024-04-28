# Discerning the Tumor Ecosystems in Colorectal Cancer (CRC) with Neural Networks

**Author:** Meenakshi Raja Mohan  
**Institution:** School of Informatics and Computing, Indiana University (IUPUI)  
**Date:** 27th April 2024

## Project Overview
This repository hosts the implementation of neural network models for analyzing spatial transcriptomics to identify distinct tumor ecosystems and predict patient survival in colorectal cancer. The project is divided into two main components:
1. **Identification of Cancer Ecotypes:** Utilizing Graph Convolutional Networks (GCN) and k-means clustering on spatial transcriptomics data.
2. **Survival Prediction:** Applying a neural network with a Cox proportional hazards layer using gene expression data from The Cancer Genome Atlas (TCGA).

## Installation

### Prerequisites
- python 3.9 or above
- pip

### Dependencies
Install all necessary Python libraries using pip:

pip install numpy pandas matplotlib scikit-learn pytorch optuna

## Usage

This project contains two primary scripts designed to analyze colorectal cancer data through advanced neural network models. Below are detailed instructions on how to use these scripts:

### Ecotypes Identification Script
- **Script Name:** `identify_ecotypes.py`
- **Purpose:** This script processes spatial transcriptomics data to identify distinct tumor ecosystems in colorectal cancer tissue using a combination of Graph Convolutional Networks (GCN) and k-means clustering.
- **How to Run:**
  python identify_ecotypes.py
  
  
  
### Survival Prediction Script
- **Script Name:** `survival_prediction.py`
- **Purpose:** Utilizes gene expression data from The Cancer Genome Atlas (TCGA) to train a neural network with a Cox proportional hazards layer for predicting patient survival.
- **How to Run:**
  python survival_prediction.py
