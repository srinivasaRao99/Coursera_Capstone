# Business Understanding

A client is planning to buy a residential property in Mumbai,India.  The client wishes to explore the different areas of Mumbai before buying a residential property.This project will aid in exploring the area as well as show the average price/sqft in the particular area. Area with similar trend in the venues will also be shown to the client.

The Location:
Mumbai is the dream city of India. It houses the film industry and is also the financial hub of India. As a result, every year people shift to Mumbai from various parts of India and this project will cater to many clients.

Foursquare API:
This project would use Four-square API as its prime data gathering source as it has a database of millions of places, especially their places API which provides the ability to perform location search, location sharing and details about a business.

Work Flow:
Using credentials of Foursquare API features of near-by places of the neighborhoods would be mined. Due to http request limitations the number of places per neighborhood parameter would reasonably be set to 100 and the radius parameter would be set to 500.

Clustering Approach:
To compare the similarities of neigbourhoods or areas, we decided to explore neighborhoods, segment them, and group them into clusters. To be able to do that, we need to cluster data which is a form of unsupervised machine learning: k-means clustering algorithm.

The dataset of the areas in Mumbai with their corresponding prices/sqft will be sourced from https://www.99acres.com/property-rates-and-price-trends-in-mumbai .
