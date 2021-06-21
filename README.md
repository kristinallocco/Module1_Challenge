# Module 1 Challenge
Columbia Data Analysis Bootcamp - Due 20Jun2021


## Overview of Project
The purpose of this project was to utilize excel in an effort to analyze the outcomes of kickstarter funding campaigns. In particular, the correlation between the launch month and outcome for theater endeavors, as well as whether fundraising goals were a factor in the success or failure of a proposed play. 

## Analysis and Challenges

In order to preform the analysis, I first calculated the launch year and month from the source data, and from there, created a pivot table to demonstrate a summary of the outcomes of theater campaigns, whether it be success or failure, for each month. From the table, I then created a line graph, to depict the relationship between success or failure and each particular month. Regarding the relationship between the fundraising goals, and the outcome of the outcome of a potential play, I first created a query, which allowed me create a custom formula to label the appropriate fundraising limits, and then grouped the data by aforementioned categories. Following this, I migrated the data into a table, and then found the total for each of the outcomes, the number of plays as well as the respective percentages. 

In regards to challenges I faced, the first that comes to mind is the grouping of the query. I am certain there is a way to lay out the columns automatically, whether it be transposing or another built in method, though I was unable format the data innately within the quey. Had I been able to do so, I would have the summations and percentages into the query, which would have been far more efficient. 


## Results

### *Outcomes by launch Month*

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/85713470/122620013-dd684200-d05f-11eb-8bdd-c358ffac8977.png)

Theater Kickstarters tend to have a better chance of succeeding when launched in the late Spring and early Summer months [May = 111, Jun = 100, Jul = 87]. Additionally, successful outcomes appear to steadily decrease following the month of July, and then pick back up in the month of April.

### *Outcomes by Fundraising Goals*

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/85713470/122619900-911d0200-d05f-11eb-84ee-6b3f710a8a54.png)

Plays that had a fundraising goal of less than $4,999 had the highest likelihood of succeeding [Less than 1000 = 76%; 1000 to 4999 = 73%], and encompassed 68% of the total number of projects. Projects that required a minimum of $45,000 had the lowest rate [$45,000 to 49999 = 0%; Greater than $50,000 = 13%].

### *Limitations of the Data*

Regarding the limitations of the analyses, one additional avenue that could be explored is the percentage of funds raised out of the goal, rather than just the total amount of funds raised. Although the results appear to favor with lower fundraising goals [Less than $1000 76% success rate; Greater than $50,000, 13% success rate], this could be due to the monetary goal not being met, and the costlier projects are unable to continue forward with production. 

Additionally, the lower end of the cost spectrum [Less than $15,000] comprises 91% [961 plays] of the total number projects, and the upper end [above $15,000] is approximately 8% of the total projects. Now although the success rate is tabulated within the category, the sample size, proportionally speaking, is quite low, so the rates may not be as indicative of the outcomes costlier plays as they would be of the lower end of the spectrum. 

Another variable that could be explored for the productions is whether they are business ventures, produced by communities or by schools/ academic centers. Seeing as the outcomes appear to taper off during the school year, it would be interesting to see if the theater projects are put on during the late Spring and early Summer months are school and/ or community productions, as well as if that correlates to projects with lower budgets having a higher success rate. 
