# CSCA-5622: Supervised Learning - Final Project/Exam

## Introduction

Vietnam is a developing country in Southeast Asia, with a population of about 100 million people and is one of the fastest growing economies in recent years. Along with economic development and rapid urbanization, housing prices in urban areas have also continuously increased and become very expensive for most people. Housing prices are always one of the issues of great concern to many families.

In this assignment, I'm going to build a simple supervised learning model to predict housing prices in Ho Chi Minh city, the economic and largest city in Vietnam. For the purpose of price prediction, I'm going to use sklearn regression methods. Various analytical techniques are also used to explore and clean data in the early stages.

#### About the dataset:

I will be using the  **'House Price Prediction Dataset Vietnam - 2024'** dataset which was downloaded from Kaggle (https://www.kaggle.com/datasets/nguyentiennhan/vietnam-housing-dataset-2024/data) for the purpose of this study.

According to the dataset description from Kaggle's website: This dataset contains information about various housing properties in Vietnam. It includes detailed attributes of each property, such as its location, physical characteristics, and legal and furnishing status, along with the price. 

The data was crawled from batdongsan.vn, which is one of the largest real estate listing websites in Vietnam.

Features:
* Address: The complete address of the property, including details such as the project name, street, ward, district, and city.
* Area: The total area of the property, measured in square meters.
* Frontage: The width of the front side of the property, measured in meters.
* Access Road: The width of the road providing access to the property, measured in meters.
* House Direction: The cardinal direction the front of the house is facing (e.g., East, West, North, South).
* Balcony Direction: The cardinal direction the balcony is facing.
* Floors: The total number of floors in the property.
* Bedrooms: The number of bedrooms in the property.
* Bathrooms: The number of bathrooms in the property.
* Legal Status: Indicates the legal status of the property, such as whether it has a certificate of ownership or is under a sale contract.
* Furniture State: Indicates the state of furnishing in the property, such as fully furnished, partially furnished, or unfurnished.

Target: 
* Price: The price of the property, represented in billions of Vietnamese Dong (VND).

