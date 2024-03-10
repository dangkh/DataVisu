---
title: "Proposal"
author: "Truong Tuan Vu, Nguyen Minh Tuong, Kieu Hai Dang"
date: "`r Sys.Date()`"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

Our group’s chosen dataset is Valentine's Day Consumer Data. The data is sourced from the National Retail Federation (NRF) in the United States. The NRF conducts annual surveys to gather information on how consumers plan to celebrate Valentine's Day.

The data has been collected through consumer surveys administered by the NRF over the past decade, from 2010 to 2022.

The dataset used in this analysis was curated by Suraj Das and published on Kaggle. Das compiled the data from the NRF's surveys into a structured dataset spanning the years 2010 to 2022.

The dataset includes variables such as the percentage of consumers celebrating Valentine's Day, average spending per person, and spending across various gift categories like candy, flowers, jewelry, greeting cards, evening out, clothing, and gift cards.

Additionally, it provides demographic breakdowns by age group and gender.

The dimension of:

- historical_spending: 13 rows x 10 columns.
- gifts_age: 6 rows x 9 columns
- gifts_gender: 2 rows x 9 columns

Our group chooses this dataset is because this month has International Women Day which is quite similar to Valentine Day.

With this dataset, we can know the trend of choosing gifts in the world, suitable for all ages, from which we can choose suitable gifts to give to our beloved women.

**Here are two questions that can be used to draw insights:**

1. How does the spending on different gift categories (e.g., Candy, Flowers, Jewelry, Greeting Cards, Evening Out, Clothing, and Gift Cards) vary across different age groups and between genders?

This question involves analyzing the relationship between three variables: age group, gender, and the various gift categories.

2. How have the overall spending on celebrating, the per-person spending, and the spending on different gift categories (e.g., Candy, Flowers, Jewelry, Greeting Cards, Evening Out, Clothing, and Gift Cards) changed over the years, and how do these trends relate to economic factors or events?

This question involves examining the trends in multiple variables over time: overall spending on celebrating, per-person spending, and spending on various gift categories.

**Plan for answering each of them:**

**Question 1**: How does the spending on different gift categories (e.g., Candy, Flowers, Jewelry, Greeting Cards, Evening Out, Clothing, and Gift Cards) vary across different age groups and between genders?

Variables involved:

- Age group
- Gender
- Spending on gift categories (Candy, Flowers, Jewelry, Greeting Cards, Evening Out, Clothing, Gift Cards)

**Plan:**

- Analyze the spending patterns across different age groups for each gift category using data from the "gifts_age.pdf" file.
- Visualize the data using appropriate charts (e.g., bar charts, line charts) to identify trends and variations in spending across age groups for each gift category.
- Repeat the analysis for gender using data from the "gifts_gender.pdf" file.
- Compare the spending patterns between genders for each gift category using appropriate visualizations (e.g., side-by-side bar charts).
- No additional variables need to be created, and no external data needs to be merged for this analysis.

**Question 2**: How have the overall spending on celebrating, the per-person spending, and the spending on different gift categories (e.g., Candy, Flowers, Jewelry, Greeting Cards, Evening Out, Clothing, and Gift Cards) changed over the years, and how do these trends relate to economic factors or events?

Variables involved:

- Year
- Percent Celebrating
- Per Person (average spending per person)
- Spending on gift categories (Candy, Flowers, Jewelry, Greeting Cards, Evening Out, Clothing, Gift Cards)

**Plan:**

- Analyze the trends in overall spending on celebrating (Percent Celebrating) and per-person spending over the years using data from the "historical_spending.pdf" file.
- Visualize the trends using line charts or area charts to identify patterns and changes over time.
- Analyze the trends in spending for each gift category over the years using data from the "historical_spending.pdf" file.
- Visualize the trends for each gift category using line charts or area charts to identify patterns and changes over time.
- Potential additional variables to create:
    - Economic indicators (e.g., GDP growth rate, inflation rate, consumer confidence index) for the corresponding years
    - Indicators for significant events (e.g., recessions, natural disasters, pandemics) that may have impacted consumer behavior
- Merge the dataset with external data sources providing economic indicators and event indicators for the corresponding years.
- Analyze the relationships between the spending trends and economic/event indicators using correlation analysis or regression models.

This plan outlines the variables involved, the visualizations and analyses to be performed, and the potential need for creating additional variables and merging external data sources to explore the relationships between spending trends and economic factors or events.