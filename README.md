# temperature-prediction-data-science-
Predicting temperature from humidity data using Linear Regression — end-to-end ML project with EDA, preprocessing, and model evaluation.
## Temperature Prediction using Linear Regression

### Objective
Predict temperature values from humidity readings using a supervised machine learning approach.

### Dataset
- 700,000+ hourly/daily weather readings
- Features: humidity
- Target: temperature
- Source: humidity.csv

### Workflow
1. Load and explore the dataset
2. Handle missing values and outliers
3. Visualize the humidity-temperature relationship
4. Train a Linear Regression model
5. Evaluate using MSE and R² score

### Tech Stack
- Python, Pandas, NumPy
- Scikit-learn (LinearRegression)
- Matplotlib, Seaborn

### Results
- Linear Regression captures the general trend between humidity and temperature
- Model evaluated on a held-out test set using Mean Squared Error and R² score

### Future Work
- Try polynomial regression for non-linear relationships
- Add more weather features (wind speed, pressure, dew point)
- Experiment with Ridge/Lasso regularization
