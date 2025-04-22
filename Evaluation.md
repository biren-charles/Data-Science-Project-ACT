ACT DATASCIENCE PROJECT by Charles Biren, Andre Oliveira & Tomas Marques
Improving Data Quality and Extracting Insights from Online Retail Transactions: A Structured Data Science Approach

1. Introduction
In recent years, the field of data science has evolved into an essential pillar of modern technology and business analysis. The increasing availability of digital data, along with advances in computing power and algorithms, has enabled organizations to uncover meaningful patterns, predict future behaviors, and make data-driven decisions. Central to this field is the ability to efficiently preprocess and analyze data — especially structured data originating from transactional systems.
This project applies core data science techniques to a real-world transactional dataset from a UK-based non-store online retail company. The dataset contains all sales transactions between December 1, 2010, and December 9, 2011, capturing crucial fields such as invoice numbers, item descriptions, quantities, prices, and customer identifiers.

2. Project Aim 
The aim of this project is to demonstrate the impact of data preprocessing on data quality improvement and to extract useful business insights through exploratory data analysis (EDA). We will also incorporate course concepts such as regular expressions, edit distance, and dictionary-based feature extraction to enrich and clean product-related textual data.

Our analysis focuses on:
Cleaning and transforming structured data to ensure accuracy and consistency
Handling missing values, duplicates, and outliers
Extracting new features (e.g., revenue per transaction, product frequency)
Visualizing patterns in customer behavior and sales performance
Applying NLP techniques such as regular expressions and vocabulary extraction on item descriptions

3. Dataset Overview
The dataset consists of approximately 500,000 transaction records and includes the following fields:
InvoiceNo – Unique identifier for each transaction
StockCode – Unique product code
Description – Name of the product
Quantity – Number of units purchased
InvoiceDate – Date and time of the transaction
UnitPrice – Price per unit of product
CustomerID – Unique identifier for each customer
Country – Country of customer origin
Given the commercial nature of the data, this project provides a practical platform to simulate data preparation and visualization processes used in data science projects across industries such as e-commerce, marketing, and retail analytics.

4. Course Relevance
This project integrates key components from the Data Science course:
Data Preprocessing (Structured): Cleaning, transformation, integration, and feature engineering will be used to enhance data quality and analysis capability.
Regular Expressions: Applied to clean product descriptions and extract structured patterns (e.g., codes, keywords).
Edit Distance: Optionally used to identify spelling inconsistencies or near-duplicate product entries.
Dictionaries and Vocabulary: Word frequency analysis will be performed on product descriptions to detect common items or categories.

5. Next Steps
The next phase of the project will include:
Implementation of structured data cleaning and transformation techniques
Use of regular expressions for textual data preprocessing
Exploratory data analysis with visualizations
Summary of insights with potential implications for marketing and inventory management