# Covid-19 Positive Cases Death Cases and Vaccination Analysis
## Introduction
The goal of this analysis is to find out the trend of the virus over time and answer, which were the most affected countries by the number of positive cases, and the number of death cases and to gauge how effective the vaccination process was and if at all it played a part in slowing down the spread of the virus and number of death cases recorded across the globe.
## Data Overview
For this project, I got 2 data sets from Kaggle, one called COVID-19 activity, which contained the daily number of cases, new cases recorded each day, and the daily number of death cases by continent, country, county, and province. The second data set, COVID-19 vaccinations, contained the daily vaccinations done for each country across the globe. I first combined the 2 datasets to get an enriched dataset for analysis, and to reduce the volume of the data, I cumulated the daily records into monthly. This helped reduce the noise that came with the daily data records.
## Exploratory Data Analysis (EDA)
I first looked at the trend of new positive cases across the globe death cases that were recorded all across the world and the number of vaccinated people. From this analysis, I realized that even though the number of new positive cases dropped gradually with the introduction of vaccines, the number of death cases recorded gradually increased over the analysis period. 
The next step was to look at the correlation between the number of new positive cases, death cases, and total vaccinations. This showed that even though the number of positive cases did reduce with the introduction of vaccines, they had very little correlation. This led me to believe that the drop was caused by another variable, not vaccinations.
I then looked at the summary statistics of my data which showed an average of 11,632 new positive cases were recorded every month with about 42,770 covid related death cases being recorded on a month-on-month basis. A standard deviation of 44,385 on new positive cases and 92,741 death cases confirmed that no month was similar to the previous over my look-up period
## Visualizations 
![image](https://github.com/Kimuyu-Charles/Covid-19-Analysis/assets/146121590/78ac4e35-4e67-4f24-b869-38eace4e9763)
This shows that while the number of new positive cases was going down with time with the introduction of vaccines, the number of death cases generally went up. Therefore the new positive cases might not be going down because of the introduction of vaccines, but rather because of the high death cases reducing the pull from the population that can be affected.
![image](https://github.com/Kimuyu-Charles/Covid-19-Analysis/assets/146121590/1671d1ff-79f4-4ae8-bf07-c3955ea23a87)
The USA followed by Canada has the highest number of COVID-19 cases recorded over the analysis period with the rest of the countries in the world barely scratching the surface of infections over the period.
![image](https://github.com/Kimuyu-Charles/Covid-19-Analysis/assets/146121590/a37c0ff7-480a-434f-b90b-069a4fe29ff0)
The USA, Canada, and China had the highest total death cases in total over the period. The high correlation between the 2 shows that the chances of one dying after being infected were very high
## Conclusion
The Covid-19 pandemic took the world by surprise especially the USA, Canada, and China where it hit the hardest. This is evidenced by the large number of monthly increase in new positive cases and death cases particularly in those 3 countries. If traveling from these countries to other countries is not limited, the latter months could see a surge in the number of cases, both new positives and deaths recorded in other countries 
## Recommendations
As per the analysis, it is evident that traveling from the USA, Canada, and China to other countries should either be restricted or stopped altogether to prevent the virus from spreading. The countries' infected should also be placed in quarantine. The rest of the countries with a small number of infected people should also place the necessary infrastructure in place as we can see that the number of infections can rise very fast from the standard deviations recorded.
