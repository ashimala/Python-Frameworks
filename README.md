# Python-Frameworks-Assignment-Week-8
# Assignment Overview

This is a basic analysis of the CORD-19 research dataset and creating a simple Streamlit application to display your findings. This simplified version focuses on fundamental data analysis skills .

#Objectives


Practice loading and exploring a real-world dataset

Basic data cleaning techniques

Create meaningful visualizations

Build a simple interactive web application

Present data insights effectively

#Dataset Information

We'll work with the metadata.csv file from the CORD-19 dataset, which contains information about COVID-19 research papers. The file includes:

Paper titles and abstracts

Publication dates

Authors and journals

Source information

You can download the dataset from Kaggle:
https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge

Note: The full dataset is very large. For this assignment, we'll work with just the metadata file or a sample of the data.

#Required Tools

Python 3.7+

pandas (data manipulation)

matplotlib/seaborn (visualization)

Streamlit (web application)

Jupyter Notebook (optional, for exploration)


Install the required packages:

bash
pip install pandas matplotlib seaborn streamlit

#Step-by-Step Tasks
Part 1: Data Loading and Basic Exploration (2-3 hours)

Download and load the data

Download only the metadata.csv file from the CORD-19 dataset

Load it into a pandas DataFrame

Examine the first few rows and data structure

Basic data exploration

Check the DataFrame dimensions (rows, columns)

Identify data types of each column

Check for missing values in important columns

Generate basic statistics for numerical columns

#Part 2: Data Cleaning and Preparation (2-3 hours)

Handle missing data

Identify columns with many missing values

Decide how to handle missing values (removal or filling)

Create a cleaned version of the dataset

Prepare data for analysis

Convert date columns to datetime format

Extract year from publication date for time-based analysis

Create new columns if needed (e.g., abstract word count)

#Part 3: Data Analysis and Visualization (3-4 hours)

Perform basic analysis

Count papers by publication year

Identify top journals publishing COVID-19 research

Find most frequent words in titles (using simple word frequency)

Create visualizations

Plot number of publications over time

Create a bar chart of top publishing journals

Generate a word cloud of paper titles

Plot distribution of paper counts by source

#Part 4: Streamlit Application 

Build a simple Streamlit app

Create a basic layout with title and description

Add interactive widgets (sliders, dropdowns)

Display your visualizations in the app

Show a sample of the data

Example app structure:

python
import streamlit as st
import pandas as pd
import matplotlib.pyplot as plt

st.title("CORD-19 Data Explorer")
st.write("Simple exploration of COVID-19 research papers")

# Add interactive elements
year_range = st.slider("Select year range", 2019, 2022, (2020, 2021))
# Add visualizations based on selection
Part 5: Documentation and Reflection

Document your work

Write comments in your code

Create a brief report of your findings

Reflect on challenges and learning




