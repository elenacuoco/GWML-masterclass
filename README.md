# GWML-masterclass

This repository contains materials for the advanced class "Big Data within Science and Industry," which will take place on September 22, 2023, at the University of Milano-Bicocca in Milan, Italy.

**Class Information:** [Big Data within Science and Industry](https://sites.google.com/unimib.it/bigdatamasterclassTutorials)

## Overview
 
In this class, you will have access to notebooks and  resources designed to guide you through the fascinating field of Gravitational Wave (GW) analysis. Our primary focus will be on two key aspects:

## 1. Gravitational Wave Data Preprocessing

Before diving into the intricate world of GW data analysis, we'll start by understanding the importance of data preprocessing. This fundamental step involves cleaning, formatting, and organizing the raw GW data to make it suitable for further analysis. You will learn how to:

- Clean noisy data.
- Correct for instrumental artifacts.
- Prepare data for feature extraction and model training.

## 2. Machine Learning Applications in GW Analysis

The second part of our tutorial delves into the realm of machine learning applied to GW data.  Throughout this class, you'll explore:

- Supervised machine learning algorithms.
- Feature engineering for GW signal detection.
- Implementing machine learning models for classification tasks.

## The Challenge: Classifying Transient Signals from Core Collapse Supernovae (CCSN)

As a hands-on project, we will tackle a real-world challenge in the field of GW analysis. Our goal is to develop a Convolutional Neural Network (CNN) model that can classify transient signals generated by different mechanisms of GW emission during Core Collapse Supernovae (CCSN).  


### Acknowledgments

Thanks to **Alberto Iess** for providing the time series dataset for this project.

**Contact:** Alberto Iess, alberto.iess@sns.it

## Requirements

Before you start, make sure you have the following prerequisites:

# Python Environment Setup

To successfully work on the tasks and projects in this course, you need to have a Python environment with the necessary packages installed. If you don't already have this environment set up on your computer, follow these instructions:

## Setting Up Python Environment

### For Windows:

1. Connect to the [Anaconda Installation Guide](https://docs.anaconda.com/free/anaconda/install/windows/).
2. Download the Anaconda installer from [Anaconda Downloads](https://repo.anaconda.com/archive/Anaconda3-2023.07-2-Windows-x86_64.exe).

### For Linux:

1. Open your terminal.
2. You have the option to install either Anaconda or Miniconda, depending on your preference:
   - To install Anaconda, refer to the [Anaconda Installation Guide for Linux](https://docs.anaconda.com/free/anaconda/install/linux/).
   - To install Miniconda, a lightweight alternative, follow the [Miniconda Installation Guide for Linux](https://docs.conda.io/en/latest/miniconda.html#linux-installers).

3. After successfully installing Anaconda or Miniconda, proceed with creating a Python environment for this project.

### Create a Conda Environment:

In your terminal, run the following commands:

1. Create a new Conda environment (replace `env_name` with your preferred environment name and Python version if necessary):
   ```shell
   - conda create --name env_name python=3.10
   - conda activate env_name

2. pip install numpy pandas matplotlib jupyter tqdm


3. Once installed, you can launch a Jupyter Notebook.

### Required Packages

You will need to install specific packages required for the tasks to be solved. You can do this by running the following commands in a Jupyter Notebook cell:

```python
!pip install gwpy
!pip install statsmodels
!pip install tensorflow
!pip install scikit-learn






