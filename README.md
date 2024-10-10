# YouTube-Data-Harvesting-and-Warehousing-using-SQL-and-Streamlit
# Project Overview: YouTube Data Dashboard

## Introduction
This project focuses on building a simple dashboard using **Streamlit** to retrieve YouTube channel data via the **YouTube API**. The collected data is stored in a SQL database (warehousing) using the **XAMPP control panel**. Users can query the data using SQL and visualize it within the Streamlit application.

### Domain
📱 **Social Media**

### Skills Takeaway
- Python Scripting
- Data Collection
- Streamlit
- API Integration
- Data Management with SQL

---

## Overview

### 🌾 Data Harvesting
Utilize the YouTube API to collect:
- Video details
- Channel information
- Playlists
- Comments

### 📥 Data Storage
- Set up a local MySQL database using **XAMPP**.
- Create tables to store the harvested YouTube data.
- Use SQL scripts to insert the collected data into the database.

### 📊 Data Analysis and Visualization
- Develop a Streamlit application for interaction with the SQL database.
- Create visualizations and perform analyses on the stored YouTube data.

---

## Technology and Tools
- **Python**: 3.12.2
- **XAMPP**
- **MySQL**
- **YouTube API**
- **Streamlit**
- **Plotly**

---

## Packages and Libraries
- **google-api-python-client**
  ```python
  import googleapiclient.discovery
  from googleapiclient.errors import HttpError

  # YouTube Data Harvesting and Warehousing using SQL and Streamlit

## Plotly

## 📚 Packages and Libraries
- **google-api-python-client**
  ```python
  import googleapiclient.discovery
  from googleapiclient.errors import HttpError
  ```
- **mysql-connector-python**
  ```python
  import mysql.connector
  ```
- **SQLAlchemy**
  ```python
  from sqlalchemy import create_engine
  ```
- **Pandas**
  ```python
  import pandas as pd
  ```
- **Streamlit**
  ```python
  import streamlit as st
  ```
- **streamlit_option_menu**
  ```python
  from streamlit_option_menu import option_menu
  ```
- **Plotly**
  ```python
  import plotly.express as px
  ```
- **Pillow**
  ```python
  from PIL import Image
  ```

---

## 📘 Features

### 📚 Data Collection
The data collection process involved retrieving various data points from YouTube using the YouTube Data API, including:
- Channel information
- Video details
- Playlists
- Comments

### 💾 Database Storage
The collected YouTube data was transformed into pandas DataFrames. Before that, a new database and tables were created using the **XAMPP control panel**. With the help of **SQLAlchemy**, the data was inserted into the respective tables. The database could be accessed and managed in the MySQL environment provided by XAMPP.

### 📋 Data Analysis
Using YouTube channel data stored in the MySQL database, performed MySQL queries to answer 10 questions about the YouTube channels. When selecting a question, the results will be displayed in the Streamlit application in the form of tables.

### 📊 Data Visualization
Using YouTube channel data stored in the MySQL database, the data was presented in visually appealing charts and graphs using **Plotly**. When selecting a query, the visualization is displayed in the Streamlit application.

---

## 📘 Usage Instructions
1. Enter a YouTube channel ID or name in the input field in the Data Collection option from the sidebar menu.
2. Click the **"View Details"** button to fetch and display channel information.
3. Click the **"Upload to MySQL"** button to store channel data in the SQL database.
4. Select Analysis and Visualization options from the sidebar menu to analyze and visualize data.

---

## Demo Video
Watch the demo here: [YouTube Demo](https://youtu.be/qsHF35eShKk)

---

## Contact Information
- **LinkedIn**: [www.linkedin.com/in/sun-raj-2930301a2](www.linkedin.com/in/sun-raj-2930301a2)
- **Email**: sunraj2525@gmail.com

