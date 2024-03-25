# DSDP-Project-1
This research project, which is in partnership with the Consumer Data Research Centre (CDRC) and Good Food Oxfordshire (GFO), investigates the spatial association between food insecurity risk and health outcomes in Oxfordshire. By identifying areas where overall food insecurity or specific risk factors could be driving the prevalence of certain health outcomes or conditions, this research empowers Good Food Oxfordshire (GFO) to support the food system in areas where it is needed to reduce health inequalities. 

The research project uses the Priority Places for Food Index (PPFI), an LSOA-level composite index developed by the CDRC, as a measure of food insecurity risk. A Lower Super Output Area (LSOA) is a geographic hierarchy and area, commonly ysed to report Census results, that is formed of 400-1,200 households and has a  The PPFI combines data across seven different dimensions (food insecurity risk factors) covering barriers to food purchase (e.g., supermarket proximity and accessibility) and deprivation (e.g., income deprivation and the need for family food support). The PPFI data was merged with open-source health data covering a variety of health outcomes (e.g., child obesity, Type 2 Diabetes, stroke, and heart attack) using geographic lookup tables (as the datasets were at different geographic levels - for example, LSOA vs Ward). 

The research's main outputs are a Power BI dashboard and a publication. 

## Power BI Dashboard

The dashboard, which is intended for public health policymakers, simultaneously visualises food insecurity risk (PPFI) data and health outcomes data using HTML text boxes, bar charts, radar charts, Shape maps, cards, and other visuals. The dashboard is also equipped with slicers and buttons to allow users to filter reports to specific Oxfordshire areas/districts and navigate between the pages.

The dashboard is formed of the following nine pages:

→ Three Information Pages: describe the physical (adult and child) and mental health data, Priority Places for Food Index (food insecurity risk) data, and demographics data used to create the visualisations. The pages also use clickable images with links to the data sources. 
- Health Data Information Page
- Food Insecurity Information Page
- Demographics Summary Information Page

→ Three Tutorial Pages: guide the user to navigate the physical and mental health reports as well as the demographic summary page by using the buttons and slicers to navigate between pages, reset map selections, or filter the reports for specific Oxfordshire districts/areas. Each of the dashboard’s three main pages (covering physical health, mental health, and demographic characteristics) has its dedicated tutorial page.
- Physical Health Report Tutorial
- Mental Health Report Tutorial
- Demographics Summary Report Tutorial

→ Three Main Pages: present visualisations that investigate the spatial association between the different food insecurity risk factors (the Priority Places for Food Index dimensions) and the considered health outcomes (adult/child physical health outcomes as well as mental health). The last page provides a demographics summary of the selected area(s) or district(s). 
- Physical Health Report
- Mental Health Report
- Demographics Summary

## Publication

The publication presents and analyses the outputs of Geographically Weighted Regression (GWR) models investigating the statistical significance of the spatial association between food insecurity risk and health outcomes in Oxfordshire. 

A GWR model is a statistical and spatial analysis technique that computes local-specific (LSOA in this case) regression coefficients estimating the relationship between the dependent variable (the prevalence of a health outcome) and the independent variable(s). 

Two models were fitted for each health outcome. The first model used the PPFI combined decile (i.e., overall food insecurity risk) as the sole predictor while the second model use the seven PPFI dimensions as the set of independent variables. 

In order to compute the LSOA-specific estimates, the GWR uses a critical parameter called the bandwidth parameter; which defines the number of geographic neighbours taken into consideration when fitting the regression model at each location. 

In order to ensure reliable inferences and maximise research impact, the analysis identifies areas where tackling specific food insecurity risk factors (e.g., fuel poverty and income deprivation) was estimated to reduce the prevalence of more than one health outcome. For instance, we focused on areas where making energy more accessible, affordable, and efficient could reduce the prevalence of child obesity (at year six) as well as the prevalence of Type 2 Diabetes. In other words, this could mean that fuel poverty in these areas is driving child obesity prevalence rates over the short-term, which is in turn contributing towards an increase in the prevalence of Type 2 Diabetes in the long-run. 
