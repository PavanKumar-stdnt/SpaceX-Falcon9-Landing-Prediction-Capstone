# 🚀 SpaceX Falcon 9: First-Stage Landing Prediction
### Data Science Capstone Project | IBM Professional Certification

## 📌 Project Overview
This project predicts the success of SpaceX Falcon 9 first-stage landings. By accurately forecasting whether a rocket will land successfully, we can determine the cost of a launch—potentially saving up to **$165 million** per mission through booster reuse.

## 🛠️ Data Science Lifecycle & Methodology
This capstone covers the end-to-end data science workflow:

*   **Data Collection:** Integrated data from the **SpaceX API** and supplemental records via **Web Scraping (BeautifulSoup)**.
*   **Data Wrangling:** Processed raw JSON and HTML data into clean DataFrames; handled missing values and performed **One-Hot Encoding**.
*   **Exploratory Data Analysis (EDA):** 
    *   **SQL:** Executed complex queries to identify mission milestones and payload trends.
    *   **Visualization:** Used **Seaborn** and **Matplotlib** to correlate payload mass, orbit types, and launch sites with success.
*   **Interactive Analytics:**
    *   **Folium:** Developed geospatial maps to analyze site proximity to coastlines and transport infrastructure.
    *   **Plotly Dash:** Created a reactive dashboard for real-time success-rate filtering.
*   **Machine Learning:** Built, tuned, and evaluated four classification models: **Logistic Regression, SVM, KNN, and Decision Tree** using **GridSearchCV**.

## 📊 Key Results & Insights
*   **Best Model:** The **LogisticRegression** achieved a test accuracy of **83.3%**.
*   **Strategic Site:** **KSC LC-39A** (Kennedy Space Center) is the most reliable launch site with the highest success rate.
*   **Payload Impact:** Success probability increases significantly for payloads exceeding **4,000kg**.

## 📁 Repository Contents
*   `jupyter-labs-spacex-data-collection-api.ipynb`: Extracting SpaceX flight data via API.
*   `jupyter-labs-webscraping.ipynb`: Scraping Wikipedia for launch history via BeautifulSoup.
*   `labs-jupyter-spacex-Data wrangling.ipynb`: Data cleaning and feature engineering.
*   `jupyter-labs-eda-sql-coursera_sqllite.ipynb`: Insight generation using SQL queries.
*   `edadataviz.ipynb`: Statistical plotting and trend analysis using Seaborn.
*   `lab_jupyter_launch_site_location.ipynb`: Geospatial clustering and distance analysis with Folium.
*   `spacex-dash-app.py`: Full source code for the interactive Plotly Dash dashboard.
*   `SpaceX_Machine Learning Prediction_Part_5.ipynb`: Model training, tuning, and evaluation.

---
**Author:** PARLAPALLY PAVAN KUMAR

