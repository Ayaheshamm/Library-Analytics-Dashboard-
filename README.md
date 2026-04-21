# Library Analytics Dashboard 📚

A comprehensive Power BI analysis of library circulation and financial performance, focusing on revenue generation, genre popularity, and book lifecycle metrics.

## 📊 Project Overview
This project transforms raw library data into actionable business intelligence. The dashboard provides a high-level overview of total revenue, borrowing trends, and collection quality to help stakeholders optimize procurement and inventory strategies.

## 🗝️ Key Insights
* **Financial Scale**: Generated a total revenue of **$5M** with an average book price of **$21.62**.
* **Borrowing Volume**: Successfully tracked **232K** total copies borrowed across the entire collection.
* **Genre Performance**: **Philosophy** is the most profitable and popular genre, accounting for **14.63% ($737K)** of total revenue.
* **Customer Satisfaction**: Maintained a high average user rating of **4.02/5.0**.
* **Top Asset**: "Creative Writing Vol. 5" identified as the highest-performing title with **900** copies borrowed.

## 🛠️ Technical Features
* **Data Transformation**: Imported and cleaned `Library_Books.xlsx` dataset.
* **Custom Calculations**: 
  * Developed a **Revenue** column (Copies Borrowed × Price).
  * Created a **Book Age Category** to segment the collection into "New" and "Old" based on publishing year.
* **DAX Measures**: Created robust measures for `TotalRevenue`, `TotalCopiesBorrowed`, `AvgRating`, and `AvgPrice`.
* **Interactive Visuals**: 
  * **Donut Charts**: Genre distribution by revenue and volume.
  * **Bar Charts**: Top 10 books by copies borrowed and revenue.
  * **KPI Cards**: Real-time tracking of core library metrics.

## 📂 Repository Structure
* `Library_Books_Analysis.pbix`: The final Power BI Desktop file.
* `Data/`: Folder containing the raw Excel data source.
* `Screenshots/`: High-resolution images of the dashboard.

## 🚀 How to Use
1. Download the `.pbix` file.
2. Open it using Power BI Desktop.
