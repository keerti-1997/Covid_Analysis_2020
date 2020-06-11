# Covid_Analysis_2020
## An attempt to visualize Covid data of the US from April 2020 to June 2020.
This work is submitted to the Spark+AI Summit 2020. 
Currently, US is the country with the highest number of coronavirus cases in the whole world. This notebook visualises the trends and patterns of the COVID-19 disease in the United States from 12th April 2020 to 9th June 2020. We use the Facebook's prophet module to forecast number of confirmed cases in different regions of the country.

### Dataset 
John Hopkins Dataset - https://github.com/CSSEGISandData/COVID-19

### Features
Province_State - The name of the State within the USA.
Country_Region - The name of the Country (US).
Last_Update - The most recent date the file was pushed.
Lat - Latitude.
Long_ - Longitude.
Confirmed - Aggregated confirmed case count for the state.
Deaths - Aggregated Death case count for the state.
Recovered - Aggregated Recovered case count for the state.
Active - Aggregated confirmed cases that have not been resolved (Active = Confirmed - Recovered - Deaths).
FIPS - Federal Information Processing Standards code that uniquely identifies counties within the USA.
Incident_Rate - confirmed cases per 100,000 persons.
People_Tested - Total number of people who have been tested.
People_Hospitalized - Total number of people hospitalized.
Mortality_Rate - Number recorded deaths * 100/ Number confirmed cases.
UID - Unique Identifier for each row entry.
ISO3 - Officialy assigned country code identifiers.
Testing_Rate - Total number of people tested per 100,000 persons.
Hospitalization_Rate - Total number of people hospitalized * 100/ Number of confirmed cases

### Run the IPython Notebook cells 
