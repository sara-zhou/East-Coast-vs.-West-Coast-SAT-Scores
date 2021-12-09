# Project 1: East Coast vs. West Coast SAT Scores

### Problem Statement

Does the West Coast have more STEM driven students compared to the East? Does the East Coast have more Business/Literature driven students? How important of a role does geography play in major choice? Should we level out academic curriculums to provide students equal opportunity? 

### Background

The SAT and ACT are standardized tests that many colleges and universities in the United States require for their admissions process. This score is used along with other materials such as grade point average (GPA) and essay responses to determine whether or not a potential student will be accepted to the university.

The SAT has two sections of the test: Evidence-Based Reading and Writing and Math ([*source*](https://www.princetonreview.com/college/sat-sections)). The ACT has 4 sections: English, Mathematics, Reading, and Science, with an additional optional writing section ([*source*](https://www.act.org/content/act/en/products-and-services/the-act/scores/understanding-your-scores.html)). They have different score ranges, which you can read more about on their websites or additional outside sources (a quick Google search will help you understand the scores for each test):
* [SAT](https://collegereadiness.collegeboard.org/sat)
* [ACT](https://www.act.org/content/act/en.html)

Standardized tests have long been a controversial topic for students, administrators, and legislators. Since the 1940's, an increasing number of colleges have been using scores from sudents' performances on tests like the SAT and the ACT as a measure for college readiness and aptitude ([*source*](https://www.minotdailynews.com/news/local-news/2017/04/a-brief-history-of-the-sat-and-act/)). Supporters of these tests argue that these scores can be used as an objective measure to determine college admittance. Opponents of these tests claim that these tests are not accurate measures of students potential or ability and serve as an inequitable barrier to entry.

Most people associated the West Coast with STEM because that's where Silicon Valley is located, which is considered the capital of the booming tech industry. Likewise, most people will associate the East Coast with business because of the New York Stock Exchange located in New York City. Due to all of these STEM and Business alumni gathering at these parts of the world along the coasts, how will this affect the students in these areas of the US? Alumni are the people who lead the future generation and help pave the path to their educational carrers. 

### Datasets

* [`sat_2017.csv`](./data/sat_2017.csv): 2017 SAT Scores by State
* [`sat_2018.csv`](./data/sat_2018.csv): 2018 SAT Scores by State
* [`sat_2019.csv`](./data/sat_2019.csv): 2019 SAT Scores by State

### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**sat_2017**|*list of pandas DataFrames*|SAT Scores from 2017|US nation-wide SAT Scores from 2017 with data on Math and EBRW scores.| 
|**sat_2018**|*list of pandas DataFrames*|SAT Scores from 2018|US nation-wide SAT Scores from 2018 with data on Math and EBRW scores.|
|**sat_2019**|*list of pandas DataFrames*|SAT Scores from 2019|US nation-wide SAT Scores from 2019 with data on Math and EBRW scores.|
|**east_states**|*tuple*|East States in Question|States included: New York, Maryland, and Massechusetts|
|**west_states**|*tuple*|West States in Question|States included: California, Oregon, and Washington|
|**east_2017_math**|*int*|2017 Average East Math Score|Average East Coast Math section score from the SATs in 2017|
|**west_2017_math**|*int*|2017 Average West Math Score|Average West Coast Math section score from the SATs in 2017|
|**east_2017_ebrw**|*int*|2017 Average East EBRW Score|Average East Coast EBRW section score from the SATs in 2017|
|**west_2017_ebrw**|*int*|2017 Average West EBRW Score|Average West Coast EBRW section score from the SATs in 2017|
|**east_2018_math**|*int*|2018 Average East Math Score|Average East Coast Math section score from the SATs in 2018|
|**west_2018_math**|*int*|2018 Average West Math Score|Average West Coast Math section score from the SATs in 2018|
|**east_2018_ebrw**|*int*|2018 Average East EBRW Score|Average East Coast EBRW section score from the SATs in 2018|
|**west_2018_ebrw**|*int*|2018 Average West EBRW Score|Average West Coast EBRW section score from the SATs in 2018|
|**east_2019_math**|*int*|2019 Average East Math Score|Average East Coast Math section score from the SATs in 2019|
|**west_2019_math**|*int*|2019 Average West Math Score|Average West Coast Math section score from the SATs in 2019|
|**east_2019_ebrw**|*int*|2019 Average East EBRW Score|Average East Coast EBRW section score from the SATs in 2019|
|**west_2019_ebrw**|*int*|2019 Average West EBRW Score|Average West Coast EBRW section score from the SATs in 2019|

### Analysis

Through the box plots and scatter points, we can clearly see that the East and West Coast average scores don't really differ much. Originally I hypothesized that the West Coast would dominate over the East Coast in the SAT Math section but each year they take turns overtaking one another by minor differences. I also expected the East Coast to dominate over the West in the EBRW section but surprisingly the West beat them in all three years, 2017, 2018, and 2019. Between the years 2017-2019 the two coasts' scores were at most off by 4 points in both sections and years. 

### Conclusion

Having the Silicon Valley or Wall Street near you doesn't affect how well you preform on either section of the SATs. Both coasts' had similar test results and fell short of the national average between the years of 2017-2019. Being surrounded by successful STEM and Business alumni did not give California, Oregon, Washington, Maryland, New York, or Massechusetts any increase in any particular section of the SATs. The quality of education provided by the alumni of the respected states didn't change due to the geographical locations of the schools.