# Real Estate Price Prediction
![images](https://github.com/febinjhon0/real_estate_price_prediction/assets/137596876/2e94ce73-ae0f-464b-82e8-83cd71d8d1fc)

## Abstraction
Housing price is an important aspect that reflects economic growth. Also, housing affordability is a major social and economic issue that has attracted the attention of policymakers, urban researchers and planners in many countries. There are many other factors that make house prices an important indicator to be analyzed deeply. For this project, let’s assume that the real estate company has asked you to build a pipeline so that you can predict house prices accurately. This will help them stay competitive while not losing too much profit. So, let’s get started with that.
                                               People looking for a new house tend to be more conservative towards the budget and market strategies. They always try to optimize the budget which matches their requirements and needs. Ideal home is something which fulfills and matches the customer requirement with an appropriate budget. So, price prediction is a very important thing when it comes to planning a budget. Mostly people approach a real estate manager or an agent who predicts price. This is helpful but it also increases your expense because you need to provide commission to the manager. Instead, when we have a website which predicts price for us, the time is saved and money too. It becomes easy for the customer to access it.

## Introduction

![Screenshot 2024-05-21 111625](https://github.com/febinjhon0/real_estate_price_prediction/assets/137596876/0040f5e5-e0af-40d9-ac07-2cd5c0fa53ed)

There comes a problem to build a model that predict property price based on certain features such as bedroom, bathroom, sq feet, location etc. So, the task is to build a website using HTML/CSS/JavaScript that predicts estimated price for your house.

In terms of project architecture, we are going to take a home set from Kaggle.com. Using that data set we will make a machine learning model. While building the model we are going to cover some data science concepts such as data cleaning, feature engineering, Dimensionality reduction, outliner detection etc.

Once the model is built, we are going to export it to a pickle file and then we will write a python flask server which will consume this pickle file and do price prediction for us.

This python flask server will expose HTTP endpoints for various requests and the UI written in HTML/CSS/JavaScript will make HTTP Get and Post calls.

In terms of tools and technology we will use python as programming language, Pandas for data cleaning, Matplotlib for data visualization, Sklearn for model building, python flask for a back-end server, HTML/CSS/JavaScript for building our website.
