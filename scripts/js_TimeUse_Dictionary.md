
# General Social Survey (Time Use) 2015
#### Statistics Canada

## Data dictionary for the subset used in the Research Data Management Jumpstart
2025


## List of variables
**Variable** |**Recoded Variable Name** | **Description** | **Type**
|:------|:------| :------| :------|
|PUMFID|id|Record identification|integer|
|AGEGR10|ageGrp|Age group of respondent (groups of 10)|factor|
|SEX|sex|Sex of respondent|factor|
|MARSTAT|maritalStat|Marital status of the respondent|factor|
|PRV|province|Province of residence|factor|
|LUC_RST|popCenter|Population centre indicator|factor|
|EHG_ALL|eduLevel|Educational attainment - Highest degree|factor|
|GTU_110|feelRushed|General time use - Feel rushed|factor|
|GTU_130|extraTime|General time use - Extra time|factor|
|DUR01|durSleep|Duration - Sleeping, resting, relaxing, sick in bed|integer|
|DUR05|durMealPrep|Duration - Meal, lunch or snack preparation|integer|
|DUR06|durEating|Duration - Eating or drinking|integer|
|DURS200|durAlone|Duration - Social contact - Alone|integer|
|DURL313|durDriving|Duration - Travel - Car - Driver|integer|
|DUR08|durWork|Duration - Paid work|integer|
|DUR13|durSchoolSite|Duration - Schooling - On site|integer|
|DUR14|durSchoolOnline|Duration - Schooling - Online|integer|
|DUR15|durStudy|Duration - Homework or studying|integer|
|MRW_20|mainStudy|Main activity - Studying full-time/part-time|factor|
|MRW_30|mainJobHunting|Main activity - Looked for a job - Last four weeks|logical|
|MRW_40|mainWork|Main activity - Job/self-employed - Past 12 months|logical|
|MRW_D40A|worked12m|Worked in the last 12 months|logical|
|MRW_D40B|workedWeek|Worked last week|logical|
|EDM_02|enrollStat|Education - Enrollment status|factor|
|TST_01|dailyTexts|Number of text messages per day (groups of 10)|factor|
|TCS_110|timeSlowDown|Perceptions of time - Plans to slow down|logical|
|TCS_120|timeWorkaholic|Perceptions of time - Workaholic|logical|
|TCS_150|timeNotFamFriends|Perceptions of time - Not spending enough time with family or friends|logical|
|TCS_200|timeWantAlone|Perceptions of time - Would like more time alone|logical|

## Detailed information for each variable

### PUMFID
Record identification

**Recoded to:** id

**Type:** integer

 - Number unique responses: 17390
 - Missing: 0
 - Count: 17390

### AGEGR10
Age group of respondent (groups of 10)

**Recoded to:** ageGrp

**Type:** factor

 - Number unique responses: 7
 - Missing: 0

|**Value**|**Description**|
|:------|:------|
|1|15 to 24 years|
|2|25 to 34 years|
|3|35 to 44 years|
|4|45 to 54 years|
|5|55 to 64 years|
|6|65 to 74 years|
|7|75 years or older|

### SEX
Sex of respondent

**Recoded to:** sex

**Type:** factor

 - Number unique responses: 2
 - Missing: 0
 
 |**Value**|**Description**|
|:------|:------|
|1|Male|
|2|Female|

### MARSTAT
Marital status of the respondent

**Recoded to:** maritalStat

**Type:** factor

 - Number unique responses: 6
 - Missing: 0
 
 |**Value**|**Description**|
|:------|:------|
|1|Married|
|2|Living common-law|
|3|Widowed|
|4|Separated|
|5|Divorced|
|6|Single, never married|

### PRV
Province of residence

**Recoded to:** province

**Type:** factor

 - Number unique responses: 10
 - Missing: 0
 
 |**Value**|**Description**|
|:------|:------|
|10|Newfoundland and Labroador|
|11|Prince Edward Island|
|12|Nova Scotia|
|13|New Brunswick|
|24|Quebec|
|35|Ontario|
|46|Manitoba|
|47|Saskatchewan|
|48|Alberta|
|59|British Columbia|


