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

### 1. Median Property Value Heat Map

<img src="https://github.com/dsasidharannair/TIF_Demographic-IPRO/blob/main/Map%20Images/Folium/Median%20Value.png" alt="TIF Transfers Heat Map" width="400">

The map is a heatmap that represents the median property values across Chicago's various census tracts, using a color scale that ranges from red to green. The color-coded outline of each census tract corresponds to its median property value, enabling a visual comparison of economic disparities within the city. The map can be read by looking at the color of a particular tract and using the color scale with the median value at the top in order to translate the color into a suitable range of property values. The darker the shade of green, the more expensive the properties in that area are, and conversely, the darker the shade of red, the less expensive the properties. 

The trend for increasingly costly real estate in these TIF regions is reflected in the heatmap of Chicago's median property values, which shows a noticeable gradient with greater values centered along the lakefront in East Chicago and the downtown area. While South and West Chicago primarily exhibit lower median property values, North Chicago exhibits a combination of greater and lower property values. The northern and center regions of the city appear to be wealthier than the southern and western regions, indicating a variation in real estate values.

### 2. Median Real Estate Tax Distribution Heat Map

<img src="https://github.com/dsasidharannair/TIF_Demographic-IPRO/blob/main/Map%20Images/Folium/Median%20Real%20Estate%20Tax.png" alt="Median Real Estate Tax Heat Map" width="400">

The above map uses a color scale, from red to green, to show the median real estate taxes of the various census tracts in Chicago. Red denotes lower tax values, while green denotes higher tax values. The color-coding and separation of the census tracts reflect the median tax value of each one. Viewers are able to understand the distribution of taxes around the city by referring to the color scale at the top of the map, which shows the precise range of taxes linked with each color. Tracts with the highest real estate taxes are indicated by dark green areas, while those with the lowest are indicated by dark red areas. 

Based on this heatmap, the distribution of median real estate taxes in Chicago shows a varied picture. Green-toned areas indicate census tracts with higher median real estate taxes, which are found in North Chicago and certain lakefront areas. This suggests a larger tax burden on real estate, which is frequently associated with greater property values and possibly more wealthy neighborhoods. Center, South, and West Chicago, on the other hand, have a more varied pattern, with some regions (yellow to light green areas) showing fairly high taxes and others (orange to red areas) showing lower taxes. 

### 3. Cumulative Property Tax Distribution Heat Map

<img src="https://github.com/dsasidharannair/TIF_Demographic-IPRO/blob/main/Map%20Images/Folium/Cumulative%20Property%20Tax%20Distribution.png" alt="Cumulative Property Tax Distribution Heat Map" width="400">

With a color scale that goes from red for smaller quantities of tax income received to green for higher amounts, the heatmap shows the cumulative property tax taken for Tax Increment Financing (TIF) across Chicago's census tracts. To read this map, you can identify the color of a tract and compare it to the color scale provided at the top, which quantifies the tax revenue. Darker shades of green suggest higher tax revenues, while darker red tones indicate areas with poor tax collection. Understanding the economic contribution of various areas to TIF is made easier with the help of this visualization, which also might show trends in city investment and development.

The map exhibits the varied distribution pattern of cumulative property tax contributions made by people of Chicago. The greener tones indicate greater contributions from the northern areas and parts of North West Chicago. These areas typically have higher property values, potentially translating to larger tax increments for TIF. The pattern in Central Chicago is more varied, with certain tracts contributing more and others less. By contrast, the majority of South and West Chicago exhibit lesser TIF contributions, as indicated by the red colors.

### 4. White Community Population Distribution Estimate Heat Map

<img src="https://github.com/dsasidharannair/TIF_Demographic-IPRO/blob/main/Map%20Images/Folium/White%20Population%20Estimate.png" alt="White Population Distribution Estimate Heat Map" width="400">

The Income Information Map visualizes income data, highlighting areas with varying income levels. It aids in identifying socio-economic disparities within the community.

### 5. Black Community Population Distribution Estimate Heat Map

<img src="https://github.com/dsasidharannair/TIF_Demographic-IPRO/blob/main/Map%20Images/Folium/Black%20Population%20Estimate.png" alt="Black Community Population Distribution Estimate HeatMap" width="400">

[Description of the fifth map and its significance]

### 6. Hispanic Community Population Distribution Estimate Heat Map

<img src="https://github.com/dsasidharannair/TIF_Demographic-IPRO/blob/main/Map%20Images/Folium/Hispanic%20Population%20Estimate.png" alt="Hispanic Community Population Distribution Estimate Heat Map" width="400">

[Description of the fifth map and its significance]

### Regression
This section will go through the statistical analysis we have conducted to try to look into the problem that we are investigating. We will use regression to answer the following questions:
- Have TIFs helped low-income communities?
- Does TIF district demographics determine whether funds are transferred (in or out)?
- Does TIF district demographics determine how much property tax is extracted?

## Results and Conclusions Summary
This section will highlight our most notable results. This will include statistical analysis of the relationship between TIF transfers, TIF fund allocation, race/ethnicity, income level, and property value.

Ethical Reflection:
During this project, we reflected on ethical outcomes that may come from our analysis. When thinking of the impact TIF districts have, we identified Chicago residents, more specifically minorities, as stakeholders. This project looked to answer whether are equitably being used across the city which is important to our stakeholders because the city claims that TIFs are meant to create opportunities for all residents. While making progress on this analysis, we continued to provide transparency and respect for individuals when searching for demographic indicators that influence the allocation of TIF funds across districts. By providing transparency, we are honest in explaining how we came to our conclusions and aiming to help minorities in Chicago that are overlooked by society.

## Sources
This section will cite all sources we have used for this project
