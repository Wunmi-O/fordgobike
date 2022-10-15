# (Ford GoBike Data Exploration)
## by (Adewunmi Olowu)


## Dataset

This data includes information about 183,412 individual rides made in a bike-sharing system covering the 
greater San Francisco Bay area. The dataset can be found [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv).


## Summary of Findings

In the exploration, I surprisingly found out that customers spent more time than subscribers on rides. 
It would normally be expected that subscribers would have some sort of incentive over customers to encourage 
them to spend more time on rides. The multivariate exploration showed that there are interactions between 
start_periodofday and member_gender, start_dayofweek and member_gender, start_periodofday and start_dayofweek 
that have an effect on the duration of rides. We see more females than males use more time on rides typically 
during the weekends. Late Nights(followed by afternoon) had the most duration.

On Frequency of rides, male subscribers that do not use bike share for all trip on Thursday evenings contributed 
largely to the number of bike share rides recorded during the period

## Key Insights for Presentation

For the presentation, I focus on just the influence of the important categorical variables to the analysis: 
start_periodofday, member_gender, start_dayofweek to the analysis. I start by introducing the duration_sec variable, 
followed by the pattern in its distribution, then plot the transformed boxplot viz a viz each categorical variable 
to show clear relationships.