### LUC_RST
Population centre indicator

**Recoded to:** popCenter

**Type:** factor

 - Number unique responses: 3
 - Missing: 0
 
 |**Value**|**Description**|
|:------|:------|
|1|Larger urban population centres (CMA/CA)|
|2|Rural areas and small population centres (non CMA/CA)|
|3|Prince Edward Island|


### EHG_ALL
Educational attainment - Highest degree

**Recoded to:** eduLevel

**Type:** factor

 - Number unique responses: 7
 - Missing: 630
 
 |**Value**|**Description**|
|:------|:------|
|1|Less than high school diploma or its equivalent|
|2|High school diploma or a high school equivalency certificate|
|3|Trade certificate or diploma|
|4|College/CEGEP/other non-university certificate or diploma|
|5|University certificate or diploma below the bachelor's level|
|6|Bachelor's degree (e.g. B.A., B.Sc., LL.B.)|
|7|University certificate, diploma, degree above the BA level|

### GTU_110
General time use - Feel rushed

**Recoded to:** feelRushed

**Question text:** How often do you feel rushed? Would you say it is...?

**Type:** factor

 - Number unique responses: 6
 - Missing: 62
 
 |**Value**|**Description**|
|:------|:------|
|1|Every day|
|2|A few times a week|
|3|About once a week|
|4|About once a month|
|5|Less than once a month|
|6|Never|

### GTU_130
General time use - Extra time

**Recoded to:** extraTime

**Question text:** How often do you feel you have time on your hands that you don’t know what to do with?

**Type:** factor

 - Number unique responses: 6
 - Missing: 76
 
 |**Value**|**Description**|
|:------|:------|
|1|Every day|
|2|A few times a week|
|3|About once a week|
|4|About once a month|
|5|Less than once a month|
|6|Never|

### DUR01
Duration - Sleeping, resting, relaxing, sick in bed

**Recoded to:** durSleep

**Unit:** Minutes in one day

**Type:** integer

 - Number unique responses: 274
 - Missing: 0
 - Count: 17390
 - Mean: 522.39
 - Std: 133.06
 - min: 0
 - 25%: 450
 - 50%: 510
 - 75%: 585
 - max: 1440
 
### DUR05 
Duration - Meal, lunch or snack preparation

**Recoded to:** durMealPrep

**Unit:** Minutes in one day

**Type:** integer

 - Number unique responses: 124
 - Missing: 0
 - Count: 17390
 - Mean: 48.96
 - Std: 67.28
 - min: 0
 - 25%: 0
 - 50%: 30
 - 75%: 70
 - max: 1260

### DUR06
Duration - Eating or drinking

**Recoded to:** durEating

**Unit:** Minutes in one day

**Type:** integer

 - Number unique responses: 126
 - Missing: 0
 - Count: 17390
 - Mean: 73.46
 - Std: 70.18
 - min: 0
 - 25%: 25
 - 50%: 60
 - 75%: 105
 - max: 830

### DURS200
Duration - Social contact - Alone

**Recoded to:** durAlone

**Unit:** Minutes in one day

**Type:** integer

 - Number unique responses: 333
 - Missing: 0
 - Count: 17390
 - Mean: 636.47
 - Std: 475.68
 - min: 0
 - 25%: 195
 - 50%: 585
 - 75%: 1035
 - max: 1440

### DURL313
Duration - Travel - Car - Driver

**Recoded to:** durDriving

**Unit:** Minutes in one day

**Type:** integer

 - Number unique responses: 145
 - Missing: 0
 - Count: 17390
 - Mean: 44.09
 - Std: 65.88
 - min: 0
 - 25%: 0
 - 50%: 20
 - 75%: 65
 - max: 900

### DUR08 
Duration - Paid work

**Recoded to:** durWork

**Unit:** Minutes in one day

**Type:** integer

 - Number unique responses: 232
 - Missing: 0
 - Count: 17390
 - Mean: 167.88
 - Std: 246.12
 - min: 0
 - 25%: 0
 - 50%: 0
 - 75%: 425
 - max: 1310

### DUR13
Duration - Schooling - On site

**Recoded to:** durSchoolSite

**Unit:** Minutes in one day

