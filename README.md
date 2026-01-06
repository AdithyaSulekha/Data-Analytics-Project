# Data-Analytics-Project
# Analyzing and Predicting Social Anxiety Patterns Using Behavioral and Demographic Data
## Abstract
**This project analyzes a synthetic dataset of 11,000 individuals to explore how behavioral, physiological, and lifestyle factors influence social anxiety. The workflow includes comprehensive data preprocessing, feature engineering, visualization, and both regression and classification modeling. Multiple machine learning methods were evaluated, including Linear Regression, Random Forest, XGBoost, an ANN regressor, and ensemble approaches such as soft voting and stacking. Among all models tested, the Stacking Classifier achieved the highest accuracy for predicting binned anxiety levels, demonstrating the strongest overall predictive performance. The final pipeline is fully reproducible, covering every stage from data preparation to model training, visualization, and evaluation.**

## Installation Instructions:
Before running the code, install all dependencies.
You can install them manually or use the provided environment instructions.

## How to Run the Analysis:
1.  Click the "play" button (▶️) next to each gray code box
2.  Watch Python do the calculations and create charts
3.  Focus on the results

## How to Reproduce the Results (Step-by-Step):

**Step 1. Download the Dataset *enhanced_anxiety_dataset.csv***
>Place the dataset file enhanced_anxiety_dataset.csv in your working directory.

**Step 2. Run Data Preprocessing**
>This step:
>-   Loads data
>-   Handles missing values
>-   Maps categorical Yes/No, Gender
>-   One-hot encodes Occupation
>-   Computes correlations
>-   Performs engineered features

**Step 3. Train Models**
>Included models:
>- Linear Regression
>- Random Forest Regressor
>- XGBoost Regressor
>- Artificial Neural Network (ANN)
>- Stacking
>- Soft voting

**Step 4. Generate figures & tables**
> Running the scripts will automatically generate:
> - Correlation heatmaps
> - Feature-importance plots
> - Training curves
> - Predicted vs. actual plots
> No manual steps are required.

**Step 5. View Performance Metrics**
> Metrics include:
> -   RMSE
> -   MAE
> -   R²
> -   Model comparison tables

## Key Components

### **Data Preprocessing**
-   Imports libraries
-   Loads dataset
-   Applies transformations
-   Checks for missing values
-   Performs correlation analysis
-   Creates engineered features

### **Feature Engineering**

Creates new features capturing:
-   Behavioral interactions
-   Physiological responses

### **Model Training**
Implements:
-   Linear Regression
-   Random Forest
-   XGBoost
-   ANN
    Includes performance plots and summaries.

### **Evaluation**
-   Computes metrics
-   Generates model comparison visualizations

## Reproducibility

All steps—from importing data to training models and generating visualizations—are fully automated within the notebook.
