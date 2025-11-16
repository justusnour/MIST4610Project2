# MIST 4610 Project 2 Group 7

## Group Members: 
1. [Justus Nour](https://github.com/justusnour)

2. [Jackson Boyer](https://github.com/Jackson9812)
   
3. [Rong Xin Hu](https://github.com/RongX02)

4. [Trey Trotti](https://github.com/treytrotti)

5. [Sophie Yoo](https://github.com/sophieyoo)


Dataset Description

Data Set: Hate Crimes by County and Bias Type Beginning 2010


https://catalog.data.gov/dataset/hate-crimes-by-county-and-bias-type-beginning-2010


Canva Link: 
https://www.canva.com/design/DAG4suJcqb0/mXVWzznl7W_f_z9J15qjTg/edit 


The dataset used for this project is titled “Hate Crimes by County and Bias Type, Beginning 2010.” It was obtained from the U.S. Data.gov open data portal and published by the New York State Division of Criminal Justice Services.


This dataset provides annual counts of reported hate crime incidents, victims, and offenders across New York State counties from 2010 to the most recent available year. Bias types are grouped into categories including race, religion, sexual orientation, gender/gender identity, and disability. Each row represents a county-year combination with counts for dozens of specific bias motivations.


At the time of analysis, the dataset included 822 rows and 44 columns. The key variables include:


County: Name of the New York county

Year: Reporting year

Crime Type: “Crimes Against Persons” or “Property Crimes”

Numerous bias-specific fields: (e.g., Anti-Black, Anti-Jewish, Anti-Gay Male, Anti-Transgender, Anti-Physical Disability)

Total Incidents, Total Victims, Total Offenders

This dataset is well-structured, rich in detail, and allows meaningful analysis of hate crime patterns over time.

Types of Analysis Conducted
1. Descriptive Data Analysis

We performed descriptive analysis to understand the overall trends in total hate crime incidents across counties and years. This included aggregating total incidents by year and visualizing how annual counts changed from 2010 through 2022.

2. Explanatory Data Analysis

Explanatory analysis was used to understand why certain categories of hate crimes are more prevalent. We grouped dozens of individual bias fields into major categories (Race, Religion, Sexual Orientation, Gender/Gender Identity, Disability) and examined how the frequency of each category changed over time.

Project Questions
Descriptive Question

How have the total number of hate crime incidents in New York State changed each year since 2010, and which counties have reported the highest or lowest totals?

This question summarizes statewide patterns and identifies which regions experience the highest levels of hate crime activity.

Explanatory Question

What types of bias—such as race, religion, sexual orientation, or gender identity—account for the largest share of hate crime incidents, and how have these patterns shifted over time?

This question explores the underlying motivations behind hate crimes and highlights how bias categories evolve over time.

Data Manipulations Applied

Before analysis, several data transformations were applied:

Filtered data to include the years 2010–2022

Grouped 30+ bias fields into major categories using Tableau calculated fields

Created aggregated totals for each major bias category

Handled missing or zero values by treating them as zeros for accurate summation

Combined crime types (“Crimes Against Persons” + “Property Crimes”) where needed

Created derived metrics (e.g., Year-over-Year changes, category totals)

These transformations allowed for clean, interpretable visualizations.

Analysis and Results

To analyze how hate crime motivations have shifted over time, we aggregated individual bias types into major categories and visualized yearly totals from 2010–2022.

The results show that race-related hate crimes consistently account for the largest number of incidents. Although they fluctuate year to year, race bias remains dominant and shows a notable upward trend after 2019.

Religion-based hate crimes are the second most common category. They follow a similar pattern to race bias with peaks in 2012, 2018, and again in recent years, suggesting periods of heightened religious tension or increased reporting.

Sexual orientation hate crimes show moderate but meaningful variation. These incidents dip around 2017 and rise again after 2020, possibly reflecting social or political shifts related to LGBTQ+ communities.

Gender and gender identity bias accounts for the smallest share but shows distinct spikes in 2016 and 2021, aligning with periods of increased public discourse surrounding transgender rights.

Overall, the analysis reveals that race and religion remain the most prevalent categories, with upward trends in recent years. Sexual orientation and gender-based hate crimes are less frequent but show important shifts that reflect evolving social dynamics.
