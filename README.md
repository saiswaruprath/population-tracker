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

Final data sheet will look like this:




### Use Tableau to visualize and publish the dashboard on Tableau Cloud:

After removing unwanted columns in the file and ensuring all relevant fields are present we then open tableau and upload the csv file. For mapping of census tract data properly, we use https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html page to download the proper spatial file based on the state that we have selected.

![](https://github.com/saiswaruprath/population-tracker/blob/main/images/Screenshot%202023-05-31%20at%2011.35.27%20AM.png)

And then select state as Hawaii and download:

![](https://github.com/saiswaruprath/population-tracker/blob/main/images/Screenshot%202023-05-31%20at%2011.36.20%20AM.png)

In tableau select text file and upload the data:

![](https://github.com/saiswaruprath/population-tracker/blob/main/images/tableau1.png)

Once uploaded, the data source will look like this in the tableau:

![](https://github.com/saiswaruprath/population-tracker/blob/main/images/teableau2.png)

Next we can upload the required spatial file for mapping the respective data based on various counties of hawaii by clicking on Add connection:

![](https://github.com/saiswaruprath/population-tracker/blob/main/images/teableau3.png)

Next we can map the hawaii data.csv to the spatial file and then provide the necessary union condition. Here we use th FIPS mapping with Geoid for effective data mapping and presentation:

![](https://github.com/saiswaruprath/population-tracker/blob/main/images/tableau4.png)

Once done, we can move to sheet1 and click on geometry to get the desired mapping as needed. Later on we can use qualifying name(to match the census tract for the county) and the population % for age 25 years or older:Bachelors degree or better and other such properties for effective mapping and displaying the results based on various counties across Hawaii which shows how the population is progressing with literacy in all counties:

![](https://github.com/saiswaruprath/population-tracker/blob/main/images/teableau5.png)

![](https://github.com/saiswaruprath/population-tracker/blob/main/images/tableau6.png)



![hawaii](https://github.com/saiswaruprath/population-tracker/blob/main/images/Screenshot%202023-05-30%20at%2011.04.59%20AM.png)


![hawaii2](https://github.com/saiswaruprath/population-tracker/blob/main/images/Screenshot%202023-05-30%20at%2011.05.17%20AM.png)
