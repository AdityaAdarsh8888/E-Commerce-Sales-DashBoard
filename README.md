# E-Commerce Sales Dashboard

This project is a dynamic and interactive E-Commerce Sales Dashboard created using Power BI. It provides comprehensive insights into sales data, allowing users to explore trends, profits, and key performance metrics visually. The dashboard is designed for business intelligence purposes and is built from two Excel files: `Orders` and `Details`.

![E-Commerce Dashboard Preview](E-Commerce%20Dashboard%20using%20Power%20BI.png)

## Features

- **Key Metrics Overview**:
  - Total Amount: 438K
  - Total Quantity: 5615
  - Total Profit: 37K
  - Average Order Value (AOV): 121.0

- **Visualizations**:
  1. **Profit by Month**: A bar chart displaying monthly profits.
  2. **Sum of Amount by State**: A horizontal bar chart representing sales across different states.
  3. **Sum of Quantity by Category**: A pie chart categorizing quantities into Furniture, Electronics, and Clothing.
  4. **Sum of Amount by Customer Name**: A bar chart showing sales contributions by top customers.
  5. **Sum of Quantity by Payment Mode**: A pie chart illustrating payment modes such as EMI, COD, UPI, and more.
  6. **Sum of Profit by Sub-Category**: A bar chart detailing profits by sub-categories like Printers, Bookcases, etc.

- **Interactivity**:
  - Dynamic filtering options for exploring specific data.
  - Drill-down capabilities to analyze data by categories, months, or customers.

## Tools and Technologies

- **Power BI**: Used for data modeling, visualization, and creating the interactive dashboard.
- **Microsoft Excel**: Used for data preprocessing and storage.

## How to Use

1. Clone this repository:
   ```bash
   git clone <repository_url>
   ```

2. Open the `.pbix` file in Power BI Desktop.

3. Ensure that the `Orders` and `Details` Excel files are in the same directory as the `.pbix` file or update the file paths in Power BI to reflect the correct locations.

4. Explore the dashboard interactively by filtering, slicing, and drilling down into the data.

## Project Structure

```
E-Commerce-Dashboard/
├── Orders.xlsx          # Excel file containing order details
├── Details.xlsx         # Excel file containing additional sales details
├── E-Commerce-Dashboard.pbix  # Power BI project file
├── README.md            # Project documentation
└── E-Commerce Dashboard using Power BI.png  # Dashboard preview image
```

## Key Insights

- **Top-performing States**: Maharashtra, Madhya Pradesh, and Uttar Pradesh.
- **Category Analysis**: Clothing contributes 63% of the total quantity sold.
- **Payment Modes**: COD (Cash on Delivery) dominates with 44% of transactions.
- **Monthly Profits**: December and February are the most profitable months.

## Future Enhancements

- Incorporate real-time data updates using APIs or database connections.
- Add more detailed analyses like customer segmentation and predictive analytics.
- Enhance visuals with advanced Power BI custom visualizations.

---
