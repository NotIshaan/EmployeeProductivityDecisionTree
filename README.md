# Employee Productivity Prediction in the Garment Industry

## Overview
This repository contains Python code for predicting employee productivity in the garment industry using machine learning techniques, specifically decision trees and random forests. The project aims to assist garment manufacturing companies in tracking, analyzing, and predicting the productivity performance of their working teams.

## Changes in Modified Code:

1. **Data Cleaning**:
   - Corrected misspellings in the "department" column.
   - Concatenated "finishing" department entries.
   - Merged "Quarter5" with "Quarter4".
   - Converted categorical values in "quarter" column to integers.
   - Converted "no_of_workers" column from float to integer.
   - Rounded "actual_productivity" column to two decimal places.
   - Removed irrelevant columns ("date", "wip", "idle_time", "idle_men", "no_of_style_change").

2. **Data Transformation**:
   - Replaced categorical values in "department" column with binary integers.
   - One-hot encoded categorical columns using `OneHotEncoder` and `make_column_transformer`.
   - Created polynomial features for selected columns.

3. **Model Building**:
   - Used DecisionTreeClassifier with specified parameters.
   - Conducted cross-validation with 10 folds.
   - Utilized RandomForestClassifier to double-check decision tree performance.

4. **Evaluation**:
   - Visualized decision tree using `plot_tree`.
   - Evaluated model using confusion matrix, classification report, and feature importance analysis.
   - Explained decision tree's structure and predictions.

5. **Conclusion**:
   - Summarized project steps and findings, emphasizing model accuracy and potential impact.


## Contributors
- Ishaan Bhadrike(https://github.com/NotIshaan): Project lead, data preprocessing, model building, and evaluation.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
Special thanks to the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php) for providing the original dataset.
