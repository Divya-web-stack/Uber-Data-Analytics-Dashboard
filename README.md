<div align="center">

# 📊 Uber Data Analytics Dashboard 🚗

*From raw ride data to actionable business insights—an interactive Power BI journey.*

</div>

<p align="center">
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI Badge">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python Badge">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas Badge">
  <img src="https://img.shields.io/badge/Data_Source-Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle Badge">
</p>

---

## ✨ The Dashboard in Action

A picture is worth a thousand words, but an interactive dashboard is worth a million. Below is a preview of the final product, designed for clarity and deep-dive analysis.

*(**Pro Tip:** Record a short screen capture of you interacting with the dashboard and save it as a GIF. It's the best way to showcase your work!)*

<p align="center">
  <img src="https://github.com/Divya-web-stack/Uber-Data-Analytics-Dashboard/blob/main/DashboardUber.png" alt="Dashboard GIF Preview" width="80%">
</p>

---

## 🎯 Project Objective

> The core objective of this project is to analyze the Uber Pickups dataset for New York City to identify key patterns and trends. This dashboard serves as a strategic tool to help stakeholders understand customer behavior and optimize service operations.

The analysis aims to answer critical business questions such as:
* 🕒 What are the busiest hours and days for Uber rides?
* 🗺️ Which locations are the hotspots for pickups?
* 📈 How do ride patterns fluctuate seasonally throughout the year?
* 🤔 What are the underlying trends in trip volume and demand?

---

## 🛠️ Tech Stack & Tools

A combination of powerful tools was used to bring this project from concept to reality.

| Tool                 | Category                    | Purpose                                                              |
| -------------------- | --------------------------- | -------------------------------------------------------------------- |
| **Python** | Data Cleaning & Processing  | Used for initial data wrangling, cleaning, and feature engineering.  |
| **Pandas & NumPy** | Python Libraries            | Essential for data manipulation and numerical operations.            |
| **Microsoft Power BI** | Visualization & Dashboarding | The core tool for creating interactive reports and visuals.        |
| **DAX & Power Query**| Data Modeling               | Used within Power BI for creating complex measures and transformations. |
| **Kaggle** | Data Source                 | Provided the raw dataset for the analysis.                           |

---

## 📈 Project Workflow

The project followed a structured data analytics pipeline, ensuring data integrity and meaningful insights.

### **`Data Sourcing ➔ Data Cleaning (Python) ➔ Data Modeling (Power BI) ➔ Dashboarding`**

1.  **Data Sourcing:** The raw dataset was acquired from the [Uber Pickups in New York City](https://www.kaggle.com/datasets/fivethirtyeight/uber-pickups-in-new-york-city) collection on Kaggle.
2.  **Data Cleaning & Feature Engineering:** A Python script was developed to handle missing values, correct data types, and engineer new, insightful features like `hour`, `day_of_week`, and `month`. The clean data was then exported to a `.csv` file.
3.  **Data Modeling & Transformation:** The cleaned data was imported into Power BI. **Power Query** was used for final transformations, and a robust data model was built. **DAX** was then leveraged to write powerful measures for dynamic calculations (e.g., `Total Rides`, `Rides on Weekends`, etc.).
4.  **Dashboard Creation:** An intuitive and visually appealing dashboard was designed with a focus on user experience, incorporating slicers, charts, maps, and KPI cards to tell a compelling story with the data.

---

## 💡 Key Features & Insights

The dashboard is packed with features that unlock powerful insights:

* **⚡ Real-time KPI Cards:** Get an instant overview of total rides, peak hours, and busiest days.
* **📅 Temporal Trend Analysis:** Interactive line and bar charts visualize ride volume by hour, day, and month, uncovering clear patterns in demand.
* **🌍 Geospatial Heatmap:** A map visual identifies pickup hotspots, allowing for strategic driver placement and targeted marketing.
* **🔬 Granular Filtering:** Dynamic slicers empower users to drill down into the data for any specific month or day, facilitating custom analysis.

### A Few Discoveries:
* **Evening Rush:** The data reveals a significant spike in ride demand between **5 PM and 7 PM** on weekdays, coinciding with the end of the workday.
* **Weekend Hotspot:** The SoHo and Greenwich Village areas show a much higher concentration of pickups on Friday and Saturday nights.
* **Seasonal Dip:** A noticeable dip in rides occurs in the colder month of February, compared to a peak in the fall (September/October).

---

## 🚀 Getting Started

To explore this project on your own machine, follow these simple steps:

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    cd your-repository-name
    ```

2.  **Run the Data Cleaning Script**
    * Make sure you have Python and Pandas installed.
    * Execute the script to generate the `cleaned_uber_data.csv`.
    ```bash
    python your_cleaning_script.py
    ```

3.  **Launch the Dashboard**
    * Open the `.pbix` file with Power BI Desktop.
    * Power BI will likely ask you to locate the data source. Simply point it to the `cleaned_uber_data.csv` file you just created.
    * Voila! The dashboard is live and ready for you to explore.

---

## 🔮 Future Scope

This project lays a strong foundation for even more advanced analysis. Future enhancements could include:
* **Integrating Weather Data:** Analyzing the correlation between weather conditions and ride demand.
* **Predictive Modeling:** Building a time-series model to forecast future ride volumes.
* **Fare Analysis:** Incorporating fare data to analyze revenue generation and pricing strategies.

---

<div align="center">
    Made with ❤️ by [Your Name]
</div>
