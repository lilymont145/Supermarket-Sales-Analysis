**🛒 Supermarket Sales Dataset Analysis**
**📌 Project Overview**

This project analyzes the Supermarket Sales Dataset (Kaggle) to explore customer purchasing behaviors, sales trends, and payment preferences. The main objective is to uncover insights through exploratory data analysis (EDA) and interactive dashboards in Power BI.

The workflow combines Python (Jupyter Notebook) for preprocessing and cleaning the dataset, followed by Power BI for visualization and storytelling. No predictive modeling is included; instead, the focus is on discovering key business insights.

**📂 Dataset Description**

Source: Kaggle – Supermarket Sales Dataset

Records: ~1,000 transactions across three supermarket branches

Features (17 total):

Branch/Location: Branch, City

Customer Demographics: Gender, Customer Type

Transaction Details: Invoice ID, Date, Time, Product Line, Quantity, Unit Price, Total, Tax, COGS

Payment: Payment Method

Other Attributes: Rating, Gross Margin %, Gross Income

**🔍 Analysis Questions**

1.How are sales distributed across different product lines?

2.Which city shows the highest sales performance, and how do sales compare across cities?

3.Which payment method is used the most in Naypyitaw, and which product line uses this payment method the most in Naypyitaw?

4.How is the distribution of product lines across cities?
What can we learn from customer ratings in relation to sales performance?

5.What can you say about customer buying habits for different product lines based on gender in each city?

**📊 Key Findings (EDA & Visualization)**

The analysis revealed several important insights into supermarket sales performance. Sales across product lines were relatively balanced, though **Food and Beverages** stood out as the top performer with over **56K in sales**, while **Health and Beauty** recorded the lowest at **49K**.

When comparing sales across cities, the contribution was fairly even, with each city accounting for around **30% of total sales**. However, **Naypyitaw led with the highest share (34.24%)**, followed by Mandalay and Yangon with slightly lower contributions.

Looking deeper into consumer behavior in **Naypyitaw, cash emerged as the most widely used payment method**. Customers there primarily used cash to purchase **Food and Beverages (11K)**, followed closely by **Electronic Accessories (10K)**.

Product line performance also varied by city. **Naypyitaw recorded the strongest sales in Health and Beauty (24K) and Fashion Accessories (22K)**, while **Yangon excelled in Sports and Travel (22K) and Home and Lifestyle (19K)**. In contrast, **Mandalay showed more balanced performance, with Home and Lifestyle (20K) and Sports and Travel (20K) leading the way**. These differences highlight distinct consumer preferences across regions.

Gender-based analysis revealed further insights. Across most product lines and cities, **female customers tended to spend more**, particularly in lifestyle and travel-related categories. For example, females dominated **Sports and Travel (12.1K) and Food and Beverages (10.5K)** in Mandalay, as well as **Home and Lifestyle (14.3K) and Sports and Travel (11.9K)** in Yangon. Meanwhile, males showed stronger preferences in **Health and Beauty** and certain food categories, such as **10K in Health and Beauty in Naypyitaw**. Overall, while both genders contributed meaningfully, spending habits reflected notable differences by city and category.

**🛠️ Tech Stack**

Python (Jupyter Notebook): pandas, numpy → preprocessing & cleaning

Power BI: interactive dashboards & visual storytelling