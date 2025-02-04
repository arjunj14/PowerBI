# E-Commerce Store Data Analysis

## Overview
This Power BI report provides a comprehensive analysis of an e-commerce store's performance. It includes key metrics, visualizations, and interactive slicers to explore sales, profit, and customer trends.

## Dataset
The dataset includes the following columns:
- **Row ID**
- **Order ID**
- **Order Date**
- **Ship Date**
- **Ship Mode**
- **Customer ID**
- **Customer Name**
- **Segment**
- **Country**
- **City**
- **State**
- **Region**
- **Product ID**
- **Category**
- **Sub-Category**
- **Product Name**
- **Sales**
- **Quantity**
- **Profit**

Additionally, a **Calendar Table** has been created to support time-based analysis.

# Superstore Dataset
This dataset is available on Kaggle: [Superstore Dataset](https://www.kaggle.com/datasets/addhyay/superstore-dataset)
or you can download it from [.xlsx file](<E-commerce store.xlsx>)


## Preview
### Dashboard Overview
![E-Commerce Store Data Analysis](Superstore.png)

## Key Performance Indicators (KPIs)
The report features several KPIs displayed using **cards**, created using DAX measures:
- **Total Sales**
- **Total Profit**
- **Total Products**
- **Total Orders**
- **Total Customers**
- **Returned Orders**
- **Quantity Sold**

A **gauge chart** is used to display the **average delivery time**, calculated using DAX.

## Interactive Slicers
Three slicers allow users to filter the data interactively:
- **Segment**: Consumer, Corporate, Home Office
- **Category**: Furniture, Office Supplies, Technology
- **Region**: Central, East, West, South

## Visualizations
### Line Chart
- Displays **Total Sales** and **Total Profit** over **Year, Quarter, and Month**.

### Stacked Bar Chart
- **Top 5 Products by Sales**
- **Sales by Sub-Category**

### Donut Chart
- Shows the distribution of the **most used Ship Mode**.

### Map
- Displays **bubble sizes based on sales** to visualize regional sales performance.

## Technologies Used
- **Power BI** for data visualization
- **DAX** for calculated measures and KPIs
- **Interactive Slicers** for dynamic filtering

## Conclusion
This report provides valuable insights into e-commerce performance, enabling stakeholders to analyze key trends in sales, profit, and customer behavior. The interactive features enhance decision-making by allowing users to explore data dynamically.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.

## License

This project is licensed under the [MIT LICENSE](LIECNSE).

## Author

arjunj - Power BI Developer & Data Analyst