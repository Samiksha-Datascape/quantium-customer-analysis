🛒 Customer Purchasing Behavior & Store Trial Analysis

---

🎯 Objective

To analyze customer purchasing behavior in the chips category and evaluate store trial performance to identify key drivers of sales and provide actionable business recommendations.

---

📌 Project Overview

This project analyzes transaction and customer data to understand purchasing patterns and identify high-value customer segments. It also evaluates the effectiveness of store-level trials using a control vs trial approach.

📌 Project Context  
This project is based on a retail analytics case study from the Quantium Virtual Internship. The entire analysis, data processing, and visualizations were implemented independently using Python.

---

🧩 Problem Statement

- Identify key customer segments contributing to sales  
- Understand purchasing behavior and trends  
- Evaluate store trial performance  
- Provide actionable business recommendations  

---

📂 Dataset Description

🧾 Transaction Data
- Date  
- Store number  
- Customer ID  
- Product details  
- Quantity  
- Total sales  

👤 Customer Data
- Customer ID  
- Lifestage  
- Premium customer category  

---

⚙️ Data Preprocessing

- Converted date column into datetime format  
- Checked for missing values and duplicates  
- Extracted pack size from product names  
- Extracted brand name from product names  
- Merged transaction and customer datasets  

---

🧠 Feature Engineering

- Created pack size column  
- Created brand column  

Derived key metrics:
- Total sales  
- Average spend per customer  
- Average quantity per customer  

---

📊 Analysis Performed

- Sales by customer segment  
- Average spend per segment  
- Quantity purchased per segment  
- Pack size contribution  
- Brand-level performance  
- Trial vs control store comparison  

---

🔍 Key Insights

- Older Families and Young Families contribute the highest sales  
- These segments spend more and purchase higher quantities  
- Sales are driven by bulk purchasing behavior  
- Larger pack sizes (175g, 150g) dominate sales  
- Top brands: Kettle, Smiths, Doritos  

---

📊 Trial Store Analysis

- Store 77 → Higher sales vs control (increase driven by higher spend per transaction)  
- Store 86 → Lower sales despite more customers (reduced spend per purchase)  
- Store 88 → Higher sales, customers, and transactions (strong trial success)  

---

📈 Visualizations

### Sales by Customer Segment
![Sales](images/sales_by_segment.png)

### Pack Size Contribution
![Pack Size](images/pack_size.png)

### Store 77 vs Control Store 41
![Store 77](images/store77_vs_41.png)

### Store 88 vs Control Store 201
![Store 88](images/store88_vs_201.png)

---

💡 Business Recommendations

- Target family segments with promotions and offers  
- Focus on larger pack sizes to increase revenue  
- Replicate successful strategies from Store 88  
- Improve pricing/product strategy in Store 86  

---

🗂️ Project Structure

quantium-retail-analysis/  
│  
├── data/  
├── notebooks/  
├── images/  
└── README.md  

---

📌 Conclusion

This project demonstrates how customer segmentation and trial analysis can be used to drive data-driven business decisions. The results highlight the importance of understanding customer behavior as well as evaluating experimental strategies before scaling them across stores.
