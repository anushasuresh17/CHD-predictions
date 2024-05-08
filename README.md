
# Heart Disease Risk Prediction

This repository contains code for analyzing and predicting the risk of heart disease using machine learning techniques. The dataset used for analysis is from the Framingham Heart Study, which includes various demographic, behavioral, and medical risk factors.

## Overview

Heart disease is a significant public health concern worldwide. Identifying individuals at high risk of developing heart disease can facilitate early intervention and personalized healthcare management. In this project, we aim to build predictive models to assess an individual's ten-year risk of developing coronary heart disease (CHD) based on available risk factors.

## Dataset

The dataset used for analysis is sourced from the Framingham Heart Study and consists of demographic, behavioral, and medical information of individuals. The target variable, TenYearCHD, indicates whether an individual developed CHD within ten years of the study period.

## Analysis Steps

1. **Data Preprocessing**: 
   - Handling missing values by imputation.
   - Dropping irrelevant columns such as 'education'.
   - Scaling numerical features.

2. **Exploratory Data Analysis (EDA)**:
   - Statistical summary and visualization of data distribution.
   - Identification and visualization of correlations between variables.

3. **Model Building**:
   - Utilizing logistic regression for predictive modeling.
   - Feature selection using Recursive Feature Elimination (RFE).
   - Evaluating model performance metrics such as accuracy, sensitivity, specificity, precision, and recall.

4. **Model Evaluation**:
   - Assessing model performance on training and test datasets.
   - Plotting ROC curve and determining the area under the curve (AUC).
   - Identifying optimal probability cutoff points for classification.

5. **Conclusion**:
   - Comparison of model performance metrics.
   - Recommendations for model improvement and further analysis.

## Results and Insights

- The logistic regression model achieved moderate performance in predicting CHD risk.
- Sensitivity and positive predictive value can be improved for better identification of high-risk individuals.
- Precision and recall tradeoff analysis helped in selecting an optimal probability cutoff point.
- Further model enhancements and alternative algorithms such as random forests can be explored for improved performance.

## Repository Structure

- `data/`: Contains the dataset used for analysis.
- `notebooks/`: Jupyter notebooks with code for data preprocessing, EDA, model building, and evaluation.
- `visualizations/`: Visualizations generated during EDA and model evaluation.
- `README.md`: Overview of the project, dataset, analysis steps, results, and repository structure.

## Dependencies

- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels

## Usage

1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Execute the Jupyter notebooks in the `notebooks/` directory to run the analysis and build predictive models.
4. Refer to the README file in each directory for detailed instructions.
