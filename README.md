This project analyzes the Bank Marketing Dataset, which contains customer demographic, economic, and contact-related data from a Portuguese bank’s direct marketing campaigns. The primary goal is to understand customer behavior and determine factors that influence whether a client will subscribe to a term deposit (y variable).

The project involves data inspection, visualization, and initial analysis, which sets the foundation for predictive modeling in future steps.

1.Data Loading & Inspection

Imported the dataset (bankmarketing.csv).

Checked data types and missing values.

Generated summary statistics.

2.Exploratory Data Analysis (EDA):

Target Variable Distribution:

Most customers did not subscribe to term deposits → dataset is imbalanced.

3.Correlation Analysis:

Created a heatmap of numerical features.

Identified correlations between attributes like age, duration, campaign calls, and outcome.

4.Insights from Data:

The dataset includes customer demographics (age, job, marital, education).

Contains financial attributes (balance, housing loan, personal loan).

Includes marketing contact details (communication type, number of contacts, last contact duration).

Imbalance challenge: Only a small percentage subscribed → models need balancing methods (SMOTE, resampling).
