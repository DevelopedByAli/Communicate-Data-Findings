# Ford GoBike System Data Exploration

## by Akbarali Mukhammadiev

<p align="center">
  <a href="https://www.udacity.com/">
    <img src='https://course_report_production.s3.amazonaws.com/rich/rich_files/rich_files/5511/s300/udacity-logo.png' alt="Udacity logo" width = 100px>
   </a>
</p>
<h3 align="center"><a href='https://www.udacity.com/course/data-analyst-nanodegree--nd002'> Udacity Data Analyst Nanodegree </a></h3>
<h4 align="center">Project V: Communicate-Data-Findings</h4>

## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area, United States. The attributes included the trip start/end time, as well as additional measurements such as user type, gender, and age. 16K data points were removed from the analysis due to missing values in some fields, data inconsistent, or outliner issues.

## Summary of Findings

> In the first section, I worked with only univariate plots. Observing the data I have found very interesting facts and information. I will share these facts as follows:

> There are way more male users than female users and the most of the users are subscribers of the company. As it was expected, the contribution of the gender among the subscribers and non-subscribers are similar as above i.e. more men than women have been using the bikes for their travelling.

> I have also observed that the frequency of the male subscribers and also the non-subscribers are dominant as well with almost 3 times difference between the two groups. The most of the bike users correspond to the age range between 20 and 40. As it is expected that the most frequent hour of the day is 5:00 pm and the least frequent is after midnight. his is probably due to the fact that everyone returned home from their offices. Thursday is the day that the most rides took place.

> Also, it should be noted that people used bikes 24 hours in a day. People have been used bikes more during the weekdays compared to weekends. The most frequent day is Thursday with above 30000 uses. It must be noted that the given dataset contains only February as a month. Therfore, we can't check the distribution in each month. 

> Concerning the unusulal points there were ages even above 120 or 140 and I found this unusual and there con't be ages like this one. I think this kind of date should be removed and hence hence I took the ages under 80 to make my analysis more reasonable. Furthermore, I needed to use logarithmic transformation to have better ideas.

> In the second section, I investigated the relationships between pairs of variables. I started by observing the correlations between non-categorical variables given in the dataset. For this exercise, I used the advantege of scatterplots. I have first explored that if there was any correlartion between travel duration and ages of the users. Using the scatterplot and also the regplot that I found that there was almost no any correlation between the two.

> Next, using a box plot , I found that there didn't exist that much difference in terms of travel durations between men and women. Whereas, there existed difference in terms of travel durations between subscribers and non-subscribers. Non-subscribers had wider travel durations compared to subscribers of the company.

> Furthermore, using a viloin plot I found that similarly as in the case of travel durations compared with ages above, the most of the subscribers are youngesters whereas non-subscribers are slightly older than subscribers.

> Next, using a countplot I found that that no matter the users are male or female, the most of the them are subscribers of the of the company. In the parallel countplot, I observed that there was distribution of subscribers are way higer than the non-subscribers and they used them a lot on weekdays than weekends.

> In the third and final section, I dealt with plots os three or more variable. First, I observed that the average travel durations of the non-subscribers are almost the same with the subscribers. Moreover, I noticed that on weekends both group have more travel durations compared to weekdays. I guess this is due to the fact that they have to go to work during the weekdays and they have more time on weekends.

> Finally, I observed that we can see from the graph above that there exists correation between the ages of the users and the average travel duration. We can see rather slightly negative correlation after the age of 20 between the two. After the age of 20, younger people travelled more than the older people. Also, looking at the plot above, we see that that the longest travel durations correspond the age interval between 20 and 30. Travel duration starts decreasing after the age 20.


## Key Insights for Presentation

> The first key result would be the information concerning the travel starting hours and the days when the travels took place. The most frequent hour of the day is 5:00 pm and the least frequent is after midnight. This is probably due to the fact that everyone returned home from their offices. Thursday is the day that the most rides took place following by Tuesday, Wdnesday etc. The weekends are the less popular days among travellers.  

> The second key result might be that there doesn't exist that much difference in terms of travel durations between men and women. Whereas, there exists difference in terms of travel durations between subscribers and non-subscribers. Non-subscribers had wider travel durations compared to subscribers of the company. Furthermore, similarly as in the case of travel durations compared with ages, the most of the subscribers are youngesters whereas non-subscribers are slightly older than subscribers.

> The third and final key result would be the fact that concerning the correation between the ages of the users and the average travel duration. We can see rather slightly negative correlation after the age of 20 between the two. After the age of 20, younger people travelled more than the older people. Moreover, the longest travel durations correspond the age interval between 20 and 30. Travel duration starts decreasing after the age 20.
