# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type
2. Sample size
3. Target population
4. Sampling frame
5. Survey mode(s) 
6. Timeline
7. Response rate
8. Weights
9. Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used


# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: `1`

Describe the purpose of your survey:
```
My goal with this survey is to identify any factors that may be driving the increased turnover among entry-level positions within the company by assessing employee satisfaction. Specifically, I want to gather data about employee satisfaction from more junior and senior employees, and identify any differences in satisfaction, and what factors may be driving those differences. The end product would ideally be a set of recommendations about what changes the company could implement to boost employee retention.

```

Describe your target population, sampling frame, sampling units, and observational units:

```
Our target population are all employees of the company who have worked at the company for at least 60 days (to ensure they have had meaningful time to assess working conditions). Our sampling frame is a list of all employee emails that meet our criteria (working for at least 60 days), while our sampling units are individual employees. The survey would be sent out as a company-wide email with all responses kept confidential and as much effort made as possible to ensure anonymity, although some information we want to collect such as the department/role for the employee could complicate that. 
I would use stratified sampling with a quota, where employees are stratified by the time they have spent at the company. The exact criteria for differentiating the strata would need to be determined according to the available data about the number of employees and their relative seniority, however the strata would presumably not be of equal size. Although it might be more optimal to conduct probability sampling, there is often a lack of response to workplace satisfaction surveys, so quota sampling is more realistic where the quota is set according to the size of the strata sampled. This does risk creating a bias where employees that feel more strongly (either positively or negatively) are more likely to answer the survey.

```
Your 5-10 question survey:
```
1.	Which department/unit are you a member of? (select from drop-down list)
2.	Rate your overall satisfaction with your current position at the company? (From 1 to 10 where 1 is extremely dissatisfied and 10 is extremely satisfied)
The following questions have 3 options: Yes, No, Unsure/Prefer not to answer
3.	Do you believe you have a long-term future within the company?
4.	Do you feel your salary fairly compensates you for the work you are currently doing?
5.	Do you feel a sense of belonging and community in your current role?
6.	Do you feel there are appropriate avenues for advancement within the position?
7.	Do you feel the company provides appropriate training and support for your role?
8.	Do you feel the company appropriately values and respects your time outside of working hours?
9.	Do you feel management appropriately supports your efforts and improves you ability to complete your responsibilities?
The final question will be open ended to gather anecdotal information that may provide specific insights
10.	Are there any factors beyond those mentioned above that positively or negatively impact your satisfaction within your current position? Are there any factors discussed above that you wish to elaborate on?

```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. Sample type: Simple random sample stratified by geographic area. It’s a little unclear, but from my understanding each Census Metropolitan Area (CMA) was considered a separate stratum, with some CMAs grouped together in Ontario, Quebec and British Columbia. Areas outside of the CMAs within each province were each considered their own stratum. There was also rejective sampling to increase the proportion of respondents who were volunteers, where some non-volunteers would have interviews terminated early (and I think excluded?) upon determining they did not volunteer.
2. Sample size: Target sample size was 20 thousand, the actual number of respondents was 16, 149.
3. Target population: All persons 15 years of age and older (excluding residents of the Yukon, Northwest Territories, and Nunavut, and full-time residents of institutions)
4. Sampling frame: List of phone numbers available to Stats Canada and the Address Register of all homes within the ten provinces
5. Survey mode(s): Electronic self-completed questionnaires and telephone interviews
6. Timeline: September to December of 2018
7. Response rate: 41.9%
8. Weights: Initial weighting was done based on the probability an individual household could be contacted, which was affected by available telephone numbers associated with that household. Out of scope and non-responses were removed. Person weights were calculated based on the number of eligible individuals living in individual households using the previously calculated household weighting. There was also some weighting for the rejective sampling according to the age of respondents (over or under 45). Finally, the person-weights were adjusted according to the population counts of their stratum, and the income, age, and sex of their province of residence.
9. Data processing: Processing began with data capture, which was either performed directly by respondents to the online questionnaire, or by interviewers performing the phone interviews. Responses to open-ended questions were then coded into existing categories, new categories or “other” according to codes determined by Stats Canada. Charitable organizations were coded based on the International Classification of Nonprofit Organizations. Data was then weighted as described previously. Variable were then created through collapsing or combining response categories. Finally, some data was anonymized, particularly donations.
10. Cleaning, imputation, etc: Duplicates, out of scope responses and non-responses were removed in an initial screening step. Imputation was used to fill in data from some item and partial non-responses using a scoring system where data would be imputed from the most similar donor response (the highest calculated score). Values that were imputed include income, hours volunteered (broken down into several sub-categories based on the type of volunteering), and donations made.
11. Sources of error: The guide lists several sources of non-sampling error, mostly related to improper responses to questions (due to mistakes from the respondent or interviewer), or errors in the entry and analysis of the data. The guide also discusses non-response error, which was addressed with imputation where possible. Finally, the guide discusses sampling error, including the calculation of standard error and the coefficient of variance. I was unable to find these values within the guide or the report published online. To better determine the variance, bootstrapping was used to estimate the standard deviation.
12. Limitations, known biases, etc: There is surprisingly little information on limitations and bias provided in the guide. An immediate limitation that seems apparent is the exclusion of the territories, seemingly from a result of the lack of coverage in the census. The format of the survey also biases responses towards individuals with stable housing given the methodology used to determine the sampling frame. The format of the survey requires respondents to have access to the internet or a phone, which could exclude some individuals. The 2023 version of the survey increased the response timeline and introduced a “targeted respondent” approach based on the results of the 2021 survey, which could improve the response rate and reduce non-response.
13. Link to documentation and any additional sources used:
Link for download of PUMF Guide for SGVP 2018: https://www150.statcan.gc.ca/n1/pub/45-25-0001/cat5/c33_2018.zip 
Link to info on SGVP 2023: https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&SDDS=4430
Report on SGVP 2018: https://www150.statcan.gc.ca/n1/en/pub/75-006-x/2021001/article/00002-eng.pdf?st=8dOEEb6d


```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 14 January 2026`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
