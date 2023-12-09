### **Data Documentation**

**Original Data Sources**

The original datasets came from the United States Environmental Protection Agency (EPA): 
https://www.epa.gov/outdoor-air-quality-data/air-quality-index-report

Here are the 9 csv files that we started off with from the EAP: 

* California, 2020, by county
* Oregon, 2020, by county
* Washington, 2020, by county
* California, 2021, by county
* Oregon, 2021, by county
* Washington, 2021, by county
* California, 2022, by county
* Oregon, 2022, by county
* Washington, 2022, by county

**Variables**

The following variables were used in our final dataset: 
_year, state, good, moderate, unhealthy for sensitive groups, unhealthy, very unhealthy, hazardous_

These variables represent the air quality level according to the _Air Quality Index_ from the EPA

**Basic Summary Statistics: Final Datasets**

Number of Rows: 18 

* organized by number of days of each air quality level in specific state of a given year

Number of Columns: 3

* merged into long-form 
* variables: _state, AQI, # of Days_

There are no missing/invalid values in any column.
