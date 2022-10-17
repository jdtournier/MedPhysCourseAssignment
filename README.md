# Assignment and associated data files for Statistics Coursework

## Diabetes Dataset

These data are courtesy of Dr John Schorling, Department of Medicine, University of
Virginia School of Medicine.
  
The data consist of 19 variables on 403 subjects from 1046 subjects who were interviewed
in a study to understand the prevalence of obesity, diabetes, and other cardiovascular risk
factors in central Virginia for African Americans. According to Dr John Hong, Diabetes
Mellitus Type II (adult onset diabetes) is associated most strongly with obesity. The
waist/hip ratio may be a predictor in diabetes and heart disease. DM II is also agssociated
with hypertension - they may both be part of "Syndrome X". The 403 subjects were the
ones who were actually screened for diabetes. Glycosolated hemoglobin > 7.0 is usually
taken as a positive diagnosis of diabetes. For more information about this study see

[Willems JP, Saunders JT, DE Hunt, JB Schorling: Prevalence of coronary heart disease
risk factors among rural blacks: A community-based study. Southern Medical Journal
90:814-820; 1997](https://pubmed.ncbi.nlm.nih.gov/9258308/)

and

[Schorling JB, Roach J, Siegel M, Baturka N, Hunt DE, Guterbock TM, Stewart HL: A
trial of church-based smoking cessation interventions for rural African Americans.
Preventive Medicine 26:92-101; 1997.](https://pubmed.ncbi.nlm.nih.gov/9010903/)

[Frank E Harrell Jr](mailto:fharrell@virginia.edu)
Last modified: Fri Dec 27 16:32:05 EST 2002


## Description of variables

403 observations and 19 variables, maximum number of missing value (NA): 262

### Table 1: description of data

Name | Labels | Units | Levels | Storage | NAs
-----|--------|-------|--------|---------|-----
id | Subject ID | | | double | 0
chol | Total Cholesterol | | | double | 1
stab.glu | Stabilized Glucose | | |  double | 0
hdl | High Density Lipoprotein | | | double | 1
glyhb | Glycosolated Hemoglobin | | | double | 13
location | | | 2 | integer | 0
age | | years | | double | 0
gender | | | 2 | integer | 0
height | | inches | | double | 5
weight | | pounds | | double | 1
frame | | | 3 | integer | 12
bp.1s | First Systolic Blood Pressure | | | double | 5
bp.1d | First Diastolic Blood Pressure | | | double | 5
bp.2s | Second Systolic Blood Pressure | | | double | 262
bp.2d | Second Diastolic Blood Pressure | | | double | 262
waist | | inches | | double | 2
hip | | inches | | double | 2
ime.ppn | Postprandial Time when Labs were Drawn | minutes | | double | 3

### Table 2: levels for nominal variables

Variable | Levels
---------|--------
location | Buckingham<br>Louisa
gender | male<br>female
frame | small<br>medium<br>large

