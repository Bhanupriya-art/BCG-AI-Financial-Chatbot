<img width="1004" height="709" alt="image" src="https://github.com/user-attachments/assets/325a84ac-1dd6-4720-a8c2-3498ffedd97c" />

# BCG AI Financial Chatbot

## Overview

This project was developed as part of the Boston Consulting Group (BCG) Virtual Experience Program by Forage. The objective was to design and implement a rule-based AI financial chatbot that transforms structured financial data into interactive, actionable insights.

The chatbot integrates financial data for Microsoft, Tesla, and Apple (2023–2025) and responds to predefined analytical queries using Python and pandas.

---

## Project Objectives

- Extract and analyze structured financial data
- Develop a rule-based chatbot using predefined financial queries
- Integrate financial insights into an interactive command-line system
- Demonstrate foundational AI chatbot development principles

---

## Technologies Used

- Python 3
- pandas (Data analysis and data handling)
- Rule-based logic (if-else conditional matching)
- Command-line interface (CLI)

---

## Dataset Information

The dataset includes financial data for:

- Microsoft
- Tesla
- Apple

### Financial Metrics:
- Revenue (USD Millions)
- Net Income (USD Millions)
- Assets (USD Millions)
- Liabilities (USD Millions)
- Operating Cash Flow (USD Millions)

### Time Period:
- 2023
- 2024
- 2025

---

## How the Chatbot Works

1. Data Loading and Cleaning  
   - Loads financial data from a CSV file  
   - Removes empty rows  
   - Converts financial columns to numeric format  
   - Handles missing values  

2. Rule-Based Query Matching  
   - Uses predefined `if-else` logic  
   - Matches exact user queries to specific financial functions  

3. Financial Data Processing  
   - Performs calculations such as totals, averages, and year-over-year changes  
   - Returns structured financial insights  

4. Error Handling  
   - If a query is not recognized, the chatbot informs the user  
   - Suggests supported predefined queries  

---

## Supported Queries

The chatbot currently responds to the following predefined queries:

- What is the total revenue of Microsoft?
- How has Apple's net income changed over the last year?
- Which company has the highest average revenue?
- Compare Tesla and Microsoft revenue.
- What was Apple's net income in 2023?


