# 🥘 EazyDinner: Web Scraping and Exploratory Data Analysis

## 📄 Overview
**EazyDinner** is a data analytics project focused on analyzing hotel and restaurant listings in **Delhi**, India. The dataset was created by web scraping an online platform using **Python** libraries like `BeautifulSoup` and `Requests`.  
It contains **1,350 records**, each representing unique hotels or restaurants, including details such as name, price, rating, cuisine type, and discounts.  

This analysis provides valuable insights into **pricing patterns**, **customer preferences**, and **market competition** in Delhi’s hospitality sector.  

---

## 👨‍💻 About Me
**Author:** K. Uday Shankar  
**Qualification:** B.Tech Graduate  
**Passion:** Data Analytics & Visualization  

> *“Data science is shaping the future across industries — I aspire to contribute to data-driven innovations through analytical insights.”*

---

## 🎯 Project Objectives
- ✅ Collect real-time hotel and restaurant data using **Python web scraping tools** (`BeautifulSoup`, `Requests`).
- ✅ Clean and organize the raw data into a structured dataset.
- ✅ Perform **Exploratory Data Analysis (EDA)** to identify pricing trends and popular cuisines.
- ✅ Analyze the relationship between **price, rating, and discount** strategies.
- ✅ Provide insights for **data-driven decision-making** in hospitality and marketing.

---

## 🧰 Tools & Technologies
- **Language:** Python  
- **Libraries:** `BeautifulSoup`, `Requests`, `Pandas`, `Matplotlib`, `Seaborn`, `NumPy`  
- **Data Handling:** CSV files, Pandas DataFrames  
- **Visualization:** Matplotlib & Seaborn plots  

---

## 🧱 Data Collection Process

### 1. Planning & Target Selection
- Identified a reliable online restaurant/hotel listing website.
- Defined key attributes: *Name, Price, Rating, Cuisine, Discount, Page Number*.

### 2. Data Extraction
- Sent automated HTTP requests using `requests`.
- Parsed HTML using `BeautifulSoup` to extract desired tags (`div`, `span`, etc.).
- Implemented loops to handle pagination (multiple pages).

### 3. Data Structuring
- Stored extracted values in Python lists.
- Combined lists into a **Pandas DataFrame** for cleaning and analysis.

---

## 🧹 Data Cleaning Steps
- Removed **duplicates** and handled **missing values**.
- Cleaned **Price** column (removed “₹” and text, converted to numeric).
- Converted **data types** (price & rating → float/int).
- Standardized **discount** fields to extract percentage values.
- Added **location** and **page number** columns for segmentation.
- Ensured **data consistency** and saved as a clean CSV.

---

## 📊 Exploratory Data Analysis

### 🔹 Univariate Analysis
- Price distribution is **right-skewed** — most hotels priced ₹500–₹2500.
- Majority of hotels fall within the **affordable to mid-range** segment.
- Outliers represent **high-end premium hotels**.

### 🔹 Bivariate Analysis
- **Barista Coffee** shows lowest average price (budget-friendly).
- **The Imperial Spice**, **Molecule Air Bar**, **Moti Mahal Delux** represent premium range.
- Mid-range options like **Berco’s** and **Zoca Café** dominate ₹1200–₹1800 range.

### 🔹 Cuisine Distribution (Pie Chart)
- **Multicuisine:** 44.2% (dominant)
- **Others:** 36.2%
- **North Indian:** 4.4%
- **Indian:** 3.6%
- Remaining cuisines (Chinese, Italian, etc.) form smaller shares.

### 🔹 Heatmap
- Highlights **cuisine specialization** by hotel.
- Confirms **multicuisine dominance** in Delhi’s restaurant market.

### 🔹 Grouped Bar Chart
- Shows **diversity of cuisines** across hotels.
- **Premium hotels** focus on fewer, high-end cuisines.
- **Café-style restaurants** target niche markets.

### 🔹 Scatter Plot (Price vs Rating)
- Weak positive correlation → higher prices slightly linked to better ratings.
- Ratings mostly between **4.0–4.5**, even for affordable hotels.

### 🔹 Pair Plot
- Strong correlation between **Price** and **Original Price**.
- **Weak link** between **Price** and **Rating** — service quality & ambiance may matter more.

---

## ❓ Key Business Questions Answered
| Question | Insight |
|-----------|----------|
| What is the most common price range? | ₹500–₹2500 — the competitive segment. |
| Which cuisines dominate the market? | Multicuisine & North Indian. |
| How do prices vary by type/location? | Premium vs budget segmentation clear. |
| Is there a link between price & rating? | Weak — affordability ≠ low quality. |
| Which hotels overlap or specialize? | Revealed via heatmaps and pair plots. |

---

## 🧩 Challenges Faced
1. **Dynamic HTML Structure** — frequent website layout changes.  
2. **Pagination Management** — loops required to fetch multi-page data.  
3. **Inconsistent Formats** — prices and discounts contained text/symbols.  
4. **Duplicate or Missing Records** — required cleaning and validation.  
5. **Encoding Issues** — special characters like “₹”, “°” caused CSV errors.  
6. **Data Type Conversion** — necessary for accurate visualizations.  

---

## 🏁 Conclusion
- Delhi’s hotel and restaurant market is **highly diverse**.  
- **Affordable and mid-range** options dominate, but **premium fine-dining** exists.  
- **Multicuisine restaurants** are the most common.  
- **Price and rating correlation is weak**, implying factors like service and ambiance are stronger influences.  
- The dataset can be extended for **predictive modeling**, **market segmentation**, or **recommendation systems** in the future.  

---

## 📦 Future Scope
- Automate periodic data scraping for trend monitoring.  
- Perform **sentiment analysis** on customer reviews.  
- Integrate **geospatial visualization** using `Folium` or `Plotly`.  
- Build a **restaurant recommendation engine**.  
