# ml-prediction-aerodynamic-heating-satellite-panel

# Machine Learning-Based Prediction of Satellite Solar Panel Temperature Using CFD

## Overview

This project combines **ANSYS thermal simulation** and **machine learning** to predict the temperature of a multilayer photovoltaic panel operating under Low Earth Orbit (LEO) conditions.

A steady-state thermal model was developed for a multilayer solar panel, followed by machine learning-based prediction using irradiation and ambient temperature.

## Objectives

* Perform steady-state thermal analysis of a multilayer solar panel under LEO conditions.
* Generate and analyse temperature data.
* Train and compare different regression models.
* Evaluate model performance using R², MAE and RMSE.
* Develop an interactive thermal prediction dashboard.

## Thermal Model

The photovoltaic panel model consists of multiple layers including:

* ETFE
* EVA
* Silicon
* PET
* CFRP
* Aluminium frame

The model considers thermal behaviour under high solar irradiation and vacuum conditions.

## Machine Learning Models

Six regression models were evaluated:

* Multiple Linear Regression
* Support Vector Regression
* K-Nearest Neighbours
* Decision Tree
* AdaBoost
* Random Forest

The input features were:

* Solar irradiation
* Ambient temperature

The target variable was:

* Maximum panel temperature

## Results

The models were evaluated using 5-fold cross-validation and test-set performance.

The Multiple Linear Regression model achieved:

* **Test R² = 0.9641**
* **MAE = 3.4251 K**
* **RMSE = 4.3028 K**

The dataset contained **1,757 samples**.

## Repository Contents

```text
├── README.md
├── Report/
│   └── CFS_Project_Report.pdf
├── ANSYS/
├── ML/
├── Dataset/
├── Dashboard/
└── Results/
```

## Tools

* ANSYS Mechanical
* Python
* Machine Learning
* Thermal analysis
* Regression modelling
* Data visualization

## Report

The complete project report is available in the `Report` folder.

## Authors

**Jaajimoggala Ramaraju**
Mechanical Engineering, IIT Indore
