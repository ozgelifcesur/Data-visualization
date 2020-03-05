Is the traffic in Istanbul really lower in religious holidays?

I tried to answer above question using new dataset released by Municipality of Istanbul (IBB). 
I created figures denoting the traffic index by months in 2019. To see the general trend, I included a continious line graph.
To visualize changes by days, I used a heatmap for days and months, which clearly shows that traffic is lower in holidays. 
I also did a basic ttest with null hypothesis that mean traffic index is different between religious holidays and normal days. 

You can reach the dataset from (also as Traffic_index.csv file in the repository):
https://data.ibb.gov.tr/en/dataset/trafik-indeks-raporu

About the Traffic index dataset:
The dataset provides the Traffic index (%) used in IBB traffic app.It has two columns index and time (including date and hour).
Though they did not include information about the calculation of the index, from the app we can deduce that it is calculated similar to the traffic index of Google Maps and it shows traffic as percentage.
In the data set min is 1% and max 81% both reasonable by being positive integers less than 100%.

The Dataset covers 5 minutes intervals between 1st of January 2019 00:00 to 4th of February 2020 11:05 am.
Since only less than 2 months in 2020 exists in the data, I will use only data for 2019 in analysis.  

Though it could be more informative to do the analysis in at least main roads level, the dataset only provides general Traffic index for Istanbul at a given time. 

Conclusion:

I tried to test the general belief that residents of Istanbul leave Istanbul in religious holidays hence leading a lower traffic in holidays but higher traffic in the days just before or after the holidays. 
I conclude that the traffic in Istanbul significantly less in religious holidays, however we can not conclude about people leaving Istanbul since we do not have higher traffic in the days before holidays.
Lastly, I acknowledge that only having 1 year data which is not even on main roads level is leaving us with a primitive analysis but we can at least see the lower traffic rates in general in holidays.


Further analysis to be done:

-Testing how much the traffic changes in 5 to 15 minutes intervals in typically rush hours in morning and evening. Is there a significant worsening of the traffic in such short intervals?
 
-Testing whether winter or summer breaks for schools lead less traffic.
