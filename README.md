# Agricultural Crop Analysis Dashboard
Exploratory Data Analysis (EDA) and visualization of optimal crop selection based on soil nutrients and climatic conditions. 

## Overview

This project involves the Exploratory Data Analysis (EDA) and visualization of agricultural data to determine the **optimal crop** for cultivation based on various soil and climatic conditions. The goal is to provide data-driven recommendations to farmers or agricultural planners, maximizing yield and efficiency.

The analysis specifically focuses on identifying the ideal ranges for Nitrogen (N), Phosphorus (P), Potassium (K), temperature, humidity, pH, and rainfall for several different crop types.

## Data Description

* N - ratio of Nitrogen content in soil
* P - ratio of Phosphorous content in soil
* K - ratio of Potassium content in soil
* temperature - temperature in degree Celsius
* humidity - relative humidity in %
* ph - ph value of the soil
* rainfall - rainfall in mm

There were no data inconsistencies and ready to explore. 

## Key Features & Visualizations

The Tableau Dashboard provides a comprehensive view of the multivariate data:

### **1. Nutrient Analysis:**
* **Nitrogen** is highest in **Cotton and Coffee**. Cotton/Coffee prioritize structural and leaf growth (high N). High Nitrogen helps the plant to keep strong, green and actively growing so that it can continuously produce high-quality shoots. 
* **Potassium** is high in **grapes and apple**. Grapes/Apple prioritize fruit quality, sweetness (high K). Potassium is the main parameter for sweetness, flavour and colour. 
* **Phosphorous** is high in **grapes and apple**. Grapes/Apple prioritize high yield (high P). Phosphorous helps is establishing strong, healthy root systems and ensure high yield in fruit developemnt. 

### **2. Climatic Requirements:**
* **Rainfall:** **Highest rainfall** requirement is for **Rice** with average rainfall of 236.18mm as it is a heavy irrigation or monsoon crop that needs standing water. **Lowest rainfall** requirement is for **Muskmelon** with 24.69mm as it can grow in very dry consitions and is sensitive to excess water.
* **Humidity:** It tells about the atmospheric moisture needed for crops. **Highest humidity** is for **Papaya** with average humidity of 92.40% as it requires extremely high, constant humidity. **Lowest** is **Chickpea** with 16.86%. It is winter/cold season crop hence needs less humidity.
* **Temperature:** **Temperature is highest** in **Papaya** with 33.72 degree Celsius and hence grown in summers. **Lowest temperature** crop is **Chickpea** with 18.87 degree Celsius which aligns with growth during cooler winter months. 

### **3. Multivariate Scatter Plots:** 
* Hot & Dry weather (High Temp, Low Rain): Papaya, Muskmelon, Mothbeans
* Cool & Wet (Low/Mid Temp, High Rain) : Rice, Coconut, Coffee, Jute
* Cool & Dry (Low Temp, Low Rain) : Chickpea, Lentil
* Mid-Range (Centre of Plot ) : Maize, Orange, Grapes

## Technologies and Tools

| Category | Tool/Technology | Purpose |
| :--- | :--- | :--- |
| **Data Source** | `Crop.csv` | Raw agricultural dataset including environmental conditions and crop label. |
| **Visualization** | **Tableau Desktop** | Used for data preparation, calculation of aggregates, and creating the interactive dashboard (`.twbx` file). |
| **Analysis Focus** | Exploratory Data Analysis (EDA), Descriptive Statistics, Optimal Range Identification. |

## Project Files

* `Crop.csv`: The clean source dataset used for the analysis.
* `Crop Analysis.twbx`: The packaged Tableau workbook containing all sheets and the final dashboard design.

## How to View the Dashboard

1.  Download the `Crop Analysis.twbx` file from this repository.
2.  Open the file using **Tableau Reader** (free) or **Tableau Desktop**.