**Type:** integer

 - Number unique responses: 118
 - Missing: 0
 - Count: 17390
 - Mean: 8.04
 - Std: 53.05
 - min: 0
 - 25%: 0
 - 50%: 0
 - 75%: 0
 - max: 780

### DUR14
Duration - Schooling - Online

**Recoded to:** durSchoolOnline

**Unit:** Minutes in one day

**Type:** integer

 - Number unique responses: 27
 - Missing: 0
 - Count: 17390
 - Mean: 0.46
 - Std: 11.41
 - min: 0
 - 25%: 0
 - 50%: 0
 - 75%: 0
 - max: 750

### DUR15
Duration - Homework or studying

**Recoded to:** durStudy

**Unit:** Minutes in one day

**Type:** integer

 - Number unique responses: 118
 - Missing: 0
 - Count: 17390
 - Mean: 6.50
 - Std: 46.73
 - min: 0
 - 25%: 0
 - 50%: 0
 - 75%: 0
 - max: 1070

### MRW_20
Main activity - Studying full-time/part-time

**Recoded to:** mainStudy

**Type:** factor

 - Number unique responses: 3
 - Missing: 16618
 
 |**Value**|**Description**|
|:------|:------|
|1|A full-time student|
|2|A part-time student|
|3|Both full-time and part-time student|

### MRW_30
Main activity - Looked for a job - Last four weeks

**Recoded to:** mainJobHunting

**Type:** logical

 - Number unique responses: 2
 - Missing: 9310
 
 |**Value**|**Description**|
|:------|:------|
|1|Yes|
|2|No|

### MRW_40
Main activity - Job/self-employed - Past 12 months

**Recoded to:** mainWork

**Type:** logical

 - Number unique responses: 2
 - Missing: 8924
 
 |**Value**|**Description**|
|:------|:------|
|1|Yes|
|2|No|

### MRW_D40A
Worked in the last 12 months

**Recoded to:** worked12m

**Type:** logical

 - Number unique responses: 2
 - Missing: 0
 
 |**Value**|**Description**|
|:------|:------|
|1|Yes|
|2|No|

### MRW_D40B
Worked last week

**Recoded to:** workedWeek

**Type:** logical

 - Number unique responses: 2
 - Missing: 0
 
 |**Value**|**Description**|
|:------|:------|
|1|Yes|
|2|No|

### EDM_02
Education - Enrollment status

**Recoded to:** enrollStat

**Type:** factor

 - Number unique responses: 3
 - Missing: 16083
 
 |**Value**|**Description**|
|:------|:------|
|1|A full-time student|
|2|A part-time student|
|3|Both full-time and part-time student|

### TST_01
Number of text messages per day (groups of 10)

**Recoded to:** dailyTexts

**Type:** factor

 - Number unique responses: 8
 - Missing: 353
 
 |**Value**|**Description**|
|:------|:------|
|1|1-10 texts|
|2|11-20 texts|
|3|21-30 texts|
|4|31-40 texts|
|5|41-50 texts|
|6|51-60 texts|
|7| over 60 texts per day|

### TCS_110
Perceptions of time - Plans to slow down

**Recoded to:** timeSlowDown

**Type:** logical

 - Number unique responses: 2
 - Missing: 470
 
 |**Value**|**Description**|
|:------|:------|
|1|Yes|
|2|No|

### TCS_120
Perceptions of time - workaholic

**Recoded to:** timeWorkaholic

**Type:** logical

 - Number unique responses: 2
 - Missing: 362
 
 |**Value**|**Description**|
|:------|:------|
|1|Yes|
|2|No|

### TCS_150
Perceptions of time - Not spending enough time with family or friends

**Recoded to:** timeNotFamFriends

**Type:** logical

 - Number unique responses: 2
 - Missing: 362
 
 |**Value**|**Description**|
|:------|:------|
|1|Yes|
|2|No|

### TCS_200
Perceptions of time - Would like more time alone

**Recoded to:** timeWantAlone

**Type:** logical

 - Number unique responses: 2
 - Missing: 386
 
 |**Value**|**Description**|
|:------|:------|
|1|Yes|
|2|No|
I edited this document!
