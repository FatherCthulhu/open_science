# open_science
Code drafts for university institutional debts in California state owned colleges

Institutional debts are debts accrued by individuals who navigate institutions and come to owe debts for the services and goods provided. Unlike traditional debts, such as student loan debt, institutional debt is highly fractured, with litte to no monitering of it. Debts can range from as little as $50 to upwards of several thousand. These debts are sought by institutions, who increasingly rely on the state to collect on their behalf through tax garnishments or private debt collection companies. These debts can create holds on students account, resulting in an inabilty to gain access to public services campuses offer.

This repository aims to create a snapshot over time of California higher education instittuional debts across all state owned colleges.

This includes:
116 California Community Colleges (CCC's)
23 California Status Universities (CSU's)
10 University of California Campuses (UC's)

The data is at the institutional level, and as such, cannot identify individual cases of students institutional debts. The data focuses on students at the undergraduate level, ranging from 2018 - 2023, though certain data points are currently limited to single years, noted within the file headers for specific resources. 

The data used in this project has been collected from the following sources:

1. Integrated Postsecondary Educational Data System (IPEDS) from the National Center for Educational Statistics
-   https://nces.ed.gov/ipeds

2. Public Records Access Requests Filed With:
- Californias Franchise Tax Board (FTB)
- CCC Chancelors Offices
- CSU Office of the Chancellor
- UC Office of the President

3. Next Gen Policy Nonprofit
- https://www.nextgenpolicy.org/


## Data plan

**HYPOTHESES**

HYPOTHESIS 1: Universities with publicly elected governance boards will have a lower rate of collection on institutional debts than universities with appointed governance boards.

I hypothesize the above pattern because universities with appointed governance boards are more likely to have bankers and financiers attached than locally elected governance boards. The presence of bankers and financiers on governance boards is shown to increase financially predatory policies and practices at universities (Eaton 2022).

HYPOTHESIS 2: Universities with a larger proportion of Hispanic or Black students will have a higher rate of institutional debts collected on.

I hypothesize the above pattern because universities with larger Hispanic or Black student populations have historically carried out predatory policies and practices at univerities that consist of larger Hispanic or Black student populations (Hamilton and Nielsen 2021).

HYPOTHESIS 3: COVID-19 may acts as a period in time where there is a change in institutional policies and practices with regards to the collection of institutional debts.

I hypothesize the above pattern because differences in governance of instituitions can be exacerbated during moments of crisis due to the different positions and networks that governing leaders are embedded in at moments of crisis for institutions (???????)

## Design Plan

**Study Type**

Correlational including predictive quantitative design - Data is collected from different state institutions and controlled to create equivalent comparative cases.

**Study Design**

I will test the hypotheses by estimating regression models that control for observed factors, including, in some cases, institution and year fixed effects

## Sampling Plan

**Existing Data**

Registration prior to analysis of the data

**Data Collection Procedures**

I will analyze data from the U.S. Department of Education National Center for Education Statistics’ Integrated Postsecondary Education Data System (IPEDS), which can be accessed at https://nces.ed.gov/ipeds/datacenter/.

I will merge IPEDS institutional characteristics data with state level and higher education institution level data.

**Sample Size**

IPEDS includes the full population of 14,759 colleges that were ever eligible since 1987 to enroll students with Title IV federal student loans or grants. I will analyze data on the 148 state owned institutions in IPEDS that are from fall 2018 and fall 2023.

**Sample Size Rational**

I will analyze existing data. The institutions excluded are done so due to a lack of institutional debt data on private universities and universities outside of California. To control for different student population sizes, I will look at institutional debt rates for colleges per 100 students enrolled.

## Variables

**Measured Variables**

Webphage Content Analysis
- Transcript holds

Franchise Tax Board Use by Campuses
- Used FTB
- Number of Debts Collected Per 100 Students
- $ Debts Offset per Enrolled Student
- Total $ Debt Garnished

IPEDS
- Total Students
- % Undergraduate Awarded Pell Grants
- Average Amount of Pell Grant Awaarded to Undergraduates
- % Part Time Students
- % Asian Students
- % Black Students
- % Hispanic or Latino Students
- % White Students
- % Two or More Race/Ethnicity Students
- College Status (CCC, CSU, UC)


## Analysis Plan

I analyze institutional student debt collection practices at all public community colleges
and state universities in California. To do so, I use mixed methods research design, combining
content analysis with descriptive statistics across school types and, regression analysis. The
content analysis examines language used by colleges to discuss their institutional student debt
policies on financial aid webpages. The quantitative analysis relies on a combined data set of
college-level surveys from the Integrated Postsecondary Education Data System (IPEDS) from
2023 and FTB financial reports on the amount of institutional debt colleges and universities have
sought collected from in 2019 and 2023.

IPEDS data provides information on school level institutional characteristics. Data from
IPEDS for this analysis includes the percent of undergraduates from different racial and ethnic
groups, percent of undergraduates that are part-time, and the percent of undergraduates receiving
Pell grants. IPEDS also provides data on the average size of a Pell grant aware at each school.
Data on schools use of state tax refund offsets for collections was acquired through Public
Records Access requests (PRA's) made from May 2024 - May 2025. Requests were made to the
Franchise Tax Board (FTB) office, the State Controller’s Office, the University of California Office
of the President, the California Community Colleges Chancellor’s Officer, and the California State
Universities Office of the Chancellor.
