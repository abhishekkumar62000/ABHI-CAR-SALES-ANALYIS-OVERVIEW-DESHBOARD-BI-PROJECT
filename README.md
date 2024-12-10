# ABHI-CAR-SALES-ANALYIS-OVERVIEW-DESHBOARD-BI-PROJECT
 **BMW i8**
![MY Car Project look 1](https://github.com/user-attachments/assets/b38229fa-c66a-43ec-8387-b61c91b55732)
**Buick Riviera**
![My car deshboard project look 2](https://github.com/user-attachments/assets/c00f4739-fe47-4cef-baa7-327ca0ddc192)
**Mercedes-Benz**
![abhi car deshboard 3 project](https://github.com/user-attachments/assets/568609cb-9508-4a79-a188-f05b7e42476c)

---

# 🚗 **ABHI Mercedes-Benz, Buick Riviera & BMW i8 CAR Sales Analysis Dashboard Project** 🏎️

## 🛠️ **Project Overview**
Today, I embarked on an exciting journey to build a **Car Sales Analysis Dashboard** that combines the power of **Power BI**, **Excel**, **SQL**, and **Python**. This project provides an **insightful** analysis of car sales data, with a focus on three iconic car models: **Mercedes-Benz**, **Buick Riviera**, and **BMW i8**.

💻 **Tools & Technologies Used:**
- **Power BI** 🖥️
- **Microsoft Excel** 📊
- **SQL** 🗄️
- **Python** 🐍
- **Data Cleaning** 🧹
- **Exploratory Data Analysis (EDA)** 🔍

## 📊 **Data Cleaning & Preparation**

📂 The raw sales data came from multiple sources, and was **messy** and unstructured. My first task was to clean it using **Excel** and transform the data into a more usable format. 

- Used **Excel** to remove duplicates, handle missing values, and standardize formats. 📑
- I applied a **cleaning strategy** to ensure that all records were consistent and ready for deeper analysis.

🔄 This process helped ensure that the data was **accurate** and **consistent** for meaningful analysis.

## 🧮 **Exploratory Data Analysis (EDA) with Python** 📈

Once the data was cleaned, I used **Python** to perform **EDA** and explore the relationships within the dataset. This phase helped me discover **trends** and **patterns** that are crucial for sales decision-making.

- **Libraries Used:** 
  - Pandas 🧳
  - Matplotlib 🎨
  - Seaborn 📊
  - Numpy 🧮

📊 **Key Insights from EDA:**
- Analyzed **monthly sales trends** for each car model.
- Identified **best-selling car models** and **regions**.
- Found correlations between **car features** and **sales performance**.
- Unveiled patterns in **seasonal sales**.

🔍 **Key Discoveries:**
- The **BMW i8** consistently performs well in urban regions, while the **Buick Riviera** has higher sales in suburban areas. 🚙
- **Mercedes-Benz** shows a high demand during the winter months, especially in colder regions. 🌨️

## 📈 **SQL Queries for Data Analysis**

After completing the EDA, I used **SQL** to run various queries for further analysis. Here are some queries that helped me analyze the data:

```sql
SELECT car_model, COUNT(*) AS sales_count
FROM car_sales
WHERE sales_region = 'Urban'
GROUP BY car_model
ORDER BY sales_count DESC;
```

🔥 **SQL Highlights:**
- **Aggregating sales data** based on regions.
- **Identifying top-performing models**.
- Analyzing **yearly sales growth**.
  
💡 The **SQL queries** helped me dive deeper into the data and extract more specific insights about **sales performance**, **regions**, and **time trends**.

## 📊 **Dashboard Creation in Power BI** 🖥️

Once the data was cleaned and analyzed, I moved to **Power BI** to create an interactive **Dashboard**. This dashboard allows users to view and interact with car sales data, identify key trends, and make data-driven decisions.

🖌️ **Features of the Dashboard:**
- **Sales Overview:** Displays total sales and sales growth for each car model. 📅
- **Car Model Comparison:** Side-by-side comparison of the **Mercedes-Benz**, **Buick Riviera**, and **BMW i8** sales figures. 📉
- **Regional Breakdown:** An interactive map showing sales by region, which highlights the top-performing areas. 🌍
- **Time-based Analysis:** Visualizations of monthly, quarterly, and yearly sales trends. 📅

✨ **Dashboard Design:** Focused on making the visuals **clean**, **interactive**, and **insightful**. Users can filter data by car model, region, and time period, allowing them to customize the view according to their needs.

## 📈 **Key Insights in the Dashboard:**
- 📅 **Yearly Sales Growth:** Displays the growth of sales for each car model year by year.
- 🚙 **Top Regions for Sales:** Shows which regions contribute the most to sales, giving insight into regional preferences.
- 🕰️ **Monthly Trends:** Interactive filters for users to compare sales performance month by month.

## 💡 **Takeaways and Learning**

🎯 **What I Learned:**
- Combining different tools and techniques can provide a **holistic view** of data.
- Excel is **great for cleaning**, but Power BI is **unbeatable for visualizing** the final insights.
- SQL is **extremely powerful** for running complex queries and aggregating data.
- Python is ideal for performing **advanced analysis** and **exploring the data** in-depth.

🚀 **Next Steps:**
- Implement machine learning algorithms to **predict future sales** trends based on historical data.
- Add **real-time data** integration to keep the dashboard updated with the latest sales figures.
- Enhance **data interactivity** for users, allowing them to customize reports even further.

## 📋 **Project Summary**

In summary, I created an insightful and interactive **Car Sales Analysis Dashboard** that provides a comprehensive view of the performance of the **Mercedes-Benz**, **Buick Riviera**, and **BMW i8** models. The project involved multiple stages, from **data cleaning** to **exploratory analysis** and finally creating a **Power BI dashboard** that anyone can use to understand the sales dynamics of these cars.

🔑 **Key Features:**
- Data cleaning using **Excel**.
- EDA with **Python**.
- Analysis using **SQL** queries.
- Visualizing insights with **Power BI**.

🌟 **I'm proud of the insights this project provides and the value it can offer to those interested in the automotive sales industry.**

---

💬 **Feel free to check out the code, and let me know if you have any questions or feedback!**

---
