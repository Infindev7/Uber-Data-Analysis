# 🚖 Uber Cab Pickups Data Analysis (2014-2015)

## 📊 Project Overview

This project provides a **visual representation** of Uber cab pickups using real-world datasets.

* The datasets are sourced from **Kaggle**. Out of 18 available files, **7 files** were selected for detailed analysis.
* The main focus is on cleaning, modifying, and analyzing the Uber pickup data to extract meaningful insights.

## 🧹 Data Cleaning & Preparation

* The file `Jan-June.csv` is the **original file**, which underwent several data cleaning operations including:

  * Location corrections
  * Latitude and longitude updates
  * Missing value handling (stored separately in `missing.csv`)
* Files with missing but writable and precise coordinates were added to `missingFound.csv` using **Google Maps**.
* A separate file named `taxi-zones.csv` was used to handle and analyze taxi zone data.

## 📁 Dataset Information

The `datasets` folder includes files for:

* **Monthly data:** Files for May, April, June, July, August, and September.
* **Data attributes:** Each file contains `year`, `month`, `time`, `latitude`, `longitude`, `base`, `day`.

The cleaned file `Jan-June.csv` was used to generate a new cleaned file: **`Jan-June-fixed.csv`**, which is used for further analysis.

## 🆚 Competitor Data

* A file named `Lyft2014.csv` is included, containing data about **Lyft**, a competitor of Uber.

## 📈 Data Visualization

Visualizations are implemented in the `visualization.ipynb` notebook and include:

* 📊 **Bar Graph:** Monthly pickups for Uber.
* 🗺️ **Map Plot:** To show pickup areas.
* 📉 **Line Graph:** For plotting **mean** and **median** of Uber pickups.


