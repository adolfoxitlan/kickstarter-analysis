# kickstarter with Excel

## Overview of Project
The objective is to analyze a Crowdfunding Kickstart company data related to the goals and actual funds collected.
### Purpose
To provide better insight into how people/companies behave in terms of interest and budgets to capitalize on cultural projects.
### Analysis of Outcomes Based on Launch Date
May, June, July are the best seasons to promote crowdfunding; the rest of the year is over 50% of success, only December has a low success rate.


![This is an image](https://github.com/adolfoxitlan/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals
Projects less than 1000 and between 40000 - 44999 are prone to succeed, projects over 45000 are mostly discarded, and projects between 25000 - 39999 tend to fail.

Projects with 50% of success are between 5000 and 19999.

![This is an image](https://github.com/adolfoxitlan/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
Although the data set is not significant (4065 rows), I got stuck in 2 issues related to nesting IF's. First, I had to validate using other excel formulas to verify my results, and second, I experienced some PC performance degradation.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  A: Intense Crowdfunding activities must be done between Q2 and Q3, leaving December (Q4) more static, and retake activities by Q1.

- What can you conclude about the Outcomes based on Goals?
  A: The size of the projects should be separated into 2, less than 1,000, and between 30,000 and 44,999 to achieve as much the success rate.

- What are some limitations of this dataset?
  A: It should include the reason for cancelation, failed and success

- What are some other possible tables and/or graphs that we could create?
  A: - A Category Graph vs Outcome
     - A Country Graph vs USD vs Outcome
     - A a USD excahnge rate to have one coin for reference
     - A backers vs outcome graph
