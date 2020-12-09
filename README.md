# Gentrification-in-the-Central-Valley

## About 
This project works collaboratively with the Center for Regional Change on an Urban Displacement Project. Our purpose is to exmamine gentrification in the Central Valley specifically counties that are vulnerable to gentrification and displacements especially as more Bay area residents move into the county and either commute to work (outside of the county) or work remotely. This research forks an existing projects code (linked below) and modifies it to the regions of interest (areas of interest include San Francisco 2018 data/map, normalized San Joaquin County (county code 077)). 

## Contributors 
The collaborators include: 
Center for Regional Change (CRC)
Urban Displacement Project 
Hack for California- UC Davis 
  (INCLUDE OURSELVES)

## How To Access 

### Access to original code via GitHub
https://github.com/urban-displacement/displacement-typologies/tree/main/code

### Link to the original typology map (Provided by UDP)
This is a finished project we are trying to fork and adapt for San Joaquin County. 
https://www.urbandisplacement.org/

## Previous work and issues encountered (ISSUE THIS IN THE ISSUES CUE)
(Using Windows 10) Inside the anaconda navigator, go to environments > open terminal using a new environment called "typologies". Attempt to run python script using commands found in readme. Be sure to use "python" instead of "python3" in commands like "python3 1_data_download.py Atlanta". Doing so will prompt the terminal to ask you to download different modules, such as "Census" or "Geopandas". Upon trying to install "Geopandas", we ran into a GDAL issue.

The 2000 Census API Key is broken. UDP has been notified about this issue, and we are waiting for the Census to fix it. In the meantime, lines of code that use 2000 data must be commented out. Code requires the below registration. 

### Link to activate API key for Census Data 
https://api.census.gov/data/key_signup.html

## Data Collection and Update Process

External datasets were provided by the Center for Regional Change. The rest of the data is obtained from the American Community Survey (ACS) on the US Census Bureau site. This study uses 2014-2018 5-yr data summarized at the census tract level. Census tracts are areas whose boundaries typically remain consistent over time, with an average population of 4,000 people. Therefore, tracts in urban areas are smaller compared to those in rural areas.
o   For more info, check out Geography and the American Community Survey
https://www.census.gov/content/dam/Census/library/publications/2020/acs/acs_geography_handbook_2020.pdf


## Next Steps 
Modify CRC's code to look at Counties in the Central Valley (Sacramento County, San Joaquin County)
Touch Bases with CRC. 

## Have Questions?
Contact hack-for-california@ucdavis.edu

