# AdvancedAnalyticsLabs
Analytics labs notebooks, supporting analytics teaching for BSc and MSc courses. I've taught these at a business school and a statistics department, so I think they fit both reasonably well. Currently, there are 19 labs uploaded divided into five topics:

## Intro to Python

1. [Introduction to Python](notebooks/python/Lab_1_Introduction_to_Python.ipynb): First few steps. Simple intro for people who might be already familiar with other languages, not meant for people with no programming experience!

2. [Functions and Revenue Management](notebooks/python/Lab_2_Revenue_Management.ipynb): Implementation of simple algorithms (Littlewood, EMSR-a and EMSR-b). Covers function creation and an introduction to PyPlot. Taught until 2019 in Southampton University as part of Advanced Analytics course.

## Banking Regulation

3. [Basel Capital Requirements](notebooks/python/Lab_2_Capital_Requirements_and_Pandas.ipynb): Covers Lambda functions and an introduction to Pandas in the context of the [Basel capital requirements formulas](https://www.bis.org/bcbs/irbriskweight.pdf).

4. [Bond Pricing](notebooks/python/Lab_3_Bond_Pricing.ipynb): Teaches bond pricing, yields and clean/dirty prices. Taught from 2019 at Western University, as part of the [Banking Analytics](https://www.uwo.ca/stats/graduate/course-outlines/2021-22/FM9528A-2021.pdf) course I created. Replaces Revenue Management lab above, and also covers function creation and an introduction to PyPlot.

## Credit Risk Modelling

5. [Data Preprocessing](notebooks/python/Lab_4_Preprocessing.ipynb): Simple data preprocessing using polars and scikit-learn.

6. [Weight of evidence transformation](notebooks/python/Lab_5_WoE.ipynb): How to calculate Weight of Evidence transformations in Python. Uses my own fork of the [scorecardpy](https://github.com/ShichenXie/scorecardpy) package by @ShichenXie, with some bugs fixed and other personalizations.

7. [Logistic Regression and Scorecards](notebooks/python/Lab_6_Logistic_Regression_and_Scorecards.ipynb): Intro to scikit-learn, how to run a Lasso and Ridge regression, and how to calculate a scorecard. It includes larger-than-memory training using SGD.

8. [Random Forest and XGBoosting](notebooks/python/Lab_7_Ensembles_and_Error_Measures.ipynb): How to run a Random Forest, an XGBoost model, tune parameters over a grid, use Shapley values to explain predictions, and compare ROC curves. It also includes larger-than-memory training.

9. [LGD Modelling](notebooks/python/Lab_LGD_Modelling.ipynb): How to model LGD using either a GLM or an XGB model.

10. [PD / LGD Calibration](notebooks/python/Lab_PD_Calibration.ipynb): How to define ratings by segmenting the AUC curve and calibrate a long-run PD / downturn LGD adjusted by macroeconomic factors using the Vasicek model.


## Deep Learning 

**[See our new book's](https://www.bankingbook.ml/labs) for the most up-to-date versions of these labs**. They are also available in the [book's GitHub](https://github.com/Banking-Analytics-Lab/DLinBankingBook). 

## Other labs

17. [SQL Refresher](notebooks/python/Lab_11_SQL_Connections.ipynb): Refresher on SQL, how to access it from Python, and a very light introduction to [SQLAlchemy](https://www.sqlalchemy.org/).

18. [Primer on Visualization](notebooks/python/Lab_12_Visualization_Primer.ipynb): A few plots using pyplot, seaborn and plotly. Very introductory primer.

19. [Explainability and Confounding](Lab_Explainability_and_SHAP.ipynb): How to use the Shap package to explain XGB models and a couple of confounding factors examples. Taught as part of the DS3000 - Intro to Machine Learning course at Western.

These labs are available under the GPL v3, feel free to use them as you wish. I'll be grateful if you can point to the Github, as I'll keep these updated in subsequent iterations of the modules where I teach this. As always, these notebooks are provided with no guarantees.

Comments are welcome!
