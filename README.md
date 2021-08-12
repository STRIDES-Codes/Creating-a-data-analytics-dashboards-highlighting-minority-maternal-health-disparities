# Creating-a-data-analytics-dashboards-highlighting-minority-maternal-health-disparities

Lina Takemaru

Theresa Boyer
tboyer3@jhmi.edu
Johns Hopkins Bloomberg School of Public Health, Baltimore, MD, 21205

Bobby Yang
yangbobby50@yahoo.com, wy22@rice.edu

Britney Forsyth

Faysal Shaikh

Khadija Wane
khardiatouwane03@gmail.com, khardiatou-wane@pgcps.org
Fairmont Heights High School, Landover MD 20785 

# Abstract
Our vision is to jump-start the creation of data analytics dashboards highlighting minority maternal health disparities using publicly-available data.

We hope to utilize modern data cleaning/wrangling techniques to prepare publicly-accessible datasets for analysis, modern tools to build (and potentially host) public-facing data dashboards, and both modern/traditional statistical methods (potentially including machine learning!) in our analyses.

# Keywords
minority health, maternal health, data analysis, dashboard, health disparities, people of color, health inequity, neonate

# Introduction
Despite modern medical advancements and public health initiatives, the United States continues to perform poorly on maternal health related metrics. These poor outcomes are especially severe for minority communities. Research points to differences in hospital quality, limited access to care, and chronic diseases as reasons for these disparities. However, larger systemic inequities including structural racism, educational opportunities, and gender hierarchy likely contribute. 
# Methods

# Implementation
This tool aggregates data about minority maternal health to demonstrate the complex systemic (national and community based) factors that contribute to maternal and neonatal health disparities. For now, the data is aggregated from 2019 Birth Certificate Data from the CDC accessible via WONDER (https://wonder.cdc.gov). 

Data from 2019 was queried in WONDER by maternal state of residence, maternal race (6 categories), and outcome/risk factor/social variable of interest. R was used to covert the data from long to wide format. Data was mered by state of residence in wide format. Rates per 1,000 live births were calculated using the number of live births within a state of residence and race category. 
# Operation
Currently, the user will need to use R to visualize the data. 
# Results
We created a sample visualization for the state of Alabama for 2019 showing maternal outcomes (ICU admission, unplanned hysterectomy, blood transfusion, maternal transfer), risk factors (pre-pregnancy chronic hypertension, pre-pregnancy diabetes mellitus), and social variables (education-level, access to prenatal care) per 1,000 live births by race category. 
# Conclusion and next steps
Next steps are determining where to store the data to allow for public use, identifying additional sources of data (not restricted to live births, more economic information, psycho-social information), and determining how to allow for appropriate statistical tests and inferences from available data. 

# References

https://www.nber.org/research/data/vital-statistics-natality-birth-data dataset

