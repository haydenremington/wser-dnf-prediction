# Predicting Systemic Biological Failure in Ultramarathons 

## Overview
This repository contains the Python machine learning pipeline and final engineering report for predicting Did Not Finish (DNF) outcomes in the Western States 100-Mile Endurance Run (WSER). 

Traditionally, medical interventions in ultramarathons are completely reactive. This project utilizes 20 years of historical race telemetry (2004 to 2025) to shift to a proactive model. By quantifying early-race pacing degradation and combining it with environmental stressors, the predictive engine can identify a systemic biological crash before it becomes irreversible.

## Repository Contents
* **`pipe_WSER_final.ipynb`**: The main Jupyter Notebook containing the data extraction pipeline, feature engineering, and model training.
* **`Predicting_Systemic_Biological_Failure_Report.pdf`**: The comprehensive final project report detailing the methodology, threshold optimization, and physiological findings.

## Key Findings
1. **Biomechanics Override Weather:** Internal pacing degradation through the high country is a significantly better predictor of late-stage failure than the raw ambient heat itself.
2. **Threshold Optimization:** The algorithmic decision boundary was empirically tuned to 63% confidence, mathematically maximizing the clinical balance between safety nets and false alarms (F1-Score).
3. **Optimal Deployment:** Spatial analysis identified Michigan Bluff (Mile 55) as the mathematically ideal location for predictive medical intervention.

## Technologies Used
* Python (Pandas, NumPy)
* Scikit-Learn (Random Forest Classifier, Logistic Regression)
* Matplotlib (Data Visualization)

## How to Run the Code
1. Clone this repository to your local machine.
2. Ensure you have the required libraries installed in your Python environment.
3. Run the Jupyter Notebook to view the data pipeline, threshold tuning, and the live race-day prediction engine.
