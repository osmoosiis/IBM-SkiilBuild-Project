# Punjab Road Quality & Safety Analytics

## Project Overview
This project was developed as part of the **IBM SkillsBuild Data Analytics with AI Academic Internship Program**, conducted by **BharatCares** in association with **AICTE**.

The objective of this project is to analyze road infrastructure conditions, pothole grievances, and traffic accident patterns across major urban centers in Punjab, India (Ludhiana, Amritsar, Jalandhar, Patiala, Bathinda, Mohali). It incorporates spatial data filtering, temporal/monsoon trend analysis, and a custom **Road Priority Index (RPI)** metric to prioritize high-risk civic repairs.

---

## Screencasts
<img width="1920" height="1080" alt="Screenshot from 2026-09-23 19-54-14" src="https://github.com/user-attachments/assets/6b8cb375-9e8b-4a8a-a1b4-bdf5bfab96a2" />
<img width="1920" height="1080" alt="Screenshot from 2026-09-23 19-54-30" src="https://github.com/user-attachments/assets/db3bbb0d-0eb1-4553-adb6-716f63083723" />


##  Technologies Used
- **Programming Language**: Python 3.10+
- **Data Manipulation**: Pandas, NumPy
- **Data Visualization & Analytics**: Seaborn, Matplotlib, Plotly Express
- **Spatial Grid Coordinates**: Bounded Latitudinal/Longitudinal Scatter Mechanics (Punjab GIS Box)
- **Environment**: Google Colab / Jupyter Notebook

---

## Dataset Information
- **Geographic Bounding Box**: Punjab Region ($29.5^\circ\text{N} \text{ to } 32.5^\circ\text{N}$ Latitude, $73.8^\circ\text{E} \text{ to } 76.9^\circ\text{E}$ Longitude).
- **Features Included**:
  - `complaint_id`: Unique identifier (e.g., `PB-2026-10001`)
  - `district`: Urban hub (Ludhiana, Amritsar, Jalandhar, Patiala, Bathinda, Mohali)
  - `latitude` / `longitude`: Spatial coordinates
  - `complaint_type`: Pothole, Damaged Asphalt, Waterlogging, Missing Signage, Traffic Accident
  - `severity`: Low, Medium, High, Critical
  - `status`: Open, In Progress, Resolved
  - `accidents_reported`: Incident counter per hazard site
  - `days_open`: Resolution tracking metric
  - `RPI`: Calculated Road Priority Index Score

---

##  Setup & Execution Instructions

### 1. Clone or Download Project Files
Ensure all four submission files reside in your project directory:
- `YourName_ProjectName.ipynb`
- `requirements.txt`
- `README.md`
- `YourName_ProjectReport.docx`

### 2. Install Dependencies
Run the following command in your terminal or notebook environment:
```bash
pip install -r requirements.txt
