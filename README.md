# Air Quality Index (AQI) Prediction

## Project Overview
This project analyzes air pollution data and uses machine learning to predict the Air Quality Index (AQI) from pollutant measurements.

## Objectives
- Analyze air quality data from Indian cities.
- Explore AQI distributions and pollution levels.
- Compare average AQI across cities.
- Study relationships between pollutants and AQI.
- Train a machine learning model to predict AQI.
- Evaluate model performance using statistical metrics.
- Visualize actual and predicted AQI values.

## Dataset
**Dataset:** Air Quality Data in India (2015–2020)

The dataset includes city information, pollutant measurements, AQI values, and AQI categories.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Machine Learning Model
**Algorithm:** Random Forest Regressor

The model uses available pollutant measurements to estimate numerical AQI values.

## Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Project Workflow
1. Load the dataset.
2. Explore and clean the data.
3. Analyze AQI distributions and pollutant levels.
4. Compare AQI values across cities.
5. Examine pollutant correlations.
6. Prepare training and testing datasets.
7. Train the Random Forest model.
8. Evaluate model performance.
9. Compare actual and predicted AQI.
10. Visualize feature importance and project results.

## Visualizations
- AQI distribution
- Average pollution levels
- Average AQI by city
- Pollutant correlation heatmap
- Actual versus predicted AQI
- Pollutant feature importance
- AQI prediction dashboard

## How to Run
1. Open `AQI_Prediction.ipynb` in Google Colab.
2. Run the notebook cells in order.
3. The dataset is loaded directly from its online CSV source.

## Internship Details
- **Organization:** CODTECH
- **Project:** AQI Prediction
- **Intern ID:** CITS9001

## Limitations
The model depends on the dataset's quality and coverage. Its predictions should not be considered official or real-time AQI measurements.

## Conclusion
This project demonstrates how data analysis, visualization, and machine learning can help estimate AQI values from air pollutant measurements.
