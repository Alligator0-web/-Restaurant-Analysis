# -Restaurant-Analysis
# Restaurant Sales Analysis 🍽️

## Project Overview  
This project, developed in **Google Colab**, analyzes a restaurant's sales data stored in a **SQLite3 database**.  
The analysis uncovers insights about:  

- Most popular products by quantity and revenue  
- Time-based revenue patterns (hourly, daily, monthly, yearly)  
- Common dish combinations for potential promotions  
- Menu optimization opportunities  

---

## Table of Contents  
- Setup  
- Data Sources  
- Key Features  
- Main Findings  
- Visualizations  


---

## Setup  

### Prerequisites  
- Google Colab (or Jupyter Notebook)  
- Python 3.x  
- SQLite3 database file  

### Required Python Packages  
- `sqlite3` (standard library)  
- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  

### Run the Notebook  
Open the notebook in Colab:  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/your-username/restaurant_analysis/blob/main/Restaurant_Analysis.ipynb)  

---

## Data Sources  
The project uses a SQLite3 database (`db.sqlite3`) with three main tables:  
- **restaurant_orderitem** – order items, quantities, links to orders and products (~74k rows)  
- **restaurant_product** – product names and prices (~250 rows)  
- **restaurant_order** – order timestamps (~13k rows)  

---

## Key Features  
- **Database Exploration**: inspection of relational structure and foreign keys  
- **Sales Performance Analysis**: identifying top-performing products  
- **Temporal Analysis**: hourly, daily, monthly, and yearly revenue trends  
- **Combination Analysis**: discovering frequently paired menu items  
- **Visualizations**: charts and graphs to represent findings  

---

## Main Findings  

### Product Performance  
- Higher-priced main dishes (e.g., Chicken Tikka Masala) drive the most revenue  
- Low-cost sides (e.g., Plain Papadum) are ordered most frequently  
- Sales volume ≠ profit contribution  

### Revenue Patterns  
- Peak hours: **17:00, 18:00, 20:00** (highest at 18:00)  
- Peak days: **Friday and Saturday**; Sunday also strong  
- Seasonal trends: **May–July and December** are top months  
- Annual: steady growth until 2018, decline in 2019  

### Dish Combinations  
- Identified top 10 most frequent dish pairings  
- Avg. order size ≈ **5.6 items**  
- Opportunities for combo meal promotions  

---

## Visualizations  
The notebook includes:  
- **Pie charts** – top products by quantity & revenue  
- **Bar charts** – temporal analysis (hourly, daily, monthly, yearly)  
- **Bar charts** – common dish combinations  

---

- Pricing elasticity study for menu optimization  

