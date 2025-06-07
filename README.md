# 🚀 SpaceX Launch Interactive Dashboard

## 📌 Project Description
This project builds an interactive dashboard application using Plotly Dash for real-time visual analytics on SpaceX launch data. The dashboard allows users to explore launch success metrics across different launch sites, payload ranges, and booster versions with dynamic charts and user input controls.

---

## 🎯 Objectives

- Build a Plotly Dash dashboard for SpaceX launch data
- Implement interactive components including dropdown menus and range sliders
- Visualize launch success rates via pie charts and scatter plots
- Enable filtering by launch site and payload range
- Analyze success rates for different booster versions
- Derive insights on launch performance based on user interaction

---

## 🗂️ Data Source

- **Dataset:** [SpaceX Launch Data](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DS0321EN-SkillsNetwork/datasets/spacex_launch_dash.csv)  
- Contains launch site info, payload mass, booster version, and launch outcomes (success/failure)

---

## 🧰 Tools and Libraries Used

- Python 🐍  
- **Dash** – for building interactive web apps  
- **Plotly** – for dynamic charts and visualizations  
- **Pandas** – for data manipulation  
- **wget** – to download datasets and app skeleton  
- Jupyter Notebook / IDE for development

---

## 📋 Key Features

- **Launch Site Dropdown:** Select a specific launch site or view all sites  
- **Success Pie Chart:** Displays launch success counts by site or detailed success/failure for a selected site  
- **Payload Range Slider:** Filter data by payload mass range (0 to 10,000 kg)  
- **Success-Payload Scatter Plot:** Shows correlation between payload mass and launch outcome, color-coded by booster version category

---

## 📊 Insights from the Dashboard

- Identify which launch site has the largest number of successful launches  
- Determine the site with the highest launch success rate  
- Analyze which payload mass ranges correspond to higher or lower success rates  
- Understand the success rate performance of different Falcon 9 booster versions  

---

## 🚀 How to Run

1. Download the dataset and app skeleton using wget commands:  
```bash
wget "https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DS0321EN-SkillsNetwork/datasets/spacex_launch_dash.csv"
wget "https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/t4-Vy4iOU19i8y6E3Px_ww/spacex-dash-app.py"
