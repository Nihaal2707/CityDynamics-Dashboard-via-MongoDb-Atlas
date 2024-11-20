# CityDynamics-Dashboard-via-MongoDb-Atlas

## Acknowledgment

I would like to express my gratitude to the following individuals and sources for their contributions to this project:

### Prof. Ashok K Harnal: 
I am thankful for the guidance and support provided by Prof. Ashok K Harnal, whose expertise has been invaluable in shaping this project.

### Tanishq dublish: 
I would like to acknowledge the work of Tanishq, whose repository (https://www.kaggle.com/tanishqdublish) served as a valuable reference for understanding and implementing this project.

## **Introduction**

This project leverages MongoDB Atlas to analyze traffic patterns and energy consumption in futuristic urban environments. The dashboard provides actionable insights into how weather, economic conditions, vehicle types, and time of day influence traffic flow and energy usage. Built using a dataset sourced from Kaggle, this project demonstrates the power of data visualization and MongoDB's capabilities in creating intelligent, data-driven solutions for smart cities.

## Table Of Contents

1.) Project Overview

2.) Features and Dataset

3.) Dashboard Overview

4.) Business Insights

5.) MongoDB Atlas and Compass

6.) How to Install and Use

## **Project Overview**

The CityDynamics Dashboard is designed to provide decision-makers with critical insights into traffic behavior. It evaluates various influencing factors like weather conditions, economic states, and vehicle types. This dashboard is built on MongoDB Atlas, a fully managed cloud database service that supports scalable data storage and robust analytics.

## Objectives

The objective of this analysis is to leverage the futuristic urban traffic dataset to gain actionable insights into traffic patterns, energy consumption, and the impact of external factors like weather and economic conditions. By utilizing this data, the aim is to optimize traffic management, enhance the performance of autonomous and innovative vehicle types, and develop sustainable strategies for smart city infrastructure. The insights will help in designing efficient, adaptive urban mobility systems to address challenges in modern traffic dynamics.

### 1. Optimizing Energy Consumption

•	Identify patterns in energy consumption across different cities, vehicle types, and traffic density levels. Use these insights to optimize energy usage in urban transport systems.

### 2. Improving Traffic Management

•	Analyze traffic density and speed patterns during peak and non-peak hours to design effective traffic management strategies, particularly in cities with high traffic density like MetropolisX.

### 3. Enhancing Autonomous Vehicle Performance

•	Leverage data on vehicle types and their average speeds to enhance the efficiency and safety of autonomous vehicles under varying weather and economic conditions.

### 4. Adapting to Weather and Economic Conditions

•	Evaluate the impact of weather and economic conditions on traffic flow and energy consumption. Develop adaptive strategies for managing traffic during adverse weather events or economic downturns.

### 5. Planning for Smart City Infrastructure

•	Use city-wise energy consumption and vehicle-type distribution data to guide investment in infrastructure that supports sustainable transportation, such as charging stations for flying cars or drones.

### 6. Predicting Traffic Bottlenecks

•	Utilize peak-hour data and random event indicators to predict and mitigate potential traffic bottlenecks, ensuring smoother traffic flow and reducing delays.

## **Features and Dataset**

**Dataset**

**Source:** https://www.kaggle.com/datasets/tanishqdublish/urban-traffic-density-in-cities/data

**Key Features:**

**City:** Name of cities like MetropolisX, SolarisVille, etc.

**Vehicle Type:** Types like Cars, Flying Cars, and Autonomous Vehicles.

**Weather Conditions:** Clear, Rainy, Snowy, and other weather states.

**Economic Conditions:** Booming, Recession, and Stable.

**Traffic Metrics:** Speed, Traffic Density, Energy Consumption, and Peak Hour indicators.

**Potential Uses:**

1.) Optimize traffic management systems for futuristic cities.

2.) Understand the impact of weather and economic states on traffic and energy.

3.) Aid in the development of smart-city applications and algorithms.

## **Dashboard Overview**

The dashboard, hosted on MongoDB Atlas, offers a dynamic and visually rich analysis of the dataset. Below are key visualizations:

**Average Energy Consumption by Vehicle Type**

**Insight:** Evaluate energy usage for different vehicle categories.

**Traffic Density vs. Speed by Economic Condition**

**Insight:** Understand traffic flow behavior under varying economic states.

**Hourly Traffic Density Patterns**

