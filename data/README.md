Our data comes from the CDC's 2017-2018 NHANES Questionaire. You can find the links to the data and their codebooks here:

https://wwwn.cdc.gov/nchs/nhanes/search/datapage.aspx?Component=Questionnaire&Cycle=2017-2018

https://wwwn.cdc.gov/nchs/nhanes/search/datapage.aspx?Component=Demographics&Cycle=2017-2018


Codebook:

SEQN | Categorical | The sequence number of the respondent: this is how we merge the data and keep track of individual respondents.

DPQ010 | Categorical (Ordinal) | A scale of how often over the last two weeks the participant has been bothered by having little interest or pleasure in doing things.

DPQ020| Categorical (Ordinal) | A scale of how often over the last two weeks the participant has been bothered by feeling down, depressed, or hopeless.

DPQ030| Categorical (Ordinal) | A scale of how often over the last two weeks the participant has been bothered by trouble sleeping or sleeping too much.

DPQ040 | Categorical (Ordinal) | A scale of how often over the last two weeks the participant has been bothered by feeling tired or having little energy.

DPQ050 | Categorical (Ordinal) | A scale of how often over the last two weeks the participant has been bothered by poor appetite or overeating.

DPQ060 | Categorical (Ordinal) | A scale of how often over the last two weeks the participant has been bothered by feeling bad about themself - or that they are a failure or have let themself or their family down.

DPQ070 | Categorical (Ordinal) | A scale of how often over the last two weeks the participant has been bothered by trouble concentrating on things, such as reading the newspaper or watching TV.

DPQ080 | Categorical (Ordinal) | A scale of how often over the last two weeks the participant has been bothered by moving or speaking so slowly that other people could have noticed? Or the opposite - being so fidgety or restless that you have been moving around a lot more than usual.

DPQ090 | Categorical (Ordinal) | A scale of how often over the last two weeks the participant has been bothered by thoughts that they would be better off dead or of hurting themself in some way.

SLD012 | Numerical | A measure of how many hours the participant usually sleeps on weekdays or workdays.

SLD013 | Numerical | A measure of how many hours the participant usually sleeps on weekends or non-workdays.

RIAGENDR | Categorical | Recording if the participant is male or female (note there is no option for non-binary or trans-gender options.)

RIDRETH3 | Categorical | Recording the participant's race (they cannot self-report, they need to identify into one of 6 categories or indicate other race.)

INDHHIN2 | Categorical | Recording the participant's annual household income through a variety of income ranges.

INDFMPIR | Numerical | Recording the ratio of the participant's family income to poverty.

DMDEDUC3 | Categorical | Recording the participant's (aged 6-19) highest level of education.

DMDEDUC2 | Categorical | Recording the participant's (aged 20+) highest level of education.

OCQ180 | Numerical | Recording how many hours the participant worked in the last week at jobs/businesses.

depression_score | Numerical | Recording a sum of the participant's responses of DPQ010-DPQ090 so long as the response is between 0-3 to mimic the aggretated score the CDC uses to screen for depression across populations.

race_label | Categorical | A non-encoded version of RIDRETH3

education_label | Categorical | A non-encoded version of DMDEDUC3

income_label | Categorical | A non-encoded version of INDHHIN2

SLD012 | Numerical | Sleep hours - weekdays or workdays

SLD013 | Numerical | Sleep hours - weekends

WHQ030 | Numerical | How do you consider your weight

WHD010 | Numerical | Current self-reported height (inches)

WHD020 | Numerical | Current self-reported weight (pounds)







