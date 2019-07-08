# Zomato_Data_Analysis
Finding best restaurants in Bangalore

### Introduction
Bengaluru being an IT capital of India. Most of the people here are dependent mainly on the restaurant food as they don’t have time to cook for themselves. Bengaluru is one such city that has more than 12,000 restaurants serving dishes from all over the world, with such high number of restaurants, it has become difficult for people who are striving to get the best food.

### Purpose
To perform data analysis on zomato dataset to find the best restaurants in Bangalore so that people have a good meal the next time they step out.

### Questions
Here we try to analyze which factors were more likely to contribute for a restaurant to become the best.

Are the locations of restaurants localised to specific parts of city?

Is there a relation between online order option and rating of the restaurant?

Is there a relation between table booking option and rating of the restaurant?

How much does cost play role for people to choose a restaurant?

Which is the most popular service type which makes the restaurant more popular?

First, the raw comma separated values (.cvs) data will be loaded into a Python (NumPy) series. Secondly, Data Wrangling process would be carried out Third, there will be some data exploration. This will be completed mostly by loading plots in order to better understand the data with visualization.

### About the dataset
This dataset contains information about restaurants in Bangalore. Description of this dataset can be viewed on the Kaggle website, where the data was obtained (https://www.kaggle.com/himanshupoddar/zomato-bangalore-restaurants).

### Data Description
url: contains the url of the restaurant in the zomato website

address: contains the address of the restaurant in Bengaluru

name: contains the name of the restaurant

online_order: whether online ordering is available in the restaurant or not

book_table: table book option available or not

rate: contains the overall rating of the restaurant out of 5

votes: contains total number of rating for the restaurant as of the above mentioned date

phone: contains the phone number of the restaurant

location: contains the neighborhood in which the restaurant is located

rest_type: restaurant type

dish_liked: dishes people liked in the restaurant

cuisines: food styles, separated by comma

approx_cost(for two people): contains the approximate cost for meal for two people

reviews_list: list of tuples containing reviews for the restaurant, each tuple consists of two values, rating and review by the customer

menu_item: contains list of menus available in the restaurant

listed_in(type): type of meal

listed_in(city): contains the neighborhood in which the restaurant is listed
