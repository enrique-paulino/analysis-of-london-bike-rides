# London Bike Rides - Insights

## Overview
In this project, I undertook the creation of an interactive and informative dashboard using Tableau, focusing on London bike ride data. The key features of this dashboard provides a user-friendly and dynamic platform for exploring temporal trends, weather impacts, and hourly patterns within the realm of London bike rides, allowing users to gain valuable insights into the factors influencing ridership and enhancing their understanding of the broader biking ecosystem in the city.

## Data Source
**[London Bike Sharing Dataset](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset)** by TFL Open Data, available on Kaggle. This comprehensive dataset provided a wealth of information related to bike-sharing activities in London; with details ranging from temperature, wind, humidity, weather season, and more.

### Column Reference Table
Below is a breakdown of the different variables in the dataset, each entry reveals the name and a brief description of the corresponding data, providing insights into the content encapsulated within the dataset.

| Column Name  | Description                                                       |
|--------------|-------------------------------------------------------------------|
| timestamp    | the date and time for specific data                               |
| cnt          | the number of unique bike rides                                   |
| t1           | the actual temperature, in celsius                                |
| t2           | how the temperature feels, in celsius                             |
| hum          | the humidity, as a percentage                                     |
| wind_speed   | the wind speed, in km/h                                           |
| weather_code | a code representing different weather conditions                  |
| is_holiday   | a boolean value representing whether the date is during a holiday |
| is_weekend   | a boolean value representing whether it is the weekend            |
| season       | a code representing different seasons                             |

## Dashboard
### Tableau Visualisation
Explore the visual representation of the dashboard in the image below, providing a glimpse into its interface and features. For an interactive experience, you can access the live dashboard **[by clicking here.](https://public.tableau.com/app/profile/enrique.paulino/viz/LondonBikeRides-Insights/Dashboard)**

![Dashboard](https://github.com/enrique-paulino/analysis-of-london-bike-rides/assets/77032207/dbf6059c-3c7b-4bee-8153-2f662b29248c)

### Features Overview
**1. Customisable Moving Average**
   - Implemented a dynamic moving average feature that allows users to select, and highlight, a range of dates.
   - Filter options allowing the user to select the period (day, week, month), the duration of that period and a range selector that limits the data based on a starting and ending date.

**2. Heatmap for Temperature vs Wind Speed**
   - Developed a visually appealing heatmap that presents the correlation between temperature and wind speed.
   - Ensured the heatmap dynamically adjusts based on the selected parameters in the moving average, providing a comprehensive overview of weather patternds during bike rides.

**3. Informative Tooltips**
 - Enhanced user interaction by incorporating tooltips that display crucial information:
    - The date currently being hovered, aiding in precise data examination.
    - Average rides for the date currently being hovered.
    - Average rides for the date currently being hovered further categorised by the hour of that specific date (ranging from 0-23), and by weather conditions.
  
## Data Analysis Process
In this project, I performed various data analysis processes, spanning from the initial gathering of data from Kaggle to comprehensive exploration and manipulation using the pandas library in Python. This resulted in a impactful data visualisation achieved through Tableau, providing valuable insights into the London bike share dataset.

### Technologies Used
- **Kaggle** - Data Gathering
- **Python** - Data Manipulation
- **Tableau** - Data Visualisation
