---
layout: post
title: US Supreme Court cases data exploration
subtitle: Exploration of Supreme Court database
tags: [US Supreme Court,data visualisation,data exploration]
---

Today, I came across an interesting [dataset](https://think.cs.vt.edu/corgis/datasets/csv/supreme_court/supreme_court.csv). 
It contains all the relevant data about US Supreme Court cases. I always thought law was boring but the dataset piqued my interest.

The database to which this introduction pertains spans all four centuries of the Court's decisions,
from its first decision in 1791 to the Court's most recent decision. This dataset is a result of extraordinary work done by Harold J. Spaeth, Distinguished University Professor, emeritus, Michigan State University

Now, that the introduction of the dataset has been done, Let's see what interesting nuggets we come across.

> We have a total of 8966 court cases data here. The earliest court case decision is from November 1946 and the latest is from June 2018

Let's start with checking the type of Issues Supreme Court handle ?
[add issue area plot]
Criminal Procedures are the major cases handled by Supreme court followed by economic activity. 

Which group of people approach Supreme court ? 
They are called petitoners. They petition the Court to look at their case. 

[add petitioner graph plot]

State Govts are the highest petitoners followed by Unites States Govt and then comes the "Person accused of crime" and "Person convicted of crime" Please notice the choice of words. I can understand "Perons convicted of crime" approaching Supreme Court to overturn their decisions but why are the "Persons accused of Crime" in such a high number in petitioner category.

Let's look at the respondents categories. Respondents are parties against whom the petitoners have approached supreme court.

[add respondents graph plot]

Again the mojor respondents are State Govts and US Govt followed by "Person accused of crime".

Does that mean that when a Criminal case is judged in the lower court, irrespective of the decision, the aggrieved party petitions to the Supreme Court. 

Information: This Dataset constitutes 310 different categories of Respondents and Petitioners, I am probably using broad brushstrokes in my observation. Except for the top 15 categories, I have clubbed all other categories under "Others".

State Govts and US Govt approach the Suprement Court a lot, let's see if they ever approach against each other.
[add_state_US govt plot]
> In 195 cases State Govts and US Govt are against each other.

Most of the cases move to Supreme Court which orginate from other courts. The top 5 lower courts which refer the most to the Supreme Court are

[add lower court plot]

Most of the cases to Supreme Court originate from lower courts but how many are cases come directly to Supreme Court

>Only 344 cases i.e 3.68% of the cases in the last 70 years have been directly handled by Supreme Court.

I wonder what makes these cases special. Let us look at the type of cases which only Supreme Court handles.

[add special cases plot]

Interstate Relations is the top category, makes sense, it is followed by Civil Rights.

How does Supreme Court take a decision ? Does it say you win or lose to the petitioning party.

Let us see the type of decisions Supreme Court takes.

Most of the decisions taken by the court are "Opinion of the Court" but in quite a few cases it is "per curiam" meaning the decision is taken collectively in the name of the court rather than in the name of Judge. 

I am curious of the type of the cases where a Judge doesn't go by opinion but by "per Curiam"



Citation:
Harold J. Spaeth, Lee Epstein, et al. 2018 Supreme Court Database, Version 2018 Release 2. URL: http://Supremecourtdatabase.org
