# Assignment 4 - Interviewing a Data Set


## Data Set

DC COVID-19 Outbreaks - DCGISopendata

* The purpose of this data is to describe the number of COVID-19 outbreaks by setting type over time in the District of Columbia.
* The data describes COVID-19 outbreaks that occur at various setting types. Data are presented by setting type (school building, university, office building, etc.) by week.

[Data Set](https://opendata.dc.gov/datasets/dc-covid-19-outbreaks/explore)

## Three Questions

1. What setting type corresponded with the highest number of COVID-19 outbreaks?
    * K-12 school buildings had the highest number of COVID-19 outbreaks. The top 9 weeks with the highest outbreaks, ranging from 19 in a week to 8 in a week, all happened at K-12 Schools.
2. Is there a correlation between the date of the oubreak and the setting of the outbreak? E.g. Did one location have an outbreak that resulted in a lot of cases over multiple weeks in a row?
    * No, there was no significant correlation.
3. Which setting type had the most instances of COVID-19 outbreaks in the data set?
    * K-12 school buildings had the most instances with 40. Then restaraurants/bars and chicldcare/daycare were tied with 35, then universities with 25 and then office buildings with 21.
    

## Cleaning & Analyzing the Data

The data was relatively clean. I had to widen the columns and then I deleted the "Time" and "Object ID" columns since they were not relevant to my inquiry into the data. I then filtered the data to find the information for my 3 questions.
* First I filtered the 'Outbreaks Number' column in descending order. I then observed which setting type correlated with the dates in which the highest number of outbreaks were reported.
* Then I filtered the 'Week Ending Date' column in descending order. I then tried to observe if there was a correlation between the time period and the setting type.
* Last, I created a pivot table and created a count of the instances of each setting type to observe which had the highest. 

## Headline and Nut Graph 

### Headline
High Rates of COVID-19 Outbreaks Observed at DC K-12 Schools

### Nutgraph 
With children under the age of 12 still not eligible to be vaccinated for COVID-19, K-12 schools are observing higher instances of outbreaks of the virus than settings in which the typical population is older and thus eligible to be vaccianted, resulting in higher vaccination rates. 

[Excel Workbook](https://github.com/Jeannie-Michele/datavisualization-fall2021/files/7469874/DC_COVID-19_Outbreaks.xlsx)



