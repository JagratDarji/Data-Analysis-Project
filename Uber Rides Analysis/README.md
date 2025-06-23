🚖 Uber Rides Data Analysis

This project analyzes Uber ride data from September 2014 to explore ride patterns over time and space using Python data analysis and visualization libraries.

---

📁 Project Structure

Uber-Rides-Analysis/
│
├── dataset/
│ └── uber-raw-data-sep14.csv
│
├── uber_analysis.ipynb 
│
└── README.md


---

📊 Dataset Overview

- File: `uber-raw-data-sep14.csv`
- Columns:
  - `Date/Time`: Date and time of the Uber pickup
  - `Lat`: Latitude of the pickup location
  - `Lon`: Longitude of the pickup location
  - `Base`: Base code affiliated with the pickup

---

🧪 Technologies Used

- Python
- Jupyter Notebook
- Pandas – Data manipulation
- Matplotlib / Seaborn – Visualizations
- Plotly Express – Interactive map visualizations

---

📌 Analysis Performed

1. 📅 Datetime Feature Extraction
- Extracted day, weekday, hour, and minute from the `Date/Time` column.

2. 📈 Visualizations
- Rides per hour (bar chart)
- Rides per weekday (bar chart)
- Heatmap: Day vs Hour
- Interactive Pickup Map using Plotly and Mapbox

3. 🗺️ Geospatial Plot
- Mapped latitude and longitude coordinates to visualize ride density in New York City.

---
📷 Sample Visuals

- Heatmap of rides by hour and day
- Map of Uber pickups
- Distribution of rides by weekday and time

---

🚀 How to Run the Project

1. Clone this repo or download the files
2. Open `uber_analysis.ipynb` in Jupyter Notebook
3. Install required libraries (if not already):

```bash
pip install pandas matplotlib seaborn plotly
