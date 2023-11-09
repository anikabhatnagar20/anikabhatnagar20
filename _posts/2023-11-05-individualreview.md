---
toc: true
comments: false
layout: post
title: Invidudal Review 
description: This is a summary of how my past trimester went in AP CSP 1 
type: tangibles
courses: { compsci: {week: 12} }
---
# Team Teaches

## Data Abstractions: 
Variables:
-Variables act as placeholders for values and simplify code readability.

-They can hold different data types such as integers, booleans, lists, strings, and dictionaries.

-Variable names must be meaningful, without spaces, and follow naming conventions.

-Examples of good variable names: highScore, firstName, isRaining, phoneNumber.

-Use the print function to display variable values.
Different data types include:
-Integer: A whole number.
-Boolean: True or False value, often used in conditions.
-String: A sequence of characters.
-Changing variable values is common and will reflect the most recent assignment.

Lists & Strings:
-Lists and strings store multiple values in a single variable.

-They use natural-number indices for access, starting at 0 in Python.

-Data abstraction involves hiding complex details, presenting only necessary information.

-Lists can contain various data types, and their elements are ordered.

-Strings are ordered sequences of characters.

-Abstraction can be implemented using classes, abstract classes, interfaces, and more.

-Examples are provided for accessing string characters and 
list elements by index.

-The json module allows conversion between strings and JSON format.

-Built-in functions like type(), isinstance(), and dir() help inspect variables and objects.
Practice exercises include creating a Person class and manipulating lists and dictionaries.

## Algorithms:

Mathematical Expressions:
-An algorithm is a step-by-step procedure for calculations, acting like a recipe.

-Algorithms involve sequencing (order of operations), selection (conditional statements like if/else), and iteration (loops like for/while).

-Algorithms can be represented using flowcharts or pseudocode.

-Examples given include calculating factorials and solving mathematical functions using Python code.

-Mathematical operations in Python include addition (+), subtraction (-), multiplication (*), division (/), and modulus (%).

-The modulus operation gives the remainder of a division and follows the same precedence as multiplication and division in PEMDAS.

-Practice exercises involve solving math problems and implementing basic arithmetic operations using Python.

Strings:
-Strings are sequences of characters that can include letters, numbers, and symbols.

-Substrings are parts of larger strings.

-Python has built-in string functions like len() for length and the + operator for concatenation.

-Example code snippets demonstrate how to work with strings, including finding lengths, concatenating first and last names, and extracting substrings.

-Palindromes are strings that read the same forwards and backwards, with provided Python code to check for them.

-Pseudocode is presented as a way to outline algorithms without specific syntax, contrasted with Python code.

-Concepts of logic gates are introduced, which are fundamental to computing and digital circuits.

-De Morgan’s Laws are explained, showing how to logically switch between AND/OR statements.

-Homework exercises suggest creating an algorithm to compute values from the Fibonacci sequence.

## Boolean:

If Statements/Conditionals:
-If statements run a portion of code if a condition is true.

-In Python, the syntax is if (condition): #code.

-An example provided is using the modulo operation to check if a number is even or odd.

Boolean Expressions:
-The Boolean data type can only be true or false.

-Booleans are used to hold truth values in logical operations and control flow.

-In Python, booleans are defined with True or False, and their type can change if they are assigned non-boolean values.
-Relational Operators are used in boolean expressions to -compare values:
== for equality,
!= for inequality,
> for greater than,
< for less than,
>= for greater than or equal to, and
<= for less than or equal to.

College Board Pseudo Code:
-Pseudo code is not an actual programming language but a simplified way to represent an algorithm.

-It uses natural language mixed with programming-like constructs to describe the steps of an algorithm without specific syntax.

-The review provides examples of pseudo code and its equivalent Python code, particularly for expressing logic gates and Boolean operations.

-Logic gates discussed include AND, OR, NOT, NAND, NOR, and XOR, each with real-life scenarios and the pseudo code representation alongside Python code examples.

## Iteration:

Loops:
-Iterate over sequences like lists, tuples, strings, or ranges.

-Execute a block of code for each element in the sequence.

-Run as long as a given condition is true.
Useful for when the number of iterations is not predetermined.

-Employ loops to traverse and manipulate lists and dictionaries.
-Use the range() and len() functions for indexed iteration over a sequence.

