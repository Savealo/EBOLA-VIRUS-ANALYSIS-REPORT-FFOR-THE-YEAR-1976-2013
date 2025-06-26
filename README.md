# EBOLA-VIRUS-ANALYSIS-REPORT-FFOR-THE-YEAR-1976-2013
The project addresses the challenge of understanding the epidemiological patterns and impact of the Ebola virus between 1976 and 2013. Specifically, it seeks to
INTRODUCTION

Objective of the Project

The objective of this project is to analyze and visualize Ebola virus outbreak data from 1976 to 2013 to identify trends in infection and mortality rates, assess the distribution of Ebola subtypes across affected countries, and provide insights into the geographic and temporal patterns of the virus. This analysis aims to support health authorities, researchers, and policymakers in understanding the historical impact of Ebola and enhancing future preparedness and response strategies..

Problem Being Addressed

The project addresses the challenge of understanding the epidemiological patterns and impact of the Ebola virus between 1976 and 2013. Specifically, it seeks to:

Identify which Ebola subtypes have been most deadly and widespread.
Highlight the countries most affected in terms of cases and deaths.
Understand the temporal spread of Ebola outbreaks over the years.
Provide data-driven insights to inform future public health interventions, outbreak preparedness, and resource allocation.
The core problem is the lack of accessible, consolidated analysis that enables quick identification of high-risk regions and virus strains — critical for early detection and rapid response to future outbreaks.

Key Datasets

The analysis is based on a consolidated dataset covering Ebola virus outbreaks from 1976 to 2013, with the following key variables:

Ebola Subtype — Identifies the strain of the virus (e.g., Zaire, Sudan, Reston, Bundibugyo, Taï Forest).
Reported Number of Human Cases — Total confirmed or suspected infections per outbreak.
Reported Number of Deaths Among Cases — Total fatalities per outbreak.
Country — Geographical location where the outbreak occurred.
Year(s) — Time period during which outbreaks were recorded.
Region/Continent — Geographic mapping of affected areas.
Subtype Occurrence by Country — Frequency and distribution of Ebola virus subtypes per country.
These datasets are likely sourced from public health records, WHO reports, CDC data, and academic publications on Ebola epidemiology.

STORY OF DATA

This dataset provides a summary of Ebola outbreaks across different countries. It includes the subtype of Ebola virus involved, the number of reported human cases, and the fatality metrics (deaths and mortality percentage). The goal is to understand the geographical and virological patterns of Ebola cases and their outcomes, which can aid in targeted healthcare responses and prevention strategies.

Data Source: The data was obtained from Kaggle.com

Data Collection Process: This data was obtained from Kaggle.com

Data Structure: The data contains 34 rows with each representing a distinct year and 6 columns representing year, country, ebola subtype, reported number of human cases, reported number of deaths among cases, and reported percentage of deaths among cases.

Data Limitations or Biases

Underreporting of Cases and Deaths
Many Ebola outbreaks occurred in remote or conflict-affected areas with weak health infrastructure, leading to incomplete or delayed reporting of cases and fatalities.

Time Gaps in Data
There are inconsistencies and missing data across different years, especially during early outbreak periods (1976–1990s), which can skew trend analysis and comparison.

Subtype Classification LimitationsSome Ebola cases may not have been accurately classified by subtype due to limited diagnostic capacity in affected regions during early outbreaks.
Country-Level Aggregation
Data is aggregated at the national level, which hides intra-country variations and localized outbreak dynamics (e.g., urban vs. rural spread).

Bias Toward High-Impact Countries
Countries with high case numbers (e.g., DRC, Uganda) may receive more attention in the analysis, potentially overshadowing important patterns in less-affected countries.

Lack of Socioeconomic and Environmental Context
The dataset does not include contextual factors such as healthcare access, population density, climate, or animal reservoirs, which are crucial for a full epidemiological understanding.

Inconsistent Case Definitions
Over the years, case definitions may have evolved, affecting comparability of data across time periods.

