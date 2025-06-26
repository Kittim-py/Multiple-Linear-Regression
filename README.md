# Multiple-Linear-Regression
==========================================================================
Title:       Correlation Analysis and Visualization
Authors:     Arindam Roy, Dr. Shubhabrata Datta, Rahul Mukherjee
Affiliation: Center for Composite and Advanced Materials,
             Department of Mechanical Engineering,
             SRM Institute of Science and Technology
===========================================================================

Citations
---------
If you use this script or its outputs for academic, scientific, or industrial work,
please cite it as follows:

Arindam Roy, Shubhabrata Datta, Rahul Mukherjee (2025).
"Correlation Analysis and Visualization for Hydrogen Desorption Modeling using MLR."
GitHub Repository: https://github.com/Kittim-py/Multiple-Linear-Regression
ORCID ID: https://orcid.org/0000-0002-4047-3772

APA Style:
Roy, A., Datta, S., & Mukherjee, R. (2025). Visualization for MLR Modeling using MLR https://github.com/Kittim-py/-mlr

BibTeX:
@misc{roy2025mlr,
  author       = {Arindam Roy and Shubhabrata Datta and Rahul Mukherjee},
  title        = {Visualization for MLR Modeling using MLR},
  year         = {2025},
  howpublished = {\url{https://github.com/Kittim-py/hydrogen-desorption-mlr}},
  note         = {GitHub repository, ORCID: \url{https://orcid.org/0000-0002-4047-3772}}
}


Description:
------------
This Python script performs a complete statistical analysis using multiple linear regression
on a dataset related to hydrogen desorption. The following operations are included:

1. Load and preprocess the dataset (cleaning and formatting)
2. Define independent and dependent variables
3. Fit the model using statsmodels' OLS regression
4. Save regression coefficients, standard errors, t-statistics, and p-values
5. Evaluate model performance using R², MSE, RMSE, and MAE
6. Plot observed vs. predicted results with interpretation line
7. Construct and print the regression equation
8. Interpret the model fit quality automatically

File Outputs:
-------------
- MLR_Coefficients.csv      : Contains model coefficients with statistics
- Significance_Values.csv   : Contains variables and their p-values

Requirements:
-------------
- Python 3.6 or higher
- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- scikit-learn

How to Run:
-----------
1. Place your dataset in the specified path (update `file_path` in the script).
2. Run the script using a Python IDE or terminal.
3. Check the console for regression results and visual output.

Interpretation:
---------------
- R² above 75% is considered a good fit
- R² between 50%-75% is moderate
- R² below 50% is poor, and the model may need revision

Note:
-----
Ensure the dataset includes all required columns:

===============================================================================
