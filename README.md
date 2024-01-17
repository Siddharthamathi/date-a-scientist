# Date-a-scientist
**Introduction**
This project analyzes data from the online dating application OKCupid. In recent years, there has been a massive rise in the usage of dating apps to find love. Many of these apps use sophisticated data science techniques to recommend possible matches to users and to optimize the user experience. These apps give us access to a wealth of information that we've never had before about how different people experience romance.

The goal of this project is to scope, prep, analyze, and create a machine-learning model to solve a question.

**Project Goals**
In this project, the goal is to apply machine learning techniques to a data set. The primary research question that will be answered is whether an OkCupid's user astrological sign can be predicted using other variables from their profiles. This project is important since many users find astrological signs an important part of matches, and if users don't input their sign, OkCupid would like to predict which sign they might be.

**Data**
The project has one data set provided by Codecademy called profiles.csv. In the data, each row represents an OkCupid user and the columns are the responses to their user profiles which include multi-choice and short-answer questions.

**Analysis**
This solution will use descriptive statistics and data visualization to find key figures in understanding the distribution, count, and relationship between variables. Since the goal of the project is to make predictions on the user's astrological signs, classification algorithms from the supervised learning family of machine learning models will be implemented.

**Evaluation**
The project will conclude with the evaluation of the machine learning model selected with a validation data set. The output of the predictions can be checked through a confusion matrix, and metrics such as accuracy, precision, recall, F1, and Kappa scores.

**Data Characteristics**
The dataframe had 59,946 rows and 31 columns, this is a good sign since there seems to be enough data for machine learning.

The columns in the dataset include:

age: continuous variable of age of user
body_type: categorical variable of body type of user
diet: categorical variable of dietary information
drinks: categorical variable of alcohol consumption
drugs: categorical variable of drug usage
education: categorical variable of educational attainment
ethnicity: categorical variable of ethnic backgrounds
height: continuous variable of height of user
income: continuous variable of income of user
job: categorical variable of employment description
offspring: categorical variable of children status
orientation: categorical variable of sexual orientation
pets: categorical variable of pet preferences
religion: categorical variable of religious background
sex: categorical variable of gender
sign: categorical variable of astrological symbol
smokes: categorical variable of smoking consumption
speaks: categorical variable of language spoken
status: categorical variable of relationship status
last_online: date variable of last login
location: categorical variable of user locations
And a set of open short-answer responses to :

essay0: My self summary
essay1: What I’m doing with my life
essay2: I’m really good at
essay3: The first thing people usually notice about me
essay4: Favorite books, movies, show, music, and food
essay5: The six things I could never do without
essay6: I spend a lot of time thinking about
essay7: On a typical Friday night I am
essay8: The most private thing I am willing to admit
essay9: You should message me if…
