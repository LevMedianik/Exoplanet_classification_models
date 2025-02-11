# Exoplanet_classification_models
## Overview
This work is about three simple machine learning model to classify exoplanets by discovery method. Models are based on Naive Bayes, Decision Trees and Random Forest architectures. All models are trained on NASA Exoplanet Achive dataset (URL: https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=PS) containing various planetary/stellar characteristics (radius, mass, etc...). These models can predict Exoplanet discovery method based on planetary and solar characteristics. For building these models, planets.csv dataset was utilized with its preprocessing and creating a separated file of planets_clean.csv representing clear dataset with noise reduction. This work is only for Google Colab.
Dataset

Raw Data: planets.csv

Processed Data: planets_clean.csv (after noise reduction and preprocessing)

Features Used

Planetary Features: Radius, density, eccentricity, equilibrium temperature, orbital period

Stellar Features: Effective temperature, mass, radius, surface gravity, density

Discovery Information: Year, method, distance from Earth

Preprocessing Steps

Renamed column titles for clarity

Visualized key characteristics with scatter plots, bar charts, and pair plots

Identified and removed missing values and duplicates

Encoded categorical variables using Label Encoding & Factorization

Balanced the dataset using SMOTE (Synthetic Minority Over-sampling Technique)

Data Visualization

Scatterplots: Planet radii vs. planet names

Bar Charts: Discovery methods distribution, recent discoveries (2010-2024)

Pair Plots: Relationship between planetary and stellar features

KDE Plots: Distribution of discovery methods

Machine Learning Models

Each model is trained and evaluated on the preprocessed dataset:

Naïve Bayes: Probabilistic classifier assuming feature independence

Decision Trees: Tree-based classification model

Random Forest: Ensemble learning with multiple decision trees

Usage

Google Colab

This project is designed for execution in Google Colab.

Run the Notebook

Upload planets.csv to Google Colab.

Run the preprocessing steps.

Train and evaluate models.

Download the processed dataset (planets_clean.csv).
