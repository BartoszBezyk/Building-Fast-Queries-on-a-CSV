# Building-Fast-Queries-on-a-CSV
Classes and algorithms in data

This is one of dataquest.io guided projects.

Data 'Laptops' that we will gonna use originally came from [here](https://www.kaggle.com/datasets/muhammetvarl/laptop-price). This is short description of rows:

You can find the data that U used [here]
(http://bioinf-mw.bihz.upwr.edu.pl/students-data/laptops.csv)
ID: A unique identifier for the laptop.
Company: The name of the company that produces the laptop.
Product: The name of the laptop.
TypeName: The type of laptop.
Inches: The size of the screen in inches.
ScreenResolution: The resolution of the screen.
CPU: The laptop CPU.
RAM: The amount of RAM in the laptop.
Memory: The size of the hard drive.
GPU: The graphics card name.
OpSys: The name of the operating system.
Weight: The laptop weight.
Price: The price of the laptop.

The goal of this guided project is to create a class that represents our inventory. The methods in that class will implement the queries that we want to answer about our inventory. We will also preprocess that data to make those queries run faster.

Here are some queries that we will want to answer:

Given a laptop id, find the corresponding data.
Given an amount of money, find whether there are two laptops whose total price is that given amount.
Identify all laptops whose price falls within a given budget.
