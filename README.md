# Punjab Road Quality & Safety Analytics

## Project Overview
This project was developed as part of the **IBM SkillsBuild Data Analytics with AI Academic Internship Program**, conducted by **BharatCares** in association with **AICTE**. 

The goal of this project is to analyze road infrastructure conditions, pothole grievances, and accident distribution across major districts in Punjab, India (Ludhiana, Amritsar, Jalandhar, Patiala, Bathinda, Mohali). It incorporates spatial data filtering, time-series seasonal trends, and a custom **Road Priority Index (RPI)** metric to prioritize high-risk road repairs.

---

## Technologies Used
- **Programming Language**: Python 3.10+
- **Data Manipulation**: Pandas, GeoPandas, NumPy
- **Data Visualization**: Plotly Express, Pydeck (Geospatial 3D Heatmaps), Seaborn
- **Dashboard Web Framework**: Streamlit
- **GIS Bounds Handling**: Shapely

---

## Dataset Information
- **Source**: Geo-fenced road condition and incident log bounded between Latitude $29.5^\circ\text{N} - 32.5^\circ\text{N}$ and Longitude $73.8^\circ\text{E} - 76.9^\circ\text{E}$ (Punjab Region).
- **Dataset Columns**: `complaint_id`, `district`, `latitude`, `longitude`, `complaint_type`, `severity`, `road_type`, `status`, `accidents_reported`, `days_open`, `created_date`.

---

## Setup & Execution Instructions

### 1. Clone or Download the Project
Ensure all files are placed in the same directory.

### 2. Install Dependencies
Run the following command in your terminal:
```bash
pip install -r requirements.txt
