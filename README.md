# 📱 Flipkart-Smartphone-Web-Scrapping

A **Python-based web scraping and data analysis project** that extracts smartphone data from **Flipkart** for brands like **Samsung, Apple, Realme, and Motorola**.  
The project uses **BeautifulSoup, Requests, NumPy, and Pandas** to collect, clean, and structure product information for **price analysis, market research, and e-commerce insights**.

---

## 🚀 Project Overview

This project automatically scrapes **smartphone listings from Flipkart** and builds a clean, analytics-ready dataset.

🔍 From each product, we capture:

- 📌 **Product Title**  
- 💸 **Price**  
- ⭐ **Rating & Number of Ratings**  
- 📝 **Review Summary / Description**  
- 🏷️ **Brand & Variant Details (RAM, Storage, Color, etc.)**  
- 🔗 **Product URL**

All scraped data is:

1. Parsed using **BeautifulSoup**
2. Stored in a **Pandas DataFrame**
3. Exported to an **Excel file** for further analysis

This makes it ideal for **data analysts, e-commerce teams, and portfolio projects** showing **data engineering + web scraping + Python** skills.

---

## 📂 Project Files

[![Excel](https://img.shields.io/badge/Flipkart_Smartphones_Dataset-Download-green?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://github.com/satyashubhamjha/Flipkart-Smartphone-Web-Scrapping/blob/main/flipkart%20smartphone%20data.xlsx)

[![Jupyter Notebook](https://img.shields.io/badge/Jupyter_Notebook-View_Analysis-orange?style=for-the-badge&logo=jupyter&logoColor=white)](https://github.com/satyashubhamjha/Flipkart-Smartphone-Web-Scrapping/blob/main/flipkart_2_scrap.ipynb)

---

## 🧰 Tech Stack & Libraries

- 🐍 **Python** – Core language for scraping & data processing  
- 🌐 **Requests** – To send HTTP requests to Flipkart pages  
- 🥣 **BeautifulSoup (bs4)** – To parse and extract HTML elements  
- 📊 **Pandas** – To build structured DataFrames & export to Excel  
- 🔢 **NumPy** – For efficient numerical operations  
- 📓 **Jupyter Notebook** – For interactive development & EDA  
- 📑 **Excel** – Final, shareable dataset for analysis  

---

## 🔄 Scraping Workflow

1. **Send Request**  
   - Use `requests.get()` to fetch HTML content from Flipkart search result pages for selected brands (Samsung, Apple, Realme, Motorola).

2. **Parse HTML with BeautifulSoup**  
   - Locate product containers and extract:
     - Title  
     - Price  
     - Rating & Rating Count  
     - Reviews / Short Description  
     - Product Link  

3. **Clean & Transform Data**  
   - Remove symbols from prices  
   - Convert to proper numeric types  
   - Handle missing values  
   - Standardize brand names and specifications  

4. **Build Pandas DataFrame**  
   - Combine all records into a single, well-structured DataFrame.  
   - Columns may include:  
     `["brand", "product_title", "price", "rating", "rating_count", "reviews", "link"]`

5. **Export to Excel**  
   - Save the final dataset as:  
     `flipkart_smartphones.xlsx`  
   - Ready to be used in **Excel, Power BI, or any BI tool**.

---

## 📊 Possible Analysis & Use Cases

- 💸 **Price comparison** across brands (Samsung vs Apple vs Realme vs Motorola)  
- ⭐ **Rating distribution** and relationship between price and rating  
- 🏷️ **Feature vs price** comparison (RAM, storage, etc.)  
- 📈 **Market positioning** and competitive analysis for smartphones  
- 🛒 Build a **product recommendation or price monitoring tool**  

---


