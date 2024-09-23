https://public.tableau.com/shared/M2CW6YSCH?:display_count=n&:origin=viz_share_link

# Project Background

The aim of this document is to provide context for the project I worked on. 

We came across a dataset of British Airways reviews, consisting of 1343 rows and 16 columns. This dataset facilitates the analysis of customer feedback to identify areas needing improvement and to optimize the overall passenger experience.

We received two files: one containing the reviews with details and the other with countries to create a mapped dashboard. These files had already been cleaned by the company, so there was no need to go through a cleaning process. However, we found one null value that needed to be removed.


# Cleaning Process

 During the cleaning process, there was a NULL value in the traveler_type. However, while creating the filter in Tableau, you can also choose to exclude the NULL values.

We aimed to create a dynamic dashboard to provide a great visualization. The main goal was to develop metrics for the reviews, such as overall rating, entertainment, food, among others. We also intended to create a timeline to identify patterns in the reviews. The next step was to create filters for seat types, continents, or aircraft.

Some questions we had in mind:

- How has the number of reviews evolved over time?
- Does business class have better ratings than economy class?
- Does the type of aircraft impact the reviews?
…



# Insights Deep Dive

We first started by creating a map using the Place value to generate a dynamic map. Next, we created a parameter called Metric to encompass all the characteristic values. We then developed a timeline with time. After that, we filtered the data by seat, traveler, aircraft, and continent.

Following this, we summarized the relevant data, including average rating, value for money, cabin staff, ground service, seat comfort, food rating, and entertainment rating.

We then created an overall rating by month to observe the evolution of ratings over time. Additionally, we calculated the average overall rating by aircraft type to analyze if the ratings were correlated to the type of aircraft. We also produced a graph showing the number of reviews.

Finally, we assembled a dashboard incorporating all these metrics. The dashboard is well-organized, dynamic, color-coded, and has an intuitive interface.

 

# Executive Summary
## Overview of Findings

Given that this is an interactive dashboard, the analysis options are numerous.

On one hand, certain types of aircraft, such as the Boeing 787, have received better ratings for entertainment, food, and seats. On the other hand, aircraft like the A321 have lower ratings. Therefore, improving these aspects could likely enhance the ratings.

It has been observed that the perceived value is lower than the actual price paid. In other words, economy class passengers feel that what they receive for the price is better than business class. Offering a perceived value that exceeds expectations in business class could improve ratings and increase sales. In fact, a similar situation occurs with first class. 

However, this does not happen worldwide. European countries and Canada perceive a high value in first class, so these issues need to be addressed in other countries.


The analysis can really be approached in different ways, such as the following:

•	Facilitating analysis of customer feedback to identify areas necessitating enhancement and to optimize the overall passenger experience.
•	Conducting sentiment analysis to gauge public sentiment and perceptions towards the company.
•	Comparing performance against other airlines within the industry.
Given that this is an interactive dashboard, the analysis options are numerous.

On one hand, certain types of aircraft, such as the Boeing 787, have received better ratings for entertainment, food, and seats. On the other hand, aircraft like the A321 have lower ratings. Therefore, improving these aspects could likely enhance the ratings.

It has been observed that the perceived value is lower than the actual price paid. In other words, economy class passengers feel that what they receive for the price is better than business class. Offering a perceived value that exceeds expectations in business class could improve ratings and increase sales. In fact, a similar situation occurs with first class. 

However, this does not happen worldwide. European countries and Canada perceive a high value in first class, so these issues need to be addressed in other countries.

The analysis can really be approached in different ways, such as the following:

•	Facilitating analysis of customer feedback to identify areas necessitating enhancement and to optimize the overall passenger experience.
•	Conducting sentiment analysis to gauge public sentiment and perceptions towards the company.
•	Comparing performance against other airlines within the industry.

![Dashboard 1](https://github.com/user-attachments/assets/d2f33dcb-aee2-44e6-b73a-09cf50641e99)


