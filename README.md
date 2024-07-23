# FORBES BILLIONAIRES ANALYSIS- MICROSOFT EXCEL
### PROJECT OVERVIEW

Inspired by my keen interest in global wealth distribution, I embarked on this project to analyze the financial growth, trends, and patterns of global billionaires as ranked by Forbes in April 2024 over the past year.

### TABLE OF CONTENTS

- [DATA SOURCE](#data-source)
- [TOOLS USED](#tools-used)
- [DATA PREPARATION](#data-preparation)
- [EXPLORATORY DATA ANALYSIS](#exploratory-data-analysis)
- [VISUALIZATION](#visualization)
- [INSIGHTS](#insights)
	
### DATA SOURCE

I sourced the dataset from Kaggle and retrieved as a CSV file.

Dataset URL: https://www.kaggle.com/datasets/guillemservera/forbes-billionaires-1997-2023

This dataset comprises 2782 entries and 19 columns, including:

•	Rankings of global billionaires

•	Net worth details

•	Personal details such as names, age, gender, and birth dates

•	Residence details and citizenship

•	Business category and industry classifications

•	Affiliations with various organizations

•	Indicators like "self-made" and current wealth status

### TOOLS USED

•	Microsoft Excel: For data preparation, analysis and visualization.

### DATA PREPARATION

During the data preparation phase, I used Microsoft Excel for cleaning and manipulating the data.

#### Data Cleaning:

•	Removed the "year" and "month" columns since the dataset pertains to April 2024, making them redundant.

•	Removed the "business industry" column as it was identical to the "business category" column.

•	Auto-fitted row heights and column widths for better readability.

•	Checked for duplicates and found none.

•	Filled blank cells with "NULL".

•	Standardized column titles to start with uppercase letters.

#### Data Manipulation/Processing:

•	Inserted the dataset into a table named Billionaires_2024.

•	Moved the "First_name" column to the correct position.

•	Added a dollar sign ($) to the "Net_worth" column.

•	Converted "Birth_date" to "Birth_year" format.

#### EXPLORATORY DATA ANALYSIS

I formulated guiding questions and used pivot tables to explore and analyze the dataset, extracting valuable insights.

#### Guiding Questions:

•	How many billionaires were ranked in the dataset?

•	Who were the top 5 ranked billionaires and their net worth distribution?

•	What was the average age of the billionaires, and who were the oldest and youngest billionaires?

•	What was the gender distribution of the billionaires?

•	Which were the top 10 countries by billionaire citizenship?

•	Which were the top 10 countries of residence?

•	What was the proportion of business categories?

•	How did the net worth of self-made billionaires compare to those who inherited wealth?

•	How did the wealth status change over the past year?

### VISUALIZATION

I utilized pivot charts to create an interactive dashboard for presenting the analysis results.

### INSIGHTS

##### Total Billionaires: 
2781 billionaires were ranked with 2692 ranking positions.

##### Top 5 Billionaires:

o	Bernard Arnault: $233.0B

o	Elon Musk: $195.0B

o	Jeff Bezos: $194.0B

o	Mark Zuckerberg: $177.0B

o	Larry Ellison: $141.0B

##### Average Age: 

65.69 years. 

##### Oldest billionaire:

George Joseph (102 years, $1.7B, ranked 1851). 

##### Youngest billionaires: 

Clemente Del Vecchio (19 years, $4.7B, ranked 661) and Livia Voigt (19 years, $1.1B, ranked 2545).

##### Gender Distribution: 

2188 males and 322 females.

##### Top 10 Countries by Citizenship:

o	United States: 744

o	China: 375

o	India: 174

o	Germany: 125

o	Russia: 101

o	Italy: 63

o	Hong Kong: 63

o	Canada: 61

o	Brazil: 56

o	United Kingdom: 55

##### Top 10 Countries of Residence:

o	United States: 768

o	China: 397

o	India: 165

o	Germany: 102

o	United Kingdom: 82

o	Russia: 80

o	Switzerland: 77

o	Hong Kong: 66

o	Italy: 55

o	Brazil: 47

##### Business Categories Distribution:

o	Finance & Investments: 388

o	Technology: 303

o	Manufacturing: 282

o	Fashion & Retail: 255

o	Food & Beverage: 196

o	Healthcare: 183

o	Diversified: 179

o	Real Estate: 178

o	Energy: 93

o	Media & Entertainment: 91

o	Automotive: 72

o	Metals & Mining: 70

o	Service: 50

o	Construction & Engineering: 43

o	Logistics: 39

o	Sports: 38

o	Telecom: 30

o	Gambling & Casinos: 20

##### Wealth Status:

o	Self-made billionaires: 1684

o	Inherited wealth billionaires: 826

##### Wealth status change over the past year:

	Increased: 1480

	Decreased: 707

	Remained Even: 232

	Returned to List: 91
