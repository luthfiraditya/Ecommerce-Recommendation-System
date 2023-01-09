### Recommender Systems on E-commerce
A **recommender system (RS)** helps users that have no sufficient competence or time to evaluate the potentially overwhelming, number of alternatives offered by a web site.

–In their simplest form, RSs recommend to their users personalized and **ranked lists of items.**

The Value of Recommendation System

* Recommendations are responsible for 70% of the time people spend watching videos on YouTube.
* 75% of what people are watching on Netflix comes from recommendations, according to McKinsey.
* 35% of the purchases on Amazon are the result of their recommender system, according to McKinsey.

In this notebook, we will be implementing recommendation model to recommend product to user by using E-commerce data that has 3.265.689 rows and 3 columns applied to 377.716 user and 1.166 product. 

### Project Overview
Using am ecommerce dataset, this recommendation system was created that recommends to users which product they will like. 

### Methodology
We will try all the model based that available in surprise library such as SVD, NMF, Slope one etc. And choose the bers perfomance method.

I also using MLflow to tracking the experiment. You can read the full tutorial [here](https://medium.com/@luthfirdty/reproducible-data-science-experiment-using-mlflow-6f2f6e1baa8c) 
