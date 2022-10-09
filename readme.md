# Stroke Dataset Exploration:
> Udacity Advanced Data Analysis Nanodegree Program
# Project Overview
> This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process.
* In Part I, Exploratory data visualization, you will use Python visualization libraries to systematically explore a selected dataset, starting from plots of single variables and building up to plots of multiple variables.
* In Part II, Explanatory data visualization, you will produce a short presentation that illustrates interesting properties, trends, and relationships that you discovered in your selected dataset. The primary method of conveying your findings will be through transforming your exploratory visualizations from the first part into polished, explanatory visualizations.


# Dataset
> According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.
This dataset is used to predict whether a patient is likely to get a stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relevant information about the patient.
you can find the original dataset [here](https://www.kaggle.com/fedesoriano/stroke-prediction-dataset?select=healthcare-dataset-stroke-data.csv)

# What are the main features causing Stroke?
Data Wrangling - *After assessing the data visually and programmatically the following quality issues were found and cleared:*
* wrong representing of null values in (smoking_status) column.
* erroneous data type of (id, gender, age, hypertension, heart_disease, ever_married, work_type, Residence_type, smoking_status, stroke) columns.
* missing data in [bmi, smoking_status] columns.
* 1 duplicated row.

# Summary of Findings

* most of the patients are females, non-smokers, and -thankfully- healthy who don't have hypertension, heart disease, or even had a stroke before.
* we can see that so many of them are adults and they're -sadly- over-weighted.
* positive relationship appears between Age and Average Glucose Level.
* from graphs, we can state that most of the patients who have experienced stroke events have high glucose levels with an average of 120-130 in their blood.
* we can also see that patients who have experienced a stroke were between 60-80 years old.
* at first I thought that BMI doesn't have a huge effect on Stroke but after another look at weight status, I figured that overweight and obese people are at higher risk of a stroke.
* another weird relationship showed that those who never smoked, nor have either hypertension or heart disease, are more likely to have had a stroke before .. but after further investigations, it's cleared that bad smoking habits do affect the Stroke.

# Key Insights for Presentation:

> As a final conclusion we can state that several variables are affecting having a stroke, like the nature effect of aging, having diseases history (Diabetes, Heart Diseases or Hypertension) in addition to bad habits like smoking or unhealthy food.
