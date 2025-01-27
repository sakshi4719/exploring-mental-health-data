# Exploring Mental Health Data 

## Overview
This notebook analyzes mental health data and predicts depression likelihood using machine learning. It covers data preprocessing, feature engineering, and model building.

## Key Steps
1. **Data Loading**: Loads train/test datasets with Pandas.
2. **EDA**: Uses `head()` and `describe()` to inspect data.
3. **Preprocessing**:
   - Encodes categorical variables (e.g., gender, family history).
   - Fills missing values for features like sleep, stress, and diet.
   - Creates features like work-life balance.
4. **Model Building**: Trains a TensorFlow/Keras model with features like gender, age, sleep, and satisfaction levels.
5. **Predictions**: Outputs depression predictions for the test dataset.

## Dependencies
- `pandas`, `numpy`, `scikit-learn`, `tensorflow`

## Output
- Generates a DataFrame with test IDs and predicted depression labels.
