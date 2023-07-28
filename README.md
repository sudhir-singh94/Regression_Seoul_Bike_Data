# Seoul Bike Rental Prediction
This project aims to predict the count of rented bikes in the Seoul Bike sharing system. The dataset comprises various environmental and temporal attributes collected over a year. The primary objective is to build a robust predictive model and identify the key factors influencing bike rental demand.

## Dataset
The dataset contains 8760 records, each representing an hour of a day over a year. There are 14 features in the dataset:

Date
Rented Bike Count
Hour
Temperature(°C)
Humidity(%)
Wind speed (m/s)
Visibility (10m)
Dew point temperature(°C)
Solar Radiation (MJ/m2)
Rainfall(mm)
Snowfall (cm)
Seasons
Holiday
Functioning Day
Approach
The project involves several steps:

### Exploratory Data Analysis (EDA) to understand the distribution of data and relationships among variables.

### Data Preprocessing, including handling of categorical variables through encoding, feature scaling, and train-test splitting.

### Feature Engineering to create a 'Comfort Index' combining temperature and humidity, and converting 'Date' into 'Month' and 'DayOfWeek'.

### Training and evaluating six regression models: Linear Regression, Ridge Regression, Lasso Regression, Decision Tree Regressor, Random Forest Regressor, and XGBoost Regressor.

### Evaluating model performance using root mean squared error (RMSE), mean squared error (MSE), mean absolute error (MAE), and R2 Score.

### Optimizing models using GridSearchCV for hyperparameter tuning.

### Analyzing feature importance to identify significant features affecting bike rentals.

## Results
Models' performance and feature importance analyses are provided for both the complete feature set and the engineered feature set.

The results offer valuable insights for bike-sharing service management and promotion strategies. For a detailed summary, please refer to the python notebook.

## Usage
Clone the repository.
Ensure the required libraries are installed (numpy, pandas, sklearn, matplotlib, seaborn, xgboost).
Run the Jupyter Notebook or Python script.
Contribution
This project welcomes contributions. If you find a bug or want to suggest improvements, please open an issue. If you want to contribute code, please open a pull request.

## #Contact
If you have any questions or comments about this project, feel free to contact me.

[Sudhir Kumar Singh]
[sudhir_94@iitkgp.ac.in]
