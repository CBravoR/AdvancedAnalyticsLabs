# AdvancedAnalyticsLabs
Analytics labs notebooks, supporting analytics teaching for BSc and MSc courses. I've tought these at a business school and a statistics department, so I think they fit both reasonably well. Currently, there are 18 labs uploaded divided into five topics:

## Intro to Python

1. [Introduction to Python](notebooks/python/Lab_1_Introduction_to_Python.ipynb): First few steps. Simple intro for people who might be already familiar with other languages, not meant for people with no programming experience!

2. [Functions and Revenue Management](notebooks/python/Lab_2_Revenue_Management.ipynb): Implementation of simple algorithms (Littlewood, EMSR-a and EMSR-b). Covers function creation and an introduction to PyPlot. Taught until 2019 in Southampton University as part of Advanced Analytics course.

## Banking Regulation

3. [Basel Capital Requirements](notebooks/python/Lab_2_Capital_Requirements_and_Pandas.ipynb): Covers Lambda functions and an introduction to Pandas in the context of the [Basel capital requirements formulas](https://www.bis.org/bcbs/irbriskweight.pdf).

4. [Bond Pricing](notebooks/python/Lab_3_Bond_Pricing.ipynb): Teaches bond pricing, yields and clean/dirty prices. Taught from 2019 at Western University, as part of the [Banking Analytics](https://www.uwo.ca/stats/graduate/course-outlines/2021-22/FM9528A-2021.pdf) course I created. Replaces Revenue Management lab above, and also covers function creation and an introduction to PyPlot.

## Credit Scoring

5. [Data Preprocessing](notebooks/python/Lab_4_Preprocessing.ipynb): Simple data preprocessing using pandas and scikit-learn.

6. [Weight of evidence transformation](notebooks/python/Lab_5_WoE.ipynb): How to calculate Weight of Evidence transformations in Python. Uses my own fork of the excellent [scorecardpy](https://github.com/ShichenXie/scorecardpy) package by @ShichenXie, with some bugs fixed and other personalizations.

7. [Logistic Regression and Scorecards](notebooks/python/Lab_6_Logistic_Regression_and_Scorecards.ipynb): Intro to scikit-learn, how to run a Lasso and Ridge regression, and how to calculate a scorecard.

8. [Random Forest and XGBoosting](notebooks/python/Lab_7_Ensembles_and_Error_Measures.ipynb): How to run a Random Forest, an XGBoost model, tune parameters over a grid, use Shapley values to explain predictions, and compare ROC curves.

9. [PD / LGD Calibration](notebooks/python/Extra_Lab_PD_Calibration.ipynb): How to define ratings by segmenting the AUC curve and calibrate a long-run PD / downturn LGD adjusted by macroeconomic factors.

## Deep Learning

10. [Introduction to Keras and Shallow ANN](notebooks/python/Lab_8_Keras_and_Shallow_Neural_Networks.ipynb): Gentle introduction to Keras and Tensorflow. Updated to Tensorflow 2.0.

11. [Embeddings](notebooks/python/Lab_8_Embeddings.ipynb): How to calculate embedding layers, and how to use pre-trained embeddings. Currently uses Facebook's [fasttext library](https://fasttext.cc/). Updated to Tensorflow 2.0.

12. [1D CNN and Keras' Model API](notebooks/python/Lab_9_ConvNets_for_Text_Analytics.ipynb): Intro to CNN, and how to use Keras' Model API. Also contains an implementation of [Kim et al. (2014)](https://arxiv.org/abs/1408.5882) CNN for text analytics. Updated to Tensorflow 2.0.

13. [2D CNN and Gradient Backtracing](notebooks/python/Lab_2D_Convolutions.ipynb): 2D Convolutions for image classification. Use of pre-trained models (VGG16), and gradient backtracing to visualize what is being used to discriminate.

14. [Multimodal learning (a)](notebooks/python/Multimodal_Learning_House_Prices.ipynb): Regression example using ResNet50v2 and the Keras' Model API. Current multimodal example I use in my lectures combining categorical data and image data.

15. [Multimodal Learning (b)](notebooks/python/Airlines.ipynb): Example shown at the 2019 [Machine Learning Bootcamp](http://www.fields.utoronto.ca/activities/19-20/bootcamp_ML_F) at the University of Toronto. Mixed content from all other labs applied to sentiment analysis. Shows how to use categorical embeddings, text embeddings, and traditional structured data to improve evaluations.

## Other labs

16. [SQL Refresher](notebooks/python/Lab_11_SQL_Connections.ipynb): Refresher on SQL, how to access it from Python, and a very light introduction to [SQLAlchemy](https://www.sqlalchemy.org/).

17. [Primer on Visualization](notebooks/python/Lab_12_Visualization_Primer.ipynb): A few plots using pyplot, seaborn and plotly. Very introductory primer.

18. [Explainability and Confounding](Lab_11_SHAP.ipynb): How to use the Shap package to explain XGB models and a couple of confounding factors examples. Taught as part of the DS3000 - Intro to Machine Learning course at Western.

These labs are available under the GPL v3, feel free to use them as you wish. I'll be grateful if you can point to the Github, as I'll keep these updated in subsequent iterations of the modules where I teach this. As always, these notebooks are provided with no guarantees.

Comments are welcome!
