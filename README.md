# End-of-Module Assignment: Predicting Atmospheric Emissions

**CSCK503 Machine Learning in Practice - End Module Assignment**

---

## Table of Contents

- Introduction
- Dataset
- Repository Setup
- Environment Setup
- Running the Notebooks
  - Data Preprocessing
  - Machine Learning Models
  - Model Evaluation
- Troubleshooting
- Group Information
- License

---

## Introduction

Welcome to our **End-of-Module Assignment: Predicting Atmospheric Emissions** for the CSCK503 Machine Learning in Practice. This project focuses on building machine learning models to predict atmospheric emissions using data from the London Atmospheric Emissions Inventory (LAEI) 2019.

---

## Dataset

The dataset used for this project is sourced from the London Datastore. You can access the data through the following link, but it is also uploaded in this repository under data/raw:

- **LAEI 2019 Emissions Summary including Forecast**: [Download Dataset](https://data.london.gov.uk/download/london-atmospheric-emissions-inventory--laei--2019/17d21cd1-892e-4388-9fea-b48c1b61ee3c/LAEI-2019-Emissions-Summary-including-Forecast.zip)

---

## Repository Setup

Clone the GitHub repository to get a copy of the project code:

    git clone https://github.com/THarmse/End_of_Module_Assignment_Predicting_Atmospheric_Emissions.git

---

## Environment Setup

### Prerequisites

- **Python 3.11** (Do not use versions above 3.11)

### Installation Steps

1. **Ensure Pip is Upgraded**

       python -m ensurepip --upgrade

2. **Install Setuptools**

       pip install setuptools

3. **Upgrade Pip**

       python -m pip install --upgrade pip

4. **Install Required Packages**

       pip install xlsxwriter
       pip install xgboost

### Git Large File Storage (LFS) Setup

1. **Download Git LFS**

   - Official Site: https://git-lfs.github.com/

2. **Install Git LFS**

   - Run the installer you downloaded.

3. **Initialize Git LFS**

       git lfs install

4. **Restart Your Development Environment**

   - If you're using Visual Studio or another IDE, restart it to apply changes.

### Install Project Requirements

1. **Navigate to the Project Folder**

   - Ensure you're in the directory containing `requirements.txt`.

2. **Install Dependencies**

       pip install -r requirements.txt
       pip install --upgrade pandas

---

## Running the Notebooks

### Open Jupyter Notebook

- Launch Jupyter Notebook or JupyterLab to run the project notebooks.

### Data Preprocessing

Data preprocessing is done once before training the models.

1. **Open the Preprocessing Notebook**

   - `notebooks/data/preprocess.ipynb`

2. **Trust the Notebook**

   - Go to **File** -> **Trust Notebook**

3. **Run the Notebook**

   - Execute all cells to preprocess the data.

### Machine Learning Models

We will train and evaluate the following three machine learning models:

1. **XGBoost**
2. **random_forest** 
3. **svr** 

#### Steps to Run Each Model

1. **Open the Model Notebook**

   - For XGBoost: `notebooks/models/xgboost.ipynb`
   - For Random Forest: `notebooks/models/random_forest.ipynb`
   - For SVR: `notebooks/models/svr.ipynb`

2. **Trust the Notebook**

   - Go to **File** -> **Trust Notebook**

3. **Run the Notebook**

   - Execute all cells to train the model.

### Model Evaluation

After training, evaluate each model's performance.

1. **Open the Evaluation Notebook**

   - For XGBoost: `notebooks/models/xgboost_model_evaluation.ipynb`
   - For Model 2: `notebooks/models/random_forest_model_evaluation.ipynb`
   - For Model 3: `notebooks/models/svr_model_evaluation.ipynb`

2. **Trust the Notebook**

   - Go to **File** -> **Trust Notebook**

3. **Run the Notebook**

   - Execute all cells to evaluate the model.

---

## Troubleshooting

If you encounter errors related to `openpyxl` or other dependencies, follow these steps:

1. **Activate Conda Environment**

       conda activate <environment_name>

2. **Install Openpyxl**

       conda install -c conda-forge openpyxl

3. **Restart Jupyter Kernel**

   - In Jupyter Notebook, go to **Kernel** -> **Restart Kernel**

---

## Group Information

This project was developed by **University of Liverpool Group C**.


