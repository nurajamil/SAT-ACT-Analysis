# Project 1: SAT ACT Analysis


### Problem Statement

Some states have low participation rate in SAT test. Which one of those states would you focus on and how would you improve participation in SAT amongst high school students in that state?

---

### Executive Summary

This project looks at participation rates and test scores for SAT and ACT tests. The data is broken down to state-level and is from 2017 and 2018. Additional data from external sources are also included in order to discover key relationships that would help to explain the different test participation rates in each state. The additional data included are income, population and policies around SAT/ACT tests for each state.

Some of the relationships that are uncovered include the strong negative relationship between ACT and SAT participation rates and the positive relationship between SAT participation rate with state-level income and population respectively.

Using exploratory data analysis, data visualisations and outside research, this project dives into the different relationships that are driving the state participation rate. Through this, the state of choice will be identified, followed by the strategy to improve the SAT participation rate in that state. 

---

### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|*object*|ACT/SAT|The 51 states in the US.| 
|**act_participation_2017**|*float*|ACT|The percentage of students who took the ACT tests in the state in 2017.| 
|**act_english_2017**|*float*|ACT|The average test score for ACT English test taken in the state in 2017.|
|**act_math_2017**|*float*|ACT|The average test score for ACT Math test taken in the state in 2017.|
|**act_reading_2017**|*float*|ACT|The average test score for ACT Reading test taken in the state in 2017.|
|**act_science_2017**|*float*|ACT|The average test score for ACT Science test taken in the state in 2017.|
|**act_composite_2017**|*float*|ACT|The mean test score of the four ACT tests taken in the state in 2017. These four tests are English, Math, Reading and Science.|
|**act_participation_2018**|*float*|ACT|The percentage of students who took the ACT tests in the state in 2018.|
|**act_english_2018**|*float*|ACT|The average test score for ACT English test taken in the state in 2018.|
|**act_math_2018**|*float*|ACT|The average test score for ACT Math test taken in the state in 2018.|
|**act_reading_2018**|*float*|ACT|The average test score for ACT Reading test taken in the state in 2018.|
|**act_science_2018**|*float*|ACT|The average test score for ACT Science test taken in the state in 2018.|
|**act_composite_2018**|*float*|ACT|The mean score of the four ACT tests taken in the state in 2018. These four tests are English, Math, Reading and Science.|
|**act_participation_pct_change**|*float*|final_add|The percentage of students who took the ACT test in 2018 minus the percentage of students who took the test in 2017.|
|**sat_participation_2017**|*float*|SAT|The percentage of students who took the SAT tests in the state in 2017.| 
|**sat_ebrw_2017**|*int*|SAT|The average test score for SAT Evidence-Based Reading and Writing test taken in the state in 2017.|
|**sat_math_2017**|*int*|SAT|The average test score for SAT Math test taken in the state in 2017.|
|**sat_total_2017**|*int*|SAT|The average total score of the two SAT tests taken in the state in 2017. These two tests are SAT Math and SAT Evidence-Based Reading and Writing.|
|**sat_participation_2018**|*float*|SAT|The percentage of students who took the SAT tests in the state in 2018.| 
|**sat_ebrw_2018**|*int*|SAT|The average test score for SAT Evidence-Based Reading and Writing test taken in the state in 2018.|
|**sat_math_2018**|*int*|SAT|The average test score for SAT Math test taken in the state in 2018.|
|**sat_total_2018**|*int*|SAT|The average total score of the two SAT tests taken in the state in 2018. These two tests are SAT Math and SAT Evidence-Based Reading and Writing.|
|**sat_participation_pct_change**|*float*|final_add|The percentage of students who took the SAT test in 2018 minus the percentage of students who took the test in 2017.|
|**population_2017**|*int*|final_add|The state population in 2017.|
|**median_income_2017**|*int*|final_add|The state median income in 2017.|
|**state_requirement**|*object*|final_add|The test requirement for each state. If the state has a mandatory SAT testing, it will return "SAT". If the state has a mandatory ACT testing, it will return "ACT". If the state has a mandatory ACT or SAT testing, it will return "ACT or SAT". Otherwise, it will return "no requirement".|
|**state_subsidies**|*object*|final_add|The indicator of whether the test is state-funded. If the state provides free SAT test, it will return "SAT". If the state provides free ACT test, it will return "ACT". Otherwise, it will return "no requirement".|

