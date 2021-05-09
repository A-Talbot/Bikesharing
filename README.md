# CitiBike Bikesharing Analysis

***Prepared for Kate - 2021APR04***

## Overview

Des Moines is the next location for CitiBike Bikesharing services, and prior to the launch an analysis of the publicyl available bikeshare data msut be completed to ensure bike stations are placed appropriately, maintenance is performed at a conveneient time, and there are enough bikes.

Provided was Bikesharing data from CitiBike spanning across the month of August in 2019.

An analysis of the CitiBike Bikesharing data was completed using Tableau. Prior to this, the raw data was reviewed and the duration of any bike checkouts was converted to a proper ***datetime*** format (see image below):
![dataframe](Resources/Dataframe.png)

Additionally, the **GENDERS** column data was formatted into a string as shown below:

![Genders Calculation](Resources/Genders Calculation.png)

## Results

![CheckoutTimes](Resources/CheckoutTimes.png)
![WeekdayHourly](Resources/WeekdayHourly.png)
![GenderWeekday](Resources/GenderWeekday.png)
![UsertypeGenderWeekday](Resources/UsertypeGenderWeekday.png)

## Summary

### Conclusion

In conclusion:
* Most riders were male
* The majority of rides lasted less than one hour
* Weekday peak times were from 7:00 am to ***9:00 am and 4:00 pm to 6:00 pm*** and weekend peak times were from around ***9:00 am to 5:00 pm***

### Additional Visualizations

Additional visualizations that can be used to help understand the data includes the following:
* Map of most common START locatons
* Map of most common STOP locations
Having the above visualizations would help determine where to place CitiBike Stations (see images below where BLUE are START locations and ORANGE are STOP locations)
![START](Resources/START.png)
![STOP](Resources/STOP.png)