Nested If Statements:
Conditional statements can be placed inside loops to perform complex checks.

Try/Except:
Error handling within loops to manage exceptions and maintain code flow.

Continue and Break:
Use continue to skip to the next iteration and break to exit the loop entirely.

Nested For Loops:
Place one loop inside another to perform multi-level iteration, such as iterating over nested lists.

Recursion:
Recursion can be used as an alternative to loops, where a function calls itself to repeat the execution.

## Developing Algorithms:

Basic Concepts:
-An algorithm is a step-by-step procedure for solving a problem with a clear sequence of actions.

-Algorithms are vital because they provide a systematic method for solving problems that can be applied generally without human intervention.

Conditional Logic in Algorithms:
-Conditional statements (if/else) are used to execute different code based on certain conditions.

-Booleans are used within conditionals to represent true or false states, determining the flow of an algorithm.

Pseudo Code and Comparison:
-Pseudo Code 1 and Pseudo Code 2 differ in their conditional structure. The first uses nested if/else statements, ensuring only one condition is met. The second uses separate if statements, allowing multiple conditions to be met independently.

-The correct conditional structure is important for an algorithm to produce the intended output.

Specific Algorithms:
-The lesson introduces algorithms for daily decision making based on the weather, discount calculations, and the famous 

-Collatz Conjecture sequence, showcasing the use of selection and iteration.

-The Collatz Conjecture example illustrates an algorithm that manipulates a number until it reaches 1, demonstrating the use of loops and conditional logic.

Algorithm Development:
-Students are encouraged to develop algorithms using pseudo code, conditionals, booleans, loops, and error handling.

-The exercises help students practice algorithm development with real-world scenarios, like choosing clothing based on temperature or calculating discounted prices.

Error Handling and Logic Flows:

-Algorithms must account for various conditions and potential inputs, handling errors and unexpected values gracefully.

-Logical flow and structure in algorithms are emphasized to ensure they perform as expected under all defined conditions.
These key points aim to build a strong foundation in understanding and developing algorithms, which is essential for problem-solving in computer science and programming.


## Python Lists:

-Ordered collections that can hold a variety of data types.
Can be modified (mutable) with methods like append for adding items.

-Elements are accessed via zero-based indexing (aList[0] for the first element).

Operations on Lists:
-Create a list with [] or by listing elements within [element1, element2, ...].

-Add items using append(element).

-Delete items with del aList[index].

-Assign the contents of one list to another aList = bList.

-Determine length with len(aList).

List Iteration:

-Loop through a list to modify or perform actions using for loops.

-Range function is often used to loop through list indices.

Search Algorithms:
-Linear search checks every element until the target is found, with a complexity of O(n).

-Binary search repeatedly divides the sorted list in half to find an item, with a complexity of O(log n).

## Procedures:
-Procedures are blocks of code that perform operations and may return values.

-Functions are collections of code that are called by name, can take parameters (inputs), perform tasks, and return values (outputs).

-Return values are the results produced by functions, which can be printed or assigned to variables.

Function Components:
-A function declaration includes the def keyword, the function's name, and any parameters.

-Parameters are inputs given to functions, and when values are passed, they are known as arguments.

-Functionality is the block of code within a function that performs actions.

-A return value is the output a function produces.

Classes:
-A class is a blueprint for creating objects (instances) with specific attributes and methods.

-A constructor method (__init__) is used for initializing instance variables.

-Getter and setter methods manage access to an object's attributes.

-The __str__ method defines how an object is represented as a string.

Working with Classes and Functions:
To create instances of classes with attributes and perform operations, you would define a class and then instantiate it with specific attributes.

## Simulations:

-A simulation uses computer software to model the behavior of a real-world system.

-It allows exploration of phenomena without real-world constraints.

Python and Randomness:
-Python’s random module is used to generate random numbers, simulating events like dice rolls and coin tosses.

-Simulations incorporate randomness to model variability and uncertainty.

Developing Procedures:
-Procedures, also known as functions or methods, execute statements to produce return values.

-Parameters are inputs specified by arguments within procedures.

Mathematics in Simulations:
-Mathematical equations and algorithms are vital for simulating physical phenomena, such as an object's fall due to gravity.

Loops in Simulations:
-Loops, such as for loops, are used to repeat actions within simulations, allowing for the modeling of iterative processes.


# Key Commit 

