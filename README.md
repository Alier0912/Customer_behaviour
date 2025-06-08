# Customer Behaviour Analysis

## Project Overview

This project analyzes e-commerce customer behaviour using the dataset [`ecommerce_customer_data.csv`](ecommerce_customer_data.csv). The analysis covers demographic profiling, behavioural segmentation, revenue impact, and customer lifetime value prediction.

---

## Data Profile

- **Source:** [`ecommerce_customer_data.csv`](ecommerce_customer_data.csv)
- **Rows:** 500 customers
- **Columns:**
  - `User_ID`: Unique identifier
  - `Gender`: Customer gender
  - `Age`: Customer age
  - `Location`: City
  - `Device_Type`: Device used (Mobile, Tablet, Desktop)
  - `Product_Browsing_Time`: Time spent browsing (minutes)
  - `Total_Pages_Viewed`: Number of pages viewed
  - `Items_Added_to_Cart`: Items added to cart
  - `Total_Purchases`: Completed purchases

---

## Key Findings

1. **Demographics**
   - Customers are mainly Millennials and Gen Z, with a balanced gender split and diverse locations.
   - Device usage is varied, with all device types represented.

2. **Behaviour by Generation**
   - Millennials and Gen Z show different browsing and purchasing patterns.
   - Gen Z tends to view fewer pages but has slightly higher purchase rates per session.

3. **Location & Revenue**
   - Certain locations contribute more to total revenue.
   - Revenue distribution is not uniform across cities.

4. **Behavioural Correlation**
   - Weak correlation between total pages viewed and purchases (Pearson r ≈ 0.01), suggesting that simply increasing page views may not directly increase purchases.

5. **Customer Segmentation**
   - Gaussian Mixture Model identified 3 distinct customer clusters with unique behavioural profiles.

6. **Customer Lifetime Value**
   - Linear regression predicts CLV based on age, browsing, and purchase behaviour.
   - Visualizations show CLV varies by generation and engagement.

---

## Recommendations

1. **Targeted Marketing**
   - Focus campaigns on high-revenue locations and the most engaged generations.
   - Personalize offers based on cluster profiles.

2. **Personalization**
   - Use behavioural clusters to tailor product recommendations and promotions.

3. **User Experience**
   - Optimize the website/app for the most popular device types in each segment.

4. **Engagement Strategies**
   - Since more page views do not guarantee more purchases, focus on improving product relevance and checkout experience.

5. **Continuous Monitoring**
   - Regularly update segmentation and CLV models as new data arrives to adapt to changing customer behaviour.

---

## Files

- [`Behaviour_analysis.ipynb`](Behaviour_analysis.ipynb): Main analysis notebook
- [`ecommerce_customer_data.csv`](ecommerce_customer_data.csv): Raw customer data

---

## How to Run

Open [`Behaviour_analysis.ipynb`](Behaviour_analysis.ipynb) in Jupyter or VS Code and run all cells to reproduce the analysis and visualizations.
