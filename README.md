# Diabetes Prediction Project

## Description

This project utilizes a dataset originally provided by the National Institute of Diabetes and Digestive and Kidney Diseases (NIDDK). The primary objective is to predict whether a patient has diabetes based on certain diagnostic measurements. The dataset includes several medical predictor variables and one target variable (Outcome).

## Dataset Description

The dataset consists of the following variables:

| Variable                  | Description |
|---------------------------|-------------|
| Pregnancies               | Number of times pregnant |
| Glucose                   | Plasma glucose concentration in an oral glucose tolerance test |
| BloodPressure             | Diastolic blood pressure (mm Hg) |
| SkinThickness             | Triceps skinfold thickness (mm) |
| Insulin                   | Two-hour serum insulin |
| BMI                       | Body Mass Index |
| DiabetesPedigreeFunction  | Diabetes pedigree function |
| Age                       | Age in years |
| Outcome                   | Class variable (either 0 or 1). 268 of 768 values are 1, and the others are 0 |

## Project Task: Week 1

### Data Exploration

1. **Descriptive Analysis**:
   - Understand the variables and their corresponding values.
   - Identify columns where a value of zero does not make sense (indicating missing values): `Glucose`, `BloodPressure`, `SkinThickness`, `Insulin`, and `BMI`.
   - Treat missing values appropriately.

2. **Visual Exploration**:
   - Create histograms for `Glucose`, `BloodPressure`, `SkinThickness`, `Insulin`, and `BMI` to explore their distributions.

3. **Data Type Analysis**:
   - Generate a count (frequency) plot describing the data types (integer and float) and the count of variables.

4. **Data Balance Check**:
   - Plot the count of outcomes by their value to check the balance of the data.
   - Describe findings and plan the future course of action based on the data balance.

5. **Scatter Charts**:
   - Create scatter charts between pairs of variables to understand relationships.
   - Describe findings based on these visualizations.

6. **Correlation Analysis**:
   - Perform correlation analysis on the dataset.
   - Visualize the correlation matrix using a heatmap.

## Project Task: Week 2

### Data Modeling

1. **Model Building Strategies**:
   - Devise strategies for building a predictive model, including selecting an appropriate validation framework.
   - Document the thought process behind the chosen strategies.

2. **Classification Algorithm**:
   - Apply an appropriate classification algorithm to predict whether the patients have diabetes.

3. **Model Comparison**:
   - Compare various models with the results from the K-Nearest Neighbors (KNN) algorithm.

4. **Classification Report**:
   - Analyze and report on sensitivity, specificity, AUC (ROC curve), and other relevant metrics.
   - Provide detailed explanations for the values of these parameters used in the analysis.

## Data Reporting

1. **Dashboard Creation**:
   - Create a dashboard in Tableau to present the findings. The dashboard should include:
     - A pie chart describing the diabetic and non-diabetic population.
     - Scatter charts between relevant variables to analyze relationships.
     - Histogram or frequency charts to analyze data distribution.
     - A heatmap of the correlation analysis among relevant variables.

2. **Age Bracket Analysis**:
   - Create bins for age values (e.g., 20-25, 25-30, 30-35, etc.).
   - Analyze different variables within these age brackets using a bubble chart.

## Conclusion

This project comprehensively analyses the NIDDK dataset, from data exploration and visualization to predictive modelling and data reporting. The aim is to accurately predict diabetes status using various diagnostic measurements, with insights presented through detailed visualizations and dashboards.

## How to Use This Repository

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/healthcare-data-insights.git
   ```

2. Navigate to the project directory:
   ```bash
   cd healthcare-data-insights
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the data exploration scripts or notebooks to perform analysis and build models.

## Acknowledgments

The dataset used in this project is provided by the National Institute of Diabetes and Digestive and Kidney Diseases (NIDDK). The project aims to contribute to the understanding and prediction of diabetes based on medical data.
