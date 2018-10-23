# Mission_TA
- <a href="http://sehir.edu.tr/"> Istanbul Sehir University </a> - CS340 Computer Systems
This repository contains various Data Science projects using <a href="https://spark.apache.org/">Spark</a> (some include <a href="https://console.bluemix.net/catalog/"> Bluemix</a>) that I used as a TA for Computer Systems.

<div>
<img src="https://upload.wikimedia.org/wikipedia/en/b/bf/Sehir_University_Logo.png" width=100>
<img src="https://cdn-images-1.medium.com/max/1350/1*Gvo0ep9MCvQcCQUBQ0TD9Q.png" width=500>
</div>


## Projects

### Spark Context, RDDs & MapReduce: GO triangles

- Data: The XY coordinations of three stones thrown 1 million times on a 100x100 Grid
- Tasks:
  - Finding valid triangles
  - Finding neighbour triangles
  - Calculating triangles circumferences
  - Exploring the relation between the number of triangle's neighbours and its circumference
- <a href="https://nbviewer.jupyter.org/github/AmmarRashed/Mission_TA/blob/master/CS340_spring_2018/triangles_weeks3_5.ipynb"> Link</a>

#### Lessons
- Intro to Spark sessions
- Learning how to use ```lambda``` functions
- Learning about RDD operations
- Learning how to use MapReduce

### Dataframes: Analyzing books ratings
- Books:
  - Data: Books names, authors, tags, ratings and other features
  - Task: Getting top rated books and tags, and presenting the results in pretty visuals
  - <a href="https://nbviewer.jupyter.org/github/AmmarRashed/Mission_TA/blob/master/CS340_spring_2018/week7_dataframes.ipynb">Link</a>
- Movies:
  - Data: <a href="https://grouplens.org/datasets/movielens/"> MovieLens 20m</a>
  - Task: Getting top rated movies using dataframe operations
  - <a href="https://nbviewer.jupyter.org/github/AmmarRashed/Mission_TA/blob/master/CS340_spring_2018/week7_movielens.ipynb">Link</a>

#### Lessons

- Learning how to ask insightful questions about data
- Learning how to use dataframes operations to get insights from the data
- Learning how to present the analysis in a comprehensive manner

### Linear Regression: Predicting house prices

- Data: House Sales in King County, USA
- Task: Predict the price of a house based on the other features
- <a href="https://nbviewer.jupyter.org/github/AmmarRashed/Mission_TA/blob/master/CS340_spring_2018/week9_ml_linearregression.ipynb">Link</a>

#### Lessons

- Learning about supervised learning
- Cleaning and processing data before feeding them into a regression model (Vectorization
- Understanding regression in the context of a real-world problem
- Learning how to evaluate regression models

### Classification: "Spam or Ham" message classifier

- <a href="https://github.com/AmmarRashed/Mission_TA/blob/master/CS340_spring_2018/data/spam.csv">Data</a>: Messages labeled as Ham or Spam
- Task: Training a ML-based message classifier
- <a href="https://nbviewer.jupyter.org/github/AmmarRashed/Mission_TA/blob/master/CS340_spring_2018/last_CV_Pipeline.ipynb">Link</a>

#### Lessons

- Learning about classification algorithms
- Learning about Cross-validation
- Learning how to use pipelines
- Learning how to evaluate classification models
- Learning about f1-score, and ROC and PR Curves
