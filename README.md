# Car Price Prediction: Azerbaijan Market 🚗

This project demonstrates a comprehensive data science workflow, from data acquisition and geospatial analysis to building a high-performance **machine learning** model for predicting car prices in Azerbaijan.


---

## Key Features 🚀

- **Web Scraping:** Extracted over 40,000 car advertisements from turbo.az to create a large-scale, real-world dataset.

- **Comprehensive EDA:** Performed extensive univariate and bivariate analysis to understand data distributions and relationships.

- **Geospatial Analysis:** Integrated data from opendata.az to create interactive choropleth and dynamic maps showing regional car prices and counts.

- **Feature Engineering:** Transformed raw data into a set of powerful, predictive features.

- **High-Performance Modeling:** Built an XGBoost model that achieved an outstanding R-squared (R2) of 0.99 and a Mean Squared Error (MSE) of 0.01.
---

##  Tech Stack 
- **Languages:** Python
- **Libraries:** Pandas, GeoPandas, NumPy, Matplotlib, Seaborn, Folium, XGBoost, Scikit-learn
- **Techniques:** Web scraping, EDA, Feature Engineering, Geospatial Analysis, Machine Learning

---
## Project Steps 

### 1. Data Collection
- **Source 1:** Web scraping from [Turbo.az](https://turbo.az/)  
  → Scraped **40,000+ advertisements** using Python and BeautifulSoup
- **Source 2:** [Open Data Azerbaijan](https://opendata.az/)  
  → Used geospatial region data for analysis.
The data included key features such as make, model, year, kilometrage, engine size, fuel type, price etc. 
---

### 2. Data Cleaning
- Fixed **inconsistencies** across multiple columns (e.g., formatting, typos, units).
- Dealt with **missing values**:
  - Imputed values using a **Random Forest Classifier** model.
  - Dropped columns/rows with **>50% missing** values.
- Removed **duplicate rows**.

---

### 3. Exploratory Data Analysis (EDA)
Performed **comprehensive EDA**, including:
- **Univariate Analysis**:
  - Examined distributions and symmetry of numeric features.
  - Visualized using histograms and density plots.
- **Bivariate Analysis**:
  - Used **bar plots**, **pie chart** and **box plot** to explore relationships between variables.
  - Interpreted patterns and trends.

---

### 4. Geospatial Analysis 🌍

- To add a geographic dimension to the project, I integrated a dataset from opendata.az containing the administrative boundaries of Azerbaijani regions.
- Data Integration: Joined the scraped car data with the regional boundary data.
- Interactive Map: Used folium to build a dynamic choropleth map. This map visualizes the average car price and car count per region, providing actionable insights into regional market variations.


Click to view the interactive map in detail➡️[Link🔗](https://jafarzadeaysel.github.io/Turbo_az_Scraping/car_price_map.html)
---
![](https://github.com/JafarzadeAysel/Turbo_az_Scraping/blob/main/photo_and_gifs/interactive_map.gif "Most Expensive cars")



---

### 5. Feature Engineering
Steps included:
1. Created new derived columns.
2. Dropped unnecessary columns.
3. Checked **multicollinearity** with heatmap.
4. Handled outliers with **log transformation** for `price` & `kilometrage`.
5. Applied **dimensionality reduction**.
6. Encoded categorical features.

---

### 6. Machine Learning Model
- **Algorithm:** XGBoost
- Set **basic hyperparameters** for initial tuning.
- Evaluated model performance and achieved promising results.

---

---

## 📌 Key Achievements
✅ Collected **40k+ real advertisements** from Turbo.az  
✅ Fixed messy, inconsistent data and imputed missing values intelligently  
✅ Created **interactive map** for Azerbaijan's car market  
✅ Designed and trained an **XGBoost** model for price prediction  

---

## 📷 Sample Visuals

---

## 📬 Contact
📧 Email: *jafarzadeaysel8@gmail.com*  
💼 LinkedIn: [Aysel Jafarzade](https://www.linkedin.com/in/jafarzadeaysel)
