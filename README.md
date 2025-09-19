# HS-Football-Recruiting-Ranking-Analysis
**This project uses data science and web scraping techniques to explore the long term accuracy of high school football recruiting rankings.** 

## Concepts demonstrated:
web-scraping, clustering, principal component analysis, probability theory, regression, tree-models, model-ensembling, model-stacking, undersampled subsets 

## Data Used
Top 500 recruits each year from 2010-2017 with their ratings from 247, ESPN, and Rivals - [On3.com](https://on3.com)

Draft records - [collegefootballdata.com](https://collegefootballdata.com)

## Problem Statement
Identifying and acquiring talent in any competitive industry is crucial to gain an advantage. The prevailing belief among people in & around the college football industry is that high school recruiting rankings are great predictors of individual success. Other research has even gone so far to say they’ve proven the relationship between recruit ranking and NFL draft status. Most say the higher rated a recruit the more likely they are to get drafted and therefore recruiting rankings are good predictors of success and draft status. 

## Results
After analyzing the relationship between draft status and recruit metrics (rating and stars) for the top 500 players from 2010-2017, the validity of the claim "recruiting rankings matter" is highly questionable. No evidence exists to confidently say that high school football recruiting rankings are predictive of NFL draft status and by proxy talent. 

## Data Dictionary:
**247_Rating**: numerical rating given to a high school football player by 247sports.com. 
- Theoretical range between 0-110, prospects below a certain star get no rating.
**247_Star**: the star rating given to a high school football player by 247sports.com. Ranges from 0-5. 

**Delta**: The percentage difference between actual drafted rate and the max possible draft rate.
- Max draft rate – draft rate.

**Drafted**: whether a player eventually got drafted or not.
- undrafted player = 0, drafted player = 1

**Draft Rate**: proportion of players drafted for that service for that star rank. 

**ESPN_Rating**: numerical rating given to a high school football player by espn.com.
- Theoretical range between 0-99, prospects below a certain star get no rating.
ESPN_Star: the star rating given to a high school football player by espn.com. Ranges from 0-5.

**Max Draft Rate**: if ALL players of that star rating were good enough, what percentage could be drafted.
- Number of available draft spots / number of players in that star level, with maximum of 1. 

**Rivals_Rating**: numerical rating given to a high school football player by rivals.com.
- Theoretical range between 0-6.1, prospects below a certain star get no rating.
Rivals_Star: the star rating given to a high school football player by rivals.com. Ranges from 0-5.