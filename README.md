\# Olist Brazilian E-Commerce Data Analysis



\## 📌 Project Overview



This project analyzes the Olist Brazilian E-Commerce dataset to understand customer behavior, revenue trends, and operational performance. Using SQL and Python, the analysis examines key metrics such as monthly revenue, customer retention, repeat purchase cycle, and delivery performance. The goal is to identify insights that can help improve customer experience, retention, and overall marketplace growth.



------------------------------------------------------------------------



\## 🎯 Business Objectives



* How does monthly revenue trend over time?
* What is the customer retention rate and repeat purchase cycle?
* How do late deliveries affect customer satisfaction and repeat purchases?
* What operational factors influence customer experience and retention?

------------------------------------------------------------------------



\## 🛠 Tools \& Technologies



\-   SQL (SQLite) – Querying and aggregating transactional e-commerce data

\-   Python (Pandas, NumPy, Matplotlib ,Seaborn)

\-   Jupyter Notebook – Interactive data exploration and documentation

\-   Kaggle Dataset – Olist Brazilian E-Commerce public dataset

\-   GitHub – Version control and project portfolio hosting

\-   PowerBI(Data Visualization)



------------------------------------------------------------------------



\## 📂 Project Structure

```
olist-ecommerce-analysis/
│
├── data/
│   └── raw/                # Dataset folder (CSV files downloaded from Kaggle; not included in repo)
│       └── .gitkeep
│
├── notebooks/
│   └── olist_brazilian_ecommerce_data_analysis.ipynb   # Main analysis notebook
│
├── outputs/
│   ├── figures/            # Generated charts and visualizations
│   └── tables/             # Exported analysis tables (CSV)
│
├── README.md               # Project documentation and overview
├── requirements.txt        # Python dependencies used in the project
└── .gitignore              # Files and folders excluded from version control


```





------------------------------------------------------------------------

\## 📂Folder details:



\- data/raw/\*\* – Original `.csv` files need to be saved here    

\- outputs/figures/\*\* – Saved plots such as Average revenue, monthly revenue, monthly aov, top 10 states, average review score and monthly orders

\- outputs/tables/\*\* – Summary tables such as customer retention, customer orders, customer value, late delivery retention, order status counts, repeat purchase cycle, review summary and other region summaries 



------------------------------------------------------------------------



\## 📊 Key Insights



* Revenue Growth: Total marketplace revenue shows consistent growth across the dataset period, reaching approximately ~15.4M GMV across ~96K delivered orders, indicating strong marketplace expansion.

* Customer Retention: Only ~3% of customers make repeat purchases, highlighting a heavy reliance on first-time buyers and a potential opportunity to improve retention strategies.

* Repeat Purchase Cycle: Customers who return typically place their second order after an average of ~81 days, suggesting a moderate repeat purchase interval.

* Customer Value: Repeat customers generate significantly higher revenue, with an average order value of approximately ~309, compared to ~161 for one-time buyers, nearly 2× higher customer value.

* Operational Impact: Orders delivered late receive much lower review scores (~2.57) compared to on-time deliveries (~4.29), demonstrating the strong impact of delivery performance on customer satisfaction.



------------------------------------------------------------------------



\## 📈 Business Recommendations



-- Improve Customer Retention: With only ~3% repeat customers, introduce loyalty programs and targeted promotions to encourage repeat purchases.

-- Focus on Repeat Buyers: Repeat customers generate nearly 2× higher revenue, making retention strategies critical for long-term growth.

-- Enhance Delivery Performance: Reducing late deliveries can significantly improve customer satisfaction and overall marketplace experience.

------------------------------------------------------------------------


\## 🚀 How to Run



1\.  Clone this repository


2\.  git clone https://github.com/your-username/olist-ecommerce-analysis.git


3\.  Download the dataset from Kaggle:

https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce


4\.  Place the CSV files inside the following folder: data/raw/


5\.  Install required Python libraries: pip install -r requirements.txt


6\.  Open the notebook and run the analysis: jupyter notebook notebooks/olist_brazilian_ecommerce_data_analysis.ipynb


------------------------------------------------------------------------



\## 💡 Author

Lalitha Anusha Nimmagadda – Data Analyst with experience in ecommerce analytics and Python-based data projects.  

Passionate about turning data into actionable business insights and creating reproducible, end-to-end data analysis workflows.





