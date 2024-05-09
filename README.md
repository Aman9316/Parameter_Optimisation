# Parameter_Optimisation

Overview

Methodology

Data Loading: The Dry Bean Dataset is loaded using the UCI ML Repository API.
Data Preprocessing: The dataset is split into features (X) and target (y). A train-test split is performed for model evaluation.
Model Selection: A Nu-Support Vector Classifier (NuSVC) with Bayesian Optimization is employed to optimize hyperparameters.
Model Evaluation: The model's accuracy is evaluated using cross-validation and convergence plots.
Result Analysis: The best hyperparameters and accuracy obtained are analyzed.
Dataset Description

The Dry Bean Dataset comprises various attributes of dry beans, including geometric, shape, and texture attributes, used for bean classification.

Features

The dataset includes the following features:

Area
Perimeter
MajorAxisLength
MinorAxisLength
AspectRatio
Eccentricity
ConvexArea
EquivDiameter
Extent
Solidity
Roundness
Compactness
ShapeFactor1
ShapeFactor2
ShapeFactor3
ShapeFactor4
Target

The target variable represents the class of the dry bean.

Data Exploration

Basic exploratory data analysis is performed.
