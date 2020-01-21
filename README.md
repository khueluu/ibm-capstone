# ibm-capstone
IBM Data Science  Professional Certificate Capstone Project

This is a Capstone Project of the 'IBM Data Science Professional Certificate'

## 1. Introduction
### 1.1 Background
Hanoi, capital of Vietnam, is a dynamic and multicultural city. Spread across 30 districts, there are a variety of entertainment for both locals and tourists to enjoy. Culture and art lovers can spend a whole day in museums to learn about Vietnamese history and traditions, or visit various art galleries to get themselves authentic artworks from talented local artists. At night, music fans can listen to the glamorous sound of the saxophone in a cozy jazz club, or watch latest blockbuster in modern movies theaters. Every year, millions of tourists from aroud the world as well as a large amount of people from different provinces come to Hanoi, looking for opportunities and experience. This could be a prospective market for entreprenerus as well as an opportunity for local people to enjoy one of the greatest distinct culture in Asia.

### 1.2 Business Problem
The objective of this project is to recommend the best district in Hanoi to open an art gallery based on the interst of people in that location. Statistical techniques and a machine learning algorithm is used to analyze and cluster districts in Hanoi based on their similarity in number of art venues. From there, I can check which cluster has the most art venues and galerries, which means there are potential custumers usually go shopping in the district, and that would be a great place to open an art gallery.

### 1.3 Who would be interested?
Business owners, artists or art fan can find the result of this project useful in their decision making process. Business owners can see areas that have many art venues and come up with further decisions. Tourist with great interest in Vietnamese artworks can look at the project's result to choose their destinaton for their next trip to Hanoi.

## 2. Data
### 2.1 Describe data
To solve the project problem, I need to collect these data:
- The list of district names in Hanoi (scraped from Wikipedia using Beautiful Soup)
- The latitude and longitude of these neighbourhoods (Geocoder package)
- Venues data related to art section in each district to help find the location with more interest in art galleries (from Foursquare API)

### 2.2 How it is used to solve the problem?
From the coordinates, I search for 50 restaurants within 10 kilometers of each district, then use k-means clustering technique to cluster neighbourhoods in 5 categories that represent the quantity of Vietnamese art venues in that district.

## 3. Methodology
section which represents the main component of the report where you discuss and describe any exploratory data analysis that you did, any inferential statistical testing that you performed, if any, and what machine learnings were used and why.

## 4. Results
This project only focus on cluster the districts based on their art venues. However, in reality, many other factors can contribute to decide which district is good to open an art gallery as well. In the scope and time frame of this project, I accept the result and hope to have further research to improve the solution.

## 5. Discussion
This project only focus on cluster the districts based on their art venues. However, in reality, many other factors can contribute to decide which district is good to open an art gallery as well. In the scope and time frame of this project, I accept the result and hope to have further research to improve the solution.

## 6. Conclusion
This project aims to cluster 30 district of Hanoi into 5 areas based on the district's common in art venues. By scraping district info and coordinates from the internet and using data analyis and machine learnig model, the project finds that districts in the city center are more art-oriented with more art galleries, whereas the districts that are near rural areas have less options. Though the findings only based on the art venues' similarity, I hop this bring values to people to have a first overview of art and entertainment market in Vietnam.