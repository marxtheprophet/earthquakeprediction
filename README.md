# Earthquake Prediction using Machine Learning

## Project Overview
This project aims to predict earthquakes using machine learning techniques. The model analyzes seismic data to detect patterns that could indicate the likelihood of an earthquake occurring.

## Dataset
- The project uses a dataset containing seismic activity records, including features such as magnitude, depth, latitude, longitude, and time of occurrence.
- Data is preprocessed to remove noise and normalize features for better model performance.

## Dependencies
To run this project, install the following dependencies:
```
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow keras
```

## Project Structure
- `earthquakepred.ipynb`: Jupyter Notebook containing data preprocessing, model training, and evaluation.

## Model Training
The machine learning model is trained using:
- **Feature Selection:** Selecting key seismic indicators.
- **Data Splitting:** Dividing data into training and testing sets.
- **Model Selection:** Experimenting with regression models.
- **Evaluation Metrics:** Using accuracy, precision, recall, and RMSE.

## How to Run
1. Open the Jupyter Notebook:
   ```
   jupyter notebook earthquakepred.ipynb
   ```
2. Run all cells to preprocess data, train models, and generate predictions.

## Results
- The model's performance is evaluated using standard metrics.
- Visualizations help interpret patterns in seismic activity.



