# Wellington Suburb Data Insights Analysis 

## Executive Summary

The **Wellington Suburb Data Insights Analysis** project aimed to assist my family in finding a suitable suburb by analyzing demographic data. In this portfolio, the focus is solely on neighbourhood data from census data due to several considerations. By leveraging data from NZ.Stat, processing it with Power Query, and visualizing it through an interactive Power BI dashboard, we were able to narrow down our housing options to three suburbs and make an informed decision accordingly. 

## Project Overview

The objective of this project was to analyze demographic data to identify the most suitable suburbs for my family in Wellington. I focused on understanding the population dynamics in various suburbs, including population size, age groups, ethnic groups, qualification levels, and income. Due to time constraints, I did not track rental prices initially but instead shortlisted two suitable suburbs and monitored housing prices there.

## Data Sources

For this project, I utilized census data from NZ.Stat, available in CSV format. Due to the website's setup, data downloads were divided into four tables: Age Group by Region, Ethnic Group by Region, Highest Qualification by Region, and Personal Income by Region.

## Data Cleaning & Transformation

I imported the CSV files into Power Query for cleaning and transformation. Given the messy data format, extensive cleaning and transformation were required. This included simple tasks like removing irrelevant rows and columns, adjusting data formats, and using the 'replace value' function for data cleaning, as well as more complex tasks such as:

1. Transposing tables, auto-filling, merging columns, then transposing back, unpivoting, and splitting columns to add year suffixes to groups, making it easier to analyze changes over time.
2. Creating an order table to manually sort groups according to common understanding and merging this order into the group table.
3. Using the IF(CONTAINSSTRING()) function to merge smaller regions into larger areas, e.g., merging "Tawa South" and "Tawa Central" into "Tawa."
4. Creating new measures and using the divide function to determine the proportion of preference groups.

## Data Analysis

### 1. Overview of Combined Suburb Key Aspects Comparison

I needed an overview page to compare key aspects of combined suburbs. I used data bars to visually represent the ranking of preference group proportions in each suburb.
![1](https://github.com/Zhenzou28/Wellington-Suburb-Choosing/assets/141204592/ec88c2fe-15f4-48d8-a9ff-d5cc343229fd)
### 2. Location

Being new to Wellington, I added a map to help me visually understand the location of each suburb within the city.
![2](https://github.com/Zhenzou28/Wellington-Suburb-Choosing/assets/141204592/a47557eb-7b15-473b-838b-253d8123294d)

### 3. Region Overview

To gain a more detailed understanding of the key aspects of each region, this page used donut charts to show the composition of each group within the selected suburb.
![3](https://github.com/Zhenzou28/Wellington-Suburb-Choosing/assets/141204592/71bf8fc6-1666-4d35-ba8f-1bf7462161e1)

### 4. Reference People Choosing

I wanted to see where reference people were choosing to live. This page used area charts to display the top 10 choices of reference people and compared trends across different years.
![4](https://github.com/Zhenzou28/Wellington-Suburb-Choosing/assets/141204592/d260b58a-d445-421a-97d0-59731858cec6)

### 5. Detailed Pages

A matrix was used to display detailed information about each key aspect, with data bars and percentages of row totals for easy visual comparison.
![5](https://github.com/Zhenzou28/Wellington-Suburb-Choosing/assets/141204592/952b2b8f-190f-490e-8ec4-527575fc536b)
![6](https://github.com/Zhenzou28/Wellington-Suburb-Choosing/assets/141204592/13aa9d5b-0c2a-4e6e-8357-4b4566163f2f)
![7](https://github.com/Zhenzou28/Wellington-Suburb-Choosing/assets/141204592/b6c98507-db01-4cf9-b419-ea8005841cde)
![8](https://github.com/Zhenzou28/Wellington-Suburb-Choosing/assets/141204592/ecb4aa40-0fb1-4b04-9a95-a6048c65846a)

## Results/Findings

Based on these insights, I conducted in-person visits to three suburbs and ultimately decided on the best suburb for my family to live in.
