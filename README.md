# Final-Project--Utility-Solar-Impact-on-Home-Prices
README

**Utility Solar Development and the Implications on Nearby Home Value Growth Rates** 

**_Final Project for ENV 617 - Samantha Almonacid, Alberto Andrade, Esaac Mazengia, Elana Shi_**


**Project Summary:**
This repository contains a file titled Utility_Solar_and_Home_Prices, which contains code for an analysis exploring the relationship between the proximity of utility scale solar and property values at the neighborhood level. This analysis defines proximity to solar as neighborhoods that fall within within one mile of a solar PV, and those that fall outside the one mile radius as not in proximity. After identifying these neighborhoods, the analysis explores the changes in home price growth (a three-year Compound Annual Growth Rate (CAGR)) by subtracting the growth rate three years prior to solar implementation from the growth rate three years after implementation. Difference-to-Difference plots, which display the annual growth rate in neighborhood prices, and Box and Whisker plots are utilized to display the results of our analysis. 


**Files in Repository:**

Utility_Solar_and_Home_Prices.ipynb: Jupyter Notebook containing Python code for data analysis.
README.md: Markdown file providing an overview of the project, its goals, and the files in the repository.

**Data Citations:**

**United States Large-Scale Solar Photovoltaic Database (USPVDB):** 
This data describes the location and attibutes of large-scale solar panel developments in the United States.

Fujita, K.S., Ancona, Z.H., Kramer, L.A., Straka, M., Gautreau, T.E., Garrity, C.P., Robson, D., Diffendorfer, J.E., and Hoen, B., 2023, United States Large-Scale Solar Photovoltaic Database v1.0 (November, 2023): U.S. Geological Survey and Lawrence Berkeley National Laboratory data release, https://doi.org/10.5066/P9IA3TUS.

**Zillow Home Value Index (ZHVI)**
This data presents the typical values for homes within the 65th to 95th percentile range for a given region. The data is smoothed and seasonally adjusted, and does not account for inflation.

Zillow. (2023). Zillow Home Value Index (ZHVI). Zillow. Retrieved from https://files.zillowstatic.com/research/public_csvs/zhvi/Neighborhood_zhvi_uc_sfrcondo_tier_0.33_0.67_sm_sa_month.csv?t=1712011928.

**Neighborhood Boundaries**
This data contains boundaries for 17,000 Zillow neighborhoods in the United States.

Environmental Protection Agency. (2018). Zillow Neighborhoods. Retrieved from https://edg.epa.gov/data/PUBLIC/OEI/ZILLOW_NEIGHBORHOODS/Zillow_Neighborhoods.zip. 

**United States Boundaries**
This data contains boundaries for all states in the United States.

United States Census. (2018). Cartographic Boundary States 20m.  Retrieved from https://www2.census.gov/geo/tiger/GENZ2018/shp/cb_2018_us_state_20m.zip
