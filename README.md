# Turkey-s-earthquake-analysis

## Turkey Earthquake Analysis \& Visualization (1915-2021)



***This project is now being developed privately.***



🏆 Award Winning Project: This project was awarded 1st Place in the Kodluyoruz - Hi-Kod Veri Bilimi Atölyesi (Kodluyoruz - Hi-Kod Data Science Workshop) Final Group Projects.

This repository contains a comprehensive Exploratory Data Analysis (EDA) and Geospatial Visualization of earthquakes in Turkey between 1915 and 2021. The project aims to identify seismic patterns, temporal trends, and high-risk zones using historical data.

## 📊 Project Overview

Turkey is located in a seismically active region with complex fault lines. In this project, we analyzed over 17,000 earthquake records to understand the frequency, magnitude, and depth distribution of seismic events.

Key Objectives:



Data Cleaning: Handling missing values, unifying inconsistent location names (e.g., merging "EGE DENİZİ" variations), and formatting datetime objects.




Temporal Analysis: Visualizing earthquake frequency trends over years, months, and seasons.




Geospatial Analysis: Mapping epicenters using Folium to visualize the distribution of earthquakes across the North Anatolian and East Anatolian Fault lines.




Depth \& Magnitude Analysis: Investigating the correlation between depth and magnitude.

## 🔎 Key Insights \& Visualizations

Regional Frequency: The Mediterranean (Akdeniz) and Aegean Sea (Ege Denizi) regions showed the highest frequency of seismic activity during the analyzed period .

Magnitude Distribution: The majority of recorded earthquakes fall within the 3.5 - 6.0 Mw range. A histogram analysis reveals the frequency decay as magnitude increases.




Depth Analysis: Most earthquakes occur at shallow depths (0-25 km), which is a critical factor in the surface impact of these events.



Time Series: A significant spike in recorded earthquakes was observed in recent years (post-2010), likely due to improved sensor networks and detection of smaller aftershocks.

## 🛠️ Technologies Used

Python: Core language.

Pandas \& NumPy: Data manipulation and cleaning.

Matplotlib \& Seaborn: Static statistical visualizations (Bar plots, Histograms, Box plots).

Folium: Interactive map visualizations (Heatmaps, Marker Clusters).

Scikit-learn: Used for experimental risk modeling.

## ⚠️ Experimental Approach: Risk Heatmap

As part of the project's experimental phase, we attempted to generate a "Risk Heatmap" using a basic Linear Regression model.


Methodology: Locations (Latitude/Longitude) were encoded to visualize areas with historically higher magnitudes.

Note: We acknowledge that Linear Regression is not the ideal statistical method for predicting earthquake magnitudes due to the stochastic and non-linear nature of seismic data. This section serves as a proof-of-concept for creating heatmaps based on historical magnitude intensity rather than a predictive model.

## 🚀 Future Improvements

Reflecting on this project with advanced statistical knowledge, future iterations would include:

Advanced Modeling: Replacing Linear Regression with Poisson Point Processes or ETAS (Epidemic Type Aftershock Sequence) models which are better suited for spatiotemporal point patterns.

Feature Engineering: Incorporating fault line distance data and historical slip rates.

Interactive Dashboard: Moving the static notebook visualizations to a Tableau or Power BI dashboard.

