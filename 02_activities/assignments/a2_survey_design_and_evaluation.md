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

The number of your chosen topic: `#1`

Describe the purpose of your survey:
```
The purpose of this survey is to obtain information on employee satisfaction from entry- and lower-level positions accross the tech company's departments. Participants will be asked about their experience in their current position.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
* Target population: entry- and lower-level employees from tech company departments.
* Sampling frame: current entry- and lower-level employees from different departments.
* Sampling units: current employees who hold entry- and lower-level positions, who have been in the position for more than 6 months, randomly selected from each department, and responded to the survey.
* Overall sampling strategy: Stratified sampling will be applied, where each department will be considered a strata. Randomly selected individuals will receive an invitation to participate which will include an explanation of the survey purpose, describing this is anonymus and will not include identification. Surveys will be distributed by sharing a link to an anonymus form. Employees will have three weeks to answer the survey. A reminder will be send at the mid-way point.
```

Your 5-10 question survey:
```
This survey is intended to learn about your experience in your current position and to understand how we can better provide a work environment that is supportive of your career goals. 
1. Please select your department: [Multiple choice answer with department names]
Please select the level of agreement you have to each of the following statements:
[Possible answers: Strongly Agree / Agree / Neutral / Disagree / Strongly Disagree]
2. I have the resources I need to perform my job 
3. I have support when having a difficulty
4. I see clear options for growth within the company
5. I know what the expectations of my job are
6. My job is valuable
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. Sample type: two-stage stratified sampling with probability sampling, using rejective sampling

2. Sample size: 25,000 was expected. An initial selection of approximatively 50,000 units was used, from which about 40,000 invitation letters to the electronic questionnaire were sent to selected households across Canada.

3. Target population: all persons 15 years of age and older living in the ten provinces of Canada, excluding those full-time residents of institutions for more than 6 momnths

4. Sampling frame: randomly selected household member aged 15 or older, selected from groups of telephone numbers associated with the same address. This was derived from a combination of landline and cellular telephone numbers from the Census and various administrative sources with Statistics Canada's dwelling.

5. Survey mode(s): questionnaire suministered electronically or via telephone assistance

6. Timeline: 2018-09-04 to 2018-12-28, 3 months and 24 days

7. Response rate: 41.9%

8. Weights: estimation weights: each person selected in the sample represents (in addition to themselves) several other persons not in the sample, bootstrap weights: to estimate variance based on design, estimates based on the survey data are also adjusted (by weighting) so that they are representative of the target population with regard to certain characteristics (each month we have independent estimates for various age-sex groups by province). Weights were also adjusted so that the weighted income distribution of GVP matched the 2017 CIS distribution by province.

9. Data processing: validation measures: analysis of changes over time, verification of estimates through cross-tabulations, confrontation with other similar sources of data. 

10. Cleaning, imputation, etc: imputation using donor records selected through a score function

11. Sources of error: 
- As the data are based on a sample of persons, they are subject to sampling error. That is, estimates based on a sample will vary from sample to sample, and typically they will be different from the results that would have been obtained from a complete census. 
- Coverage errors: when there are differences between the target population and the surveyed population
- Non-response errors: questions with no response
- Response errors: mistakes made at the moment of answering a question
- Processing errors: data entry, data management, data cleaning

12. Limitations, known biases, etc: Individuals without telephone numbers and without access to housing were excluded from sampling. People who do not speak either English or French could not take the survey. Participants who did not allow linkage of data and got imputation might be part of vulnerable groups. The income variable showed high non-response rates and those who reported are usually rough estimates. Rejective sampling may cause bias, as volunteers could be from higher income settings. Long vs short interview differences. Only one individual per household selected (communal living, multigenerational living, student housing, etc).

13. Link to documentation and any additional sources used:
https://www150.statcan.gc.ca/n1/en/catalogue/45250011
https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=796234
```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 18/04/2025`
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
