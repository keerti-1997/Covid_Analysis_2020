# Covid_Analysis_2020
## An attempt to visualize Covid data of the US from April 2020 to June 2020.

This project is submitted to the SparkAISummit 2020. Currently, US is the country with the highest number of coronavirus cases in the whole world. This notebook visualises the trends and patterns of the COVID-19 disease in the United States from 12th April 2020 to 9th June 2020. We use the Facebook's prophet module to forecast number of confirmed cases in different regions of the country.

### Dataset 
John Hopkins Dataset - https://github.com/CSSEGISandData/COVID-19

### Features
Province_State - The name of the State within the USA.<br/>
Country_Region - The name of the Country (US).<br/>
Last_Update - The most recent date the file was pushed.<br/>
Lat - Latitude.<br/>
Long_ - Longitude.<br/>
Confirmed - Aggregated confirmed case count for the state.<br/>
Deaths - Aggregated Death case count for the state.<br/>
Recovered - Aggregated Recovered case count for the state.<br/>
Active - Aggregated confirmed cases that have not been resolved (Active = Confirmed - Recovered - Deaths).<br/>
FIPS - Federal Information Processing Standards code that uniquely identifies counties within the USA.<br/>
Incident_Rate - confirmed cases per 100,000 persons.<br/>
People_Tested - Total number of people who have been tested.<br/>
People_Hospitalized - Total number of people hospitalized.<br/>
Mortality_Rate - Number recorded deaths * 100/ Number confirmed cases.<br/>
UID - Unique Identifier for each row entry.<br/>
ISO3 - Officialy assigned country code identifiers.<br/>
Testing_Rate - Total number of people tested per 100,000 persons.<br/>
Hospitalization_Rate - Total number of people hospitalized * 100/ Number of confirmed cases.<br/>


### Installation
 
```
pip install fbprophet==0.6
pip install plotly==4.4.1
pip install pandas==1.0.4
pip install numpy==1.18.5
pip install matplotlib==3.2.1
pip install -U scikit-learn
```


### Run the IPython Notebook cells 

