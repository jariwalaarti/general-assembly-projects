# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: SAT-ACT Analysis

### Problem Statement


ACT and SAT are nationally recognized standardized tests and common admission requirements for US schools. All US colleges and universities accept scores from either the ACT or SAT.

As a part of administers of SAT organization team, the objective is to analyze the participation rates of SAT over ACT and provide recommendations to increase the participation rates for SAT.


### Executive Summary


This project analyses the participation of students who appeared for SAT and ACT examination for the year of 2017 and 2018 after the SAT format was updated in 2016. All universities in US accept either SAT or ACT. So students opt for one out of the two based on their convenience, state policies, fee, etc.

The data is state wise representation of participation percentage and the scores for both the test. SAT data includes participation rate, Evidence based reading and writing, math and total score for both 2017 and 2018. ACT data includes participation rate, English, Math, Reading, Science and Composite score for both 2017 and 2018.

Analysis has been carried out based in several stages on the data and outside research through numeric statistic and graphs.

2017 Data Import & Cleaning : First stage is to load data from csv file for SAT and ACT 2017 test and perform data cleaning

2018 Data Import and Cleaning : Next stage is to load data from csv file for SAT and ACT 2018 test and perform data cleaning

Exploratory Data Analysis : Analyze the statistical aspects of data

Data Visualization : Analyze the data through visual aspects i.e. by plotting graphs

Descriptive and Inferential Statistics : Describe the fields associated with the data and conduct hypothesis testing

Outside Research : Conduct outside research to support the observations and recommendations

Conclusions and Recommendations : Describe the conclusion drawn from the analysis carried out provide recommendations

It was observed after analyses that the SAT participation rate increased for year 2018 over 2017 but has not taken over the ACT. Moreover, the SAT and ACT scores do not share a co relation. But the SAT 2017 vs 2018 scores and ACT 2017 vs 2018 scores do show a linear pattern which states there is not much variance in the scores for year 2017 and 2018. As there was new format introduced in 2016, several changes were made which might be the reason for increase in the SAT participation rate. 


### Data Dictionary


**Data Dictionary for SAT and ACT 2017/2018**

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|SAT|State of US country|
|sat2017_part|int|SAT|Participation percentage for year 2017|
|sat2017_erw|int|SAT|Evidence-Based Reading and Writing score for year 2017|
|sat2017_math|int|SAT|Math score for year 2017|
|sat2017_total|int|SAT|Total score from ERW and Math for year 2017|
|act2017_part|int|ACT|Participation percentage for year 2017|
|act2017_eng|int|ACT|English score for year 2017|
|act2017_math|int|ACT|Math score for 2017|
|act2017_reading|int|ACT|Reading score for year 2017|
|act2017_science|int|ACT|Science score for 2017|
|act2017_composite|int|ACT|Mean of all ACT subjects for 2017|
|sat2018_part|int|SAT|Participation percentage for year 2018|
|sat2018_erw|int|SAT|Evidence-Based Reading and Writing score for year 2018|
|sat2018_math|int|SAT|Math score for year 2018|
|sat2018_total|int|SAT|Total score from ERW and Math for year 2018|
|act2018_part|int|ACT|Participation percentage for year 2018|
|act2018_eng|int|ACT|English score for year 2018|
|act2018_math|int|ACT|Math score for 2018|
|act2018_reading|int|ACT|Reading score for year 2018|
|act2018_science|int|ACT|Science score for 2018|
|act2018_composite|int|ACT|Mean of all ACT subjects for 2018|


### Conclusion


- We can conclude from the data statistics and graphs above that there has been increase in the SAT participation rate but the average rate is still lower in comparison to ACT.

- In addition to this, few states like Illinois, Colorado, Rode Island has shown significant increase in the participation rate for SAT in 2018.


### Recommendation


- It was noticed that participation increased if the students were given fee waiver. Appropriate planning towards minimal fee or fee waiver can improve the participation rate.

- We observed for Illinois and Colorado that the rates increased after they signed the new contract with the College Board. Hence, more states can be engaged in similar contracts to boost the students’ participation rate for SAT.

- Possible to make the mathematics portion less text heavy which may encourage a higher take-up rate of students for SAT.
