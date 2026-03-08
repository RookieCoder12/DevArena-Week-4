# DevArena-Week-4

## Overview
This is Week 4 weekly submission for my internship at Developers Arena. In this project I analysed the sales data of Amazon for the first few months of year 2022. In the preporcessing part, I first split the Date column into year, month, date so that it is easy for us to analyze monthly trends. Then we went to remove handled null values from Amount after careful analysis. Then we analysed the monthly trends for the different categories. Finally we found out the percentage of total orders that were cancelled and its monthly trends. 

## Files
- data/
    - `Amazon Sales Report.csv` - <b>CSV file</b> that contains the data we analysed for insights and recommendation in this project.

- report/
    - `Report.md` - <b>Markdown file</b> that consists of the <b>executive summary</b>, <b>insights</b> and <b>recommendation</b> I could develop by analyzing this data.

- visualizations/
    - `cancelled_orders.png` - <b>Line chart</b> showing trend in the <b>number of orders cancelled per month</b>.
    - `category_monthly_sales.png` - <b>Line chart</b> showing trend in <b>monthly sales for different categories</b>.
    - `sales_trend_monthly.png` - <b>Line chart</b> showing trend in the <b>monthly sales on the overall platform</b>.
    - `top_10_states_orders_and_sales.png` - <b>Bar chart</b> displaying the <b>top 10 states in terms of quantity sold and revenue genrated</b>.

- `analysis.ipynb` - Main <b>Python Notebook</b> showing the <b>exploratory data analysis</b> done on the data and different visualizations picturising the insights generated from the data.

- `requirements.txt` - Consist of <b>Python libraries</b> required for this project.

- `sales_analysis.ipynb` - My Practice file also used as reference for this project and also contains the analysis of the sales data provided by Developers Arena.

## Getting Started

### Prerequisites
Ensure you have Python 3.x installed on your system.

### Cloning Repository
Cloning the repository:
```zsh
git clone https://github.com/RookieCoder12/DevArena-Week-4.git
```

### Installation
Install the required dependencies:
```zsh
pip install -r requirements.txt
```

### Running the Project

#### Running the Python Notebook
1. Run jupyter notebook:
```zsh
jupyter notebook
```
2. Open ```analysis.ipynb```

## Structure
In this project, I performed <b>Exploratory Data Analysis (EDA)</b> on Amazon e-commerce sales data to uncover trends and insights. The analysis was carried out using Python in a Jupyter Notebook environment. <br>
During the preprocessing stage, the dataset was cleaned by handling missing values and transforming the <b>Date</b> column into separate <b>year, month, and day</b> components to make time-based analysis easier.<br>
After preprocessing, the data was analyzed to identify patterns such as monthly sales trends, category-wise performance, order cancellations, and regional sales distribution. Basic visualizations were created using Matplotlib and Seaborn to represent these insights in an intuitive and easy-to-understand manner.