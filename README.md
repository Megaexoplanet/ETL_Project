# ETL_Project

# Proposal
# To be able to search number of Co-Vid 19 cases in a geographical area related to income. This will enable your business to get an idea of future outbreaks based on income. Lower income has been associated with higher Co-Vid 19 instances. If your offices are located in an area that is a hotspot than you would be able to take preventative measures to reduce loss of capital and protect your work force. I am going to join Co-Vid 19 data with IRS tax data. This will be joined on zip code. This will result in having access to number of Co-Vid 19 cases in relation to income level.

2.1 Income data was downloaded from the IRS off of Kaggle in a CSV file at this website https://www.kaggle.com/irs/individual-income-tax-statistics. Co-Vid 19 data was downloaded from the New York Times off of Kaggle in a CSV file at this website https://www.kaggle.com/fireballbyedimyrnmom/us-counties-covid-19-dataset. The CSV file that listed state abbreviations was downloaded from world population review at this website https://worldpopulationreview.com/states/state-abbreviations/. There are no restrictions on the CSV files from Kaggle.
2.2 Data for geographical location of Co-Vid 19 cases was needed along with income information related to geographical location. Both sources of data are static. In order to update or obtain the data again it would have to be downloaded from the IRS and the New York Times again through Kaggle. Data downloaded from Kaggle for the New York Times has had the same columns and would work with the existing code. The data from the IRS was from 2014 and updates rarely. If they updated their data they may use different column names and would need to be coded again. 
2.3 The IRS data had to have several columns dropped because they were extraneous to our purpose and we needed to optimize the database. Other columns needed to be renamed in order to understandably label the data and call it in the database. The Co-Vid 19 data needed a couple columns dropped that were not useful for our purpose. Finally, we needed the Co-Vid 19 data to be capable of being related to the IRS data. I decided to merge a state abbreviation list to the Co-Vid 19 data.
2.4 The Co-Vid 19 data had fips numbers that were not standardly used with decimal points after them. Also, there were NAs and unknowns in several columns in the Co-Vid data on the county level. The Co-Vid 19 data is updated frequently while the IRS data has not been updated since 2014. It would be necessary to update the local data with the new Co-Vid data at least weekly in order to keep track of changing numbers of Co-Vid cases to states. Since the data has to be downloaded in a CSV file to load into PANDAS and then uploaded to pgAdmin then it would make sense to notify the team when it is updated. I wouldn’t think that it would be necessary to notify the team.
2.7 Data Loading and Availability This section addresses the data schema and during of data retention. Discuss the interface that will allow your Client/Users to access the data. The clients will be able to access the data through querying pgAdmin. 


# Data One link
https://www.kaggle.com/irs/individual-income-tax-statistics?select=15zpallagi.csv

# Data Two link
https://www.kaggle.com/sudalairajkumar/covid19-in-usa





