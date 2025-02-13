# Clinical Time-Series Forecasting

This project focuses on developing a time-series forecasting model to predict patient outcomes based on clinical data. The dataset is simulated and contains time-series records of vital signs for multiple patients.

## Project Overview
- **Objective**: Predict patient outcomes using clinical time-series data.
- **Data**: Simulated dataset containing patient vital signs and outcomes over a period of 30 days.
- **Methods**: Statistical and machine learning-based forecasting models.
- **Evaluation**: Model performance measured using RMSE, MAE, and accuracy metrics.

## Dataset
### Simulated Clinical Data
The dataset consists of the following fields:
- `Patient_ID`: Unique identifier for each patient.
- `Date`: Observation date.
- `Heart_Rate`: Patient's heart rate (bpm).
- `Blood_Pressure`: Systolic blood pressure (mmHg).
- `Temperature`: Body temperature (°C).
- `Oxygen_Saturation`: Blood oxygen saturation level (%).
- `Outcome`: Patient status (Stable, Deteriorating, Recovered).

### Data File
- `simulated_clinical_data.csv`: Contains synthetic patient time-series data for model training and evaluation.

## Steps to Run the Project
1. **Install Dependencies**
   ```sh
   pip install pandas numpy scikit-learn matplotlib seaborn statsmodels tensorflow
   ```
2. **Load the Data**
   ```python
   import pandas as pd
   df = pd.read_csv("simulated_clinical_data.csv")
   print(df.head())
   ```
3. **Perform Exploratory Data Analysis (EDA)**
4. **Feature Engineering**
5. **Train and Evaluate Time-Series Forecasting Models**
6. **Optimize the Model and Interpret Results**

## Future Work
- Implement deep learning models (LSTM, Transformer)
- Integrate real-world clinical datasets
- Deploy the model as an API for real-time predictions

## License
This project is open-source


