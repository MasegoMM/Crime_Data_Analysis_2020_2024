# Crime Data Analysis: 2020–2024

## 📊 Project Overview

This project focuses on analysing **over 1 million recorded crime incidents from 2020 to 2024** using Python and Jupyter Notebook.

The objective of the project is to clean, explore and analyse crime data to identify patterns and trends across **crime types, police areas, time periods, victim demographics, premises and weapon information**.

The analysis demonstrates how raw datasets can be transformed into meaningful insights that can support data-driven decision-making.

---

## 🎯 Project Objectives

The main objectives of this project were to:

* Clean and prepare a large crime dataset for analysis.
* Identify trends in recorded crime over time.
* Analyse the most frequently reported crime categories.
* Compare crime volumes across police areas.
* Explore victim age and sex distributions.
* Analyse crime patterns by time of day.
* Identify common premises where incidents occurred.
* Examine recorded weapon information.
* Create visualisations to communicate findings clearly.
* Generate insights that could support further analysis and decision-making.

---

## 🗂️ Dataset

The dataset contains **1,004,894 crime records** covering incidents that occurred between **2020 and 2024**.

Key information includes:

* Crime codes and descriptions
* Crime occurrence and reporting dates
* Police areas
* Victim age and sex
* Premise descriptions
* Weapon descriptions
* Time of occurrence
* Geographic information

---

## 🛠️ Technologies & Tools

| Tool                 | Purpose                                   |
| -------------------- | ----------------------------------------- |
| **Python**           | Data analysis and processing              |
| **Pandas**           | Data cleaning and manipulation            |
| **NumPy**            | Numerical analysis                        |
| **Matplotlib**       | Data visualisation                        |
| **Jupyter Notebook** | Analysis and documentation                |
| **GitHub**           | Project documentation and version control |

---

## 🔍 Analysis Performed

### 1. Data Cleaning

The dataset was inspected for:

* Missing values
* Duplicate records
* Invalid victim ages
* Incorrect data types
* Date formatting

Additional analytical columns were created, including:

* Year
* Month
* Day
* Hour
* Time Period
* Victim Age Group

---

### 2. Crime Trends

The analysis examines how recorded crime incidents changed between **2020 and 2024**.

Visualisations were created to identify:

* Yearly crime volumes
* Year-on-year changes
* Monthly patterns
* Average crime levels by month

---

### 3. Crime Types

The project identifies the **most frequently recorded crime categories** and examines their contribution to the overall dataset.

This helps provide a clearer understanding of the types of incidents that occur most frequently in the dataset.

---

### 4. Police Area Analysis

Crime incidents were compared across police areas to identify areas with higher recorded incident volumes.

The analysis also combines **crime type and police area** to investigate which crime categories occur most frequently within the highest-volume areas.

> Note: Raw incident counts should not automatically be interpreted as crime risk because areas can differ in population, geography and activity levels.

---

### 5. Victim Demographics

The project explores:

* Victim age distribution
* Median victim age
* Victim age groups
* Recorded victim sex

This provides demographic context around the incidents contained in the dataset.

---

### 6. Time-of-Day Analysis

Crime incidents were analysed according to the time they occurred.

Time periods were grouped into:

* Morning
* Afternoon
* Evening
* Night

Hourly analysis was also performed to identify periods with higher recorded incident volumes.

---

### 7. Premise Analysis

The analysis identifies the most common locations or premise types where incidents were recorded.

Examples include different categories of:

* Streets
* Residences
* Businesses
* Public locations

---

### 8. Weapon Analysis

Weapon information was analysed to determine:

* How frequently weapon information was recorded.
* Which weapon categories appeared most frequently.
* How much weapon information was missing.

Missing weapon information was not automatically interpreted as meaning that no weapon was involved.

---

## 📈 Key Findings

The analysis identified several notable patterns within the dataset:

* The dataset contains **1,004,894 recorded incidents**.
* The crime occurrence data covers **2020–2024**.
* **Vehicle – Stolen** is the most frequently recorded crime category.
* **Central** has the highest number of recorded incidents among the police areas.
* Crime volumes vary across different months and times of day.
* Victim demographics show different distributions across age and sex categories.
* Premise types and weapon information provide additional dimensions for understanding crime patterns.

These findings are descriptive and reflect patterns in the recorded dataset rather than establishing the causes of crime.

---

## 📁 Project Structure

```text
Crime-Data-Analysis/
│
├── Crime_Data_Analysis_2020_2024.ipynb
├── Crime_data_from_2020_to_2024.csv
└── README.md
```

---

## 💡 Business / Analytical Value

**Raw Data → Data Cleaning → Exploratory Analysis → Visualisation → Insights**

The analysis could be extended to support:

* Operational planning
* Resource allocation analysis
* Geographic analysis
* Trend monitoring
* Crime-category analysis
* Interactive dashboards
* Further statistical modelling

---
## 📚 Skills Demonstrated

This project demonstrates practical experience with:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Transformation
* Data Visualisation
* Feature Engineering
* Missing Data Analysis
* Statistical Summaries
* Trend Analysis
* Categorical Analysis
* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

---

## 👤 Author

**Masego**

BSc Information Technology | Aspiring Data Analyst

Interested in transforming raw data into meaningful information and actionable business insights through **data analysis, SQL, Python, visualisation and database technologies**.

---

## ⭐ Project Goal

The goal of this project is to demonstrate the ability to take a large real-world dataset, investigate its quality, analyse meaningful patterns and communicate the results through clear and understandable visualisations.


## 🚀 Future Improvements

Future versions of the project could include:

### Geospatial Analysis

Use latitude and longitude information to create maps and investigate geographical patterns.

### Population-Adjusted Analysis

Combine crime data with population statistics to calculate incident rates and provide more meaningful comparisons between areas.

### Predictive Analysis

Explore forecasting or machine-learning approaches to analyse future incident volumes, with appropriate validation and limitations.

---
