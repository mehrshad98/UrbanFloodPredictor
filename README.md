# UrbanFloodPredictor
Multi Label Classification Approach for Flood Outcome Prediction in Houston, TX

## Overview
This is my Final Project of Machine Learning Course @ Polimi_2023_24 

## Dataset
Descrription of the dataset and its columns:

- **ObservationIndex:** An identifier for the observation.
- **SurfaceType:** Type of urban surface.
- **Waterflow:** Intensity and duration of water flow.
- **InitialWaterLevels:** Pre-simulation underground water level.
- **DrainageSystemCapacity:** Indicator of drainage efficiency.
- **GreenSpaceRatio:** Proportion of greenery in the urban area.
- **head_id:** ID of the head node.
- **tail_id:** ID of the tail node.
- **flooded_init:** Whether the edge was initially flooded.
- **flooded_final:** Whether the edge was flooded after the simulation (target variable).

- You can find a complete dataset for this project here: [Dataset](https://drive.google.com/drive/folders/1JqYgHdtN7MsMO2df0E2LSJk3K323sRun?usp=sharing)

## Goal
The goal is to build a data-driven model to predict the 'flooded_final' column for each sample in the test set.

## Predictive Model
**Decision Tree Classifier:**
Chose Decision Tree Classifier for its interpretability and ability to handle non-linear relationships.

**Principal Component Analysis (PCA):**
Implemented PCA for dimensionality reduction, capturing essential information while reducing computational complexity.

**Logistic Regression:**
Used Logistic Regression as a baseline model for its simplicity and interpretability.

## Model Evaluation

**Accuracy:** 90%

**Confusion Matrix:**

|           | Predicted 0 | Predicted 1 |
|-----------|-------------|-------------|
| **Actual 0** | 207313      | 9714        |
| **Actual 1** | 16235       | 26538       |


**Classification Report:**

              precision |   recall  | f1-score

         0.0       0.93      0.96      0.94  
         1.0       0.73      0.62      0.67 

## Files
- **main_script.py:** Python script containing the predictive model.
- **notebook.ipynb:** Jupyter notebook with code and explanations.

## Usage
- Clone the code
- Customize the links to the dataset and models
- Run the code

## Author
**Mehrshad Alipoor**
@Jan 2024
