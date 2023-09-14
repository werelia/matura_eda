# Matura Exam Analysis

In the Polish education system, the maturita exam is officially known as “matura” (egzamin maturalny). The matura exam is taken at the end of high school education. 
This exam is not mandatory, although Polish pupils are required to pass this exam in order to apply for higher education studies at Poland universities. 


To obtain information and visualize the data I cleaned, translated and analyzed datasets from Polish Statistic's Office about 'Matura' results over years.

# Data Cleaning and Preparation

I have deleted the columns that were not useful. Also, casted the numerical values to float as in dataset it appeared as string.
After that I have translated the columns and values using lambda functions.

# Data Analysis

The average results have not changed much over the years. In fact it was stable, with slight downtrend. It is worth to notice that the gap between Advanced and Basic level increased. 
In 2015 it was about ~13%, however in 2021 it increased to about 20%.


![image](https://github.com/werelia/matura/assets/69116952/a1ed8ab0-85b0-4c29-8231-f7b1f9e39787)


I grouped subjects into 'Language', 'Humanistic' and 'Science' categories. I have taken into account only advanced level as there was not many Science subjects on basic level.
It turns out that students feel significantly more comfortable with languages, than humanistic or science subjects.

![image](https://github.com/werelia/matura/assets/69116952/dc404e8e-b1b0-44d6-b065-a3dd6b8a7e98)


I decided to analyze the required subjects that each student must take: foreign language, mathematics and Polish.
Scores on basic level tend to be better. 

![image](https://github.com/werelia/matura/assets/69116952/d64df950-a5fb-4b1e-88b1-da951be0f584)



Exploring further it looks like men scored better in English and slightly better on Mathematics. However women scored much better in Polish exam with about 5% difference.
On advanced level men kept their position with English, but got outscored in mathematics and Polish.

![image](https://github.com/werelia/matura/assets/69116952/a1451530-2610-498e-8c30-9aee093bd2f9)

![image](https://github.com/werelia/matura/assets/69116952/035c475c-5145-4abf-be26-7f0ae33555fb)
average_score_by_category_advanced.png
![Alt text](/average_score_by_category_advanced.png?raw=true "")
