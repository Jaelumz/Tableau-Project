# Real Estate Analysis & Insights

## Project Overview
Real estate markets are influenced by various factors, including economic conditions, demographics, and changing policies. Understanding the dynamics of real estate prices and incomes is crucial for making informed decisions in this sector. This project utilizes data analysis and visualization techniques to uncover patterns and trends in real estate prices and incomes across Canadian districts.

## Goals
Generate insights into real estate price fluctuations across Canadian districts.
Analyze the relationship between real estate prices and incomes over time.
Create informative visualizations and dashboards to facilitate understanding and decision-making.

## Data Sources
The project utilizes data on real estate prices and incomes across select districts in Canada. The datasets may include information such as:
    Historical real estate prices by district.
    Average incomes by district.
    Economic indicators

## Process
    Data Preparation:
        Downloaded the provided datasets.
        Uploaded all datasets (CSV and JSON file) to Tableau.

    Exploratory Analysis:
        Conducted exploratory analysis on the datasets to grasp the data and its datatypes.
        Checked for any missing values or necessary manipulations to prepare the data for visualization.

    Data Transformations:
        Executed data transformations, using calculated fields to extract specific insights from the data.

    Visualization:
        Utilized optimal visualizations to provide desired insights to consumers of the report to base their decisions.


## Results and Insights
- Identification of trends and patterns in real estate prices across Canadian districts.
- Analysis of the relationship between real estate prices and incomes, including correlations and causal factors.
- Insights into factors influencing real estate market dynamics, such as economic conditions 

From analysis of the data and modelling relationships, the following conclusions were drawn:
- Prices of homes and offices have consistently risen over the last 40 years, with a significant surge occuring between 1983 and 1984.
- Canadian districts with the highest priced homes are Greater Vancouver, Lower Mainland and Oakville Milton. The price difference of homes in these districts has remained relatively consistent; however, earnings across Canada have exhibited a steady annual growth rate.
- There is no discernible difference between the Consumer Price Index and House Price Index over the years. Both indices have grown at the same rate.
- Changes in the proportion of income allocated to home expenses over time. In 2001, Canadians allocated over 150% of their incomes to home expenses and by 2014 this proportion decreased to slightly over 50%. Although no direct correlation has been observed between key economic events in the past and incomes or real estate prices in Canada, a subtle relationship exists with the prices of house construction, notably with a dip in the cost of construction materials during those pivotal years.

## Challenges 
Challenges faced entailed:
- Difficulties importing the JSON file into Tableau, resulting in an inaccurate table. This was addressed this by importing the file into Python, utilizing pandas to convert it into a dataframe, and subsequently exporting it to CSV.
- Limitations encountered in accessing specific charts needed to optimally provide visualization to support insights.

## Future Goals
- Incorporate additional datasets to enrich the analysis, such as demographic data and economic indicators.
- Implement advanced modeling techniques to forecast real estate prices and assess future trends.
- Enhance the interactivity and user experience of the dashboards based on feedback and user testing.
