# QGIS_COVID_Map

Data was scraped on 06/05/2023 from https://www.worldometers.info/coronavirus/weekly-trends/#weekly_table
The resulting file was modified to remove data not pertaining to the countries of interest.
Countries like USA and UK were renamed to their full names, e.g. United States of America and United Kingdom. This allowed for subsequent joining with the feature table of the world map in QGIS.

QGIS (v. 3.30) was used to create the choropleth map.

The displayed values are 'Deaths in the last 7 days'.
![World_COVID_Deaths_Week_of_06052023](https://github.com/alekseymor/QGIS_COVID_Map/assets/10982274/fe23d61d-b972-48ec-b5b8-9270eb01bbe3)
