# Database LLM

## Overview
Database LLM is a project that integrates a language model with SQL databases to analyze T-shirt sales data. This project utilizes LangChain to provide intelligent querying capabilities, enabling users to interact with the database using natural language prompts.

## Features
- **Natural Language SQL Queries**: Convert user queries into SQL statements using a language model.
- **Few-Shot Learning**: Implements examples to enhance the model's SQL query generation accuracy.
- **Data Visualization**: Provides insights into T-shirt sales data using interactive notebooks.
- **Database Integration**: Uses a structured database to store and retrieve sales data efficiently.

## Project Structure
```
Database_LLM/
│-- .env                     # Environment variables
│-- atliq_tees.png           # Project-related image
│-- few_shots.py             # Few-shot learning examples for SQL queries
│-- langchain_helper.py      # LangChain utility functions
│-- main.py                  # Main application script
│-- README.md                # Project documentation
│-- requirements.txt         # Dependencies
│-- t_shirt_sales_llm.ipynb  # Jupyter notebook for analysis
│-- database/
│   └── db_creation_atliq_t_shirts.sql  # Database schema creation script
```

## Usage
- Execute SQL queries using natural language.
- Run `t_shirt_sales_llm.ipynb` for an interactive data analysis experience.
- Modify `few_shots.py` to enhance query accuracy.

## Technologies Used
- Python
- LangChain
- SQL
- Jupyter Notebook


