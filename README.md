# FoodHub – Food Delivery Data Analysis

## Project Overview

This project explores food delivery order data from FoodHub, an online food delivery platform operating in New York. The goal is to analyze customer ordering patterns, restaurant performance, cuisine preferences, and delivery efficiency to identify meaningful business insights and provide data-driven recommendations.

Using Python and exploratory data analysis (EDA), this project examines order trends, customer ratings, food preparation times, delivery times, and estimated commission revenue.

## Business Objectives

- Understand customer ordering behavior and preferences.
- Identify the most popular restaurants and cuisines.
- Analyze order costs and customer ratings.
- Evaluate food preparation and delivery performance.
- Estimate platform commission revenue based on order values.
- Identify opportunities to improve customer experience and operational efficiency.

## Dataset Overview

The dataset contains **1,898 food delivery orders** and **9 columns**, including:

| Column | Description |
|---|---|
| order_id | Unique order identifier |
| customer_id | Unique customer identifier |
| restaurant_name | Name of the restaurant |
| cuisine_type | Type of cuisine ordered |
| cost_of_the_order | Total cost of the order |
| day_of_the_week | Weekday or weekend |
| rating | Customer rating |
| food_preparation_time | Time taken to prepare the food |
| delivery_time | Time taken to deliver the order |

The dataset includes 1,200 unique customers and 1,898 unique orders.

*Note: The dataset file is not included in this repository. Add an authorized copy to the `data/` folder before running the notebook.*

## Tools & Technologies

- **Python** – Programming and analysis
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Jupyter Notebook** – Interactive analysis

## Analysis & Key Findings

The analysis explores several aspects of FoodHub's business:

### 1. Restaurant Performance
- Shake Shack received the highest number of orders (219).
- The Meatball Shop followed with 132 orders.
- Blue Ribbon Sushi received 119 orders.

### 2. Customer Ordering Patterns
- The dataset contains 1,200 unique customers.
- American cuisine was the most frequently ordered cuisine on weekends, with 415 orders.
- Approximately 29.24% of orders had a cost greater than $20.

### 3. Food Preparation & Delivery
- Average food preparation time was approximately 27.37 minutes.
- Average delivery time across all orders was approximately 24.16 minutes.
- Average delivery time was approximately 28.34 minutes on weekdays and 22.47 minutes on weekends.

### 4. Customer Ratings
- A total of 736 orders did not have a customer rating.
- Missing ratings were retained as missing values rather than treated as actual customer scores.

### 5. Estimated Commission Revenue
Based on the commission assumptions used in the analysis:
- 25% commission on orders costing more than $20.
- 15% commission on orders costing more than $5 and up to $20.

The estimated commission revenue was **$6,166.30**.

## Business Recommendations

Based on the analysis, the following actions could help improve platform performance:

- **Restaurant partnerships:** Explore opportunities to strengthen partnerships with frequently ordered restaurants.
- **Customer experience:** Encourage customers to provide ratings and feedback after order completion.
- **Delivery optimization:** Investigate the longer average delivery times observed on weekdays.
- **Promotional campaigns:** Consider promotional opportunities for restaurants with consistently strong customer ratings.
- **Revenue strategy:** Use order-value patterns to evaluate opportunities for increasing higher-value orders and platform commission.

## Project Structure

```text
foodhub-data-analysis/
│
├── README.md
├── foodhub_data_analysis.ipynb
│
└── data/
    └── foodhub_order.csv
```

## How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/SwatiVerma20/foodhub-data-analysis.git
   ```

2. Navigate to the project folder:

   ```bash
   cd foodhub-data-analysis
   ```

3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

4. Place the dataset file `foodhub_order.csv` inside the `data/` folder.

5. Open the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

6. Open `foodhub_data_analysis.ipynb` and run the cells.

## Conclusion

This project demonstrates how exploratory data analysis can be used to understand food delivery operations, uncover customer and restaurant trends, evaluate delivery performance, and derive actionable business recommendations.

It highlights the use of Python-based data analysis and visualization to translate raw business data into meaningful insights.

---

**Author:** Swati Verma  
**GitHub:** [SwatiVerma20](https://github.com/SwatiVerma20)
