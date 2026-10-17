# industrial-predictive-maintenance
Industrial predictive maintenance using Python, sensor data, Random Forest, and automated failure alerts.
# Industrial Predictive Maintenance Using Random Forest

## Overview

An end-to-end machine learning project exploring how industrial sensor measurements can be used to classify machine failure records and generate maintenance alerts.

## Business Problem

Unexpected equipment failures can cause production downtime and repair costs. This project investigates whether sensor readings can help identify failure-related patterns and support maintenance prioritization.

## Dataset

- **Source:** [UCI AI4I 2020 Predictive Maintenance Dataset](https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset)
- **Size:** 10,000 observations
- **Features:** Air temperature, process temperature, rotational speed, torque, tool wear, and machine type
- **Target:** Machine failure
- **Data type:** Synthetic industrial data

## Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Joblib
- Google Colab
- GitHub

## Methodology

1. Data inspection and quality validation
2. Duplicate and data-type checks
3. Exploratory Data Analysis
4. Feature engineering
5. Train-test splitting
6. Random Forest classification
7. Model evaluation
8. Feature importance analysis
9. Automated failure-risk scoring and alert reporting

## Evaluation

The model is evaluated using precision, recall, F1-score, ROC-AUC, average precision, and a confusion matrix.

**Results:** Add the actual metrics produced by the notebook.

## Automation

The pipeline scores sensor records, applies a configurable demonstration threshold, and exports a maintenance alert report.

## Limitations

The dataset is synthetic, and the target indicates a recorded failure rather than a future failure over a defined time horizon. The model has not been validated on live industrial equipment and should not be used as a safety-critical decision system.

## Reproducibility

1. Download the dataset from UCI.
2. Open the notebook in Google Colab.
3. Upload the CSV when prompted.
4. Run the notebook cells in order.
5. Review the metrics and exported maintenance report.

## Data Attribution

Dataset: AI4I 2020 Predictive Maintenance Dataset, UCI Machine Learning Repository. DOI: [10.24432/C5HS5C](https://doi.org/10.24432/C5HS5C). Licensed under CC BY 4.0.

## Author

Business Analytics & IT Student
