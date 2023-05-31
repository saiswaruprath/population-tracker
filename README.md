# POPULATION TRACKER

## INITIAL DEVELOPMENT

The initial target is to create a static webpage and add Tableau visualization dashboard for hawaii state taking various census tract data from social explorer for ACS 2021 5 year estimates data. After data was processed and the data for population 25 years or over with Bachelors degree or better was presented in the tableau sheet, the sheet was integrated with react app and presented for users to view and use it for further purposes.

The map with the data in tableau was presented by downloading the proper spatial file from census shapefiles and indicating for year and state with layer type as census tracts.

## STEPS FOLLOWED FOR CURRENT PROGRESS
### 1) Gather Data
Firstly we used Social explorer- https://www.socialexplorer.com/explore-tables that helps to efficiently take use census data and also enables us to clean out the data with its various tools and helpful links while downloading the correct data according to specific needs. For this scenario, we have taken the American Community Survey(ACS) 2017--2021(5 year estimates data) as shown below and lick on "Begin Report":

![]()

In the next page we select geographic type as Census Tract, select the state as Hawaii and select all census tracts in hawaii that will include data for all counties in Hawaii culminating till 2021. And then click on proceed to tables.

![]()

![]()

Once done, we next select the table type as Educational attainment for population 25 years or older(Collapsed version) as shown below and then click on show results:

![]()

### 2) Download Data
Once data is ready, we can then use various output options that Social Explorer provides and then download the CSV file:

![]()


### Use Tableau to visualize and publish the dashboard on Tableau Cloud:

After removing unwanted columns in the file and ensuring all relevant fields are present we then open tableau and upload the csv file. For mapping of census tract data properly, we use https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html page to download the proper spatial file based on the state that we have selected.

![](https://github.com/saiswaruprath/population-tracker/blob/main/images/Screenshot%202023-05-31%20at%2011.35.27%20AM.png)

And then select state as Hawaii and download:

![](https://github.com/saiswaruprath/population-tracker/blob/main/images/Screenshot%202023-05-31%20at%2011.36.20%20AM.png)



![hawaii](https://github.com/saiswaruprath/population-tracker/blob/main/images/Screenshot%202023-05-30%20at%2011.04.59%20AM.png)


![hawaii2](https://github.com/saiswaruprath/population-tracker/blob/main/images/Screenshot%202023-05-30%20at%2011.05.17%20AM.png)