from flask import Blueprint, jsonify, request
import pandas as pd
import yfinance as yf
import plotly.graph_objs as go
from datetime import datetime
from flask_restful import Api, Resource
import numpy as np
from flask_cors import CORS
import tensorflow as tf
from tensorflow import keras
from tensorflow.keras import layers
import random
stock_api = Blueprint('stock_api', __name__, url_prefix='/api/stocks')
api = Api(stock_api)
CORS(stock_api)
def get_stock_graph(stock_name):
    end_date = datetime.now()
    start_date = end_date - pd.Timedelta(days=4856)

    df = yf.download(stock_name, start=start_date, end=end_date)

    graph = go.Figure(data=go.Candlestick(x=df.index,
                                          open=df['Open'],
                                          high=df['High'],
                                          low=df['Low'],
                                          close=df['Close'],
                                          name=stock_name))
    graph.update_layout(title=f'{stock_name} Stock Price',
                        xaxis_title='Date',
                        yaxis_title='Price')

    graph_data = graph.to_dict()
    graph_data['data'][0]['x'] = graph_data['data'][0]['x'].astype(
        str).tolist()
    graph_data['data'][0]['open'] = graph_data['data'][0]['open'].tolist()
    graph_data['data'][0]['high'] = graph_data['data'][0]['high'].tolist()
    graph_data['data'][0]['low'] = graph_data['data'][0]['low'].tolist()
    graph_data['data'][0]['close'] = graph_data['data'][0]['close'].tolist()
    return graph_data
class _ReadStockGraph(Resource):
    def get(self, stock_name):
        graph = get_stock_graph(stock_name)
        return graph
class _GetLatestStockData(Resource):
    def get(self, stock_name):
        try:

            stock = yf.Ticker(stock_name)
            latest_data = stock.history(period="1d")

            if latest_data.empty:
                return jsonify({'error': 'No data found for the provided stock ticker.'}), 404

            latest_data = latest_data[['Open', 'High', 'Low', 'Close']]
            latest_data = latest_data.rename(
                columns={'Open': 'open', 'High': 'high', 'Low': 'low', 'Close': 'close'})

            latest_data_dict = latest_data.to_dict(orient='records')[0]

            for key, value in latest_data_dict.items():
                if isinstance(value, (float, int)):
                    latest_data_dict[key] = round(value, 2)

            return jsonify(latest_data_dict)
        except Exception as e:
            return jsonify({'error': str(e)}), 500
api.add_resource(_GetLatestStockData, '/latest_data/<string:stock_name>')
api.add_resource(_ReadStockGraph, '/stock_graph/<string:stock_name>')

It grabs the stock data for the latest business day by sending a request to the Yahoo Finance API and turning it into a JSON string that can be accessed by the frontend to create a list of the data from the inputted stock using a fetch request.

# Reflection

## Issues Faced 
- Passion Project: At first we had a little trouble deciding the specifics of our project. We wanted something finance-related, our opinions on its purpose varied. We were split prettty half and half on if we should make it a tax organizer or a stock market app. Eventually, we focused on creating an app that teaches beginners about the stock market.
-Passion Project: Many teams struggle to connect their frontend and backend, and our team did too. We had to adjust our frontend to match the backend, which helped us all learn more about the code.
- Personal: I had really bad storage issues to the point where I could not download the needed apps for this class. I had only around 7 gbs left. I had to go through and delete so many things off of myt Macbook to the point where I once acciedntly deleted all my contacts!



## What I learned throughout Trimester 1 
- Learning how to use Github and VS code

- Fundementals for python 

- How to work with a partner and small group 

- How to deal with an issue, ask for help


## Hopes For Trimester 2 
- Fixing problems in programs by stopping them at certain points to find errors.
- Getting better at computer science by learning about the data that runs in the background.
- Discovering more about how to connect different parts of a website and make them work together.
- Becoming more familiar with using the text-based control of a computer.

## Advice I would give to someone who wants to take CSP 
- Make sure you surround yourself with people you know can work, and wont distract you. 

- Stay on task, this class moves pretty fast and missing information can be really hard to deal with since we are still learning the basics. 

- Always be ready to put in extra effort outside of class. I didn't really have a background with coding so I would have to work at home to either learn the concepts better or finish up some classwork/homework on my own. 

### Overall this has been a very fun class where I learned many things and I am very excited to continue doing so next trimester. 




