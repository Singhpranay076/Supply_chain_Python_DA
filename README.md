# Supply Chain Inventory Analytics & Demand Forecasting

## Overview
Modern supply chains rely heavily on data-driven decision making to maintain optimal inventory levels while minimizing 
costs and avoiding stockouts.

This project demonstrates how 

1. Python-based analytics can be used to support inventory planning, demand forecasting, and product prioritization
2. Using real-world supply chain data. (Source: Kaggle.com)

Using a supply chain dataset containing product demand, stock levels, lead times, and revenue information,this project 
applies several core supply chain analytics techniques:

a) Demand Forecasting
b) Safety Stock Calculation
c) Reorder Point Optimization
d) Economic Order Quantity (EOQ)
e) ABC Inventory Classification
f) Forecast Accuracy Measurement (MAPE)
g) Data Visualization for decision making

The goal is to transform raw operational data into actionable inventory insights that can help businesses improve supply chain efficiency.

--------------------------------------------------------------------------------------------------------

# Key Objectives

This project aims to demonstrate how data analytics can answer important supply chain questions such as:

1. Which products generate the most revenue?
2. Which products require tighter inventory control?
3. How much inventory should be ordered each cycle?
4. When should a product be reordered to prevent stockouts?
5. How accurate are our demand forecasts?

----------------------------------------------------------------------------------------------------------

# Concepts Implemented

## 1. Demand Forecasting

A moving average method is used to estimate future product demand based on historical sales.

This helps organizations anticipate demand patterns and plan procurement accordingly.

Formula:

Forecast = Average of previous demand observations

-----------------------------------------------------------------------------------------------------------

## 2. Safety Stock

Safety stock acts as a buffer inventory that protects against demand variability and supplier delays.

Safety Stock Formula:

Safety Stock = Z × σ × √Lead Time

Where:

> Z = Service level factor
> σ = Standard deviation of demand
> Lead Time = Supplier delivery time

------------------------------------------------------------------------------------------------------------

## 3. Reorder Point

The reorder point determines when to place a new order before stock runs out.

Reorder Point Formula:

Reorder Point = (Average Demand × Lead Time) + Safety Stock

This ensures continuous product availability.

-------------------------------------------------------------------------------------------------------------

## 4. Economic Order Quantity (EOQ)

EOQ determines the optimal order quantity that minimizes total inventory cost.

EOQ Formula:

EOQ = √((2 × Demand × Ordering Cost) / Holding Cost)

This balances:

> Ordering costs
> Inventory holding costs

---------------------------------------------------------------------------------------------------------------

## 5. ABC Inventory Classification

ABC analysis categorizes products based on revenue contribution.

Class             Description                           

A                 High-value products
B                 Medium importance                     
C                 Low-value products                   

This allows businesses to focus tighter control on the most critical products.

----------------------------------------------------------------------------------------------------------------

## 6. Forecast Accuracy (MAPE)

Forecast performance is evaluated using **Mean Absolute Percentage Error (MAPE).

MAPE Formula:

MAPE = (1/n) Σ |(Actual - Forecast) / Actual| × 100                        

Lower MAPE indicates better forecasting accuracy.

-----------------------------------------------------------------------------------------------------------------

# Visualizations

The project includes several analytical visualizations to support decision-making:

> Demand distribution analysis
> Top selling products
> Stock levels vs reorder points
> EOQ vs current inventory
> Forecast error distribution
> ABC classification breakdown

These visualizations make inventory insights **easy to interpret and communicate**.

--------------------------------------------------------------------------------------------------------------------

# Technologies Used

Python Libraries:

> pandas → data manipulation
> numpy → numerical computation
> matplotlib → visualization

Environment:

* Jupyter Notebook
----------------------------------------------------------------------------------------------------------------------

# Business Insights Generated

The analysis enables several operational insights:

> Identify products that require immediate replenishment
> Detect potential stockout risks
> Optimize order quantities to reduce inventory costs
> Prioritize high-value products using ABC classification
> Evaluate forecasting accuracy

-------------------------------------------------------------------------------------------------------------------

# Key Takeaways

This project demonstrates how data analytics can support **strategic supply chain decision-making,including:

> Inventory optimization
> Demand forecasting
> Product prioritization
> Risk mitigation

By combining supply chain theory with data analytics tools, organizations can significantly improve operational efficiency.

----------------------------------------------------------------------------------------------------------------------

# Author

Pranay

Aspiring Supply Chain & Data Analytics Professional
Focused on applying analytics to optimize operations and decision-making.

