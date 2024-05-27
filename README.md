# Stellar Classification
Welcome to the Stellar Classification repository! This project was completed by an astronomy enthusiast and focuses on classifying stars, galaxies, and quasars based on their properties such as temperature, luminosity, and spectral class using data analysis and machine learning techniques.

<img alt="Capture d’écran 2024-05-27 à 23 18 19" src="https://github.com/dianasolangel/Stellar-Classification/assets/87640597/ce8de78d-2ddc-4d37-a301-566bf47a4de8">

Credit: Hubble Ultra Deep Field NASA, ESA, and S. Beckwith (STScI) and the HUDF Team


## Overview

Stellar classification is a fundamental task in astrophysics, helping astronomers understand the evolution, structure, and composition of celestial objects. This project applies various data science and machine learning methods to classify galaxies and stars from observational data.

## Dataset

The dataset used in this project includes several attributes related to each object, captured through different spectral filters and measurement techniques:

- **Photometric System Filters (`u, g, r, i, z`)**: Magnitude measurements across five different filters from ultraviolet (u) to infrared (z).
- **Spectroscopic ID (`spec_obj_ID`)**: Unique identifier for spectroscopic objects, essential for distinguishing different observations.
- **Redshift (`redshift`)**: Indicates the increase in wavelength due to the universe's expansion.
- **Observation Details (`plate, MJD, fiber_ID`)**: Logistical details including the plate number, modified Julian date, and fiber ID used during observation.

These columns provide the necessary features for our machine learning models to classify the celestial objects.

## Classification Categories

The project classifies objects into three categories:
1. **Stars**
2. **Galaxies**
3. **Quasars**

## Methodology

The analysis workflow includes several key steps:

1. **Data Loading and Exploration**: Initial assessment of the dataset to understand the distribution and nature of the data.
2. **Data Preprocessing**: Cleaning and normalizing data to ensure quality input for modeling.
3. **Model Building**:
   - **Machine Learning Models**:
     - `RandomForestClassifier`: An ensemble method based on decision trees.
     - `DecisionTreeClassifier`: A base model that uses a tree-like model of decisions.
     - `GradientBoostingClassifier`: An ensemble model that optimizes on a loss function.
     - `SVC()`: Support vector machine for classification.
   - **Deep Learning Model**: A neural network approach designed to handle the complexity and depth of the data.
4. **Model Evaluation**: Comparing the models to determine the best performer based on accuracy and other metrics.

## Conclusion

This project showcases the effective use of machine learning in the field of astrophysics, particularly in the classification of astronomical objects. It is interesitng to see how by using data science and machine learning we can study the Universe. 

