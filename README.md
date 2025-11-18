# swiggy_sales_analysis_excel

## About the Dataset
Imagine opening the door to a bustling city where thousands of people are ordering their favorite meals at any moment—morning idlis, evening snacks, midnight cravings. This dataset is a snapshot of that world. <br>
It captures the pulse of Swiggy’s food delivery ecosystem across multiple cities and states. <br>

Every row in the dataset tells a story: <br>

A customer in Bengaluru ordering crispy Murukku from Anand Sweets… <br>
Someone in Kengeri grabbing a hot Badam Milk to start their day… <br>
A family trying out a new restaurant based on glowing ratings… <br>
A dish climbing the popularity charts because of a surge in weekly demand. <br>

The dataset brings together: <br>
The where (State, City, Location) <br>
The who cooked it (Restaurant Name) <br>
The what was ordered (Dish, Category, Food Type) <br>
The when (Order Date, Day, Week, Quarter) <br>
And the how customers felt (Rating and Rating Count) <br>

To make the narrative richer, additional features like Day, Week, Quarter, and Food Type were crafted—turning raw dates and dish names into meaningful patterns. Now, trends reveal themselves: weekends showing order spikes, certain quarters driving more revenue, and specific food types dominating customer cravings.<br>

From this rich tapestry, the dashboard brings the story to life—tracking how sales evolve month by month, which states drive the highest revenue, what cities love the most, and how ratings shape customer choices. Top-selling cities rise to the spotlight, weekly rhythms emerge, and KPIs show the heartbeat of Swiggy’s business performance. <br>

This dataset isn’t just numbers. It’s a living narrative of people, food, preferences, and patterns—served fresh, one order at a time.<br>

## Feature-Engineered Columns (Created for Analysis)
1. Day <br>
This column extracts the day of the week (Monday, Tuesday, etc.) from the order date. <br>
It helps uncover patterns like weekend order spikes or weekday slowdowns, showing how customer behavior changes throughout the week.<br>

2. Week<br>
This represents the week number of the year (1–52).<br>
It’s useful for studying weekly demand fluctuations, spotting seasonal peaks, and aligning sales cycles with marketing or festival periods.<br>

3. Quarter<br>
The year is divided into four quarters:<br>
Q1 → Jan–Mar<br>
Q2 → Apr–Jun<br>
Q3 → Jul–Sep<br>
Q4 → Oct–Dec<br>
This column helps analyze higher-level business trends, such as which quarter drives the highest revenue or receives the best customer ratings.<br>

4. Food Type <br>
This column classifies every dish into two simple categories: <br>
Veg and Non-Veg <br>
It was created to understand customer preferences at the most fundamental level—whether people tend to order vegetarian dishes or non-vegetarian ones more frequently. <br>
This helps identify trends such as which cities prefer Veg items, how Non-Veg sales change over time, and how food type influences overall revenue and ratings.<br>