**Insight:** Identify peak traffic times and optimize city resources accordingly.

**Energy Consumption by City and Weather**

**Insight:** Compare energy usage trends across different cities and weather conditions.

**Explore the live dashboard here:** https://charts.mongodb.com/charts-project-0-peualds/public/dashboards/65bf7c6c-985d-4496-af7e-e58daf2a5049

## **Business Insights**

**1. Avg. Energy Consumption (Donut Chart)**

**Detailed Insight:**
![Screenshot 2024-11-20 232125](https://github.com/user-attachments/assets/31b31fbb-21da-40f5-821f-17e1f6bfc964)

The average energy consumption of 49.517 kWh per vehicle indicates a significant reliance on energy-intensive transportation methods. This average varies depending on vehicle type, traffic density, and weather conditions. High energy consumption may strain city energy grids, especially during peak hours or under adverse conditions.

**Recommendation:**

Promote energy-efficient transportation modes such as autonomous electric vehicles. Introduce policies to incentivize low-energy consumption vehicles and discourage high-energy-consuming modes during peak hours. Implement infrastructure for renewable energy charging stations to support the growing energy demand.

**2. Highest Energy Consumption (City-Wise)**

**Detailed Insight:**

MetropolisX's position as the highest energy-consuming city likely stems from a combination of high traffic density, diverse vehicle types, and possibly a larger proportion of energy-intensive flying cars. Cities like MetropolisX may also experience higher congestion due to economic activity or infrastructure bottlenecks.

**Recommendation:**

Conduct a detailed analysis of MetropolisX’s traffic patterns to identify areas with recurring congestion. Deploy congestion pricing models, incentivize public transportation, and invest in smart traffic systems to reduce energy wastage. Explore partnerships with energy providers to ensure sustainable supply.

**3. Economic Condition (Pie Chart)**

**Detailed Insight:**

The distribution of economic conditions (e.g., Booming, Recession) shows how urban mobility demand fluctuates. Cities in a "Booming" economy typically exhibit higher traffic density due to increased activity levels, such as commuting and logistics, while "Recession" periods may see reduced congestion but uneven infrastructure usage.

**Recommendation:**

Tailor traffic management strategies to economic conditions. For instance, during economic booms, expand public transportation availability and optimize road usage to reduce strain on the system. Conversely, during recessions, maintain infrastructure efficiency to avoid underutilization and operational costs.

**4. Vehicle Type Distribution (Pie Chart)**

**Detailed Insight:**

The variety in vehicle types, including cars, autonomous vehicles, and flying cars, reveals the need for differentiated traffic management strategies. Flying cars may reduce road congestion but place unique demands on air traffic systems and energy grids. Autonomous vehicles provide opportunities for smoother traffic flow due to consistent driving behavior.

**Recommendation:**

Develop policies to regulate flying car usage during specific hours or locations. Prioritize infrastructure for autonomous vehicles, such as dedicated lanes, and invest in charging infrastructure for all vehicle types. Incorporate flying car air routes into urban planning.

**5. Weather Conditions (Pie Chart)**

**Detailed Insight:**

The weather distribution shows that "Clear" conditions dominate, but adverse weather (Rainy, Foggy, etc.) significantly impacts traffic flow, reducing vehicle speeds and increasing energy consumption. Weather-resilient traffic systems become crucial for maintaining efficiency in such conditions.

**Recommendation:**
Implement adaptive traffic systems that adjust signal timings and lane prioritization during adverse weather. Provide real-time weather and traffic updates to drivers, particularly for autonomous systems, to enable efficient routing decisions.

**6. Peak Hour vs. Avg. Speed (Bar Chart)**

**Detailed Insight:**

The significant drop in average speed during peak hours highlights the inefficiencies caused by high traffic density. Weather conditions further exacerbate the situation, with speeds dropping more drastically under adverse conditions.

**Recommendation:**

Encourage staggered work hours or flexible schedules to reduce peak-hour congestion. Introduce real-time congestion pricing to distribute traffic more evenly throughout the day. Expand high-capacity public transportation options during peak times to reduce road usage.

**7. Speed and Traffic Density by Economic Condition (Line Graph)**

**Detailed Insight:**

The graph shows that traffic density is notably higher during a booming economy, which impacts average vehicle speeds. Economic activity drives vehicle usage, and higher traffic density can lead to energy inefficiency and delays.

**Recommendation:**

Implement data-driven urban traffic models that account for economic trends. Use historical data to anticipate traffic density increases during boom periods and adjust traffic signal timings or open additional lanes accordingly.

**8. Avg. Speed by Hour of Day (Bar Chart)**

**Detailed Insight:**

Speeds are lower during peak hours and recover during off-peak periods. This pattern highlights congestion in early morning and evening hours. Autonomous vehicles may help mitigate these bottlenecks due to their ability to operate at more consistent speeds.

**Recommendation:**

Advocate for carpooling during peak hours to reduce the number of vehicles on the road. Deploy intelligent traffic routing systems to divert traffic from congested areas to alternative routes during these times.

**9. Energy Consumption City-Wise (Segmented by Vehicle Type) (Stacked Bar Chart)**

**Detailed Insight:**

Cities with high energy consumption, particularly for flying cars and autonomous vehicles, demonstrate the need for efficient energy distribution systems. Variations in energy consumption also reflect disparities in urban planning and vehicle technology adoption.

**Recommendation:**

Focus on promoting lower-energy vehicle technologies in high-consumption cities. Establish partnerships with renewable energy providers to address the energy demands of futuristic vehicle types like flying cars.

**10. Hour of Day vs. Traffic Density (Line Graph)**

**Detailed Insight:**

Traffic density peaks during specific hours (morning and evening commutes), indicating high congestion during these times. Such trends are consistent across cities, emphasizing a universal need for targeted interventions during peak periods.

**Recommendation:**

Expand public transportation capacity during these hours. Implement real-time traffic monitoring systems to dynamically manage road usage and suggest alternative routes to reduce congestion.

**11. Traffic Density vs. Energy Consumption (Scatter Plot)**

**Detailed Insight:**

The scatter plot shows a positive correlation between traffic density and energy consumption. Higher traffic density leads to more stop-and-go conditions, which increase energy inefficiency.

**Recommendation:**

Focus on reducing traffic density through improved infrastructure, such as additional roadways or alternate routes. Introduce policies that incentivize energy-efficient driving behaviors or the use of energy-saving vehicle technologies.

**12. Avg. Speed vs. Vehicle Type (Bar Chart)**

**Detailed Insight:**

The variation in speeds by vehicle type suggests that autonomous vehicles are better at maintaining consistent speeds, reducing congestion and improving fuel efficiency. In contrast, traditional vehicles may struggle under dense traffic.

**Recommendation:**

Encourage the adoption of autonomous vehicles by providing tax benefits or infrastructure incentives. Promote their use in public transportation fleets to demonstrate their efficiency benefits.

**13. Energy Consumption and Traffic Density by Economic Condition (Table)**

**Detailed Insight:**

This table consolidates multiple dimensions, highlighting which combinations of economic conditions, vehicle types, and cities contribute most to energy consumption and traffic density.

**Recommendation:**

Use this data to prioritize intervention areas. For instance, during booming economies, focus on high-density cities using energy-intensive vehicles. Roll out targeted public policies such as subsidies for efficient vehicles or investments in public transportation infrastructure.


## **MongoDB Atlas and Compass**

MongoDB Atlas is a cloud-based database service that provides scalability, high availability, and integrated analytics. It allows seamless data visualization through charts and dashboards.

MongoDB Compass is a GUI tool for managing MongoDB collections, allowing you to query and organize your data effectively.

**Benefits of MongoDB for This Project:**

1.) Efficient handling of large datasets.
2.) Integrated visualization tools for creating live dashboards.
3.) Easy scalability to manage futuristic urban data.

## **How to Install and Use**

### **1. Install MongoDB Tools**

**MongoDB Atlas:**

1.) Create a MongoDB Atlas account here: https://www.mongodb.com/products/platform/atlas-database

2.) Create a new cluster and configure your database access.

3.) Import the dataset into MongoDB Atlas using Compass or MongoDB's import tools.

**MongoDB Compass:**

1.) Download MongoDB Compass here: https://www.mongodb.com/try/download/compass

2.) Connect Compass to your Atlas cluster and verify the imported dataset.

### **2. Configure the Dashboard**

1.) Open MongoDB Atlas Charts.

2.) Create a new dashboard and build charts using the dataset's features.

3.) Publish the dashboard for public sharing.

