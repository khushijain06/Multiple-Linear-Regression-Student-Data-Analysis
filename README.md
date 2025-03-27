# Multiple Linear Regression - Student Data Analysis

## Overview
This project demonstrates the application of Multiple Linear Regression to analyze student performance based on various factors such as study hours, previous scores, sleep hours, and sample question papers practiced. The goal is to predict a student's performance index using a linear regression model.

## Dataset
The dataset used in this project (`Student_Performance.csv`) includes the following features:
- **Hours Studied**
- **Previous Scores**
- **Sleep Hours**
- **Sample Question Papers Practiced**
- **Performance Index** (Target variable)

## Features Implemented
- **Data Preprocessing**: Load and clean the dataset using Pandas.
- **Correlation Analysis**: Identify relationships between features using a correlation matrix.
- **Data Visualization**: Use Seaborn and Matplotlib to generate a heatmap and scatter plots.
- **Model Training**:
  - Split data into training and testing sets.
  - Train a Multiple Linear Regression model using `sklearn`.
- **Model Evaluation**:
  - Predict student performance on the test set.
  - Calculate the Mean Squared Error (MSE).
  - Display model coefficients and intercept.
- **Result Visualization**: Plot the regression fit comparing actual and predicted values.

## Requirements
To run this project, install the following dependencies:
```bash
pip install pandas numpy seaborn scikit-learn matplotlib
```

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/khushijain06/Multiple-Linear-Regression-Student-Data-Analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Multiple-Linear-Regression-Student-Data-Analysis
   ```
3. Run the Python script:
   ```bash
   python practical3_multiplelinearregression_studentperformance.py
   ```

## Results
- Displays the correlation matrix heatmap.
- Prints model coefficients, intercept, and Mean Squared Error (MSE).
- Generates a regression fit visualization.

## Author
**Khushi Jain**

## License
This project is open-source and available under the [MIT License](LICENSE).

