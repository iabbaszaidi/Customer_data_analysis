## Project Overview
This project analyzes customer shopping behavior using a dataset of **3,900 transactions** across different product categories. The goal is to understand spending patterns, customer segments, and product preferences to support data-driven business decisions.

The project demonstrates an end-to-end data analysis workflow using **Python, SQL, and Power BI**.

---

## Dataset Information
The dataset contains **3,900 rows and 18 columns** including:

- Customer demographics (Age, Gender, Location, Subscription Status)
- Purchase information (Item Purchased, Category, Purchase Amount)
- Shopping behavior (Discount Applied, Promo Code Used, Purchase Frequency)
- Product details (Size, Color, Season)
- Customer feedback (Review Rating)
- Shipping Type

Some missing values in the **Review Rating** column were handled during data preprocessing.

---

## Tools & Technologies
- **Python** – Data cleaning and preprocessing  
- **Pandas** – Data manipulation and analysis  
- **PostgreSQL** – Business query analysis  
- **Power BI** – Data visualization and dashboard creation  

---

## Data Preparation (Python)
The dataset was first cleaned and prepared using Python:

- Loaded dataset using pandas
- Checked dataset structure and statistics
- Handled missing values in the review ratings
- Standardized column names for better readability
- Created new features such as age groups and purchase frequency
- Removed redundant columns

The cleaned dataset was then stored in a **PostgreSQL database** for further analysis.

---

## Data Analysis (SQL)
Several SQL queries were used to answer business questions:

- Revenue comparison by gender
- High-spending customers who used discounts
- Top-rated products
- Purchase amount comparison by shipping type
- Spending behavior of subscribers vs non-subscribers
- Discount dependent products
- Customer segmentation (New, Returning, Loyal)
- Top products in each category
- Relationship between repeat purchases and subscriptions
- Revenue contribution by age group

---

## Power BI Dashboard
An interactive **Power BI dashboard** was created to visualize the insights.  
The dashboard highlights:

- Revenue distribution
- Product performance
- Customer segments
- Purchase behavior patterns

This makes the insights easier to understand and useful for decision-making.

---

## Business Recommendations
Based on the analysis:

- Encourage more **subscription-based customers**
- Introduce **loyalty programs** for repeat buyers
- Review **discount strategies** to balance profit and sales
- Promote **top-rated and best-selling products**
- Focus marketing on **high-spending customer groups**

---

## Project Goal
The main goal of this project is to demonstrate how **data can be transformed into meaningful insights** using modern data analysis tools and techniques.
