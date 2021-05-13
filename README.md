# CIS9650-Group6


Overview
===
  New York City has been the largest city in the United States since 1790. The Statue of Liberty welcomed millions of immigrants who came to America by ship in the late 19th and early 20th centuries. New York City is a symbol of America and its ideals of freedom and peace. Because it is the largest city in the United States, security has been one of the major problems plaguing these large cities. In our group's project we selected the NYPD's police reports of shootings from 2006-2019, which include data related to the incidents such as : date, time, borough，sex, age, ethnicity, etc. of victims and perpetrators as well as the latitude and longitude of the case。
  
What is the benefit of knowing this for us？
===
  For those of us who live in New York City, it is important that we have some understanding of the security situation in the boroughs and even streets where we live. Using our data analysis to understand how the security situation in New York City has been trending over the last decade or so and the level of danger at various times can help us better understand the safety of our own living environment.


  
  Datasets
  ===
  The data used in this project is generated from Data.gov.  Data.gov is the central clearinghouse for open data from the United States federal government and also provides access to many local government and non-federal open data resources.
  
  Here is the link to our data set：

https://catalog.data.gov/dataset/nypd-shooting-incident-data-historic

Size:~3.52MB

Metadata Created Date 	November 10, 2020

Python Libraries
=====
Data Cleanning: pandas

Data Exploratory analysis: matplotlib,

 Data Preprocessing and Exploratory
====
![GroupProject Step1](https://user-images.githubusercontent.com/83876072/117866253-eb5ac400-b264-11eb-9e0c-aedb9da47fcd.png)

Over the past decade or so, we have been able to see the number of shootings decline each year, and by the year ending 2019 the number of shootings in our cities was at the lowest level in the data

 Visualization
===
## Shooting case counts per boro
![Step4](https://user-images.githubusercontent.com/83876072/118156492-6946d880-b3e7-11eb-84dc-1646a5372518.png)


According to the chart, the darker the color of the area, the more the total number of shootings, first is the highest BROOKLYN in 14 years with 8913 incidents, and then the lowest is STATEN ISLAND with 646 incidents.







## Shooting case counts per time period
![Step3](https://user-images.githubusercontent.com/83876072/118066082-0cf2a300-b36c-11eb-81a8-f9f9d95ef1cd.png)

We can see a similar trend in both the Bronx and Brooklyn graphs, with both having the highest chance of an accident at night (6-12), followed by midnight. The trend is similar for Manhattan, Queens, and Staten Island, with more accidents occurring after midnight followed by night. However, the same is true for all boroughs where the morning is always the safest time.
## Age distribution of victims
![VictimsAge](https://user-images.githubusercontent.com/83876072/118179461-54783e00-b403-11eb-8c34-019eb9103ee4.png)

As we can see that roughly 82% of the victims were between the ages of 18-44. Younger people and older people account for less than 20% of the victims.

## Were the shootings purposeful?

![STEP6](https://user-images.githubusercontent.com/83876072/118184385-45948a00-b409-11eb-87d2-50570f6aee0f.png)


We are able to see from the statistical chart that only 19.1% are planned murders, e.g. you may have had a conflict with someone else/have a dispute of interest. But for 80.9% of the victims, there is no reason. Random shootings are the most frequent in New York


