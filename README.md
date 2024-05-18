# steller-classification
##Project Overview
This project aims to develop a classification model that can accurately identify celestial objects—specifically stars, galaxies, and quasars—based on their spectral characteristics. Using a dataset of 100,000 observations from the Sloan Digital Sky Survey (SDSS), the model will be trained to differentiate between these objects and generalize well to new, unseen data, providing reliable predictions for new observations.
##Source
Sloan Digital Sky Survey (SDSS): A comprehensive survey of space, providing detailed imaging and spectroscopic data of celestial objects.
##Description
Total Observations: 100,000
Features: Spectral characteristics of celestial objects.
Classes:
Stars
Galaxies
Quasars
Celestial-Object-Classification/
│
├── data/
│   ├── raw/                      # Raw dataset from SDSS
│   ├── processed/                # Preprocessed dataset ready for modeling
│
├── notebooks/
│   ├── 01_data_exploration.ipynb # Exploratory data analysis
│   ├── 02_data_preprocessing.ipynb # Data cleaning and preprocessing
│   ├── 03_model_training.ipynb   # Model training and evaluation
│   ├── 04_model_testing.ipynb    # Testing model on unseen data
│
├── src/
│   ├── data_preprocessing.py     # Data preprocessing scripts
│   ├── model_training.py         # Model training scripts
│   ├── model_evaluation.py       # Model evaluation scripts
│   ├── utils.py                  # Utility functions
│
├── models/
│   ├── trained_model.pkl         # Trained model file
│
├── README.md                     # Project overview and instructions
├── requirements.txt              # Required packages and dependencies
├── setup.py                      # Package setup script
│
└── .gitignore                    # Files and directories to be ignored by git

uses differnet differnt CLASSIFIER for training
