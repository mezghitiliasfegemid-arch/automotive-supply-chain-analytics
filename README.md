# Supply Chain Management Dashboard (Power BI)

## Overview
Supply Chain Management for Cars in Power BI provides a comprehensive overview of the entire supply chain process for automotive companies. This includes tracking the flow of materials, components, and finished products from suppliers to manufacturers, distributors, and customers.

Using **Python, MS SQL Server, and Power BI**, companies can visualize key supply chain metrics such as inventory levels, production schedules, delivery performance, and supplier quality to optimize operations and reduce costs.


## Problem Statement
The automotive supply chain involves complex processes with numerous suppliers, manufacturers, distributors, and customers. Tracking and optimizing this network is critical for reducing costs, improving efficiency, and ensuring on-time delivery. This project addresses common challenges like siloed data and lack of visibility.

## Project Architecture & Workflow
1. **Data Gathering:** Connecting SQL Server databases with Kaggle APIs using Python (Jupyter Notebook & Pandas) to automate data ingestion.
2. **Data Cleaning:** Transforming data in Power Query Editor by filtering out unnecessary attributes and retaining core metrics.
3. **Data Modeling:** Building a Date Master table and establishing one-to-many relationships in Power BI, alongside dedicated DAX measure tables.
4. **Data Visualization:** Developing a multi-page interactive dashboard featuring Home, Order, Sales, and Customer Views with custom navigation.

## Tech Stack
* **Languages & Tools:** Python (Pandas, PyMySQL), MS SQL Server, Power BI
* **Key Topics:** ETL Pipeline, Data Mining, DAX Functions, Business Requirements Analysis