# Jamboree Admission Predictor

## Context

Jamboree has helped thousands of students like you make it to top colleges abroad. Be it GMAT, GRE, or SAT, their unique problem-solving methods ensure maximum scores with minimum effort. They recently launched a feature where students/learners can come to their website and check their probability of getting into an Ivy League college. This feature estimates the chances of graduate admission from an Indian perspective.

## How Can You Help Here?

Your analysis will help Jamboree in understanding what factors are important in graduate admissions and how these factors are interrelated among themselves. It will also help predict one's chances of admission given the rest of the variables.

## Dataset

**Dataset Link:** [jamboree_admission.csv](data/Jamboree_Admission.csv)

### Column Profiling

- **Serial No.:** Unique row ID
- **GRE Scores:** Scores out of 340
- **TOEFL Scores:** Scores out of 120
- **University Rating:** Rating out of 5
- **Statement of Purpose and Letter of Recommendation Strength:** Rating out of 5
- **Undergraduate GPA:** GPA out of 10
- **Research Experience:** Either 0 or 1
- **Chance of Admit:** Ranging from 0 to 1

## Concept Used

This project involves the following key concepts:

1. **Data Preprocessing:**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling

2. **Exploratory Data Analysis (EDA):**
   - Understanding the distribution of variables
   - Identifying relationships between variables
   - Visualizing data using plots and charts

3. **Feature Engineering:**
   - Creating new features
   - Handling multicollinearity using Variance Inflation Factor (VIF)

4. **Model Building:**
   - Splitting the data into training and testing sets
   - Building and evaluating multiple regression models (e.g., Linear Regression, Ridge Regression)

5. **Model Evaluation:**
   - Calculating performance metrics (MAE, RMSE, R², Adjusted R²)
   - Checking model assumptions (linearity, homoscedasticity, normality of residuals, multicollinearity)

6. **Model Interpretation:**
   - Understanding the significance of predictor variables
   - Providing actionable insights and recommendations

