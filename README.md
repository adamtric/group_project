# Project Roadmap

## Topic
Researching effects of working remotely on the productivity of S&P 500 companies.

### Reason topic selected: 
Reason topic chosen was due to the unprecedented disrupting effect 
of the Covid-19 Pandemic on the global labor market during 2020.
Short term consequences included millions of people losing jobs while others had to adjust rapidly
to working from home. Other workers were deemed essential and continued to work in hospitals,
grocery stores, sanitation, and warehouse workers all while under new protocols to reduce the
spread of the virus. This topic was selected to specifically understand how companies were 
affected by the paradigm shift of having a large portion of the workforce suddenly start 
working from home. 

## Team Layout

### Team Roles
- Square: Responsible for Repo - Adam
- Triangle: Create machine learning mockup - Brian
- Circle: Create mockup of database - Melis
- X: what languages should be used? - Adam, Brian, Melis

### Team Communication: 
Every Tues/Thurs night we are working in tandem communicating through Zoom. We also are taking advantage of our Slack channel to get out
updates to team. We also are meeting every Saturday at 1:30 PM to discuss updates and any areas where we may need assistance.

## Data 

We are pulling annual earnings from Yahoo Finance starting 
with the beginning of 2018 through the end of 2021 so that we have two years
of precovid data to compare to postcovid data (2020-2021). BLS is also a great secondary source
to help explore productivity and cost statistics during the Pandemic. Headcount info was extracted from Liberated Stock Trader.

### Questions hope to answer with the data?
- Did remote work affect company earnings during covid vs precovid earnings?
- Does working remotely save companies money and did it affect quarterly earnings?
- How did remote work impact worker productivity (measured in financial numbers per employee)
- How did remote work impact expenses of an organization?


## Machine Learning
Present provisional machine learning model that accomplishes the following:
- Unsupervised Model will take in multiple points of historical financial data (2018-2021) and output a classification of of how productive each organization was over the past few years (3 Clusters)
- Model will also utilize company size, and whether they offered remote work during these time frames
- Financial info (per employee) will include Net Income, Total Revenue, Total Operating Expenses, Gross Profit, and Operating Income
- 3 PCA components will be used

## Dashboard Integration

### Provisional Database (PG Admin Image)

<img width="683" alt="image" src="https://user-images.githubusercontent.com/102189324/187052038-4a703f00-a8a0-4145-b742-1e892a9dd45d.png">
<img width="468" alt="image" src="https://user-images.githubusercontent.com/102189324/187052059-20b7c1af-d4f0-44f9-976f-3f42306ae83a.png">

### Final Database (PG Admin Image)

![image](https://user-images.githubusercontent.com/102189324/188336164-7ca89b77-656a-4b2c-87c5-e81ebee6b0f0.png)
<img width="541" alt="image" src="https://user-images.githubusercontent.com/102189324/188336182-4173f706-b41d-443f-ad88-2878860cb3a9.png">

## Dashboard

https://docs.google.com/presentation/d/1m2YvaGSmpUc6-TqyvoD3m7YBSXOmTBLeKVGED506_aw/edit#slide=id.p

