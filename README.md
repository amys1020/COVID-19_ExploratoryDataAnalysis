# COVID-19_Florida
**BACKGROUND**\
COVID-19 is a highly contagious, respiratory illness caused by severe acute respiratory syndrome coronavirus 2 (SARS-Cov-2). The coronavirus was first identified in Wuhan, China in December 2019. On March 11, the World Health Organization (WHO) declared COVID-19 a global pandemic. The main transmission route of the virus is through person-to-person contact. Infected individuals have reported experiencing a wide range of symptoms ranging from mild to severe illness. To prevent the spread of the virus, public health guidance includes washing hands often, wearing a mask in public, avoiding close contact, cleaning and disinfecting potential contaminated surfaces, and monitoring your health daily. 
As of December 4, the United States has the highest number of reported total cases (14.6 million) and total deaths (over 284 thousand) followed by India and Brazil. More specifically, Texas, California, and Florida have each surpassed one million total cases.

**FLORIDA TIMELINE**\
•March 1- Governor DeSantis declares a public health emergency\
•March 17- DeSantis orders all bars and nightclubs state-wide to shut down for 30-days\
•March 30- DeSantis issues a stay-at-home order for South Florida counties\
•April 1- DeSantis issues a stay-at-home order for the entire state of Florida\
•May 4- “Phase 1” reopening begins with updates on May 11, 14, and 15\
•June 5- “Phase 2” reopening begins, except Miami-Dade, Broward, and Palm Beach counties\
•September 25- “Phase 3” reopening begins for all Florida counties\
•December 1- Florida surpasses 1 million reported COVID-19 cases since the start of the pandemic\

**METHODOLOGY**\
When working with datasets containing hundreds of thousands of records, it is no longer practical to utilize Excel for data analyses. Python serves as a popular language amongst data scientists because it comes with many powerful libraries for data processing and modeling (Pandas, NumPy, SciPy) and data visualization (Matplotlib and Seaborn), just to name a few.\ For this project, all Python code was run in Jupyter Notebook and the imported Python libraries were Pandas and Matplotlib). 

**DATA SET**\
Each day the Florida Department of Health publishes an updated comma-separated values (CSV) file containing records of all the COVID-19 cases. The data is available to the public for download on https://open-fdoh.hub.arcgis.com/datasets/florida-covid19-case-line-data
The main attributes of the data set are County, Age, Age_group, Gender, Jurisdiction, Travel_related, Origin, Hospitalized (status), Died (status), and Case1 (date).

**OBJECTIVES**\
•To leverage Python’s libraries for data analysis purposes\
•To clean and format the data for visualization and analysis. This includes but is not limited to checking for null values, converting appropriate variables to DateTime format, replacing NaN values with ‘Unknown’, etc.\
•To provide graphical representations of the data in the form of bar charts, histograms, pie charts, and line graphs\
•To write functions with parameters that allow the user to be able to see specific metrics\
•To identify significant trends/relationships between variables and provide actionable recommendations for combating future pandemics
