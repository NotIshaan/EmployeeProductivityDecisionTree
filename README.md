# Employee Productivity Prediction in the Garment Industry

## Overview
This repository contains Python code for predicting employee productivity in the garment industry using machine learning techniques, specifically decision trees and random forests. The project aims to assist garment manufacturing companies in tracking, analyzing, and predicting the productivity performance of their working teams.

## Dataset
The dataset used in this project is a modified version of the [Productivity Prediction of Garment Employees Dataset](https://archive.ics.uci.edu/dataset/597/productivity+prediction+of+garment+employees). It includes various features such as date, day, quarter, department, team, number of workers, standard minute value (SMV), overtime, incentive, targeted productivity, actual productivity, and more.

## Key Features
- **Data loading and preprocessing:** The code handles missing values, cleans the dataset by fixing misspelled entries and removing unnecessary columns, and converts categorical variables into numerical ones.
- **Model building:** It builds a decision tree classifier to predict employee productivity based on features such as incentive, number of workers, SMV, and more.
- **Model evaluation:** The code evaluates the model's performance using cross-validation, confusion matrix, classification report, and feature importance analysis.
- **Random Forest:** In addition to decision trees, the code also implements a random forest classifier to mitigate overfitting and improve model performance.

## Usage
1. Clone the repository: `git clone https://github.com/yourusername/employee-productivity-prediction.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Run the Jupyter Notebook or Python script to execute the code.
4. Explore the results, including model accuracy, confusion matrix, feature importance, and more.

## Contributors
- Ishaan Bhadrike(https://github.com/NotIshaan): Project lead, data preprocessing, model building, and evaluation.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
Special thanks to the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php) for providing the original dataset.
