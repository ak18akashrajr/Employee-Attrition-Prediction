# Employee-Attrition-Prediction
# Employee Attrition Prediction

## Overview

This project aims to predict whether an employee is likely to leave the company or not using a logistic regression machine learning model. The model is trained on a dataset that includes various features such as satisfaction level, last evaluation, average monthly hours, time spent in the company, work accident history, promotion status in the last 5 years, department, and salary.

## Features

The dataset contains the following features:

1. **satisfaction_level**: Employee satisfaction level (numeric, ranging from 0 to 1).
2. **last_evaluation**: Employee's last performance evaluation score (numeric, ranging from 0 to 1).
3. **average_monthly_hours**: Average number of hours the employee works per month (numeric).
4. **time_spend_company**: Number of years the employee has spent at the company (numeric).
5. **Work_accident**: Whether the employee has had a work accident (binary: 1 for yes, 0 for no).
6. **left_company**: Whether the employee has left the company (binary: 1 for yes, 0 for no) - target variable.
7. **promotion_last_5years**: Whether the employee has been promoted in the last 5 years (binary: 1 for yes, 0 for no).
8. **Department**: Department in which the employee works (categorical: "sales," "technical," "support," etc.).
9. **salary**: Level of salary (categorical: "low," "medium," "high").

## Dependencies

Make sure you have the following dependencies installed to run the project:

- Python 3.x
- NumPy
- Pandas
- Scikit-learn

You can install these dependencies using the following command:

```bash
pip install numpy pandas scikit-learn
```

## Usage

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/employee-attrition-prediction.git
   ```

2. Navigate to the project directory:

   ```bash
   cd employee-attrition-prediction
   ```

3. Run the script:

   ```bash
   python employee_attrition_prediction.py
   ```

   This will train the logistic regression model on the provided dataset and display the prediction results.

## Model Training

The logistic regression model is trained on the provided dataset using a supervised learning approach. The dataset is split into training and testing sets to evaluate the model's performance accurately. The training process includes feature scaling, model fitting, and performance evaluation.

## Dataset

The dataset used for this project is provided in the `hr_company_data.csv` file. It contains records of employees with various features, including whether they have left the company.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The dataset used in this project is sourced from Kaggle ( https://www.kaggle.com/giripujar/hr-analytics).

Feel free to contribute and improve this project! If you encounter any issues or have suggestions, please open an issue in the [issue tracker](https://github.com/your-username/employee-attrition-prediction/issues).