Absence of Patient Demographics
No information on age, gender, or occupation of infected individuals limits the ability to perform demographic risk analysis.

DATA SPLITTING AND PREPROCESSING

Data Cleaning: The data was cleaned by removing duplicates, identifying and removing blanks, and ensuring that no inconsistencies are observed. Thereafter, the data was converted to a standard excel table to ease analysis.

To remove duplicate, simply copy the entire data (ctrl +shift + end) then navigate to the data tab and on the data tools ribbon to select “remove duplicates”.

To identify and remove blanks, simply copy the entire data (ctrl +shift + end) on the home tab navigate to the editing ribbon and click “Find and select”, then navigate to “Go to Special” and select “Blanks”, finally click on OK.

Handling Missing Values: There are no missing values in the data.

Data Transformations: No data transformations were performed.

Tool used: Power BI

DATA SPLITING

Independent Variables:

Country

Ebola subtype

Dependent Variables:

Reported number of human cases

Reported number of deaths among cases

Reported % of deaths among cases

STORY OF THE DATA

This dataset provides a summary of Ebola outbreaks across different countries. It includes the subtype of Ebola virus involved, the number of reported human cases, and the fatality metrics (deaths and mortality percentage). The goal is to understand the geographical and virological patterns of Ebola cases and their outcomes, which can aid in targeted healthcare responses and prevention strategies.

Stakeholders of the Project

Public Health Authorities (e.g., WHO, CDC)

Epidemiologists and Medical Researchers

Government Health Ministries

International Aid Organizations (e.g., Red Cross, MSF)

Policy Makers

Data Analysts in Health Sectors

Pharmaceutical and Biotech Companies

What Success means to the Industry

Early Detection & Containment of future Ebola outbreaks

Reduction in Mortality Rates

Effective Allocation of Resources in high-risk areas

Informed Policy Making and outbreak preparedness

Identification of High-Risk Subtypes for vaccine or treatment development

PRE-ANALYSIS

Potential Analysis Questions

Which country had the highest number of Ebola cases?
Which Ebola subtype is the most deadly?
Is there a correlation between number of cases and mortality rate?
Are certain countries consistently more affected across different outbreaks?
What is the average mortality rate by subtype?
How does the virulence differ by geographic region?
Potential Analysis Insights

Geographic hotspots of high mortality or case concentration
Subtypes associated with higher case fatality rates
Trends in how countries respond to outbreaks (case/death ratios)
Evidence of reporting discrepancies (e.g., high case count but unusually low death rate)
Identification of underreported regions or outbreaks
IN-ANALYSIS

IN ANALYSIS OBSERVATIONS AND INSIGHTS

Total Ebola Subtypes: 5

Total Reported Cases: 2,361

Total Reported Deaths: 1,548

Fatality Rate: ~65.6%

Total Affected Countries: 15

This highlights a high fatality rate across outbreaks,

pointing to the extreme danger posed by Ebola viruses, particularly in areas with limited healthcare infrastructure.

Subtype Impact Analysis

Zaire Virus is the deadliest: Responsible for ~70.16% of total deaths.

Sudan Virus: Second most lethal, contributing to about 26.61% of deaths.

Other subtypes (Bundibugyo, Reston, Tai Forest) have much lower death counts.

Insight: Prioritizing vaccine and treatment

development for Zaire and Sudan viruses could reduce the vast majority of deaths.

Country-Level Impact

Top 3 countries by death count:

DR Congo — 465 deaths

Uganda — 269 deaths

Republic of the Congo — 280 deaths

To 3 by case count:

DR Congo — 647 cases

Uganda — 592 cases

Sudan (South Sudan) — 335 cases

Insight: These countries are not only frequently affected but may also serve as reservoirs or hotspots for future outbreaks. Cross-border preparedness is crucial.

Subtype Distribution by Country

Gabon has seen 4 different Ebola subtypes, indicating high viral diversity.

Republic of the Congo and Russia report 3 and 2 subtypes, respectively.

