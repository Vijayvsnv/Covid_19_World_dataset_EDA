

## 🌍 COVID-19 Global Data Analysis

### 🔍 Overview

This project performs a detailed **Exploratory Data Analysis (EDA)** on the **Worldometer COVID-19 dataset**, focusing on country-wise trends in total cases, deaths, recoveries, and other pandemic-related metrics.

The notebook includes powerful visualizations and statistical insights derived using **Pandas**, **Matplotlib**, and **Seaborn** in Python.

---

### 📁 Dataset Info

* 📦 **File:** `worldometer_data.csv`
* 🗂️ **Source:** [Worldometer COVID-19 Dataset](https://www.worldometers.info/coronavirus/)
* 🧮 **Attributes:** Total cases, deaths, recoveries, continent, WHO region, population, etc.

---

### 🧰 Technologies Used

* Python
* Google Colab
* Pandas, Numpy
* Matplotlib, Seaborn

---

### 🧹 Data Cleaning & Preparation

* Removed unnecessary columns like `NewCases`, `NewDeaths`, `NewRecovered`.
* Filled missing values with logical estimates or global averages.
* Cleaned number formats (commas, missing values).
* Converted columns to appropriate data types.
* Derived new features such as:

  * `deaths_rate` = (TotalDeaths / TotalCases) \* 100

---

### 📊 Key Visualizations

1. 📈 **Top 10 countries** by total COVID-19 cases
2. ☠️ **Top 10 countries** by total deaths
3. 📉 **Death rate analysis** — highest and lowest by country
4. 🌍 **WHO region-wise case distribution**
5. 🥧 **Pie chart** showing contribution of top 5 countries to global case count
6. 📊 **Scatter plot** between total cases and total deaths

---

### 📷 Sample Visuals

> Add plots from your Colab session like this (or use screenshots)

```
📊 Bar Chart - Top 10 Countries by Total Cases
📊 Bar Chart - Top 10 Countries by Death Rate
🌍 Pie Chart - Top 5 Countries vs Others
```

---

### 🚀 How to Run the Project

1. Clone the repo or download the files:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Open the notebook or `.py` file in Google Colab or Jupyter Notebook.
3. Ensure `worldometer_data.csv` is placed in the correct path.
4. Run all the cells sequentially to reproduce the analysis and graphs.

---

### 👨‍💻 Author

* **Name:** Vijay Bairagi
* **GitHub:** [@vijayvsnv](https://github.com/vijayvsnv)



