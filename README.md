# TIF_Demographics-IPRO

## Team Members:
- Andres Iniguez: Project Lead
- Zaid Iqbal: Data Analytics Lead
- Darshan Nair: Data Collection Lead
- Jean-Yves Thomason: Data Visualization Lead

## About the Project:
Our project delves into investigating the relationship between the demographics of Tax Increment Financing (TIF) districts and the allocation of funds within them. Inspired by CivicLab's TIF illumination project, which highlighted disparities in TIF fund distribution based on race in Chicago, our aim is to broaden this analysis to encompass various demographic factors such as age, income level, ethnicity, and more. By exploring potential correlations between demographics and TIF fund allocation, we seek to identify any inequities that may exist within the system.

This research is vital as it serves as a foundational step towards advocating for more equitable TIF policies. By gathering and presenting statistical evidence of potential disparities in fund allocation, we aim to inform policymakers and stakeholders, ultimately fostering dialogue and action towards creating fairer TIF policies.

## What is the problem?
Chicago has historically had a problem with allocating funds for government programs in an equitable manner. Many demographics have largely been underfunded, ignored, or discriminated against which has snowballed into larger and larger inequalities between groups of people such as gaps in wealth, income, education, health, and crime. Addressing these issues is an important step to help uplift these groups and correct the wrongs of the past. If we are able to find correlations that show certain demographics are being treated unequally when it comes to distributing TIF funds, then these issues can be addressed and corrected by crafting and passing better policies. 

## Problem Approaches
This section will go into detail about the approach we took to tackle this problem and why.
### Data Collection
The first step of the approach was collecting our data. This included the Civic Lab report data on TIFs; City of Chicago data portal geojson files for TIF, census tract, and community area boundaries; and US Census data at the census tract level for Cook County. We will provide links for all of these datasets and provide information as to why we used them.
### Data Preparation
This next step included preparing our data before performing our statistical analysis. In the process of data preparation for our statistical analysis, meticulous steps were taken to ensure the reliability and coherence of the datasets utilized. Initial efforts involved amalgamating demographic data sourced at the census tract level, encompassing key indicators such as racial population distribution, median household income stratified by race, median property values, and property tax figures. To accurately contextualize these demographic insights within the framework of TIF (Tax Increment Financing) districts, an additional layer of complexity was introduced: the determination of the overlap ratio between census tracts and TIF districts. Leveraging the assumption of even population distribution across census tracts, estimations of population breakdown by race were derived for each TIF district. This nuanced approach enabled the creation of a comprehensive dataset, which was subsequently merged with a TIF report dataset housing exhaustive information on fund allocation to TIFs. The resultant amalgamation of data sets facilitated our capacity to undertake robust exploratory analyses, illuminating the intricate correlations between demographic indicators and fund allocation within Chicago's TIF districts.
### Visualizations
This section will focus on going through our maps and how to interact with them, while also going through what each map is showing such as heat maps for TIF transfers, fund allocation, demographics, and income information.
### Regression
This section will go through the statistical analysis we have conducted to try to look into the problem that we are investigating. We will use regression to answer the following questions:
- Have TIFs helped low-income communities?
- Does TIF district demographics determine whether funds are transferred (in or out)?
- Does TIF district demographics determine how much property tax is extracted?

## Results and Conclusions Summary
This section will highlight our most notable results. This will include statistical analysis of the relationship between TIF transfers, TIF fund allocation, race/ethnicity, income level, and property value.

## Sources
This section will cite all sources we have used for this project
