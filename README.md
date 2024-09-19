---

# Financial Data Analysis and AI-Powered Chatbot

This project was completed as part of the **BCG Gen AI Virtual Experience Program on Forage**. The goal of this project is to extract and analyze key financial data from 10-K and 10-Q documents, followed by the development of an AI-powered financial chatbot that provides insights and interacts with users to deliver complex financial information in a simple, user-friendly manner.

## Table of Contents
- [Project Overview](#project-overview)
- [Task 1: Financial Data Extraction and Analysis](#task-1-financial-data-extraction-and-analysis)
  - [Key Metrics](#key-metrics)
  - [Data Preparation and Analysis](#data-preparation-and-analysis)
- [Task 2: AI-Powered Financial Chatbot](#task-2-ai-powered-financial-chatbot)
  - [Chatbot Logic and Queries](#chatbot-logic-and-queries)
  - [How to Run the Chatbot](#how-to-run-the-chatbot)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Conclusion](#conclusion)

---

## Project Overview

The project consists of two main tasks:

1. **Task 1: Extracting and analyzing key financial data** from the client's 10-K and 10-Q documents. This involves understanding and interpreting the financial statements, identifying trends in key metrics, and preparing data for AI-driven applications.
   
2. **Task 2: Developing an AI-powered financial chatbot** capable of analyzing the financial data and providing meaningful insights. The chatbot was designed to communicate complex financial information interactively, responding to predefined user queries with relevant financial data.

---

## Task 1: Financial Data Extraction and Analysis

### Key Metrics

The key financial metrics that were extracted and analyzed from the company's 10-K and 10-Q documents include:

- **Total Revenue**
- **Net Income**
- **Total Assets**
- **Total Liabilities**
- **Cash Flow from Operating Activities**

Additionally, year-over-year percentage changes were calculated for each metric to assess the financial growth of the company over time.

### Data Preparation and Analysis

- The financial data for three companies—**Microsoft**, **Tesla**, and **Apple**—was extracted for the last three fiscal years.
- Year-over-year growth rates for the above metrics were calculated, providing insight into the companies' financial performance.
  
The data was then used to analyze the financial health of each company based on trends and changes across the key metrics, which would later form the foundation for the chatbot's responses.

---

## Task 2: AI-Powered Financial Chatbot

The second task involved developing a simple chatbot in Python that uses the extracted financial data to respond to user queries. The chatbot is designed to answer predefined queries related to the company's key financial metrics.

### Chatbot Logic and Queries

The chatbot is capable of responding to the following predefined queries:

1. **What is the total revenue?**
2. **How has net income changed over the last year?**
3. **What is the growth rate of total assets?**
4. **What is the liabilities growth rate?**
5. **How has cash flow from operating activities changed?**

The chatbot logic is implemented using basic Python `if-else` statements. The user inputs a company name (e.g., Microsoft, Tesla, or Apple) and one of the predefined queries, and the chatbot returns the corresponding financial data.

### How to Run the Chatbot

The chatbot can be run either as a command-line application or a simple web application using Flask. For simplicity, the project includes the command-line version of the chatbot.

---

## Installation

To set up the environment, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/amishksinghal/BCG_GenAI_JobSimulation.git
   ```

2. Install the required Python packages:
   ```bash
   pip install pandas
   ```

---

## Usage

To run the chatbot, navigate to the project directory and execute the Python script:

```bash
python chatbot.py
```

You'll be prompted to enter a company name (Microsoft, Tesla, Apple) and a query (e.g., "What is the total revenue?"). The chatbot will return the relevant financial information based on the extracted data.

Example interaction:

```
Enter the company name: Tesla
Enter your question: How has net income changed over the last year?
Output: The net income has changed by 18.96% over the last year.
```

---

## Conclusion

This project successfully demonstrates how AI can be used to simplify and communicate complex financial data. The chatbot developed for this project is a basic prototype, but it showcases the potential for integrating AI into financial applications to enhance user experience and provide actionable insights.

The **BCG Gen AI Virtual Experience Program on Forage** has provided an excellent opportunity to apply AI in financial data analysis and chatbot development, highlighting the intersection of data science, finance, and AI-driven user interaction.

For future work, this project can be extended by:
- Adding more predefined queries.
- Expanding the chatbot's scope to cover more companies and financial metrics.
- Developing a more advanced natural language processing (NLP) model to handle a wider range of user inputs.

---

### License

This project is open-source and available under the [MIT License](LICENSE).

---
