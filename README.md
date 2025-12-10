# zomato-restaurant-eda

# Zomato Restaurant Data Analysis (EDA with Python & Pandas)

This project is an Exploratory Data Analysis (EDA) on a Zomato restaurant dataset using **Python, Pandas, Matplotlib, and Seaborn**.  
The goal is to understand patterns in **ratings, cuisines, locations, and pricing** and to extract insights useful for food-tech / restaurant businesses.

---



---

## 🧰 Tech Stack & Libraries

- **Language:** Python
- **Environment:** Jupyter Notebook 
- **Libraries:**
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`

---

## 📝 Problem Statement

Zomato contains information about thousands of restaurants:  
📌 Where are they located?  
📌 Which cuisines are popular?  
📌 How do price range and ratings relate?  
📌 Which restaurants get the most votes?

The objective of this project is to:

- Analyze restaurant ratings, votes, and price ranges.
- Identify popular cuisines and high-performing locations.
- Understand patterns that can help business decisions.

---

## 📊 Dataset Overview

The dataset contains columns like:

- `name` – Restaurant name  
- `location` – Area / locality  
- `cuisines` – Type(s) of food served  
- `rate` – Rating of the restaurant  
- `votes` – Number of user votes  
- `approx_cost` / `price_range` – Cost information  
- Other columns depending on the dataset version.

---

## 🔄 Project Workflow (Step by Step)

### 1️⃣ Import Libraries & Load Data

- Loaded the CSV file using `pandas.read_csv()`.
- Took an initial look at the data using:
  - `head()`
  - `info()`
  - `describe()`
  - `shape`

### 2️⃣ Data Cleaning

- Removed duplicate records.
- Handled missing values in:
  - Ratings
  - Cuisines
  - Cost-related columns
- Converted:
  - Rating columns to numeric
  - Price / cost to numeric formats
- Cleaned text columns such as `cuisines` and `location`.

### 3️⃣ Exploratory Data Analysis (EDA)

Performed univariate and bivariate analysis:

- Rating distribution (histogram).
- Most popular cuisines (value counts + bar plots).
- Relationship between:
  - `rating` vs `votes`
  - `price range` vs `rating`
- Location-wise restaurant counts.

Visuals created using:

- `matplotlib.pyplot`
- `seaborn` (barplot, countplot, scatterplot, boxplot, etc.)

### 4️⃣ Key Insights

Some example insights (modify as per your notebook):

- Restaurants with **more votes generally have higher ratings**.
- **North Indian and Chinese** are among the most popular cuisines.
- **Premium price range** restaurants tend to show higher average ratings.
- Certain **locations have a high density of restaurants**, indicating competitive markets.

### 5️⃣ Conclusion

- Completed a full EDA pipeline: **Load → Clean → Analyze → Visualize → Conclude**.
- Identified trends in **cuisines, pricing, and ratings**.
- This project showcases:
  - Data cleaning skills
  - Exploratory analysis
  - Visualization
  - Business-oriented insight generation

---


