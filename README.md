Scenario 1: Ocean Water Temperature Prediction
This project predicts ocean water temperature using environmental and spatial data.
The CalCOFI dataset is used with temperature (T_degC) as the target variable.
Depth, salinity, oxygen, latitude, and longitude are selected as input features.
Missing values are handled using statistical imputation techniques.
Feature scaling is applied using StandardScaler.
A Linear Regression model is trained and evaluated using MSE, RMSE, and R² score.
Actual versus predicted values are visualized to assess model performance.

Scenario 2: LIC Stock Price Movement Classification
This project classifies whether the LIC stock price will increase or decrease.
Historical stock price data is collected from a public Kaggle dataset.
Price movement is defined using opening and closing prices.
Open, high, low, and volume are used as input features.
Data preprocessing includes missing value handling and feature scaling.
A Logistic Regression model is trained to predict price movement.
Model performance is evaluated using accuracy, precision, recall, and F1-score.
