                                              📊 Target E-commerce Data Analysis (Brazil)
📌 Project Overview

This project presents an in-depth SQL-based exploratory and analytical study of Target’s e-commerce operations in Brazil. The analysis focuses on customer behavior, order trends, geographic distribution, logistics performance, payments, and economic impact using structured queries on relational datasets.
The objective is to extract actionable business insights that can support strategic decisions in marketing, supply chain optimization, and payment systems.
________________________________________
🗂 Dataset Description

The analysis is performed on the Target dataset consisting of the following key tables:

•	customers – Customer ID and geographic details (city, state, zip code)

•	orders – Order lifecycle timestamps and status

•	order_items – Product price and freight cost

•	payments – Payment types, installments, and payment values

📅 Data Timeline:

Orders placed between September 2016 and October 2018 (≈ 2 years)

🌎 Coverage:

•	27 Brazilian states

•	4,119 cities
________________________________________
🔍 Key Analysis Performed

1️⃣ Exploratory Data Analysis (EDA)

•	Inspected schema and data types of all tables

•	Identified customer distribution across cities and states

•	Determined the operational time range of the dataset

📌 Insight:

Most customers and orders originate from São Paulo (SP), followed by Minas Gerais (MG) and Rio de Janeiro (RJ).
________________________________________
2️⃣ Order Trends & Seasonality

•	Year-over-year order growth analysis

•	Monthly and seasonal ordering patterns

•	Time-of-day ordering behavior

📈 Insights:

•	Orders increased significantly from 2016 → 2017 → 2018

•	Peak ordering months: May, July, August, and November

•	Most orders are placed during the afternoon (1 PM – 6 PM)
________________________________________
3️⃣ Geographic Analysis

•	Month-on-month order volume by state

•	Customer distribution across Brazilian states

📌 Insights:

•	São Paulo (SP) consistently leads in order volume

•	States like Acre (AC) and Roraima (RR) show minimal activity

•	Urbanized states demonstrate steady growth trends
________________________________________
4️⃣ Economic Impact Analysis

•	Yearly comparison of total order value

•	State-wise total and average order price

•	Freight cost analysis by state

💰 Insights:

•	137% increase in order value from 2017 to 2018 (Jan–Aug)

•	SP has the highest total revenue but lowest average order value

•	Remote states show higher average freight costs

________________________________________
5️⃣ Logistics & Delivery Performance

•	Actual vs estimated delivery time analysis

•	State-wise average delivery duration

•	Identification of fastest delivery states

🚚 Insights:

•	Delivery time ranges from 8 to 29 days

•	SP, PR, MG, DF have the fastest deliveries

•	Some states deliver up to 20 days earlier than estimated
________________________________________
6️⃣ Payment Behavior Analysis

•	Monthly payment type trends

•	Installment-based payment analysis

💳 Insights:

•	Credit cards are the most used payment method, followed by UPI

•	Customers prefer 1–4 installments, with some opting up to 24

•	A small number of undefined payment types exist
________________________________________
🛠 Tools & Technologies

•	SQL (Google BigQuery)

•	Relational Database Concepts

•	Aggregate & Window Functions

•	CTEs (WITH clauses)

•	Date & Time Functions
________________________________________
📈 Business Value

This analysis helps:

•	Identify high-performing regions

•	Optimize logistics and freight pricing

•	Understand customer payment preferences

•	Improve delivery estimations

•	Support strategic planning and operational efficiency
________________________________________
📎 Conclusion

The project demonstrates how structured SQL analytics can uncover meaningful insights from large-scale e-commerce data. It highlights regional demand patterns, operational bottlenecks, and growth opportunities within Target’s Brazilian market.

