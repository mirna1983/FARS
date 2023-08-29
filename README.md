# Fatal Accident Reporting System (FARS) Data Analysis

## Project Overview

The goal of this project is to analyze the Fatal Accident Reporting System (FARS) dataset and develop a predictive model to classify accident severity levels. The FARS dataset contains information about various factors related to fatal traffic accidents in the United States.

## Project Steps

1. **Data Preprocessing:**
   - Loaded and examined the FARS dataset.
   - Handled missing values, duplicates, and inconsistent data entries.
   - Explored data types and converted columns where necessary.

2. **Exploratory Data Analysis (EDA):**
   - Visualized the distribution of accidents across different months using bar plots.
   - Analyzed accidents during weekdays versus weekends.
   - Investigated accidents by time of day using histograms.
   - Explored correlations between numerical variables using a correlation heatmap.
   
3. **Outlier Handling:**
   - Detected and visualized outliers in numeric columns using box plots and scatter plots.
   - Addressed outliers by replacing extreme values with thresholds.

4. **Model Training and Evaluation:**
   - Employed three machine learning models: LightGBM, Random Forest, and Neural Networks.
   - Utilized preprocessing techniques, including feature selection and SMOTE oversampling.
   - Evaluated model performance on training, validation, and testing datasets.
   - Assessed models using classification reports including precision, recall, and F1-score metrics.

## Model Performance

### LightGBM Model

- **Training Classification Report:**
  - Precision: 0.77
  - Recall: 0.75
  - F1-score: 0.75

- **Validation Classification Report:**
  - Precision: 0.61
  - Recall: 0.65
  - F1-score: 0.62

- **Testing Classification Report:**
  - Precision: 0.62
  - Recall: 0.65
  - F1-score: 0.63

### Random Forest Model

- **Training Classification Report:**
  - Precision: 0.79
  - Recall: 0.76
  - F1-score: 0.77

- **Validation Classification Report:**
  - Precision: 0.61
  - Recall: 0.64
  - F1-score: 0.61

- **Testing Classification Report:**
  - Precision: 0.61
  - Recall: 0.65
  - F1-score: 0.62

### Neural Networks Model

- **Testing Classification Report:**
  - Precision: 0.62
  - Recall: 0.66
  - F1-score: 0.61

## Metrics

- **Precision:** The ratio of correctly predicted positive observations to the total predicted positives.
- **Recall:** The ratio of correctly predicted positive observations to the actual positives.
- **F1-score:** The weighted average of precision and recall.
- **Accuracy:** The ratio of correctly predicted observations to the total observations.

## Conclusion

Through extensive data preprocessing, exploratory analysis, and model training, we were able to develop predictive models that classify accident severity levels based on various features. The project aimed to provide insights into factors affecting fatal traffic accidents and showcase the application of machine learning techniques to enhance road safety.


## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- lightgbm
- imbalanced-learn
- tensorflow

## Acknowledgments

The Fatal Accident Reporting System (FARS) dataset used in this project is provided by [National Highway Traffic Safety Administration (NHTSA)](https://www.nhtsa.gov/).
