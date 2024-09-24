# Exploratory Data Analysis on COVID-19 in 2020

![Status Badge](https://img.shields.io/static/v1?label=STATUS&message=COMPLETE&color=008000)

## 1. Introducing the Problem

In 2020, the COVID-19 pandemic affected the lives of millions of people around the world. In Brazil, the consequences of the pandemic have varied greatly between different social groups. Exploratory data analysis was carried out to better understand how socioeconomic factors related to the virus and access to testing. The aim is to provide insights into which groups have been most affected and how the virus has impacted different segments of the population.

## 2. Final Result

The analysis revealed important information such as:
- **Gender and Age:** Different age groups and genders showed variations in terms of infection. The most infected age group was between 30 and 50. And women had 1 percentage point more positive cases.
- **Urban vs. rural residence:** The highest incidence of positive cases occurred in urban areas.
- **Color or Race:** Among different racial groups, the indigenous population was the most affected proportionally. Among indigenous respondents, the infection rate was 5%. In the other groups, the average infection rate was 2%.
- **Educational Level:** Among those surveyed, the largest subgroup had Elementary School Incomplete (34%) and the second largest High School Complete (22%). However, when analysing those who tested positive for COVID-19, the proportions were reversed: 20% had Elementary School Incomplete and 29% had High School Complete. This inversion may indicate that there are more important factors influencing the level of infection.
- **Brazilian Region:** The regions of Brazil showed disparities in the infection rate, with the Northeast (33%) having the highest percentage among those surveyed and the South (9.5%) the lowest. In percentage points, comparing the proportion between the regions, the Northeast had the biggest increase (10 percentage points) in positive cases and the South the biggest drop (-7.5 percentage points).
- **Income:** The largest number of infected people had an income between R$801 and R$1600.
- **Healthcare establishment:** Only 23% of people who had any symptoms seek medical attention at healthcare establishment.
- **COVID test:** 20% of who had any symptom did the covid test.
- **Health insurance:** 17% even with symptoms and health insurance, didn't take the test.

These results offer a detailed view of how the pandemic has affected different segments of the population and can help formulate more effective policies for future health crises.

In addition, the low demand for health facilities and the low percentage of tests carried out may indicate additional barriers to testing and treatment of the disease.

## 3. Considerations and Assumptions

During the analysis, some considerations and assumptions were made:
- **Data representativeness:** The study assumes that the data sample is representative of the Brazilian population.

## 4. Development of the Solution
<img alt="Python" src="https://img.shields.io/badge/-Python-blue?style=flat&logo=python&logoColor=yellow" />  ![Badge](https://img.shields.io/badge/Colab-Google-%F9AB00?style=flat&logo=Google-Colab&color=blue)

The analysis was carried out using the following steps:
1. **Data Collection:** The public data from the PNAD COVID-19 survey was obtained from [IBGE](https://www.ibge.gov.br/estatisticas/sociais/saude/27947-divulgacao-mensal-pnadcovid2.html?edicao=28351&t=downloadsArquivos) website. The period analysed was from 07/2020 to 09/2020.
    * Downloads > microdados > Dados > PNAD_COVID_X2020.zip
    * Documentação > Dicionário_ PNAD_COVID_X2020_20210726.xls

2. **Data Cleaning and Preparation:** Missing data was understood to be the result of questions not applicable to the respondent. The only important transformation occurred with the categorical variables, which in the database were integer or float and were changed to string. In addition, to facilitate analysis, three more variables were created (region; had_symptom; positive_test). The database resulted in 1,157,984 rows and 109 columns.

3. **Data exploration**: Graphs were used to identify patterns and trends in the variables of interest.

4. **Interpretation of Results:** The data was analysed to extract meaningful insights into the impact of the pandemic.

## 5. Problems Faced

There were some challenges during the analysis:
- **Large volume of data**: The recommendation would be to use PySpark to analyse the data. Even when using cloud processing, there was a problem with lack of RAM.

## 6. Next Steps

To improve understanding of the impacts of the pandemic and support future research, we suggest the following next steps:
- **Deepen Analysis:** Investigate possible lack of access to COVID testing.

## Author

[![Linkedin Badge](https://img.shields.io/badge/-Patrícia-blue?style=flat&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/pathilink/)](https://www.linkedin.com/in/pathilink/)

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-750014.svg)](https://opensource.org/licenses/MIT)