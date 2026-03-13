# Dennis Sila Muia- *AI Student at IYF We Can Academy.*

# week4-ai-assignment

# Part 1: Data Foundations
## Question 1

## What is Data?
## Explain in your own words.

Data is information that can be text, numbers or images. It can be collected, stored, analysed and measured.

## give two Examples.

1. An example of data is the attendance register of students in a class room containing names and student registration no.'s.
2. The census results for a given town's population for use in demography to show it's population's trends in birth-rate, death-rate 
   and migration; the results also show demographics such as age, gender, income, occupation and location.
   
## Question 2 
### Explain the difference between:

### Structured Data+

It is organised data that is stored in rows and columns for ease of storage, searching and analysing in relational databases.

### Unstructured Data

It is information that is lacks order i.e. lacks a predefined format or data model, making it difficult to store and process in traditional relational databases.

### Give two Examples of each.

## Structured data:
Relational Databases containing customers names, addresses and phone numbers in an SQL table. 
Spreadsheets/CSV Files.
Web Server Logs that display Date, Time, and IP address of website visits.

## Unstructured data:
emails, social media posts.


## Question 3
### What is a  Schema?
A schema is a technical blueprint in computing defining database structure (tables, fields, relationships). It helps simplify complex information, allows for quick processing

### Explain using a simple example:

CREATE TABLE Customers (

    customer_id INT NOT NULL PRIMARY KEY,
    first_name VARCHAR(50),
    last_name VARCHAR(50),
    email VARCHAR(100),
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);


#### Key Components of above Simple Schema:
Table Name: The entity being described (e.g., Customers).
Field/Column Names: Specific attributes (e.g., first_name, email).
Data Types: Defines the type of data (e.g., INT for integers, VARCHAR for text).
Constraints: Rules for data, such as PRIMARY KEY for uniqueness or NOT NULL.

# Part 2: Python Basics
## (As done in the python file: assignment.py)



Question 4

Write a Python program that prints the following message:
Hello AI Students

Question 5

Create the following variables in Python:
name
age
city
Print them so the output looks like this:

Name: John
Age: 20
City: Nairobi

Question 6
Create a list of five programming languages.

Example:
["Python", "Java", "C++", "JavaScript", "Go"]

Print the first language in the list.

Question 7
Create a dictionary  with the following student information:
Name
Age
Course
Print the student's name.

Example dictionary format:
student = {
"name": "John",
"age": 21,
"course": "AI"
}

# Bonus Question (Optional)
## Explain the difference between:
### A list
### A dictionary

A list Stores an ordered sequence of items. Items are accessed by their position (index), starting from 0. Ideal for collections where the order of items matters or when you need to access items by position.	

A dictionary Stores data in key-value pairs. Items are accessed by their unique keys. Ideal for collections where you need to associate data points (like a name with an age) and quickly look up information by a specific identifier.
