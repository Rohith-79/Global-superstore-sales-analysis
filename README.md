# Global Superstore Sales Analysis & Demand Forecasting

---

## Project Overview

This project presents a comprehensive **sales performance analysis** and **demand forecasting** pipeline built using the Global Superstore dataset. The aim is to uncover business-critical insights, identify high-value customers and products, optimize inventory and regional strategies, and build predictive models to help a retail business make data-driven decisions.

---

## Dataset

- **Source:** Kaggle – [Global Superstore Dataset](https://www.kaggle.com/datasets/)
- **Records:** 51,290 rows, 18 columns
- **Attributes:** Order ID, Product, Category, Region, Customer, Order Date, Ship Mode, Shipping Cost, Discount, Profit, Quantity, Sales, Segment, etc.

---

## Key Business Insights

- **Top-Selling Products:** Phones, Copiers, and Chairs lead in sales and profit.
- **Profitable Customers:** A small group of customers (e.g., Tamara Chand) contributes significantly to total profit.
- **Regional Performance:** Matabeleland North and Kabarole have the lowest sales; South and Central regions have high shipping costs.
- **Profitability Drivers:** Technology segment outperforms Furniture and Office Supplies.
- **Inventory & Logistics:** Identified optimization opportunities in shipping and product mix.
- **Forecasting:** Predictive models (ARIMA, Prophet, LSTM) help anticipate demand, reducing stockouts and overstock risks.

---

## Why This Project Matters for Business

- **Enables Data-Driven Decisions:** Move from guesswork to fact-based planning for sales, marketing, and operations.
- **Optimizes Inventory & Logistics:** Forecasting demand minimizes costs and maximizes availability.
- **Improves Marketing ROI:** Focus promotions and loyalty programs on high-value customers and profitable segments.
- **Informs Regional Strategy:** Tailor actions to boost underperforming regions and manage logistics costs.
- **Increases Profitability:** Aligns product mix, pricing, and customer engagement to boost margins and growth.

---

## Methodology

1. **Data Preparation:**  
   - Loaded and cleaned data, verified no null values, converted date fields, engineered new features.

2. **Exploratory Data Analysis (EDA):**  
   - Visualized sales and profit by product, region, category, and customer.
   - Identified key drivers and bottlenecks.

3. **Predictive Modeling:**  
   - Split data by order date for time series forecasting.
   - Implemented ARIMA, Prophet, and LSTM models.
   - Evaluated results using RMSE and MAE.

4. **Business Recommendations:**  
   - Provided actionable next steps for sales, marketing, and logistics teams.

---

## How to Use This Repository

1. **Clone the Repo**
2. **Install Dependencies**
3. **Run the Analysis**
- Open `global-super-store-sales-analysis.ipynb` in Jupyter Notebook and execute all cells.

4. **View Presentations/Reports**
- PDF summary: `global-super-store-sales-analysis.pdf`

---


## Future Work

- Deep-dive customer segmentation and clustering
- Real-time dashboard for ongoing monitoring
- A/B testing for targeted promotions and pricing strategies
- Advanced time series models for more granular forecasting

---

## References

- [Global Superstore Dataset – Kaggle](https://www.kaggle.com/datasets/)
- McKinney, W. (2022). *Python for Data Analysis* (3rd ed.)
- Python documentation: pandas, matplotlib, seaborn, prophet

---





