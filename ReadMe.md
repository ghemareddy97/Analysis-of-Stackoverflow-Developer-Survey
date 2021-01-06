# Data Analysis on Stackoverflow Developer Survey- 2017

## Contents

* [Installation](#installation)
* [Motivation](#motivation)
* [About the data](#data)
* [About the notebook](#notebook)
* [Questions to solve](#questions)
* [Results](#results)
* [Licensing and Acknowledgments](#license)

## Installation {#installation}

Basic [Anaconda](https://www.anaconda.com/) installation would be enough to run this code. The following packages have been used to create this notebook.

| Library | Usage |
| ----------------- | ----------- |
|Pandas|to handle and manipulate data|
| Numpy | to perform numpy array operations |
| Matplotlib | for data visualization |
| re | regular expressions for performing string operations on the data in the dataframe |

## Motivation {#motivation}

For this project, I wanted to understand how to break into the field to become a developer and other aspects like success. The survey was conducted by Stackoverflow among developers in 2017.

## About the data {#data}

The data has two csv files. 

1. survey_results_public.csv
2. survey_results_schema.csv

survey_results_public.csv has 51392 rows and 154 columns with many insightful columns like EmploymentStatus, FormalEducation, ExpectedSalary. Each of these columns are based on certain questions that were posed to the respondents like How satisfied are you with your job and were asked to rate on it. 

survey_results_schema.csv is the schema used for the survey. Each row in the schema is the question posed to the respondent and the results are displayed in the first csv as columns. 

## About the notebook {#notebook}

The notebook has five sections that we will follow as a standard called the CRISP-DM process. 

1. Business Understanding
2. Data Understanding
3. Data Preparation 
4. Evaluating Results

## Questions to solve {#questions}

In this notebook we attempt to solve the following questions and hopefully get some very interesting insights which will be recorded in the results section. 

1. How many developers loved solving problems?  
2. How many developers have job and career satisfaction? Are more people satisfied with jobs or careers?
3. What languages, frameworks, databases and platforms developers used before vs what do they want to work on?
4. How did respondents become developers?
5. How does parent’s education influence success of respondent?

## Results {#results}

The main findings of the study can be found on my [blog post](https://ghemareddy97.medium.com/a-guide-to-becoming-a-developer-f46af73f0a4).

## Licensing and Acknowledgements {#license}
Stack Overflow has to be credited for conducting the survey and presenting the data. The licensing for data can be found on [Kaggle](https://www.kaggle.com/stackoverflow/so-survey-2017). Other than this, feel free to use the code!