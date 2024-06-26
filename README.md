# SQL-IDE
# Introduction
This side project essentially is a practice of developping an IDE, and integrating API calls and learning how to make a functional website. It will be an SQL IDE that allows users to run SQL queries.

# Features
## Auto-Data Generation
In this project I wish to include a very important feature, automatically generated tables/ dummy data for users to run their queries. This stems from my annoyance with having to make dummy tables and data to test my SQL queries for school projects.

## Data View
As the user writes thier query, the IDE will create the dummy data, this will be viewable on a seperate tab, in a table format for easier comprehension.

## Table Manipulation
The generated table will be editable to allow the user to add edge cases to test their query. There will also be sliders to easily increase the size of the tables.

## Syntax Highlighting
While a query is being written, the IDE will highlight key works, syntax including but not limited to table names, column names and aliases. This will also display errors in the query generated by the user.

## Query Effeciency
The IDE will display a graph showing how time consuming and how many rows the query looked at during its execution, allowing users to get a grasp of how effecient thier queries are.

## Feedback Section
The site will include a small feed back section that will send any feedback users might have to an email address that I can monitor and keep track of.

# Scope
This project will not be a full fleged IDE it is simply meant to be a simple online resource where users can quickly test queries, this means there are some limitations on what the IDE is capable of, to elaborate if the query the user makes references values that are non-existent in their real world intended test the IDE cannot identify it and will generate dummy data regardless, it cannot point out SQL errors that are in relation to wrong references, only syntax errors

For this Initial trial it will not include the ability to save previous queries, or any sort of account logging to enable previous history. Hence there won't be any query sharing on the site itself. The site will also not include an auto fill function since the premise of the site is to assume your query is right, it is in this way it can generate dummy data.