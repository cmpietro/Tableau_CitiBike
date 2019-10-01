# Tableau_CitiBike

File documenting work:  Homework-CitiBike.xlsx
File documenting cleaning work: CitiBike.ipynb
Link to Tableau data:  https://public.tableau.com/profile/carol8224#!/vizhome/CitiBikeAnalysis2018/CitiBike2018AView?publish=yes

The cleansed data files as well as the raw data used could not be pushed to repository due to size.  

Files Used: 

Daily data: 
201803-citibike-tripdata.csv
201806-citibike-tripdata.csv
201809-citibike-tripdata.csv
201812-citibike-tripdata.csv

Customer Level Data: 
FirstQuarterData.csv
SecondQuarterData.csv
ThirdQuarterData.csv
FourthQuarterData.csv

Process to report: 

1. The customer level data contained all of 2018 and was used for finding growth in subscribers over time.  
2. The daily data contained only one month snap shots across each of the seasons so that comparisons could be made. 
3. The daily data needed to be cleansed of erroneous data such as:  removal of all customers whose date of birth documented puts them over the age of 100.  Since it is possible people aged 100 could ride, they were left in, however the volume of them I believe is still false.  The daily data also needed to be cleansed of trips over four hours, since these are most likely the result of faulty returns or abandoned bikes or potential theft.  The model for renting a bike, keeps the cost effective rental at 30 minutes, therefore, the likelyhood of trips over four hours is extremely small. 
4. Once most of the data was cleaned of obvious erroneous data and evaluated for some simple stats, smaller sections of the data was created for import into tableau.  
5. All the reports focus on grouped areas of interest: Customer / ridership information, equipment / bike information, trip information, customer detail comparsions, and station mapping details. 



