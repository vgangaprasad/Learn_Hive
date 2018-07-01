# Learn_Hive

Please download the census_2010pop_estimatetill2017.csv file and open Hive and follow the instructions to create the table as follows:


hive> create table if not exists census2010(
place int comment 'City id',
name string comment 'City name',
stname string comment 'State name',
census2010pop int comment '2010 population',
census2011est int comment '2011 estimated population',
census2012est int comment '2012 estimated population',
census2013est int comment '2013 estimated population', 
census2014est int comment '2014 estimated population', 
census2015est int comment '2015 estimated population', 
census2016est int comment '2016 estimated population', 
census2017est int comment '2017 estimated population'),
comment 'census 2010 data with estimates for 2011 - 2017'; 

OK 
Time taken: 2.47 seconds 
