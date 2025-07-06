An end-to-end data analytics and ML project that forecasts how many units of product will sell based on features like price and shipping info.  
Built using Python, Pandas, Seaborn, and Scikit-learn with a real-world dataset (scraped from AliExpress).

---

##  Dataset

The dataset includes information about:
- `productTitle`: Name of the product
- `price`: Current price on platform
- `tagText`: Shipping information (Free/Paid)
- `sold`: Number of units sold (target variable)

Dataset rows: 445  
Source: Scraped dataset (AliExpress 2024)

---

## Problem Statement

E-commerce platforms list thousands of furniture products, but only a few drive the majority of sales.  
This project aims to **predict the number of units sold**, using available metadata — helping businesses make smarter pricing, shipping, and inventory decisions.

---

##  Tech Stack Used

- `Python`
- `Pandas`
- `NumPy`
- `Matplotlib`
- `Seaborn`
- `Scikit-learn`
- `Jupyter Notebook`

---

##  What I Did

✔ Cleaned and preprocessed real-world messy data  
✔ Analyzed skewed sales distribution  
✔ Visualized patterns between price and sales  
✔ Applied Log Transformation  
✔ Extracted features from productTitle using **TF-IDF**  
✔ Trained and compared **Linear Regression** and **Random Forest**  
✔ Explained model performance with **R² and MSE**

---

##  Results

- Linear Regression R²: `0.02`
- Random Forest R²: `-1.12`
- Insights: Most products have low sales; dataset is heavily skewed

---

##  Future Work

- Use deep learning models like XGBoost or LightGBM  
- Add external features like product rating or category  
- Deploy as an API using Flask or Streamlit

---


