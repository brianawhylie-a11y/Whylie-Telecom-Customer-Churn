WHYLIE CUSTOMER CHURN DEEP DIVE PACKAGE
=======================================

OVERVIEW
--------
This package contains the final deep-dive materials for the telecom customer churn project:
- Jupyter notebook for the full analysis
- PowerPoint presentation for class
- presenter notes
- dataset
- output charts, tables, and saved model

MAIN FILES
----------
1. Whylie_Customer_Churn_Deep_Dive_Notebook.ipynb
   Main notebook. Run this in Jupyter from top to bottom.

2. Customer Churn.csv
   Dataset used in the notebook and presentation.

3. Whylie_Customer_Churn_Deep_Dive_Presentation.pptx
   Final presentation deck.


HOW TO OPEN AND RUN THE NOTEBOOK
--------------------------------
1. Unzip the package.
2. Keep all files together in the same folder.
3. Open Jupyter Notebook or JupyterLab.
4. Open: Whylie_Customer_Churn_Deep_Dive_Notebook.ipynb
5. Make sure the kernel is set to Python 3.
6. Run the notebook from top to bottom.

IMPORTANT
---------
The CSV file must stay in the same folder as the notebook unless you manually change the file path in the notebook.

WHAT THE NOTEBOOK DOES
----------------------
- loads and cleans the telecom churn dataset
- removes redundant columns
- performs exploratory data analysis
- compares Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting
- evaluates models using accuracy, precision, recall, F1-score, ROC-AUC, and confusion matrix
- explains feature importance in more depth
- explores why complaints, status, seconds of use, and frequency of use matter
- creates scenario sensitivity charts and deeper business interpretation

KEY TAKEAWAYS
-------------
- Random Forest is the strongest overall model in this project.
- Complaints, status, seconds of use, and frequency of use are among the most important churn signals.
- A feature importance value such as 0.19 does NOT mean 19% churn probability.
  It means the model relied heavily on that feature relative to the others when making predictions.
- High complaints and lower engagement are warning signs of churn risk.

IMPORTANT OUTPUT FILES
----------------------
outputs/charts/class_distribution.png
outputs/charts/churn_correlations_bar.png
outputs/charts/model_performance.png
outputs/charts/roc_curves.png
outputs/charts/random_forest_confusion_matrix.png
outputs/charts/random_forest_feature_importance.png
outputs/charts/complaints_status_churn_rates.png
outputs/charts/usage_quintile_churn_rates.png
outputs/charts/partial_dependence_key_drivers.png
outputs/charts/scenario_sensitivity.png

outputs/tables/holdout_model_metrics.csv
outputs/tables/cross_validation_metrics.csv
outputs/tables/random_forest_feature_importance.csv
outputs/tables/random_forest_permutation_importance.csv
outputs/tables/top_correlations_with_churn.csv
outputs/tables/complaints_churn_rates.csv
outputs/tables/status_churn_rates.csv
outputs/tables/seconds_of_use_quintile_churn.csv
outputs/tables/frequency_of_use_quintile_churn.csv
outputs/tables/scenario_sensitivity.csv
