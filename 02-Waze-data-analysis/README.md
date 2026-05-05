# 🚗 Waze Data Analytics Project Using Python

## 📌 Project Overview

This project analyzes user activity data from Waze to better understand driving behavior, app engagement, and user retention patterns.

The main goal of this analysis is to explore how users interact with the Waze application by studying variables such as sessions, drives, navigation activity, kilometers driven, driving duration, device type, and user retention status.

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Understand the structure and quality of the Waze dataset
- Explore user behavior and driving activity
- Analyze engagement metrics such as sessions, drives, and activity days
- Compare retained and churned users
- Identify patterns that may help explain user retention
- Present findings in a clear and professional way

---

## 🗃️ Dataset Description

The dataset contains user-level activity information from Waze.

Key variables include:

| Column | Description |
|------|-------------|
| `ID` | Unique user identifier |
| `label` | User status, such as retained or churned |
| `sessions` | Number of app sessions |
| `drives` | Number of drives completed |
| `total_sessions` | Total number of sessions |
| `n_days_after_onboarding` | Number of days since the user joined |
| `total_navigations_fav1` | Navigations to favorite place 1 |
| `total_navigations_fav2` | Navigations to favorite place 2 |
| `driven_km_drives` | Total kilometers driven |
| `duration_minutes_drives` | Total driving duration in minutes |
| `activity_days` | Number of active days |
| `driving_days` | Number of days with driving activity |
| `device` | User device type |

---

## 🛠️ Tools & Technologies

This project uses:

- 🐍 Python
- 🐼 Pandas
- 🔢 NumPy
- 📓 Jupyter Notebook
- 📊 Data Analysis
- 🔍 Exploratory Data Analysis

---

## 📂 Repository Structure

```txt
Waze-Data-Analytics-Project/
│
├── README.md
├── Waze Data Analysis.ipynb
└── waze_dataset.csv
