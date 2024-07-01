# Developing an Automated System for Extracting Cryptocurrency Data from Web APIs Using Python 

#### Problem Statement:
The cryptocurrency market is highly volatile and rapidly evolving, posing significant challenges for investors and analysts in tracking and analyzing trends accurately. Manual data collection and analysis are time-consuming and susceptible to errors, impeding informed decision-making in this dynamic industry.

#### Data Acquisition:
API Link: [CoinMarketCap API](https://coinmarketcap.com/api/)

In this phase, we connect with the CoinMarketCap API and configure essential parameters such as the start point, limit, and currency conversion. Utilizing the Requests library, the code sends HTTP GET requests to the API endpoint, retrieving the latest cryptocurrency listings. This automated process ensures a consistent and reliable data source for analysis.

#### Data Preparation (Cleaning and Preprocessing):
After data acquisition, the code prepares the data for analysis by performing various cleaning and preprocessing tasks. This includes:
- Removing missing or incomplete values
- Handling outliers
- Addressing any inconsistencies or errors
Using the Pandas library, the code applies data manipulation techniques such as converting data into appropriate data types, creating new features, and implementing necessary complex transformations. Additionally, a timestamp column is added to track when the data was pulled, enhancing traceability and ensuring data accuracy.


#### Data Analytics:
With the preprocessed data ready, the code conducts basic analytics to uncover insights into cryptocurrency trends. The code offers a snapshot of cryptocurrency price fluctuations over time by grouping the data by cryptocurrency names and calculating the mean percentage change values over various time intervals (e.g., 1-hour, 24-hour, and 7-day). This analysis helps to identify patterns and trends in the market.

#### Data Visualization
The code employs visualization techniques to facilitate understanding and interpretation using the Seaborn and Matplotlib libraries. Through line plots and categorical plots (catplots), the code visually represents trends in cryptocurrency prices and percentage changes over various time intervals. These visualizations help identify patterns and anomalies, enhancing the communication of findings to stakeholders and fostering informed decision-making.

#### Conclusion
This project provides a comprehensive solution to the challenges of analyzing cryptocurrency market trends by automating data acquisition, executing rigorous data preparation, conducting insightful analytics, and presenting compelling visualizations. As a result, stakeholders can efficiently gain actionable insights and make informed, data-driven decisions in the fast-paced and volatile cryptocurrency landscape.
