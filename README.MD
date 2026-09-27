# 🛍️ Customer Shopping Behaviour & Retail Sales Analytics

> An end-to-end Data Analytics project focused on understanding customer purchasing behaviour, spending patterns, product performance, discounts, subscriptions, and customer segments.

---

## 📌 Overview

This project analyzes **3,900 customer purchase records** to understand customer shopping behaviour and purchasing patterns.

The project covers the complete analytics process, from **data preparation and exploration to SQL analysis, dashboard development, documentation, and presentation**.

The goal is to transform customer transaction data into **meaningful business insights** that can support data-driven retail decisions.

---

## 🛠️ Tools & Technologies

* 🐍 **Python & Pandas** — Data cleaning and EDA
* 🗄️ **PostgreSQL & SQL** — Business analysis
* 📊 **Power BI** — Interactive dashboard
* 📓 **Jupyter Notebook** — Python analysis
* 📑 **Gamma** — Project presentation
* 🌐 **Git & GitHub** — Project management and version control

---

## 📊 Dataset

The dataset contains **3,900 customer purchase records** with **18 columns** covering customer demographics, purchases, products, discounts, subscriptions, and shopping behaviour.

### 🔑 Key Data Areas

* 👤 Customer demographics
* 🛒 Product and purchase details
* ⭐ Review ratings
* 🏷️ Discount usage
* 💳 Payment methods
* 🔄 Previous purchases
* 📦 Shipping information
* 🔔 Subscription status
* 📅 Purchase frequency

📁 **[View Dataset](Dataset/customer_shopping_behaviour.csv)**

---

## 🐍 Python — Data Cleaning & EDA

Python and Pandas were used to prepare and explore the raw dataset.

### 🔎 What I Did

* Loaded and inspected the dataset.
* Checked data types, structure, and missing values.
* Performed descriptive analysis.
* Handled missing `review_rating` values.
* Standardized column names.
* Created `age_group` and `purchase_frequency_days`.
* Checked redundant information and removed `promo_code_used`.
* Loaded the cleaned data into PostgreSQL for SQL analysis.

📓 **[View Python Analysis](Data_Modeling_and_EDA/Customer_Shopping_Behaviour_Analysis.ipynb)**

---

## 🗄️ SQL — Business Analysis

PostgreSQL was used to perform structured business analysis on the cleaned customer data.

The analysis includes **15 business questions** covering:

* 💰 Revenue and customer spending
* 👥 Customer demographics and segments
* 🛍️ Product performance
* 🏷️ Discount behaviour
* 🔔 Subscription behaviour
* 💳 Payment methods
* 🚚 Shipping analysis
* 📅 Purchasing patterns

The SQL analysis focuses on turning customer transaction data into **business-oriented insights**.

📄 **[View SQL Analysis](Data_Analysis/Customer_Shopping_Behaviour_Analysis.sql)**

---

## 🎯 Business Focus

The analysis was designed around practical retail questions such as:

* Which customer groups contribute to revenue?
* How do customers purchase across different categories?
* How are discounts and subscriptions related to customer behaviour?
* Which products and categories show stronger customer engagement?
* How can customer segments support targeted business strategies?

These questions helped connect the technical analysis with **real-world business decision-making**.

---

## 📊 Power BI — Interactive Dashboard

An interactive Power BI dashboard was developed to communicate the analysis visually.

The dashboard presents information related to:

* 💰 Customer spending
* 🛍️ Product performance
* 👥 Customer segments
* 🏷️ Discounts
* 🔔 Subscriptions
* 📈 Purchasing patterns

### 🖼️ Dashboard Preview

![Customer Shopping Behaviour Dashboard](Screenshots/19_Customer_Shopping_behaviour_dashboard.png)

📊 **[Open Power BI Dashboard](Interactive_Dashboard/Customer_Shopping_behaviour.pbix)**

---

## 📚 Project Documentation

The complete documentation provides the detailed project work, including:

* 📌 Project overview and business problem
* 📊 Dataset details
* 🐍 Python data preparation and EDA
* 🗄️ SQL business questions and queries
* 📊 Power BI dashboard
* 💡 Business recommendations
* 🏁 Project conclusion

📖 **[Check Complete Project Documentation](Project_Report/Project_Documentation.md)**

---

## 🎤 Presentation

A professional project presentation was created using **Gamma** to communicate the analysis clearly.

It covers the project overview, business problem, dataset, data preparation, EDA, SQL analysis, key findings, Power BI dashboard, recommendations, and conclusion.

🎤 **[View Project Presentation](Presentation/Customer_Shopping_Behaviour_Analysis.pptx)**

---

## 🏁 Conclusion

This project demonstrates a practical **end-to-end Data Analyst workflow**, from preparing raw customer data to communicating business insights.

Using **Python, SQL, and Power BI**, the project combines data cleaning, exploratory analysis, business-focused SQL analysis, and interactive visualization.

It also demonstrates the ability to **document analytical work and communicate findings clearly through a professional presentation**.

Overall, the project showcases practical skills in **data preparation, analysis, visualization, and business communication** using commonly used Data Analytics tools.
