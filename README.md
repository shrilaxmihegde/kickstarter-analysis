# Kickstarting with Excel

## Overview of Project
Conducted a data analysis to answer how many kickstaretr campaigns came close to their fundrasing goal in a short period of time and 
determine whether the length of a campaign contributes to its ultimate success or failure.Helping Louise learn trends and outcomes to decide create a campaign to fund her project , a play "Fever".



### Purpose
 Use excel features to analyze the data and plot various trends. Within the exersise, i learned how to use;
   1. Convert ***Unix Timestamps*** in to month/day/year format.
   2. How to create ***Pivot table*** and pivot chart based on the data.
   3. Apply ***Statistical Formulas*** to identify outliers(mean, median, quartiles, box chart)
   4. Use the ***Vlookup*** and ***countif*** forrmulas.


## Analysis and Challenge

### Analysis of Outcomes Based on Launch Date

![Theater Outcomes Based on Launch Date-pivot](/Resources/Theater_Outcomes_vs_Launch_pivot.png)


![Theater Outcomes Based on Launch Date](/Resources/Theater_Outcomes_vs_Launch.png)


Based on the trends we can conclude that, Theater category campaigs are more successful in Spring months, compared to winter months.Although high number of failed also in May. It shows total 166 theater kickstarter campaign May month is the successful 
and failuer which is the all other months.

### Analysis of Theater_Outcomes_vs_Launch

![Theater_Outcomes_vs_Launch](/Resources/Outcomes_vs_Goals.png)
From the Outcomes Based on Goals line chart we can see Goals between the $1000 to $5000 are most successful with 70% success rate. At the same time, we can see, campaign with very high goal are also with 67% success rate.
This indicates, campaign success or failure is not just based on the goal. There are other factors also play a role in campaign success or failure.
 

### Challenges and Difficulties Encountered
The raw data  contained dates in the ***UNIX timestamps***. We used a formula to convert them to a human readable date values. Using excel's built in feature of pivot table were used to extract the year.
Another one, perent and subcategory in concatinated format. But the ask was to report on them indipendently. So we used ***Text to colum*** feature of excel and separate them into two different columns.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
   1. May month had more number of successful campaigns related to Theater category.
   2. As year progressed number of successful campaigns started decling.

- What can you conclude about the Outcomes based on Goals?
   1. Campaings with goal amount between $1000 to $5000 had most success rate.(its average 70%).
   2. This chart indicates, campaign success or failuer can be impacted by other factors like backers count, category and time of the campaign.

- What are some limitations of this dataset?
The dataset is just represention of the sample from a handful number of countries, and it might not be accurate representation of global trends.
The data set has Goals and pledges amounts in various currencies and adjestments are the currency exchange rate has to be made to paint to accurate picture while comparing country statistics.

- What are some other possible tables and/or graphs that we could create?
We can create more graphs based on this data  by country, bakers_count,category and subcategory to view the campaign success/failuer by this dimentions.
 
