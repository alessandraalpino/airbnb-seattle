# Project Motivation

This is a project for my Data Scientist NanoDegree at Udacity. I found a dataset of listings of Airbnbs in Seattle to explore some questions.  We'll try to answer the following questions and give suggestions to people who wants to boost their listings on Airbnb or start hosting:

1. Which host's characteristics most affect reviews?
2. Which host's characteristics most affect prices?
3. How do the different accommodation's characteristics relate to price?

The dataset contains 3818 listings of airbnbs and 92 columns about it's characteristics, such as: reviews, price, number of bedrooms… You can find this dataset in Kaggle. 

[Here](https://medium.com/@alessandraalpino/tips-that-will-make-you-boost-your-airbnb-2fd523975f16) you can read my article on Medium about this analysis. 

# Installation
```
import pandas as pd
import numpy as np 
import seaborn as sns
import matplotlib.pyplot as plt
from scipy import stats
import plotly.graph_objects as go
```

# File Descriptions

**Udacity_project.ipynb** -> notebook with analysis 

**listings.csv** -> dataset that can be found in [Kaggle](https://www.kaggle.com/datasets/airbnb/seattle?resource=download&select=listings.csv)


# Results

Suggestions to people who wants to boost their listings on Airbnb or start hosting:

1. Try to answer guests **within 1 day or less**.
2. Be a **superhost**.
3. Be aware that price is related to basic characteristics of the place, such as **number of people it accommodates**.
