# data-science-flatworld-sales

## Objective: 
Using the most recent data on institutions (2016), I’ll be analyzing student sales from the past year (2018) to see if there are relationships between school characteristics and student sales.

## Dataset: 
I will be using a custom dataset that combines IPEDS (Integrated Postsecondary Education Data System) data with FlatWorld’s student purchase data. I have the right access permissions. Each row will be a different institution that has FlatWorld sales in 2018, and each column will be a different institutional characteristic. The data is scoped to US institutions with FlatWorld student orders in 2018. There are almost 7,000 institutions I originally pulled from the IPEDS database, but after combining that CSV with the CSV created from FlatWorld student sales data in 2018, the number of institutions is narrowed to 1,112 institutions (because only 1,112 US institutions in the IPEDS database have purchased from FlatWorld).

## The goal: 
Predict FlatWorld sales at a school.

## The success metric: 
The number of student orders.

## The risks or limitations:
1. The limited FlatWorld sales data available (only 1,112 institutions have FlatWorld sales out of the 6,000+ institutions available in the IPEDS database).
2. The delay between the surveyed institution characteristics data (from 2016) and the sales data used (from 2018). This is because FlatWorld database sales records are the most complete for 2018 because we transitioned off of using another system right before the 2018 sales year.

## Problem Statement:
What are the most influential factors on sell-through? Are there characteristics of schools that make them better targets for us? (Factors here are things like tuition of the school, percentage of students on financial aid, college type (comm vs 4-year), grad rates, school size, and student acceptance rate).
