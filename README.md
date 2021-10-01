# Kaggle-Survey-2020

# Kaggle-Survey-2020-Commpetition :
- The code in this Repo is submission for the annual Kaggle ML &amp; DS survey Competition.

# Our goal :

- In this competition we were given the data of the annual survey that Kaggle conducts every year and we were asked to explore this data and come up with some conclusions that might be unique and wouldn't be visible if we just glanced through the data.  
- I performed EDA on the data on features like - Age of a person, the country they live in, The Language they use to code, the IDEs they preder, their job titles and much more. After exploration we were able to come up with some conclusions which i have mentioned at the end of my notebook.

# Data
## Main Data:
- kaggle_survey_2020_responses.csv: 39+ questions and 20,036 responses
Responses to multiple choice questions (only a single choice can be selected) were recorded in individual columns. Responses to multiple selection questions (multiple choices can be selected) were split into multiple columns (with one column per answer choice).

## Supplementary Data:
- kaggle_survey_2020_answer_choices.pdf: list of answer choices for every question. With footnotes describing which questions were asked to which respondents.
- kaggle_survey_2020_methodology.pdf: a description of how the survey was conducted. You can ask additional questions by posting in the pinned Q&A thread.

## Cleaned and Transformed Data:
After cleaning, transforming and splitting the provided data(kaggle_survey_2020_responses.csv), we get 4 seperate DataFrames, namely:

- 1.questions: Questions asked in the survey
- 2.response: Responses entered by the respondents
- 3.professionals: Responses by professional respondents
- 4.non professionals: Responses by non-professional respondents

According to the Survey Methodology provided with the Data, a respondent can be categorised as `Non Professional` if the respondent is either a student or unemployed or has never spent money on cloud services.

## Tecnologies Used:
- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn 

# Few Results and Observations :

- 1.Most Kaggle user's are quite young with their age between 22-29. 
- 2.The Number of Men using Kaggle is huge as compared to the Woman. But we could see a significant growth in number of female Kagglers recently. 
- 3.Most Kaggler's are from India followed by USA and other countries. 
- 4.Most Kagglers have a Master's Degree. 
- 5.Majority of Kagglers are Students followed by Data Scientists and Machine Learning Engineers.
- 6.Most Kagglers have Experience of 3-5 Years in the Programming and then there are Kagglers with an experience of 1-2 years. 
- 7.Most Kagglers use Python followed by SQL and R. 
- 8.Most Recommended Languages for Data Science Beginners is Python followed by R. 
- 9.The most used data visualization Libraries are Matplotlib and Seaborn. 
- 10.The most used framework for Machine learning and Deep learning is Sci-Kit learn followed by Tensorflow along with Keras. 
- 11.The Most commonly used algorithms are Regression based followed by Decision trees, random forests and so on. 
- 12.Most users share their work on Github followed by Kaggle and Colab. There are also many who dont like to share their work. 
- 13.Most users preferred Coursera to learn Data science and Machine Learning followed by Kaggle Courses and Udemy. 
- 14.Most users make use of Kaggle notebooks and forums to stay updated about latest Data science and ML topics followed by Youtube and Blogs on various websites.
- 15.The most Preffered IDEs are Jupyter, VScode and PyCharm. 
