# Binary Classification of Footwear

This project implements a k-fold cross-validation pipeline to train and evaluate machine learning models—specifically Support Vector Machines (SVMs) and Neural Networks—for binary classification tasks on footwear data.

## Overview

The code demonstrates a k-fold cross-validation approach to train various machine learning models. For this experimentation, SVMs with linear and Gaussian kernels were selected, along with a variety of neural networks featuring several hidden layer configurations.

## Features

- **k-Fold Cross-Validation**: Robust evaluation using k-fold cross-validation.
- **Support Vector Machines**: Implementation of SVMs with linear and Gaussian (RBF) kernels.
- **Neural Networks**: Training of neural networks with varying hidden layer configurations.
- **Performance Evaluation**: Assessment of model performance across different configurations.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python packages:
  - `numpy`
  - `scikit-learn`
  - `tensorflow` or `torch` (depending on your chosen framework)

You can install required packages with:

```bash
pip install -r requirements.txt
```
Note: A requirements.txt file is recommended but not included in the original repo. Consider creating one.

### Installation
Clone the repository:

```bash
git clone https://github.com/Pardo6604/Binary-Classification-of-Footwear.git
```
Navigate to the project directory:

```bash
cd Binary-Classification-of-Footwear
```
Ensure the following are in the same directory:

  - code.ipynb

  - moist_reader.py

  - fashion/ directory containing the dataset

If the dataset is elsewhere, update the path in the second cell of the notebook accordingly.

Usage
Open the notebook in Jupyter:

```bash
jupyter notebook code.ipynb
```
Run all cells to execute the training and evaluation pipeline.

Note: Some methods may take a considerable amount of time to execute. Optimization might not always converge depending on the model and parameters.

Project Structure
```bash
├── code.ipynb           # Main notebook containing the experiment
├── moist_reader.py      # Script for reading and preprocessing the data
├── fashion/             # Directory containing footwear dataset
├── report.pdf           # Report of findings and model comparisons
```

### Results
The report.pdf file provides a detailed overview of the conducted experiments, including model configurations, performance metrics, and result analysis.




# Binary Classification of Footwear
Cross-validation pipeline to train and test Neural Networks and SVMs.

The code shows a k-fold cross validation implemantation to train different ML models.
For this experimentation SVMs with linear and gausian kernels were selected together with a variety of neural networks with several hidden layers configuration.

Intructions to Code.ipynb:

1. Open Code.ipynb in a Jupyter enviroment

2. Make sure moist_reader.py and fashion are in the same directory as Code.ipynb or adjust the directory pat if necessary in the second cell instead of just "fashion".

3. Run all cells to execute the code and see the results.

Ps: Some of the methods took a very long time to execute and for some experimentations the optimization did not converged.
