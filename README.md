# AdvancedAnalyticsLabs
Analytics labs notebooks, supporting analytics teaching for BSc and MSc business school modules. Currently, there are 12 labs  uploaded divided into four topics:

## Intro to Python

1. [Introduction to Python](notebooks/python/Lab_1_Introduction_to_Python.ipynb): First few steps. Simple intro for people who might be already familiar with other languages, not meant for people with no programming experience!

2.a. [Revenue Management](notebooks/python/Lab_2_Revenue_Management.ipynb): Implementation of simple algorithms (Littlewood, EMSR-a and EMSR-b). Also teaches about functions, assignments, etc. Taught until 2019 in Southampton University as part of Advanced Analytics course.

2.b. [Bond Pricing](notebooks/python/Lab_2_Bond_Pricing.ipynb): Same as above, but now applies functions, assignments, etc. to the problem of bond pricing, teaching about yields and clean/dirty prices at the same time. Taught from 2019 at Western University, as part of the [Banking Analytics](https://www.uwo.ca/stats/graduate/course-outlines/FM-9528-course-outline-20193.pdf) course.

## Credit Scoring

3. [Data Preprocessing](notebooks/python/Lab_3_Preprocessing.ipynb): Simple data preprocessing using pandas and scikit-learn.

4. [Weight of evidence transformation](notebooks/python/Lab_4_WoE.ipynb): How to calculate Weight of Evidence transformations in Python. Uses the excellent [scorecardpy](https://github.com/ShichenXie/scorecardpy) package by @ShichenXie.

5. [Logistic Regression](notebooks/python/Lab_5_Logistic_Regression.ipynb): Intro to scikit-learn and how to run a Lasso and Ridge regression.

6. [Scorecards and Random Forest](notebooks/python/Lab_6_Scorecards_and_Ensembles.ipynb): How to estimate a scorecard, run a Random Forest, and compare ROC curves.

## Deep Learning

7. [Introduction to Keras and Shallow ANN](notebooks/python/Lab_7_Keras_and_Shallow_Neural_Networks.ipynb): Gentle introduction to Keras and Tensorflow.

8. [Embeddings](notebooks/python/Lab_8_Embeddings.ipynb): How to calculate embedding layers, and how to use pre-trained embeddings. Currently uses Facebook's [fasttext library](https://fasttext.cc/).

9. [1D CNN and Keras' Model API](notebooks/python/Lab_9_ConvNets_for_Text_Analytics.ipynb): Intro to CNN, and how to use Keras' Model API. Also contains an implementation of [Kim et al. (2014)](https://arxiv.org/abs/1408.5882) CNN for text analytics.

10. [2D CNN and Gradient Backtracing](notebooks/python/Lab_10_2D_Convolutions.ipynb): 2D Convolutions for image classification. Use of pre-trained models (VGG16), training of own models and separable convolutions, and gradient backtracing to visualize what is being used to discriminate.

## Data Management and a Primer on Visualization

11. [SQL Refresher](notebooks/python/Lab_11_SQL_Connections.ipynb): Refresher on SQL, how to access it from Python, and a very light introduction to [SQLAlchemy](https://www.sqlalchemy.org/).

12. [Primer on Visualization](notebooks/python/Lab_12_Visualization_Primer.ipynb): A few plots using pyplot, seaborn and plotly. Very introductory primer.


These labs are available under the GPL v3, feel free to use them as you wish. I'll be grateful if you can point to the Github, as I'll keep these updated in subsequent iterations of the modules where I teach this. As always, these notebooks are provided with no guarantees.

Comments are welcome!
