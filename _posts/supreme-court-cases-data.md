---
layout: post
title: US Supreme Court cases data exploration
subtitle: Exploring 1000 Songs
tags: [US Supreme Court,data visualisation,data exploration]
---

Today, I came across an interesting [dataset](https://think.cs.vt.edu/corgis/datasets/csv/supreme_court/supreme_court.csv). 
It contains all the relevant data about US Supreme Court cases. I always thought law was boring but the dataset piqued my interest.

The database to which this introduction pertains spans all four centuries of the Court's decisions,
from its first decision in 1791 to the Court's most recent decision. This dataset is a result of extraordinary work done by Harold J. Spaeth, Distinguished University Professor, emeritus, Michigan State University

Now, that the introduction of the dataset has been done, Let's see what interesting nuggets we come across.

> We have a total of 8893 court cases data here. The earliest court case decision is from November 1946 and the latest is from June 2018

Let's see, What types of cases does Supreme Court have ?

Criminal Procedures are the major cases handled by Supreme court followed by economic activity. 

Which group of people approach Supreme court ? Is it people worried about consititutional rights or businesses worried about over regularisation.

State Govts are the highest petitoners followed by Unites States Govt and then comes the "Person accused of crime". Please notice the choice of words.

If Govts are both State and US Govt approach the court so much how come maximum type of cases taken up by Supreme Court are Criminal procedures.

For that we will have to see the respondents categories. Respondents are parties against whom the petitoners have approached suprement court.
Again the respondents are also State Govt , US Govt followed by "person accused of crime".

Does that mean that when a Criminal case is judged in the lower court, irrespective of the decision, the aggrieved party petitions to the Supreme Courty. Even if this true, should the "Persons accused of crime" number be the more than State Govt and US Govt.

Let's check, the number of cases where respondent and petitioner or either State of US Govt.


Citation:
Harold J. Spaeth, Lee Epstein, et al. 2018 Supreme Court Database, Version 2018 Release 2. URL: http://Supremecourtdatabase.org
