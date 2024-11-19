# Unit 3 - Data for Social Good Project 

## Introduction 

Software engineers develop programs to work with data and provide information to a user. Each user has different needs based on the information they are looking for from data. Your goal is to create a data analysis program for your user that stores and analyzes data to provide the information they need. 

## Requirements 

Use your knowledge of object-oriented programming, one-dimensional (1D) arrays, and algorithms to create your data analysis program: 
- **Write a class** – Write a class to represent your user or business and store and analyze their data with no-argument and parameterized constructors. 
- **Create at least two 1D arrays** – Create at least two 1D arrays to store the data that your user needs information about. 
- **Write a method** – Write a method that finds or manipulates the elements in a 1D array to provide the information your user needs. 
- **Implement a toString() method** – Write a toString() method that returns general information about the data (for example, number of values in the dataset). 
- **Document your code** – Use comments to explain the purpose of the methods and code segments and note any preconditions and postconditions. 

## User Story 

Include your User Story you analyzed for your project here. Your User Story should have the following format: 

> As a new record shop business owner, <br> 
> I want to create a successful record shop business, <br> 
> To do this, I must know what records/albums are popular. 

## Dataset 

Overall, our dataset provides us information on what genres or artists are popular, therefore we selected the top 5000 of all time. With the amount of information present within this dataset, we’ll be able to deduce how many albums of a certain type of genre or from a certain artist we should stock up with.


Dataset: https://www.kaggle.com/datasets/michaelbryantds/top-5000-albums-of-all-time-rateyourmusiccom 
- **Album** (String) - Our dataset includes information on 5000 different albums. 

- **Genre** (int) - We have implemented 5000 different genres available to search for.

- **Artist** (double) - There are 5000 artists that customers can select from. 

- **Average Rating** (double) - 5000 average ratings from individuals worldwide that provide an additional opinion for customers.


## UML Diagram


![alt text](<(Unit 3) UML Diagram-1.png>)

## Description 

One specific part of the code utilizes our instance variables of the UserStory (describes a feature, or requirement, that is to be implemented and is independent of a specific tool), loading specific messages from the specified text files. We called things through the parameters (allows a program to specify the details of how a function works when it is called, rather than when the program is defined), representing a welcome message based on the which choice the user chose.
