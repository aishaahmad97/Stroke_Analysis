# Stroke Dataset Exploration:
## by: A'isha Ahmad Mahmoud Eshra


## Dataset

> According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.
This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.
you can find the original dataset here: https://www.kaggle.com/fedesoriano/stroke-prediction-dataset?select=healthcare-dataset-stroke-data.csv

> What are the main features causing Stroke?

> Data Wrangling:
1- after i downloaded the dataset I did an assessment visually and programmatically using pandas.
2- I found some quality issues like:
	* wrong representing of null values in (smoking_status) column.
	* erroneous data type of (id, gender, age, hypertension, heart_disease, ever_married, work_type, Residence_type, smoking_status, stroke) columns.
	* missing data in [bmi, smoking_status] columns.
	* 1 duplicated row.
3- I cleaned the dataset using pandas and numpy + I added 2 catigorical columns ['age_groups', 'weight_status] to facilitate visualization and analysis.

## Summary of Findings

1- in our data most of them are female non-smookers and -thankfully- healthy who doesn't have hypertension, heart disease or even had a stroke before.
2- we can see that so many of them are adults and they're -sadly- over weighted.
3- positive relationship appears between Age and Average Glucose Level.
4- from graphs we can state that most of the patients who has experienced stroke event have high glocuse level with average like 120-130 in their blood.
5- and we can also see that patients who has experienced stroke were between 60-80 years old.
6- at first i thought that BMI doesn't have a huge affect on Stroke but after another look at weight status i figured that actually over weight and obese are at higher risk of a stroke.
7- another weired relathionship showed that those who never smoked, nor have either of hypertension or heart disease, more likely to have had a stroke before .. but after further investigations it's cleared thta bad smoking habits DOES effect the Stroke.

## Key Insights for Presentation

> As a final conclusion we can state that several variables are affecting have a stroke like diseases history (Suger, Heart Diseases or hypertension) in addition to bad habits like smoking or unhealthy food .. and the natural effect of aging.