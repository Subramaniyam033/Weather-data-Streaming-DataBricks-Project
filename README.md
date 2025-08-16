# Weather-data-Streaming-DataBricks-Project
End-to-end real-time weather monitoring system using Azure Databricks, Azure Event Hubs, and Delta Lake. Streams live weather data from a public API, processes it through Bronze–Silver–Gold layers, and visualizes live metrics &amp; forecasts in Power BI using PySpark &amp; Structured Streaming.

- Developed a real-time weather data pipeline by extracting live data from a public Weather API using Databricks and streaming it into Azure Event Hubs for ingestion.
- Implemented a multi-layer Delta architecture (Bronze–Silver–Gold) in Databricks, stored raw binary data in Bronze, applied schema in Silver, and performed JSON flattening transformations in Gold.
- Integrated Azure Databricks with Power BI to create an interactive dashboard displaying live temperature, humidity, air quality, and 3-day forecasts.
- Utilized PySpark, Structured Streaming, Azure Event Hubs, Delta Lake, and Power BI to build an end-to-end real-time data analytics solution

### Project - Architecture 
![Architecture](https://github.com/Subramaniyam033/Weather-data-Streaming-DataBricks-Project/blob/e9de39b4978425c4b6533a0b9a74d3c25907251b/weather%20Streaming%20project%20pic.png)

### Code - refer the ipynb file in the repositories

### Data stream stored in Event Hub

![EventHub](https://github.com/Subramaniyam033/Weather-data-Streaming-DataBricks-Project/blob/e9de39b4978425c4b6533a0b9a74d3c25907251b/Azure%20Event%20Hub%20Steaming%20data.png) 

### PowerBi - Power Query to Get the latest Weather Data

![Power Query](https://github.com/Subramaniyam033/Weather-data-Streaming-DataBricks-Project/blob/e9de39b4978425c4b6533a0b9a74d3c25907251b/Power%20BI%20Latest%20Data%20details.png)

### PowerBI - Live Weather Dashboard 

![Weather Update Dashboard](https://github.com/Subramaniyam033/Weather-data-Streaming-DataBricks-Project/blob/e9de39b4978425c4b6533a0b9a74d3c25907251b/weatherpowerbi.png)
