# Machine-Learning---Apache-Spark-with-Python-
## PySpark | Linear Regression &amp; Decision Tree

- Building LR and DT Models and with PySpark and MLlib
- Linear Regression Ploting

# Packages used:
from pyspark import SparkConf, SparkContext
from pyspark.sql.session import SparkSession
sc = SparkContext()
spark = SparkSession(sc)

from pyspark.ml.feature import VectorAssembler
from pyspark.ml.regression import LinearRegression
from pyspark.ml.evaluation import RegressionEvaluator
import matplotlib.pyplot as plt
import numpy as np
from numpy import polyfit

from pyspark.ml import Pipeline
from pyspark.ml.feature import StringIndexer
from pyspark.ml.regression import DecisionTreeRegressor
