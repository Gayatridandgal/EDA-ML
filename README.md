# EDA-ML
### Zomato Data Analysis & Simple Chatbot

## Overview
This project includes basic Exploratory Data Analysis (EDA) on the Zomato dataset and a simple chatbot designed for beginners. The goal is to extract insights from restaurant data and create a basic chatbot to assist users with common queries related to restaurants.

## Features
### 1. **Exploratory Data Analysis (EDA)**
- Data Cleaning (handling missing values, removing duplicates)
- Statistical Summary of Features
- Visualizations:
  - Distribution of restaurant ratings
  - Most popular cuisines
  - Price range vs. ratings
  - Geographic distribution of restaurants

### 2. **Simple Chatbot**
- Built using basic NLP techniques
- Can answer questions such as:
  - "Which is the best-rated restaurant?"
  - "What are the top cuisines?"
  - "Find me a budget-friendly restaurant."
- Uses keyword-based matching to respond to user queries

## Dataset
The dataset contains attributes such as:
- `Restaurant Name`
- `Cuisines`
- `Location`
- `Average Cost for Two`
- `Rating`
- `Votes`

## Installation
To run this project, install the required dependencies:
```bash
pip install pandas numpy matplotlib seaborn nltk
```

## Usage
1. Run the EDA script to explore the dataset:
```bash
python eda_zomato.py
```
2. Start the chatbot:
```bash
python chatbot.py
```
3. Interact with the chatbot and explore restaurant data!

## Results
- Key insights about restaurant trends
- A beginner-friendly chatbot to assist with restaurant searches
- Visualizations to understand food trends

