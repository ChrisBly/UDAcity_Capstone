# Udacity: Data Scientist Capstone

#### Table of Contents:

1: Libraries:
2: Motivation for the project
3: files in the repository
4: Blog Post Link.


### End Table of Contents

1: Libraries:

# import libraries
import pandas as pd
import numpy as np
import warnings
warnings.filterwarnings('ignore')
import matplotlib.pyplot as plt
import re 
import nltk
from nltk.tokenize import word_tokenize
from nltk.tokenize import sent_tokenize
from nltk.stem import WordNetLemmatizer
from nltk.tokenize import word_tokenize
from sklearn.pipeline import Pipeline
from sklearn.feature_extraction.text import CountVectorizer, TfidfTransformer
from sklearn.multioutput import MultiOutputClassifier
from sklearn.ensemble import RandomForestClassifier
from sklearn.model_selection import train_test_split
from nltk.corpus import stopwords 
from sklearn.metrics import classification_report
from sklearn.model_selection import GridSearchCV
from sklearn.linear_model import LogisticRegression
import seaborn as sns

2: Motivation for the project:

## Project Definition:

### Project Overview

- The Mobile Gaming Industry revenue will be 152 Billion US by the end of 2019, there has been 9.6 Billion investments in the last 18 months. If this level of investment stays at current levels, then that is higher than the combined eight year of previous investment in the industry.

- As the market growth increases, there is a problem in certain regions to get users to use in-app purchase. We be using the Kaggle: apple-app-store-strategy-games data set.

### Problem Statement

#### Start up company in the Apple mobile strategy gaming space is looking to ways to increase the global coverage and revenue. There are three business cases for different types of Apple game apps:

- 1: Mobile strategy: Storm Gang: This game contains In-app Purchases and is english only.

- 2: Mobile strategy: Wildfire Rabbits : This game contains In-app Purchases and is multi languages.

- 3: Mobile strategy: Koalas Crossing This game contains Price amd In-app Purchases and english only,age range: 4 to 16.

#### The Business Case for each Mobile strategy game has been investigated, however due to changes in the way customer has been spending there money, they want to use the apple stored data to predict where the customers will be spending there money, In-app Purchases, multi languages or age range

#### Metrics
Model Performance Metrics will be using the classification_report
F1, recall, precision metrics to compare how are modellings are performing

3: files in the repository:

3.1: readme.md contains the information and files in the project. 
3.2: Data Scientist Capstone - Project 7.ipynb - Data Modelling
3.3: appstore_games.csv data set from Kaggle

4: Blog Post Link.

4.1: https://medium.com/@chrisbnsw/udacity-data-scientist-capstone-kaggle-mobile-gaming-a2afb688033c
This link contain a blog journal on the steps taken in this project.



