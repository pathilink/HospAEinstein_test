# Documentation

## Variables

| Column | Description | Type | Changes | 
|-|-|-|-|
| UF | Unit of the federation | categorical | int -> string |
| CAPITAL | Capital | categorical | float -> string |
| RM_RIDE | Metropolitan region | categorical | float -> string |
| V1008 | Home selection number | discrete ||
| V1012 | Week of the month | categorical | int -> string |
| V1013 | Month of research | categorical | int -> string |
| V1016 | Home interview number | discrete ||
| Estrato | Subdivision of the population into homogenous groups based on specific characteristics. | categorical | int -> string |
| UPA | Primary sampling unit | categorical | int -> string |
| V1022 | Household situation: 1-Urban; 2-Rural | categorical | int -> string |
| V1023 | Type of area: Capital;... | categorical | int -> string |
| V1030 | Population projection | discrete||
| V1031 | Monthly weight with correction for non-interview without post-stratification by population projection | continuous ||
| V1032 | Monthly weight with correction for non-interview with post-stratification by population projection | continuous ||
| posest | Projection domains - The first 2 positions represent the Federation Unit code, the third, the resident's sex and the last, the resident's age group. UF(2) + A003(1) + Age group based on A002(1) | discrete |  int -> string |
| A001 | Order number | discrete ||
| A001A | Status in the household - spouse, child, son-in-law, etc.| categorical | int -> string |
| A001B1 | Day of birth| discrete ||
| A001B2 | Month of birth | discrete ||
| A001B3 | Year of birth | discrete ||
| A002 | Age of the resident | discrete ||
| A003 | Gender: 1-Man; 2-Woman | categorical | int -> string |
| A004 | Color ou race:<br> 1-White; 2-Black; 3-Asian; 4-Parda; 5-Indigenous; 6-Ignored | categorical | int -> string |
| A005 | Education: <br> 1-No education; 2-Elementary School Incomplete; 3-Elementary School Complete; 4-High School Incomplete; 5-High School Complete; 6-Higher Education Incomplete; 7-Higher Education Complete; 8-Post-graduate, master's or doctorate programme | categorical | int -> string |
| A006 | Attends school: 1-Yes; 2-No | categorical | float -> string |
| A007 |Last week, ____ were school activities made available to do at home? | categorical | float -> string |
| B0011 | Did you have a fever last week? | categorical | int -> string |
| B0012 | Did you have a cough last week? | categorical | int -> string |
| B0013 | Did you have a sore throat last week? | categorical | int -> string |
| B0014 | Did you have difficulty breathing last week? | categorical | int -> string |
| B0015 | Did you have a headache last week? | categorical | int -> string |
| B0016 | Did you have chest pains last week? | categorical | int -> string |
| B0017 | Were you nauseous last week? | categorical | int -> string |
| B0018 | Did you have a blocked or runny nose last week? | categorical | int -> string |
| B0019 | Did you have fatigue last week? | categorical | int -> string |
| B00110 | Did you have pain in your eyes last week? | categorical | int -> string |
| B00111 | Did it lose its smell or flavour last week? | categorical | int -> string |
| B00112 | Did you have muscle pain last week? | categorical | int -> string |
| B00113 | Did you have diarrhoea last week? | categorical | int -> string |
| B002 | Have you been to a health centre because of this? | categorical | float -> string |
| B0031 | The only way to recover from the symptoms was to stay at home | categorical | float -> string |
| B0032 | The first thing she did to recover from the symptoms was to call a health professional | categorical | float -> string |
| B0033 | The only way to recover from the symptoms was to buy and/or take medication on their own | categorical | float -> string |
| B0034 | The only way to recover from the symptoms was to buy and/or take medication on medical advice | categorical | float -> string |
| B0035 | Action taken to recover from symptoms was to receive a visit from a SUS health professional (family health team, community agent, etc.) | categorical | float -> string |
| B0036 | The first step to recovering from the symptoms was a visit from a private health professional  | categorical | float -> string |
| B0037 | Another measure taken to recover from the symptoms | categorical | float -> string |
| B0041 | The place where they sought care was a health centre/basic health unit/Family Health Team (doctor, nurse, nursing technician or community health worker) | categorical | float -> string |
| B0042 | The place where he sought care was the SUS/UPA emergency room | categorical | float -> string |
| B0043 | The place where he sought care was a SUS hospital | categorical | float -> string |
| B0044 | The place where he sought care was an outpatient clinic or private practice or one linked to the armed forces | categorical | float -> string |
| B0045 | The place that sought care was a private emergency room or one linked to the armed forces | categorical | float -> string |
| B0046 | The place where he sought care was a private hospital or one linked to the armed forces | categorical | float -> string |
| B005 | When he went to hospital, he had to stay for a day or more | categorical | float -> string |
| B006 | During hospitalisation, he was sedated, intubated and put on artificial respiration with a ventilator | categorical | float -> string |
| B007 | Do you have a medical insurance plan, whether private, company or public? | categorical | int -> string |
| B008 | Have you been tested for coronavirus?  | categorical | int -> string |
| B009A | Have you taken a swab from your mouth and/or nose (SWAB)? | categorical | float -> string |
| B009B | What's the result? | categorical | float -> string |
| B009C | Have you had a finger prick blood test? | categorical | float -> string |
| B009D | What's the result? | categorical | float -> string |
| B009E | Have you had blood taken from your arm vein? | categorical | float -> string |
| B009F | What's the result? | categorical | float -> string |
| B0101 | Has a doctor ever diagnosed you with diabetes? | categorical | int -> string |
| B0102 | Has a doctor ever diagnosed you with hypertension? | categorical | int -> string |
| B0103 | Has a doctor ever diagnosed you with asthma/bronchitis/emphysema/chronic respiratory disease or lung disease? | categorical | int -> string |
| B0104 | Has a doctor ever diagnosed you with heart disease (heart attack, angina, heart failure, arrhythmia)? | categorical | int -> string |
| B0105 | Has a doctor ever diagnosed you with depression? | categorical | int -> string |
| B0106 | Has a doctor ever diagnosed you with cancer? | categorical | int -> string |
| B011 | What was the result of the test?  Last week, due to the Coronavirus pandemic, to what extent did you restrict contact with people? | categorical | int -> string |
| C001 | Did you work or do odd jobs for at least an hour last week? | categorical | float -> string |
| C002 | Were you temporarily off work last week? | categorical | float -> string |
| C006 | You have more than one job | categorical | float -> string |
| C007 | In the (only or main) job I had that week, it was: private sector, public sector, etc. | categorical | float -> string |
| C007B | Do you have a work permit or are you a civil servant? | categorical | float -> string |
| C007C | What type of work, position or function do you do in your job (sole or main)? | categorical | float -> string|
| C007D | What is the main activity of the place or company where you work? | categorical | float -> string|
| C008 | How many hours a week did you normally work? | continuous ||
| C009 | How many hours did you actually work last week? | continuous ||
| C01011 | Income/cash withdrawal band number | categorical | float -> string |
| C01012 | Cash value | continuous ||
| C011A11 | Income/cash withdrawal band number | categorical | float -> string |
| C011A12 | Cash value | continuous ||
| C012 | Most of the time last week, was this job (sole or main) carried out in the same place where you usually work? | categorical | float -> string |
| C014 | Do you contribute to the INSS? | categorical | float -> string |
| C015 | Last week, did ___ take any effective steps to get a job? | categorical | float -> string |
| C016 | What was the main reason you didn't look for work last week? | categorical | float -> string |
| C017A | Although you didn't look for work, would you have liked to have worked last week? | categorical | float -> string |
| D0011 | Retirement and pension income received by all residents | categorical | int -> string |
| D0013 | Sum of amounts received | continuous ||
| D0021 | Income from alimony, donations or pocket money from a person who did not live in the household | categorical | int -> string |
| D0031 | Income from the Bolsa Família Programme | categorical | int -> string |
| D0041 | In the month of ... (reference month), ... received income from the Benefício Assistencial de Prestação Continuada – BPC-LOAS? | categorical | int -> string |
| D0051 | Emergency aid related to the coronavirus | categorical | int -> string |
| D0053 | Sum of amounts received | continuous ||
| D0061 | Unemployment insurance | categorical | int -> string |
| D0071 | Other income, such as rent, leasing, private pensions, scholarships, investment income, etc. | categorical | int -> string |
| E001 | Has anyone in this household applied for a loan during the pandemic? | categorical | int -> string |
| F001 | This home is: owned, rented, etc. | categorical | int -> string |
| F002A1 | The following basic cleaning and protection items are available in your home: soap or detergent | categorical | int -> string |
| F002A2 | The following basic cleaning and protection items are available in your home: alcohol 70% or higher (gel or liquid) | categorical | int -> string |
| F002A3 | The following basic cleaning and protection items are available in your home: masks | categorical | int -> string |
| F002A4 | The following basic cleaning and protection items are available at your home: disposable gloves | categorical | int -> string |
| F002A5 | The following basic cleaning and protection items are available in your home: bleach or disinfectant | categorical | int -> string |
| F0061 | Who answered the questionnaire? | categorical | int -> string|
| F006 | Order number of the resident who provided the information | discrete | float -> int|
| region | Brazilian federal regions | categorical | |
| had_symptom | Each respondent had 1 or more symptoms | bolean ||
| positive_test | Tested positive for COVID-19 in at least 1 type of test | bolean ||
