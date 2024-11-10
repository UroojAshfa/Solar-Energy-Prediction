# Solar Energy Prediction from Weather Data 🌞
This project predicts solar energy output using historical weather data. The model leverages features such as temperature, humidity, wind speed, and solar irradiance to forecast energy production. By modeling the relationship between weather variables and solar irradiance, this project aims to assist in renewable energy planning and optimization.

## Project Overview
Using a machine learning pipeline, this project explores weather-related features, cleans and preprocesses data, builds a predictive model, and evaluates its accuracy. The final model is trained on historical weather data and tested to determine its effectiveness in predicting solar irradiance.

## Key Features
* Data Cleaning & Preparation: Handles missing values, removes outliers, and transforms time-related features.

* Feature Selection: Employs correlation-based feature selection to include only the most impactful variables.

* Model Training: Uses a tuned XGBoost regressor for high predictive accuracy.

* Evaluation: Assesses model performance through Mean Squared Error (MSE) and residual analysis.

## Technologies Used
* Python for data manipulation and analysis.
* Pandas for data handling.
* Scikit-Learn for preprocessing and evaluation metrics.
* XGBoost for optimized predictive modeling.
* Matplotlib for data visualization.

## Results & Analysis
After training the model on the cleaned data, the final Mean Squared Error (MSE) on the test set was 0.00017, indicating a strong predictive accuracy. The model performed well on unseen data, accurately capturing patterns in solar irradiance. Key findings:

* Feature Importance: Attributes like Direct Normal Irradiance (DNI) and Diffuse Horizontal Irradiance (DHI) had the highest influence on predictions.
* Residual Distribution: Analysis of residuals indicated minimal variance, suggesting a well-fitted model.

## Future Work
* Expand Dataset: Incorporate more diverse weather conditions and extended time periods.
* Hyperparameter Tuning: Further refine parameters for improved accuracy.
* Deployment: Build a Streamlit web interface to make predictions interactively.
## How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/solar-energy-prediction.git
cd solar-energy-prediction
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Run the Jupyter notebooks in notebooks/ for data exploration and model training.
