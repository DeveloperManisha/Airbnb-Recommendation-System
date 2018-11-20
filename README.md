# CMPE256-Airbnb

Airbnb application supports adding your apartment/room to the platform as a host and booking an apartment/room as a user. The objective is to use Airbnb’s publicly available data in order to develop business logic and recommendation engine to support customers as well as hosts in order to recommend favorable listings and to predict optimal pricing for host respectively

Dataset(s) Used:

Dataset: AirBnB Open data NYC

Size: 910.7 MB

- Module 1:
Predict Rating from review comments
Performing sentiment analysis of the reviews and categorize reviews into a different set of ratings using machine learning algorithms. This is useful to visualize the user ratings better for a particular property.

- Module 2:
Recommend the listing to the user, based on collaborative filtering
Building a feature matrix based on the user reviews ratings computed from sentiment analysis in order to predict recommend properties to the user.

- Module 3:
Predict the optimum listing price for the host
As the listing prices of the property changes based on holidays, weekends, season and month.  The idea is to analyze the price trends over the period and predict the optimum listing price for the selected period. This price can be used by the host to maximize profit and increase the occupancy rate.


Technologies & Tools used:

Libraries: pandas, numpy, matplotlib, Surprise, Spark ml, Spark  MLib, NLTK, scikit
Python 3 with Jupyter Notebook, Spark

Dependencies:
- Install surprise

- pip install scikit-surprise

- conda install -c conda-forge scikit-surprise (Windows, Mac, Linux) using conda

- Install PySpark

Reference tutorial:https://medium.com/@GalarnykMichael/install-spark-on-windows-pyspark-4498a5d8d66c
