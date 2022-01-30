# bikesharing

## Overview 

### This project will use data from the Citi Bike program in New York City to see how bike sharing product works.

First it is important to who are the type of people would rent bikes to go around NYC, then we will need to see in a week, which days and times are they going out. 

In order to get the data right, first I converted the duration data type via Pandas, then I imported the updated csv file into Tableau to visualize the data.  

## Results 

[link to dashboard] (https://public.tableau.com/app/profile/yumi.kimura/viz/Citybikes5-Whoarethosebikers/WhoarethoseNYCbikers)

As you can see from the "Chekout Times by Gender", if we filter trips by within 1 hour, 1-2 hours, more than 2 hours, most trips are longer than 2 hours, and least trips are less than 1 hour.  Then we separate this by gender, and we can see gender 1 are the largest driver for the length of the trips, then the trips for gender 2 is much less than gender 1. For gender 0, perhaps the total number of this gender is much smaller, it does not impact the total outcome that much.   Then we take a look at "Trips by Weekday per Hour"table, surprisingly Thursday at 8m has the biggest amount of people stop trips. If we check out the "User Trips by gender by weekday" table we can further determine those users are regular users as they are subscribers, and they all from gender 1. This is probably because those people ride the bike for bodybuilding purposes.  We can also tell most customer bike on Saturday and Sunday from 10am to 8pm. It seems like those are more likely to be the visitors. 

## 

[link to dashboard] (https://public.tableau.com/app/profile/yumi.kimura/viz/Citybikes6-BirthYearGenderVSduration/BirthYearGenderVSduration)

As we can see from the chart, it looks like the year of 1970, 1975, and 1989 have the longest trip duration, and 1970 and 1975 are both from gender 0. Gender 0 are likely to be in the customer group instead of Subscriber group. 


Then we take a look at where those people trip to, [link to dashboard] (https://public.tableau.com/app/profile/yumi.kimura/viz/Citybikes7-tripareasbygender/TripAreasbygender) it looks like the gender 0 people are visiting touristy places in the NYC. They are likely to be visitors. 


We can do more analysis into the subscribers to see their age groups, and gender. 