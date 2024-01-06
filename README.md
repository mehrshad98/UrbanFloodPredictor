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

## Models Evaluation

### K-Nearest Neighbors (KNN) Classifier:
- **Accuracy:** 0.8394
- **Precision:** 0.88 (Class 0), 0.53 (Class 1)
- **Recall:** 0.94 (Class 0), 0.35 (Class 1)
- **F1-Score:** 0.91 (Class 0), 0.42 (Class 1)
- **Support:** 265947 instances of Class 0, 53127 instances of Class 1

### Logistic Regression Classifier:
- **Accuracy:** 0.8326
- **Precision:** 0.84 (Class 0), 0.47 (Class 1)
- **Recall:** 0.99 (Class 0), 0.04 (Class 1)
- **F1-Score:** 0.91 (Class 0), 0.07 (Class 1)
- **Support:** 265947 instances of Class 0, 53127 instances of Class 1

### Decision Tree Classifier:
- **Accuracy:** 0.8978
- **Precision:** 0.93 (Class 0), 0.73 (Class 1)
- **Recall:** 0.95 (Class 0), 0.62 (Class 1)
- **F1-Score:** 0.94 (Class 0), 0.67 (Class 1)
- **Support:** 265947 instances of Class 0, 53127 instances of Class 1

In summary, the Decision Tree classifier outperforms both K-Nearest Neighbors (KNN) and Logistic Regression in terms of accuracy and F1-Score on this dataset. It demonstrates higher precision and recall for both classes, indicating better overall performance.

## Usage
- Clone the code
- Customize the links to the dataset and models
- Run the code

## Author
**Mehrshad Alipoor**
@Jan 2024
