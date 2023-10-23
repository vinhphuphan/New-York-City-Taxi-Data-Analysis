<h1 align="center">New York City Taxi Data Analysis using Python <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="55" height="40" style="display: inline-block;"> </h1>

### Introduction
New York City Taxi Data Analysis is aimed to explore, clean, analyze, and visualize the dataset related to 🚕 **Taxi Trip Records in New York City** to derive meaningful insights and provide actionable recommendations.

**Dataset** : Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pickup and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. The data used in the attached datasets were collected and provided to the NYC Taxi and Limousine Commission (TLC) by technology providers authorized under the Taxicab & Livery Passenger Enhancement Programs (TPEP/LPEP).

### Meaningful Insights

#### Exam the correlation

<p align="center"><img style="align: center;" src="https://raw.githubusercontent.com/vinhphuphan/New-York-City-Taxi-Data-Analysis/main/Visualisation/correlation_matrix.png" width=600></p>

**The graph indicates that :**

- There are significantly positive relationships between `Trip_distance`, `total_amount`, and `fare_amount`. This observation indicates that as the distance of the trip (`Trip_distance`) increases, the total fare (`total_amount`) and fare amount (`fare_amount`) tend to increase as well. This is a logical relationship, as longer trips typically result in higher fares.

- Additionally, `total_amount`, `tip_amount`, and `tolls_amount` are positively related. This finding makes sense since the `total_amount` includes both the fare amount (`fare_amount`) and additional charges such as tolls and tips. Therefore, when any of these components increase, the total amount charged to passengers (`total_amount`) also increases.

#### Top 10 Pickup and Dropoff Zones

<p align="center"><img style="align: center;" src="https://raw.githubusercontent.com/vinhphuphan/New-York-City-Taxi-Data-Analysis/main/Visualisation/Top_10_pickup_dropoff_zone.png" width=100%></p>

- The top pickup zone in New York City is JFK Airport with **147,508 trips** followed by Upper East Side South and Upper East Side North.
- The top dropoff zone in New York City is Upper East Side North with **141,274** trips, closely followed by Upper East Side South and Midtown Center.

#### Rank the vendors by popularity

<p align="center"><img style="align: center;" src="https://raw.githubusercontent.com/vinhphuphan/New-York-City-Taxi-Data-Analysis/main/Visualisation/vendor_popularity.png" width=600></p>

`VendorID 2` has a significantly higher trip count compared to `VendorID 1`, indicating its higher popularity or usage in the dataset.

#### What are the peak travel hours?

<p align="center"><img style="align: center;" src="https://raw.githubusercontent.com/vinhphuphan/New-York-City-Taxi-Data-Analysis/main/Visualisation/pickup_dropoff_by_hour.png" width=100%></p>

The graphs show that the peak travel hours are generally between **15:00 PM** and **19:00 PM**, which corresponds to the late afternoon and early evening when people are likely traveling to and from work or other activities. On the other hand, the early morning hours from **3:00 AM** to **5:00 AM** have the fewest number of trips, likely due to fewer people traveling during those hours.

This information can be valuable for understanding the trends and demand for taxi services during different times of the day.

#### Differences between weekdays and weekends

<p align="center"><img style="align: center;" src="https://raw.githubusercontent.com/vinhphuphan/New-York-City-Taxi-Data-Analysis/main/Visualisation/average_passenger_count.png" width=600></p>

<p align="center"><img style="align: center;" src="https://raw.githubusercontent.com/vinhphuphan/New-York-City-Taxi-Data-Analysis/main/Visualisation/average_trip_distance.png" width=600></p>

- The average trip distance on weekends is **3.4548 miles** which is slightly longer than on weekdays , **3.31285 miles**, indicating a modest increase in trip distance during weekends.
- The average number of passengers in a trip is slightly higher on weekends (**1.4647**) compared to weekdays (**1.3452**).

### Summary 
- The dataset contains 🚕**New York City yellow taxi trip data** from different months, revealing insights into travel patterns.
- There's a **variation** in the average distance, trip duration, and fare amount across the months, potentially reflecting seasonal changes.
- The passenger count is generally **low**, with the majority of trips having **only one passenger**.
- Pickup and dropoff patterns indicate popular zones, with **JFK Airport** being a top pickup location with **147,508** trips and **Upper East Side North** being top dropoff zone with **141,274** trips.
- Weekday and weekend trips exhibit slight differences in terms of **average trip distance** and **passenger count**.
- **Vendor 2** is more popular based on trip count, while **Vendor 1** shows higher average fare amounts.
- There is a **moderate positive correlation** between fare amount and tip amount which suggests that passengers are more likely to tip more when the fare amount is higher.
- There is only a **very weak positive relationship** between the fare amount and the number of passengers.

#### Possible Next Steps

- Further analysis could involve **outlier detection and handling** to improve data quality.
- **Geospatial analysis** could provide insights into **trip patterns** and the impact of locations on fares.
- **Predictive modeling** to forecast fares, trip duration, or passenger count based on different factors could be valuable.
- **Incorporating external data sources** (e.g., weather data, special events) for more comprehensive analysis.
- Conducting more detailed **time-series analysis** to identify trends over time.
- Analyzing **pricing structures** and **fare changes** across different trip types and vendors.

## Related Projects:question: 👨‍💻 🛰️

**Data Analysis**

<code>[Olympic-Weightlifting-Data-Analysis Using R](https://github.com/vinhphuphan/Olympic-Weightlifting-Data-Analysis)</code> 📊

<code>[Australia Road Deaths Statistic Report Using Excel](https://github.com/vinhphuphan/Australia-Road-Deaths-Statistic)</code> 📊

<code>[Titanic - Machine Learning from Disaster using Python](https://github.com/vinhphuphan/Titanic-Machine-Learning-from-Disaster)</code> 📊

<code>[Australian Politicians Twitter Data Analysis Using Python](https://github.com/vinhphuphan/Tweets-Analysis)</code> 📊

**Data Science Applications**

<code>[Text Classification With Movie Reviews](https://github.com/vinhphuphan/Text-Classification-With-Movie-Reviews/)</code> 📊

<code>[Living Species Image Classification using Python](https://github.com/vinhphuphan/Living-Species-Image-Classification)</code> 📊

<code>[Name Entity Recognition](https://github.com/vinhphuphan/Name-Entity-Recognition)</code> 📊

**Website Front End Practice**

<code>[Hospital-Landing-Page](https://github.com/vinhphuphan/Hospital-Landing-Page/)</code> 📊

<code>[LaslesVPN Landing Page](https://github.com/vinhphuphan/Lasles-VPN-Landing-Page)</code> 📊

<code>[Frontend Mentor Challenge Submission Using HTML&CSS](https://github.com/vinhphuphan/Frontendmentor-Challenge-HTML-CSS)</code> 📊

**Have fun building!** 🚀
