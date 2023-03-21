Instructions for creating a comparison between 2010 and 2020 stats by area based off:
https://www.nhgis.org/geographic-crosswalks

*Import the crosswalk to the geodatabase if it hasn't been already
*Add the desired 2010 fields to the crosswalk
*Join 2010 geography with data to the crosswalk table and calculate the fields using the weights and 2010 data
*Run summary statistics on the new table by geoid20
*Create fields in the 2020 geography file for the 2010 data
*Join the crosswalk to the 2020 geography and calculate the values in the 2020 geography file
