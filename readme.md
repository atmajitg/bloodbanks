
## Motivation
The main motivation behind this simple shiny app is to make it easier to locate blood banks in India along with pincodes, addresses, contact person name and number.

## Data:
Data for the blood bank application is sourced from [Open Government Data Platform](https://data.gov.in/). The original data is available as a csv file called "Blood Bank Directory (updated Till Last Month)". The raw data file, processed data file and my shiny code is made available on my github.

I have tried my best to comment and explain where necessary.

## Data limitation
One of the limitations of this application is that the data is not accurate. If we plot the raw data we see a few bloood bank location in Africa. There are close to 82 NA values for latitude and longitude.

Hence when we create the shiny application we will ignore these points. I am in a process to update these points.

## Help:
In case you observe the data projected on map is incorrect and you have more accurate or additional information that could be updated it will be great if you can email me and i will update the same.
