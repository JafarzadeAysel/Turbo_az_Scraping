# 🚗 Car Price Prediction — Azerbaijan Market

A **Data Science** project to predict car prices in Azerbaijan using **machine learning**, geospatial analysis, and advanced feature engineering.

---

## 📌 Project Overview
In this project, I collected, cleaned, and analyzed a large dataset of cars for sale in Azerbaijan, and then built a predictive model for car prices.  
I combined **web scraping**, **data preprocessing**, **EDA**, **feature engineering**, and **machine learning** to achieve the final results.

---

## 📊 Data Collection
- **Source 1:** Web scraping from [Turbo.az](https://turbo.az/)  
  → Scraped **40,000+ advertisements** using Python and BeautifulSoup/Selenium.
- **Source 2:** [Open Data Azerbaijan](https://opendata.az/)  
  → Used geospatial region data for analysis.

---

## 🛠 Data Cleaning
- Fixed **inconsistencies** across multiple columns (e.g., formatting, typos, units).
- Dealt with **missing values**:
  - Imputed values using a **Random Forest Classifier** model.
  - Dropped columns/rows with **>50% missing** values.
- Removed **duplicate rows**.

---

## 📈 Exploratory Data Analysis (EDA)
Performed **comprehensive EDA**, including:
- **Univariate Analysis**:
  - Examined distributions & symmetry of numeric features.
  - Visualized using histograms and density plots.
- **Bivariate Analysis**:
  - Used **bar plots** & **box plots** to explore relationships between price and categorical variables.
  - Interpreted patterns & trends.

---

## 🌍 Geospatial Analysis
- **Merged** car dataset with region shapefile from Open Data Azerbaijan.
- Built:
  - **Choropleth map** showing average car price by region.
  - **Dynamic Folium map** showing car counts & regional price distribution.

---

## 🧩 Feature Engineering
Steps included:
1. Created new derived columns.
2. Dropped unnecessary columns.
3. Checked **multicollinearity** with heatmap.
4. Handled outliers with **log transformation** for `price` & `kilometrage`.
5. Applied **dimensionality reduction**.
6. Encoded categorical features.

---

## 🤖 Machine Learning Model
- **Algorithm:** XGBoost
- Set **basic hyperparameters** for initial tuning.
- Evaluated model performance and achieved promising results.

---

## 🚀 Tech Stack
- **Languages:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Folium, Geopandas, XGBoost, Scikit-learn
- **Tools:** Jupyter Notebook, GitHub
- **Techniques:** Web scraping, EDA, Feature Engineering, Geospatial Analysis, Machine Learning

---

## 📌 Key Achievements
✅ Collected **40k+ real advertisements** from Turbo.az  
✅ Fixed messy, inconsistent data and imputed missing values intelligently  
✅ Created **interactive maps** for Azerbaijan's car market  
✅ Designed and trained an **XGBoost** model for price prediction  

---

## 📷 Sample Visuals
*(You can add screenshots or GIFs of your EDA, maps, and model results here.)*

---

## 📬 Contact
📧 Email: *jafarzadeaysel8@gmail.com*  
💼 LinkedIn: [Aysel Jafarzade](https://www.linkedin.com/in/jafarzadeaysel)