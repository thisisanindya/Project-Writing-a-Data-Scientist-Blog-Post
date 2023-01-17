## Project-Writing-a-Data-Scientist-Blog-Post

## Blog-Post
#### https://medium.com/@thisisanindya.chaudhuri/finding-an-economy-airbnb-homestay-in-seattle-42575448b7c0

## Project Motivation:
#### The main idea of this project is to find out if there a way to find out a set of features which can help to predict the price of airbnb homestay. Analysis was done around various features like neighborhod, property type, room type and amenities etc. Later on focus was on a smaller set of features which can help to predict the price. 

## Questions: 
#### Question-1: Which neighborhood has maximum presence of airbnb listing?
#### Question 2: How neighborhood influences the homestay price? 
#### Question 3: How property type influences the homestay price?
#### Question 4: How number of bedrooms influences the homestay price?
#### Question-5: Which amenities are offered in various airbnb homestay?
#### Question-6: Is it possible to predict price of a homestay with a set of features? 

## File Details: 
#### listing.csv
#### calendar.csv
#### reviews.csv
#### airbnb.ipynb
#### README.md

## Methodology Used
#### Step-1: Business Understanding - We would like to analyse which are the key features influencing the price of an airbnb homestay in Seattle and if there are some trends that can be used to make prediction to find the best price of airbnb homestay. Answer to the below set of questions will help us to get there.

#### Step-2 - Data Understanding - Here we look at the listing, calender and reviews data. Check on all the columns datatypes and few statistical details. 

#### Step-3: Data Preparation & Cleaning - Here We look for missing values, wrong data types, unnecessary features that can be dropped, remove characters like $.  

#### Step-4: Evaluation and Modeling

## Libraries Used
#### numpy
#### pandas
#### matplotlib.pyplot
#### sklearn
#### seaborn
#### collections

## Summary
#### Question-1: Broadway has the highest number of airbnb listing which is almost double number of Belltown which is the second position.  
#### Question-2: Highest median prices are around the nighbourhoods of 1) Briajrcliff, 2) Pioneer square. Lowest median prices are around the nighbourhoods of 1) Olympic Hills, 2) Rainier Beach. 
#### Question-3: It is evident that 'Boat', 'Condominium', 'Apartment' has higher median price than the other property types.
#### Question-4: Price is more i there are more number of bedrooms.
#### Question-5: The most common amenities are - 1) Wireless Internet, 2) Heating, 3)Kitchen, 4) Smoke Detector, 5) Essentials. Also the least common amenities are 1) Elevators, 2) Hangers, 3) pets, 4) Indoor Fireplace, 5) Cable tv.
#### Question-6: Key features identified are related to accommodation, availability and review score. The predicted value was very less but the overall trend appears very similar. So we can say that the prediction on the price is quite possible with the features we have selected.

## Acknowledgements
#### Dataset Credit - https://www.kaggle.com/airbnb/seattle
#### Others: Thanks to Udacity for excellent course material and also to the mentors for timely help.
