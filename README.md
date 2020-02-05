# Project 1 Group 1
* Tristan Holmes
* Angie Ong
* Ty Sorensen
* Ryan Dickson

## Motivation
With the 2020 Summer Olympic games upcoming, we were interested in analyzing data and making predictions for Tokyo. This was further motivated by a lack of Olympic research, especially prediction, on cursory examination. We were interested in identifying factors that predict medal success on both a country wide and individual basis

## Goals
We attempted to find answers to the following questions:
* How has gender and age breakdown of athletes changed over time?
* Is GDP predictive of medal success for countries?
* Is there a host country advantage that can be seen in the medal count?
* Does Body Mass Index (BMI) predict medal success? We use the men's 100m dash as a case study.

## Data Munging
Web scraped data was obtained from [Kaggle](https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results). GDP data from 2000 to 2018 was taken from the [World Bank](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD) For consistency in events and other factors, only data post WWII was considered. Further, the data was broken down by Summer and Winter games and analyses run separately.

## Age and Gender Analysis
The average age of participants in both the Summer and Winter games declined steadily after WWII until the 1980s, at which point it began to increase again.

[summer_age](images/summer_age_year.png)

[winter_age](images/winter_age_year.png)