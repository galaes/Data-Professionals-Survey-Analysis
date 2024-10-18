# Data Professionals Survey Analysis

## Table of Contents
  - [Objective](#objective)
  - [Dataset](#dataset)
  - [Tools](#tools)
  - [Methodology](#methodology)

### Objective

The primary goal of this project is to conduct a deep analysis and show the results of a survey made to data professionals in a comprehensive dashboard.

### Dataset

The dataset of Data Professional Survey (https://t.ly/oBTVD) contains the following key features:

- Unique ID: Indentification code of the surveyee
- Email: Email of the surveyee
- Q1 Which Title Best Fits your Current Role?: The answers include Data Analyst, Data Architect, Data Engineer, Data Scientist, Student/Looking/None, other.
- Q2 Did you switch careers into Data?: The answers are Yes or No.
- Q3 Current Yearly Salary (in USD): The answers are between eight options such as 0-40K, 41K-65K, 66K-85K, etc.
- Q4 What Industry do you work in?: The answers are between nine options such as Finance, Healthcare, Telecomunication, Construction etc.
- Q5 Favorite Programming Language: The answers are between six options such as Python, R, C/C++, etc.
- Q6 How Happy are you in your Current Position with the following? (Salary): The answers range from 1 to 10, where 1 is very dissatisfied and 10 is very satisfied.
- Q6 How Happy are you in your Current Position with the following? (Work/Life Balance): The answers range from 1 to 10, where 1 is very dissatisfied and 10 is very satisfied.
- Q6 How Happy are you in your Current Position with the following? (Coworkers): The answers range from 1 to 10, where 1 is very dissatisfied and 10 is very satisfied.
- Q7 How difficult was it for you to break into Data?: The answers range to easy to very difficult.
- Q8 If you were to look for a new job today, what would be the most important thing to you?: The answers are remote work, good work/life balance, better salary, good culture, and other.
- Q9 Male/Female? The answers are Male or Female.
- Q10 Current Age: Current age of the surveyee.
- Q11 Which Country do you live in?: Country where the surveyee lives.

### Tools
- Power Query for Data Cleaning
- Power BI for Data Visualization

### Methodology

#### 1. Data Collection and Preparation

The data cleaning done in Power Query includes:
- Data loading and inspection
- Removing of unneccesary columns
- Handling missing and duplicate values
- Transforming values for easy analysis

#### 2. Data Visualization

[Dashboard Power BI](https://github.com/galaes/Data-Professionals-Survey-Analysis/blob/ed7275d1b3cbaef4a2feb063c11661958e2b1bec/Data%20Professional%20Survey%20Dashboard.pbix)

<img src="images/Dashboard.png" width="90%" alt="images">


#### 3. Insights and Findings

- The highest peaks of total worldwide layoffs between March 2020 and March 2023 were in November 2022, with 53,451, and in January 2023, with 84,714.
- The consumer industry was the hardest hit for the period under study, with 45,182 layoffs, followed by the retail sector with 43,613 layoffs.
- Amazon, Google, and Meta were the top three companies with the most layoffs globally, with 18, 150, 12,000, and 11,000, respectively.
- This explains why the United States has the highest number of layoffs in the world, with 256,059 total layoffs between March 2020 and 2023.
