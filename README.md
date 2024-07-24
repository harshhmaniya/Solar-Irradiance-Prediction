## Solar Irradiance Prediction

This project aims to predict solar irradiance levels using machine learning techniques. By leveraging historical weather data, the goal is to develop an accurate forecasting model that can optimize solar energy generation.

### Key Features

- Utilizes real-world meteorological data including solar radiation, temperature, humidity, wind speed, and pressure.
- Employs various feature engineering techniques to select and transform relevant variables.
- Implements and compares multiple machine learning models such as XGBoost and Multi-Layer Perceptron.
- Evaluates model performance using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

### Libraries Used

- **Pandas** and **NumPy** for data manipulation and preprocessing
- **Matplotlib** and **Seaborn** for data visualization and exploration
- **Scikit-learn** for machine learning algorithms and evaluation
- **XGBoost** for gradient boosting models
- **TensorFlow** and **Keras** for deep learning with Multi-Layer Perceptron

### Data Preprocessing

1. Extracted date and time features from the given parameters using Python datetime methods.
2. Parsed sunrise and sunset information using regular expressions.
3. Dropped unnecessary columns and checked for null values.

### Feature Selection

1. Calculated the correlation matrix to identify relationships between variables.
2. Utilized the SelectKBest method with the chi-square statistic to select the top 10 features.
3. Employed the Extra Trees Classifier for further feature importance analysis.

### Models and Results

1. **XGBoost**: Achieved an MAE of 0.15 and RMSE of 0.20 on the test set.
2. **Multi-Layer Perceptron**: Obtained an MAE of 0.18 and RMSE of 0.23 on the test set.

### Future Improvements

- Explore additional feature engineering techniques to enhance model performance.
- Investigate the impact of weather forecasts on solar irradiance prediction.
- Optimize hyperparameters for the machine learning models.

### Usage

1. **Clone the repository**:
2. `git clone https://github.com/harshhmaniya/Solar-Irradiance-Prediction.git`
3. **Install the required libraries**:
4. `pip install -r requirements.txt`
5. **Run the Jupyter Notebook**:
6. `jupyter notebook Solar Irradiance Prediction.ipynb`

### Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.
