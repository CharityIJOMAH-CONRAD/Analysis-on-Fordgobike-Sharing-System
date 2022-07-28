# (Fordgobike Share Trip Analysis)
## by (Charity Ijomah-Conrad)


## Dataset

This data set includes information about individual rides made in Fordgobike-sharing system covering the greater San Francisco Bay area in the year 2019.
In this Fordgobike dataset, there are 183,412 entries with 16 columns made up of the following features (variables):

    i. Duration_sec,
    ii. Start_time,
    iii. End_time,
    iv. Start_station_id,
    v. Start_station_name,
    vi. Start_station_latitude,
    vii Start_station_longitude,
    viii End_station_id,
    viv End_station_name,
    x. End_station_latitude,
    xi End_station_longitude,
    xii Bike_id,
    xiii User_type,
    xiv Member_birth_year,
    xv Member_gender,
    xvi Bike_share_for_all_trip)


## Summary of Findings

In summary, my exploration on the Ford GoBike share trips which took place in the Bay Area of San Francisco within the period: February - March 2019, shows the following observations.

- The Duration time (seconds)** of the bike trips occurred mostly between 250 and 350 seconds (i.e 4 - 6 mins) amongst riders with a total count of 10,000 to 12,000.

- The user type known as Subcribers has the highest population of the bike riders at 90.5% with Customers sitting at the bottom at 9.5%. Hence, the bike share trips within the given period has more subcribers than Customers.

- Majority of the riders are of the Age bracket of 18 to 40 years.

- The Male gender has the highest population of the users at 74.6% followed by Females at 23.3% and Other counterparts at 2.1%.

- There are top favourite Start and End stations mostly used by the riders. My analysis covered for the top 11 Start and End stations. 


## Key Insights for Presentation

For the presentation, I focus on the influence and interactions among the my main features of focus i.e duration time (seconds), user Age, Gender and user Types in the bike share trips. I started by observing the distribution of the duration time (seconds) with a histogram plot followed by its interaction with Age and then gradually introduced the other categorical variables to it using scatter plots, cluster bar chart and pie chart for insight. But before my exploration, I carried out the following operations on the data.

To know the exact Age range of the riders of the SF Bike share trips, I created a variable called Age from Member Birth Year and also structured it into Age groups for further analysis. I also separated/extracted the start date from start time to ascertain the top 10 start date with the highest bike share trip count. I also dropped a minut portion of rows with missing values and also removed outliers from the Age variable because it went from a minimum of 18, to median of 31 and a whopping maximum of 141 years. a maximum age of 80 years was adopted in other not to lose so much data. I went further to plot a bar chart to  ascertain if there are popular start and end stations where riders used the most, doing this revealed that the top 11 'start' and 'end' stations had a correlation with each other as my bar chart for start stations exposed same station name at the end station.

I ensured to use some interactive and explicit visuals plottings like heatmap, bar chart, pie chart, cluster bar chart, and box plot to find solution to my insight. my heatmap showed that there was little to intangible level of correlation between the main features above and other variables in the data. The cluster bar chart helped more in establishing the correlation between the main variables of of interest.
