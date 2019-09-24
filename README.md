# AdvancedAnalyticsLabs
Analytics labs notebooks, supporting analytics teaching for BSc and MSc business school modules. Currently, there are 13 labs uploaded divided into five topics:

## Intro to Python

1. [Introduction to Python](notebooks/python/Lab_1_Introduction_to_Python.ipynb): First few steps. Simple intro for people who might be already familiar with other languages, not meant for people with no programming experience!

2. [Functions and Revenue Management](notebooks/python/Lab_2_Revenue_Management.ipynb): Implementation of simple algorithms (Littlewood, EMSR-a and EMSR-b). Covers function creation and an introduction to PyPlot. Taught until 2019 in Southampton University as part of Advanced Analytics course.

## Banking Regulation

3. [Bond Pricing](notebooks/python/Lab_2_Bond_Pricing.ipynb): Teaches bond pricing, yields and clean/dirty prices. Taught from 2019 at Western University, as part of the [Banking Analytics](https://www.uwo.ca/stats/graduate/course-outlines/FM-9528-course-outline-20193.pdf) course I created. Replaces Revenue Management lab above, and also covers function creation and an introduction to PyPlot.

4. [Basel Capital Requirements](notebooks/python/Lab_3_Capital_Requirements_and_Pandas.ipynb): Covers Lambda functions and an introduction to Pandas in the context of the [Basel capital requirements formulas](https://www.bis.org/bcbs/irbriskweight.pdf).

## Credit Scoring

4. [Data Preprocessing](notebooks/python/Lab_3_Preprocessing.ipynb): Simple data preprocessing using pandas and scikit-learn.

5. [Weight of evidence transformation](notebooks/python/Lab_4_WoE.ipynb): How to calculate Weight of Evidence transformations in Python. Uses the excellent [scorecardpy](https://github.com/ShichenXie/scorecardpy) package by @ShichenXie.

6. [Logistic Regression](notebooks/python/Lab_5_Logistic_Regression.ipynb): Intro to scikit-learn and how to run a Lasso and Ridge regression.

7. [Scorecards and Random Forest](notebooks/python/Lab_6_Scorecards_and_Ensembles.ipynb): How to estimate a scorecard, run a Random Forest, and compare ROC curves.

## Deep Learning

8. [Introduction to Keras and Shallow ANN](notebooks/python/Lab_7_Keras_and_Shallow_Neural_Networks.ipynb): Gentle introduction to Keras and Tensorflow.

9. [Embeddings](notebooks/python/Lab_8_Embeddings.ipynb): How to calculate embedding layers, and how to use pre-trained embeddings. Currently uses Facebook's [fasttext library](https://fasttext.cc/).

10. [1D CNN and Keras' Model API](notebooks/python/Lab_9_ConvNets_for_Text_Analytics.ipynb): Intro to CNN, and how to use Keras' Model API. Also contains an implementation of [Kim et al. (2014)](https://arxiv.org/abs/1408.5882) CNN for text analytics.

11. [2D CNN and Gradient Backtracing](notebooks/python/Lab_10_2D_Convolutions.ipynb): 2D Convolutions for image classification. Use of pre-trained models (VGG16), training of own models and separable convolutions, and gradient backtracing to visualize what is being used to discriminate.

## Data Management and a Primer on Visualization

12. [SQL Refresher](notebooks/python/Lab_11_SQL_Connections.ipynb): Refresher on SQL, how to access it from Python, and a very light introduction to [SQLAlchemy](https://www.sqlalchemy.org/).

13. [Primer on Visualization](notebooks/python/Lab_12_Visualization_Primer.ipynb): A few plots using pyplot, seaborn and plotly. Very introductory primer.

These labs are available under the GPL v3, feel free to use them as you wish. I'll be grateful if you can point to the Github, as I'll keep these updated in subsequent iterations of the modules where I teach this. As always, these notebooks are provided with no guarantees.

Comments are welcome!
