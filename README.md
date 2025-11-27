# 📱 Flipkart-Smartphone-Web-Scrapping

A **Python-based web scraping and data analysis project** that extracts smartphone data from **Flipkart** for major brands like  
**Samsung, Apple, Realme, and Motorola**.  
The project uses **BeautifulSoup, Requests, NumPy, and Pandas** to collect, clean, and structure product information for **market research, competitive analysis, and e-commerce insights**.

---

## 🚀 Project Overview

This project automatically scrapes **smartphone listings from Flipkart** and builds a clean, analytics-ready dataset.

### 🔍 From each product, we capture:
- 📌 **Product Title**  
- 💸 **Price**  
- ⭐ **Rating & Number of Ratings**  
- 📝 **Review Summary / Description**  
- 🏷️ **Brand & Variant Details (RAM, Storage, Color, etc.)**  
- 🔗 **Product URL**

### 🔎 **Scraped Brands**
We scraped smartphone data for **Samsung**, **Motorola**, **Realme**, and **Apple** from multiple Flipkart pages to ensure complete coverage.

All scraped data is:
1. Parsed using **BeautifulSoup**  
2. Cleaned & transformed  
3. Stored in a **Pandas DataFrame**  
4. Exported to an **Excel file** for further analysis  

Perfect for students, analysts, and developers showcasing **web scraping + data engineering + Python** skills.

---

## 📂 Project Files

[![Excel](https://img.shields.io/badge/Flipkart_Smartphones_Dataset-Download-green?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://github.com/satyashubhamjha/Flipkart-Smartphone-Web-Scrapping/blob/main/data/flipkart_smartphones.xlsx)

[![Jupyter Notebook](https://img.shields.io/badge/Jupyter_Notebook-View_Analysis-orange?style=for-the-badge&logo=jupyter&logoColor=white)](https://github.com/satyashubhamjha/Flipkart-Smartphone-Web-Scrapping/blob/main/notebooks/Flipkart_Smartphone_Web_Scraping.ipynb)

---

## 🧰 Tech Stack & Libraries

- 🐍 **Python** – Core language for scraping & data processing  
- 🌐 **Requests** – For sending HTTP requests to Flipkart  
- 🥣 **BeautifulSoup (bs4)** – HTML parsing & element extraction  
- 📊 **Pandas** – Creating clean DataFrames & exporting to Excel  
- 🔢 **NumPy** – Data manipulation & helper functions  
- 📓 **Jupyter Notebook** – For EDA & documenting steps  
- 📑 **Excel** – Final export format for analysis  

---

## 🔄 Scraping Workflow

1. **Send Request**  
   - Fetch HTML content for Samsung, Apple, Realme, and Motorola smartphone pages.

2. **Parse HTML with BeautifulSoup**  
   - Extract titles, prices, ratings, reviews, and links.

3. **Clean & Transform Data**  
   - Remove unwanted characters  
   - Convert price & rating fields to numeric  
   - Standardize brand names & specifications  

4. **Build Pandas DataFrame**  
   - Combine all products across 4 brands into a single dataset.  

5. **Export to Excel**  
   - Save final dataset as:  
     `flipkart_smartphones.xlsx`

---

## 📊 Possible Analysis & Use Cases

- 📈 **Brand comparison** (Samsung vs Apple vs Realme vs Motorola)  
- 💸 **Price trends** across models & variants  
- ⭐ **Rating distribution** by brand  
- 🛍️ **Best-value phones** based on features vs price  
- 🛒 Build a **price monitoring bot**  

---

## ⚙️ How to Run Locally

```bash
# Clone the repository
git clone https://github.com/satyashubhamjha/Flipkart-Smartphone-Web-Scrapping.git
cd Flipkart-Smartphone-Web-Scrapping

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter notebook
jupyter notebook notebooks/Flipkart_Smartphone_Web_Scraping.ipynb


---


