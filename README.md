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
