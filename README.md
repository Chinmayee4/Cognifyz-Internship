# Cognifyz-Internship

Welcome to the Restaurant Analysis project! This repository contains the code and data used to analyze various aspects of restaurant performance, customer reviews, and other relevant metrics.

# Introduction
This project aims to provide insights into restaurant performance through data analysis. By leveraging customer reviews, price range , and other relevant information, uncovering trends and patterns that can help restaurants make informed decisions.

# Project structure
* Importing Libraries: First, ensure you have all the necessary libraries imported. This typically includes libraries for data manipulation, and visualization.
* Importing Dataset: Load the dataset into your workspace. Ensure the data file is placed in the 'df' directory.
* Basic Information of the Dataset: Get an overview of the dataset to understand its structure, including the number of rows, columns, and data types.
* Data Cleaning: Clean the dataset to handle missing values, duplicate records, and any inconsistencies.
* Exploratory Data Analysis (EDA): Perform EDA to understand the data and identify any patterns or trends.
* Generate Reports: Generate detailed reports and visualizations of the analysis results.
# Features
  * Level 1
    
     * Top cuisines
     * City Analysis
     * Price range distribution
     * Online delivery
 * Level 2

    * Restaurant ratings
    * Cuisine combinations
    * Geographical analysis
    * Restaurant chains
* Level 3

  * Restaurant reviews
  * Vote analysis
  * Price range v/s Online delivery & Table bookings
# Key insights
* North Indian (3960), Chinese (2735), and Fast Food (1986) are the top 3 Cuisines among all the restaurants. Percentage of restaurants that serve each of the top cuisines 
  are 41.50%, 28.66%,and 20.81%, respectively.
* New Delhi (5473) is the city with the highest number of restaurants in the dataset. Debriefed on the average rating for restaurants in each city. 'Inner City' stands out on thr top for 
  city with the highest average rating of 4.9.
* Restaurants having least price on there dishes get more orders. Order with price range of 1 have been ordered more, 46.51% of the entire dataset.
* 2,451 restaurants are providing online delivery, 25.7% of the entire dataset. Restaurants providing online delivery are given more average ratings.
* The most common rating range exists from 3 - 4, the most common rating in all the dataset is marked at 3.5 and Average number of votes received by restaurants are 156.77.
* North Indian and Chinese is the most common cuisine combination. Italian & Deli, the cuisine combinations in the dataset having higher ratings.
* Geographical analysis of the restaurants helps in determining the clusters forming in South east Asia, majorly from India the followed by USA,UK,Australia,UAE,Turkey,South Africa,
 Indonesia and then the rest of the world.
* 734 restaurant chain in the dataset, and Cafe coffe day has most numbers of restaurnats (83). "Talaga Sampireun" the restaurant chain that has total of 5,514 votes with average rating 
 of 4.9.
* The most common positive review is "Average" with 3,734 counts (39.1% of the data). The most common negative review is "Poor" with 186 counts (1.9% of the data). Additionally, there is 
  a negative correlation between review length and rating is -0.60 : as review length increases, the aggregate rating tends to decrease.
* The restaurant "Toit" from Bangalore, India, received the maximum votes (10934), while "Cantinho da Gula" from Sao Paulo, Brazil, received none. The weak positive correlation between 
  the number of votes and the aggregate rating is confirmed by a correlation coefficient of 0.31.
* The proportion of restaurants offering online delivery rises with higher price ranges, peaking at range 2. Similarly, table booking availability increases with price, highest in ranges 
  3 and 4. Among 1,991 high-priced restaurants, 464 (23.3%) offer online delivery, while 918 (46.1%) offer table booking.
