## Project-Writing-a-Data-Scientist-Blog-Post

## Project Motivation:
### The main idea of this project is to find out if there a way to find out a set of features which can help to predict the price of airbnb homestay. Analysis was done around various features like neighborhod, property type, room type and amenities etc. Later on focus was on a smaller set of features which can help to predict the price. 

## Questions: 
### Question-1: Which neighborhood has maximum presence of airbnb listing?
### Question 2: How neighborhood influences the homestay price? 
### Question 3: How property type influences the homestay price?
### Question 4: How number of bedrooms influences the homestay price?
### Question-5: How amenities influence the price of the airbnb homestay?
### Question-6: Is it possible to predict price of a homestay with a set of features? 

## File Details: 
#### listing.csv
#### calendar.csv
#### reviews.csv
#### airbnb.ipynb
#### README.md

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
#### Question-5: The most common amenities which influences the price are - 1) Wireless Internet, 2) Heating, 3)Kitchen, 4) Smoke Detector, 5) Essentials. Also the least common amenities are 1) Elevators, 2) Hangers, 3) pets, 4) Indoor Fireplace, 5) Cable tv and they do not influence price much.
#### Question-6: Key features identified are related to accommodation, availability and review score. The predicted value was very less but the overall trend appears very similar. So we can say that the prediction on the price is quite possible with the features we have selected.

## Acknowledgements
### Dataset Credit - https://www.kaggle.com/airbnb/seattle
### Others: Thanks to Udacity for excellent course material and also to the mentors for timely help.
