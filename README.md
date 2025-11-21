# Group-2-Project-2

# Hate Crimes in New York by County and Bias
Hate Crime and Bias Dataset Link: https://catalog.data.gov/dataset/hate-crimes-by-county-and-bias-type-beginning-2010
Population Dataset Link: https://1drv.ms/x/c/7ba90ea3105cae52/EXf_nuqbDOxFsstgviZ4P1IBm4whTDxF4D9MaslUPIJfgA?e=cgBNs5
# Data Set Overview:
## Hate Crime and Bias Dataset:
- Our data set includes hate crime records for every county in New York State, annually, from 2010 through 2022
- It has 823 Rows and 44 Columns
- Data types include String (county and crime type), Int (crime counts),
- The columns include crime type (Crimes Against Persons vs. Property Crimes) and hate-crime bias type 
- The rows group the crime and bias types by year and county 
## Population Dataset:
- To help with deeper analysis, we also added in this population data set
- This data set includes population estimates for every New York county, annually, from 2010 through 2022 and averages them to get one average population over the 12 years 
- It has 16 columns and 62 rows
- Data types include String (county), Int (yearly populations), Decimal (population average)
- We created this data set by compiling data from different excel sheets on the US Census Bureau website
# Limitations in our Dataset:
1. Our original data set did not include any population data, so the first visualizations we made were essentially just population heatmaps and were not very helpful in     comparisons among counties. 
2. The data set also contained 40+ columns, some of which were not helpful for answering descriptive and prescriptive questions. For example, some rows said crime occurred in  “Multiple Counties”, but did not specify specific counties. The amount of information made the data hard to navigate at first. 
3. The original data set did not have any information on Yates county, so this county appears as grey on our visualizations.
# Modifications to our Dataset: 
To address the above limitations, we modified the data by: 
1. We created and added in the population data set. This helped with adjusting the hate-crime counts for population size and allowed us to identify which counties have a higher relative risk rather than just higher totals
2. We divided the columns of the data set into different categories:Race, Religion, Sex, and Gender. We also removed “Multiple Counties” rows. This helped us to organize the data and made it better suited to use for answering our questions.
   



