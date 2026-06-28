#  Data Cleaning Project - Airbnb NYC 2019 Dataset

## 📌 Project Overview

This project focuses on cleaning and preprocessing the Airbnb NYC 2019 dataset using Python and Pandas. The objective is to identify and handle missing values, validate data types, detect duplicate records, identify outliers, and prepare the dataset for further analysis and visualization.

This project was completed as part of the **Oasis Infobyte Data Analytics Internship**.

---

## 📂 Dataset

- **Dataset Name:** Airbnb NYC 2019
- **Format:** CSV
- **Records:** ~48,895
- **Features:** 16

---

## 🎯 Objectives

- Load and inspect the dataset
- Identify and handle missing values
- Remove invalid records
- Check for duplicate entries
- Validate and correct data types
- Detect outliers
- Perform exploratory visualizations
- Save the cleaned dataset

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🔍 Data Cleaning Steps

### ✅ Imported Required Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn

### ✅ Loaded Dataset

Imported the Airbnb NYC 2019 dataset into a Pandas DataFrame.

### ✅ Dataset Inspection

- Checked dataset dimensions
- Viewed column names
- Examined data types
- Generated summary statistics

### ✅ Missing Value Handling

- Filled missing values in **host_name** with `"Unknown"`
- Filled missing values in **reviews_per_month** with `0`
- Converted **last_review** into datetime format
- Removed rows where **name** was missing

### ✅ Duplicate Check

Verified that no duplicate records existed in the dataset.

### ✅ Data Type Validation

Validated and corrected data types where necessary.

### ✅ Outlier Detection

Detected outliers in:

- Price
- Minimum Nights

using boxplots and descriptive statistics.

### ✅ Invalid Data Removal

Removed listings with a price of **0** because they represent invalid or unrealistic entries.

---

## 📊 Visualizations

The following visualizations were created:

- Distribution of Room Types
- Listings by Neighbourhood Group
- Price Distribution
- Correlation Heatmap
- Top 10 Most Expensive Neighbourhoods

---

## 📈 Key Insights

- Most Airbnb listings are either Entire Home/Apartments or Private Rooms.
- Manhattan and Brooklyn have the highest number of listings.
- The majority of listings are reasonably priced, with only a few luxury outliers.
- Duplicate records were not found.
- Missing values were successfully handled.
- Invalid price records were removed.

---

## 📁 Project Structure

```
OIBSIP-Data-Cleaning/
│
├── Airbnb_Data_Cleaning.ipynb
├── AB_NYC_2019.csv
├── Cleaned_AB_NYC_2019.csv
├── README.md
└── images/
    ├── room_type_distribution.png
    ├── neighbourhood_distribution.png
    ├── price_distribution.png
    ├── correlation_heatmap.png
    └── top10_neighbourhoods.png
```

---

## 🚀 Future Improvements

- Feature Engineering
- Machine Learning Preparation
- Dashboard using Power BI
- Predictive Analytics

---

## 👨‍💻 Author

**Kashish Jagtap**

 **Oasis Infobyte Data Analytics Intern**
