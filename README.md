# Coursera_IBM-Data-Science-Capstone-Project

A repository for the capstone project for the IBM Data Science Certificate course

## Introduction / Business Problem

Colombo is the commercial capital and largest city of Sri Lanka by population. According to the Brookings Institution, Colombo metropolitan area has a population of 5.6 million, and 752,993 in the city proper. It is the financial center of the island and a tourist destination. Colombo is arguably Sri Lanka's most popular tourist destination. The coastal city is a beautiful place to spend a couple of days just relaxing, indulging in the local food, and leisure activities. In Colombo, most common restaurants are aimed at tourists, with a mix of Sri Lankan, seafood and Western dishes and South Indian-style places.

Our stakeholder is willing to open a restaurant in Colombo. Choosing a restaurant type and a good spot, relies on common sense and domain knowledge. Data science provides valuable insights regarding market trends and consumer lifestyles so that stakeholder can better address and meet public demand.
In this project, we will implement the basic analysis and try to find the most optimal sub-urbs to open the restaurant according to those criteria. It's obvious, that there are many additional factors, such as distance from parking places or distance from the main streets, but this analysis mainly focuses on the type of restaurants

## Data

The problem will be addressed in following steps:

Step 1. Using a table on 'https://en.wikipedia.org/wiki/Colombo#:~:text=Colombo%20(/%20k%C9%99%CB%88l%CA%8Cmbo%CA%8A%20/;%20Sinhala:%20%E0%B6%9A%E0%B7%9C%E0%B7%85%E0%B6    %B9,%20romanized:%20Kolamba,,and%20largest%20city%20of%20Sri%20Lanka%20by%20population., collect information about Colombo suburbs.

Step 2. Use the Geopy and Folium library to get the coordinates of every locations and map geospatial data on a Colombo map.

Step 3. Using Foursquare API, collect the top 100 restaurants and their categories for each location within a radius 1000 meters.

Step 4. Group collected restaurants by location and by taking the mean of the frequency of occurrence of each type, preparing them for clustering.

Step 5. Cluster restaurants by k-means algorithm and analyze the top 5 most common restaurants in each cluster.

Step 6. Visualize clusters on the map, thus showing the best locations for opening the chosen restaurant.
