# Simple Financial Chatbot

## Overview
This simple chatbot is designed to provide financial information about three companies: Microsoft, Tesla, and Apple. It answers predefined queries related to total revenue, net income growth, asset growth, liabilities growth, and cash flow growth based on the data provided.

## Predefined Queries
The chatbot can respond to the following queries:
1. What is the total revenue?
2. How has net income changed over the last year?
3. What is the growth rate of total assets?
4. What is the liabilities growth rate?
5. How has cash flow from operating activities changed?

## How it Works
- The chatbot uses basic `if-else` logic to match the user input with predefined queries.
- The data for each company is stored in a dictionary, and the chatbot fetches the relevant information based on the company and query input.

## Limitations
- The chatbot can only handle predefined queries and cannot process custom financial questions.
- Currently, it is limited to three companies and five predefined financial metrics. Expansion would require manual addition of more companies and queries.
