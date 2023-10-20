# Matura Exam Analysis

In the Polish education system, the maturita exam is officially known as “matura” (egzamin maturalny). The matura exam is taken at the end of high school education. 
This exam is not mandatory, although Polish pupils are required to pass this exam in order to apply for higher education studies at Poland universities. 


To obtain information and visualize the data I cleaned, translated and analyzed datasets from Polish Statistic's Office about 'Matura' results over years.

## Data Cleaning and Preparation

I have deleted the columns that were not useful. Also, casted the numerical values to float as in dataset it appeared as string.
After that I have translated the columns and values using lambda functions.

## Data Analysis

The average results have not changed much over the years. In fact it was stable, with slight downtrend. It is worth to notice that the gap between Advanced and Basic level increased. 
In 2015 it was about ~13%, however in 2022 it increased to about 20%.

![Alt text](/average_score_over_years.png?raw=true "")


I grouped subjects into 'Language', 'Humanistic' and 'Science' categories. I have taken into account only advanced level as there was not many Science subjects on basic level.
It turns out that students feel significantly more comfortable with languages, than humanistic or science subjects.

![Alt text](/average_score_by_category_advanced.png?raw=true "")

I decided to analyze the required subjects that each student must take: foreign language, mathematics and Polish.
Scores on basic level tend to be better. 

![Alt text](/most_common_subjects_by_gender_basic.png?raw=true "")

![Alt text](/most_common_subjects_by_gender_advanced.png?raw=true "")

Exploring further it looks like men scored better in English and slightly better on Mathematics. However women scored much better in Polish exam with about 5% difference.
On advanced level men kept their position with English, but got outscored in mathematics and Polish.


## Power BI Visualization

The visualization made in PowerBI can be found in the file "matura_PowerBi.mp4".


