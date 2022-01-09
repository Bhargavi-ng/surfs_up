# surfs_up
This project is to do analysis for a business proposal - start a "Surf n Shake" shop in Hawaii that serves surfboards and ice creams to locals and tourists. There is a real investor who is ready to back for this business but wants to see some "Weather Analysis" on the dataset from Oahu where the shop will be set up to determine if the venture will successful.

## Overview of the analysis:
Challenge: After reviewing the data from the above analysis the investor wantsadditional analysis on the temperature for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round. 

## Results:

#### Jypyter Notebook: [Deliverables 1 and 2 Codebase](https://github.com/Bhargavi-ng/surfs_up/blob/main/SurfsUp_Challenge.ipynb)

### Deliverable 1: Determine the Summary Statistics for June
Using Python, Pandas functions and methods, and SQLAlchemy, I filtered the date column of the Measurements table in the  [hawaii.sqlite](https://github.com/Bhargavi-ng/surfs_up/blob/main/hawaii.sqlite)database to retrieve all the temperatures for the month of JUNE. Then I converted those temperatures to a list, created a DataFrame from the list, and generated the summary statistics.

![Deliverable 1 Output](https://github.com/Bhargavi-ng/surfs_up/blob/main/Resources/Deliverable_1_June_Stats.PNG)

### Deliverable 2: Determine the Summary Statistics for December
Using Python, Pandas functions and methods, and SQLAlchemy, I filtered the date column of the Measurements table in the  [hawaii.sqlite](https://github.com/Bhargavi-ng/surfs_up/blob/main/hawaii.sqlite)database to retrieve all the temperatures for the month of DECEMBER. Then I converted those temperatures to a list, created a DataFrame from the list, and generated the summary statistics.

![Deliverable 1 Output](https://github.com/Bhargavi-ng/surfs_up/blob/main/Resources/Deliverable_1_June_Stats.PNG)

## Summary:
Based on the above statistics for "Temperature" measure I can summarize that
- there is just 0.5 difference in the Standard Deviation between the two months, which isn't very significant, and
- the average temperature for June is 74.9 and for December it is 71, which are suitable for surfing and ice-cream sales.

But we need to run additional queries to determine the statistics for Precipitation to determine average rainfall for the months of June and December.

![Additional Query and Output - Statistics for Precipitation for month of June](https://github.com/Bhargavi-ng/surfs_up/blob/main/Resources/Addtnal_query_June_Stats.PNG)
![Additional Query and Output - Statistics for Precipitation for month of December](https://github.com/Bhargavi-ng/surfs_up/blob/main/Resources/Addtnal_query_December_Stats.PNG)

Based on the above statistics for "Precipitation" measure you can see that
- there is only 0.2 difference in Standard deviation between the two months, and
- December has maximum precipitaion of 6.42 versus June's 4.43. But, the average rainfall for December is 0.22 versus June's 0.14.

## Resources:
#### Data resources:
- hawaii.sqlite
#### Software:
- Python
- Juypter Notebook
- Pandas
- SQLAlchemy
- SQLite
- Visual Studio Code
- Flask
