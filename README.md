# Alfido Tech — Sales Performance Analysis

## Overview

This repository contains an end-to-end data analytics project evaluating multi-year superstore sales and order performance (2015–2018) for **Alfido Tech**. The project leverages Python for automated data cleaning, exploratory data analysis (EDA), and metric computation, supplemented by an interactive HTML dashboard and a formal executive report.

---

## Dataset

* **File Name:** `superstore_final_dataset.csv` (and cleaned output)


* **Scope:** 9,800 order line items across 4,922 distinct orders spanning January 2015 to December 2018.


* **Key Attributes:** Order/Ship dates, shipping modes, customer segments, geography (region, state, city), product hierarchy (category, sub-category, product name), and sales revenue.



---

## Tools & Tech Stack

* **Programming Language:** Python


* **Libraries:** Pandas, NumPy (Data manipulation & metrics); Matplotlib, Seaborn (Data visualization & EDA styling)


* **Reporting & BI:** Jupyter Notebook (`.ipynb`), interactive HTML dashboard interface, and PDF executive documentation.



---

## Project Steps

1. **Setup & Data Ingestion:** Loaded raw sales records in Python, inspected schema types, and verified record counts.


2. **Data Cleaning & Preprocessing:** Handled missing values (negligible missing postal codes), dropped duplicates, parsed date fields (`DD/MM/YYYY`), and engineered time-based features (`Order_YearMonth`, `Ship_Lead_Days`).


3. **Exploratory Data Analysis (EDA):** Analyzed central tendencies, statistical distributions, category contributions, and regional revenue shares.


4. **Interactive Dashboard & Reporting:** Built a responsive HTML/JS sales dashboard and generated a publication-ready executive report summarizing critical metrics and business recommendations.



---

## Dashboard Preview

An interactive single-file dashboard (`Alfido Tech Sales Data cleaned.xlsx`) has been structured to allow dynamic filtering across regions, categories, customer segments, and order years with live-updating KPIs and charts.

---

## Results & Key Findings

* **Total Revenue:** Generated **$2,261,537** total revenue across the 4-year span.


* **Category Performance:** **Technology** led total revenue at **$827K**, closely followed by **Furniture** ($729K) and **Office Supplies** ($705K), despite Office Supplies handling the highest volume of order line items.


* **Regional Disparities:** The **West** and **East** regions drive roughly 61% of total sales, whereas the **South** significantly under-indexes in volume and high-ticket category adoption.


* **Seasonality:** Sales exhibit a strong upward trajectory year-over-year accompanied by a heavy seasonal spike between September and December (peaking in November at roughly $350K combined) and a sharp trough in February.



---

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/Alfido-Tech-Superstore-Sales-Performance-Analysis.git

```


2. Install required dependencies:
```bash
pip install pandas numpy matplotlib seaborn

```


3. Open and run the Jupyter Notebook for step-by-step code and analysis:


```bash
jupyter notebook Alfido_Tech_Sales_Analysis.ipynb

```


4. Open `Alfido Tech Sales Data cleaned.xlsx` (HTML dashboard) in any modern web browser to interact with the filtering components.
