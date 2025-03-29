# **Turkish Retail Sales Dataset (2017-2019)**

## **📌 Context**
This dataset contains **daily sales data** from a Turkish retail company covering the period **from 2017 to the end of 2019**. The dataset has been merged from **three original CSV files** to provide a comprehensive view of **sales transactions, product hierarchy, store details, and promotional activities**.

---

## **📊 Dataset Overview**
The dataset includes **store details, product hierarchy, sales transactions, and promotions** applied over time.

### **🛒 Sales Information**
- **store_id**: Unique identifier for each store.
- **product_id**: Unique identifier for each product.
- **date**: Sales date (`YYYY-MM-DD`).
- **sales**: Quantity of products sold.
- **revenue**: Total sales revenue on that day.
- **stock**: End-of-day stock quantity.
- **price**: Sales price of the product.

### **🏬 Store & Location Details**
- **storetype_id**: The type/category of the store.
- **store_size**: The size of the store.
- **city_id**: The city where the store is located.

### **🛍️ Product Hierarchy & Dimensions**
The dataset includes **hierarchical categorization** of products along with size details.
- **hierarchy1_id** to **hierarchy5_id**: Product category hierarchy levels.
- **product_length**: Length of the product.
- **product_depth**: Depth of the product.
- **product_width**: Width of the product.

### **📢 Promotions & Discounts**
- **promo_type_1**: Type of promotion applied on channel 1.
- **promo_bin_1**: Binned promotion rate for `promo_type_1`.
- **promo_type_2**: Type of promotion applied on channel 2.
- **promo_bin_2**: Binned promotion rate for `promo_type_2`.
- **promo_discount_2**: Discount rate for the applied promotion.
- **promo_discount_type_2**: Type of discount applied.

### **📂 Training & Testing Data**
- **train_or_test**: 
  - `"train"` → Rows used to train the **KNN Regressor** model.
  - `"test"` → Rows used for **accuracy calculation**.

---

## **🎯 Learning Objectives**
By analyzing this dataset, students will:
- Explore **sales trends over time** from 2017 to 2019.
- Analyze **the impact of promotions on sales & revenue**.
- Understand how **product hierarchy & store types** affect performance.
- Gain hands-on experience in **forecasting sales using machine learning models**.

### **📌 Suggested Analysis**
- How do **different store types** perform in terms of revenue?
- What is the **impact of promotions** on sales volume?
- Can we predict **future sales trends** based on past data?
- How does **store size** affect daily sales?

---

## **📂 Dataset Usage**
Students are encouraged to:
✅ Perform **data cleaning & preprocessing** to handle missing values.  
✅ Conduct **descriptive statistics** on sales trends.  
✅ Use **data visualization** (line charts, bar plots) to explore revenue patterns.  
✅ Build **predictive models** to forecast future sales performance.  

🚀 **Let's explore retail sales and uncover valuable business insights!** 🏪📊
