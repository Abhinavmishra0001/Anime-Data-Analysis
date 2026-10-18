# 🎬 Anime Data Analysis with Pandas & NumPy

## 📌 Overview
This project is a weekend learning activity dedicated to revising core Data Analysis concepts using Python, Pandas, and NumPy. I used a dataset of top-rated Anime to practice data cleaning, string manipulation, and Exploratory Data Analysis (EDA).

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy
* **Environment:** Jupyter Notebook

## 🚀 Key Skills Practiced

### 1. Data Cleaning & String Manipulation
* Extracted specific substrings (like episodes and running time) from messy, combined text columns using custom loops and slicing.
* Separated start and end months/years into distinct columns for better time-series analysis.
* Handled data type conversions (converting string years to integers for calculations).

### 2. Exploratory Data Analysis (EDA) & Filtering
* **Sorting:** Ranked anime by highest score and longest running time.
* **Filtering Logic:** Created custom conditions to find specific subsets of data (e.g., finding "Binge-Worthy" anime by filtering for scores > 8.5 AND episodes <= 24).
* **Index & Row manipulation:** Used `.loc[]` and `.sort_values()` for precise data retrieval without permanently altering the original dataset.

## 📊 Fun Insights Discovered
* Found the highest-rated short anime (perfect for a weekend binge!).
* Calculated the total years an anime ran by subtracting the parsed start and end years.
* Discovered how Pandas handles sorting string dates vs. integer values.

## 💡 What I Learned
Working with real-world data means dealing with messy text formats. This project was a great refresher on how to systematically break down complex strings into usable data points and use Pandas filtering to answer real questions about the data.