Insight:

Countries with multiple subtypes may face challenges in diagnostics, vaccine suitability, and outbreak control.

Temporal Trends

Peak Outbreak Periods:

Highest case and death numbers between 1976–2003. A visible dip in reported numbers during 1989–1992 and 2011–2013.

Insight: This suggests periods of underreporting, effective control, or natural lull. More

consistent surveillance is necessary to avoid undetected outbreaks.

Geographical Spread

Concentration in Central and Western Africa. Very limited spread outside Africa — isolated subtypes like Reston appear elsewhere but show minimal fatality.

Insight: Ebola remains a primarily African public health threat, but global travel and mutations pose future risks.

POST-ANALYSIS AND INSIGHTS

DATA VISUALIZATIONS & CHARTS

COUNTRY BY NUMBER OF EBOLA SUBTYPES

![image](https://github.com/user-attachments/assets/2380541b-c3c3-42d4-a8fe-42184f303093)
![image](https://github.com/user-attachments/assets/2380541b-c3c3-42d4-a8fe-42184f303093)

Gabon has the highest diversity of Ebola virus subtypes, with 4 different subtypes reported, indicating its critical role in understanding Ebola virus ecology and mutation patterns.

The Republic of the Congo follows with 3 subtypes, suggesting multiple outbreaks or spillover events.

Russia and Zaire (now the Democratic Republic of the Congo) each reported 2 subtypes, reflecting repeated exposure or viral variation over time.

South Africa had 1 subtype, showing limited but notable exposure.

Key Insight:
The variation in subtype presence across countries points to differing levels of surveillance, ecological exposure, and outbreak history. Gabon’s high subtype diversity makes it a potential hotspot for studying the evolution and spread of the Ebola virus.

REPORTED NUMBER OF DEATHS AMONG CASES BY COUNTRY

![image](https://github.com/user-attachments/assets/1d9341b4-45f6-4825-a73a-aae67003accb)
![image](https://github.com/user-attachments/assets/1d9341b4-45f6-4825-a73a-aae67003accb)

The Democratic Republic of the Congo (DRC) reports the highest number of deaths at 465, emphasizing its central role in the historical impact of Ebola.

Zaire (now part of DRC) and Uganda follow with 280 and 269 deaths respectively, highlighting repeated and severe outbreaks.

The Republic of the Congo (200 deaths), Sudan (South Sudan) (180 deaths), and Gabon (150 deaths) also show significant mortality burdens.

Russia reports only 2 deaths, likely indicating either a single isolated incident or laboratory exposure.

Key Insight:

The DRC and surrounding Central African countries bear the heaviest mortality burden from Ebola, reinforcing the need for sustained public health investment, early detection systems, and localized outbreak management strategies in these regions.

REPORTED NUMBER OF DEATHS AMONG CASES BY COUNTRY

![image](https://github.com/user-attachments/assets/26be0cae-79ca-4846-997e-51097d4c2fb4)
![image](https://github.com/user-attachments/assets/26be0cae-79ca-4846-997e-51097d4c2fb4)

Democratic Republic of the Congo (DRC) leads with the highest number of reported Ebola-related deaths (465), indicating it was the most severely impacted country during the 1976–2013 period.

Zaire & Uganda follow closely with 280 and 269 deaths respectively, reflecting major outbreaks with high fatality rates.

Republic of the Congo (200 deaths) and Sudan (180 deaths) also experienced significant loss of life, showing the broader regional impact within Central and East Africa.

Gabon recorded 150 deaths, despite also having the highest number of Ebola subtypes, suggesting complex outbreak dynamics.

Russia, with only 2 deaths, likely experienced a rare and isolated incident.

Insight:
The analysis reveals a concentration of Ebola-related deaths in Central and East Africa, pointing to a geographic hotspot for outbreaks. These high fatality numbers emphasize the need for strengthened healthcare systems, rapid response capacity, and sustained research in the most affected countries.

COUNTRY AND EBOLA SUBTYPE
