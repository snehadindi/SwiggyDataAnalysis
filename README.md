# Swiggy Data Analysis & Interactive Dashboard 🥡📊

This project presents an interactive data visualization dashboard built with **Plotly** to analyze restaurant data from Swiggy. It explores various insights such as restaurant types, online order availability, rating distribution, and more.

## 📁 Files in This Repo

| File Name                 | Description |
|--------------------------|-------------|
| `interactive_dashboard.py` | Main script that loads, cleans, and visualizes Swiggy data. Saves interactive HTML visualizations and opens them in your browser. |
| `Swiggydata.csv`         | Dataset used for analysis (ensure this is added or instructions are given to download). |
| `swiggy_analysis_report.pdf` | PDF report summarizing the key findings using static plots (if included). |
| `README.md`              | Project description, setup guide, and usage instructions (this file). |

---

## 📊 Features

- Histogram of restaurant types
- Line chart of total votes by restaurant type
- Online vs. offline order availability
- Distribution of restaurant ratings
- Cost for two people distribution
- Box plot: ratings vs. online orders
- Heatmap: online order distribution by restaurant type

---

## 📦 Requirements

Make sure you have the following Python libraries installed:

```bash
pip install pandas plotly