---

### Conclusions/ Recommendations

The participation rate for SAT and ACT test for each state is heavily influenced by the state policies. Most of the states with full or near full participation in SAT or ACT test has set policies around it. These policies include making either one of the test mandatory and providing the test for free. 

It has been observed that when one test is made mandatory over the other, it would result in full participation or near full participation for that particular test and a sharp drop in the latter. This is seen in Colorado and Illinois. In 2017, both Colorado and Illinois had full or near full ACT participation. However, when the states switched from mandatory ACT testing to SAT testing, their ACT participation rates dropped drastically. Their SAT participation rates on the other hand, went up to 99-100%. 

There are 20 states with no mandatory testing or state-funded test. These states have generally low SAT and ACT participation rates. One of the 20 states include Oregon.

Oregon has the second lowest ACT and SAT participation rate. As there is no mandatory test set and ACT test has not monopolised the test market in Oregon, there is a big opportunity for growth for SAT test. Additionally, its SAT participation rate in 2018 is slightly higher than its ACT participation rate, indicating that SAT might already have a head start in the state. Hence, the College Board should focus its attention on Oregon and boost the state SAT participation rate. 

Since state influence has demonstrated to be a strong driving force behind test participation, it is important for us to engage with state and local governments. Some of the ways that state or local governments could contribute include providing full or partial test subsidy or state-wide subsidized SAT preparation classes. As there is a positive relationship between income level and SAT participation rate, providing some financial assistance to low-income groups could potentially help to boost SAT participation rate in the state. This relationship needs to be further studied.

Collaboration with nearby states like California and Washington could also be helpful. Like Oregon, these states have no state requirement around the SAT or ACT test. Even so, their SAT participation rates are higher than Oregon's. By working together with them, we could potentially uncover other important factors that would help to boost Oregon's participation rate. 

Additionally, more research could be done to find out the students test preference and the reason behind it. For example, if the SAT test is not the students test of choice, then why is it so? Is it due to the cost, test grading structure, difficulty level of the test or some other reasons? 

Moreover, some students are bound to go to colleges that are outside of their home state. Hence, the test preference of these students are not entirely dependent on Oregon's state policy. It would also be dependent on the policy of the other states and the colleges that they are planning to enrol in. Thus, it would be useful to research on the type of colleges that these students intend to go to after highschool and the respective policies of these colleges. This would likely have an impact on our effort to boost the SAT participation.

---

### External Data Sources:

**ACT/SAT 2017**
- [ACT 2017](http://ipsr.ku.edu/ksdata/ksah/education/6ed16.pdf)
- [SAT 2017](https://www.act.org/content/dam/act/unsecured/documents/cccr2017/ACT_2017-Average_Scores_by_State.pdf)

**State-Level Population and Income**
- [State-Level Population](https://www.census.gov/data/tables/time-series/demo/popest/2010s-state-total.html)
- [State-Level Income](https://en.wikipedia.org/wiki/List_of_U.S._states_and_territories_by_income)

**State ACT/SAT Policies**
- [Prepscholar](https://blog.prepscholar.com/which-states-require-the-sat)
- [Magoosh - Free SAT](https://magoosh.com/hs/sat/free-sat-tests-by-state/)
- [Magoosh - ACT or SAT](https://magoosh.com/hs/sat/states-that-require-the-act-or-sat/)
- [Magoosh - Free ACT](https://magoosh.com/hs/act/free-act-tests-by-state/)
- [Collegeraptor - Free ACT or SAT](https://www.collegeraptor.com/getting-in/articles/act-sat/states-act-sat-given-free/)
