# Project 1: SAT & ACT Analysis

## Problem Statement
Analyze trends in SAT & ACT scores from 2017 - 2018 and make recommendations to increase SAT participation and scores.

## Executive Summary
Analyze the trend between 2017 and 2018 SAT and ACT participation using EDA and plots to see the relationship between the 2 and provide solution.
### Contents:
- [2017 Data Import & Cleaning](#Data-Import-and-Cleaning)
- [2018 Data Import and Cleaning](#2018-Data-Import-and-Cleaning)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Data Visualization](#Visualize-the-data)
- [Descriptive and Inferential Statistics](#Descriptive-and-Inferential-Statistics)
- [Outside Research](#Outside-Research)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)

## Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|SAT|name of state|
|sat17_participation|float|SAT|SAT % of participant in 2017| 
|sat17_evidence-based reading and writing|float|SAT|average SAT ERW Score 2017| 
|sat17_math|float|SAT|average SAT Math Score 2017| 
|sat17_total|float|SAT|average SAT Total Score 2017| 
|act17_participation|float|ACT|ACT % of participant in 2017| 
|act17_english|float|ACT|average SAT English Score 2017| 
|act17_math|float|ACT|average SAT Math Score 2017|
|act17_reading|float|ACT|average SAT Reading Score 2017|
|act17_science|float|ACT|average SAT Science Score 2017|
|act17_composite|float|ACT|average SAT Composite Score 2017|
|sat18_participation|float|SAT|SAT % of participant in 2018| 
|sat18_evidence-based reading and writing|float|SAT|average SAT ERW Score 2018| 
|sat18_math|float|SAT|average SAT Math Score 2018| 
|sat18_total|float|SAT|average SAT Total Score 2018| 
|act18_participation|float|ACT|ACT % of participant in 2018| 
|act18_english|float|ACT|average SAT English Score 2018| 
|act18_math|float|ACT|average SAT Math Score 2018|
|act18_reading|float|ACT|average SAT Reading Score 2018|
|act18_science|float|ACT|average SAT Science Score 2018|
|act18_composite|float|ACT|average SAT Composite Score 2018|

## Outside-Research

**Relevant Links:**

* [Which States Require the SAT? Complete List](https://blog.prepscholar.com/which-states-require-the-sat)
* [Six reasons not to be worried about Michigan's switch to the SAT](https://www.mlive.com/education/2015/07/worried_about_michigans_switch.html)
* [Colorado Switches from ACT to SAT for High School College-Entrance Assessments](https://www.coloradokids.org/colorado-switches-from-act-to-sat-for-high-school-college-entrance-assessments/)
* [Illinois Switches From ACT, Will Give Students SAT Instead](https://www.nbcchicago.com/news/local/illinois-switches-from-act-will-give-students-sat-instead-2/118432/)
* [Which States Require the SAT? Complete List](https://blog.prepscholar.com/which-states-require-the-sat)

## Conclusions-and-Recommendations

**SAT School Day**

The program seems to have a positive impact for SAT participation. States that is part of the program has an average of 73% whereas other states has an average of 36% in 2018.


**Targets for improvement**

There are a few states that we can target to further improve the participation rate of SAT, through additional funding. There is also district that do not require ACT, therefore they may be more willing to opt for SAT School Day Program. 
* District of Columbia: largest decrease of participation rate from 2017 - 2018, 8% drop


* States already in SAT School Day with low 2018 participation: Oklahoma, Ohia, South Carolina, Tennessee, West Virginia.

  * It is interesting to note that despite having the option to choose between SAT and ACT, the students in Oklahoma, Ohio, South Carolina and Tennessee has a higher ACT participation as compared to SAT participation. (West Virginia has an West Virginia Alternative Summer Assessment that students can opt for)


* Arkansas and Minnesota has the very low SAT participation rate compared to their high ACT participation in both years despite being offered both test and is not necessary to graduate. We can consider approaching these states to be part of SAT School Day to see if we can increase the participation rate of SAT.

**Key Takeaway**

States that has benefited from SAT School Day and has been showing great participation rates:

* Illinois (largest increase in the number of participation for SAT test)
* Colorado (2nd largest increase in number of SAT participation, and largest decrease in ACT test participation)
* Michigan, Delaware and Connecticut have the 100%  SAT participation for both years