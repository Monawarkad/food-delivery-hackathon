# food-delivery-hackathon

## 📌 Project Overview
This project analyzes food delivery data by integrating multiple data sources
in different formats (CSV, JSON, and SQL). The objective is to create a unified
dataset and perform data analysis to answer business and hackathon-specific
questions.

---

## 📂 Datasets Used
- **orders.csv** – Transactional order data
- **users.json** – User master data (membership, city, etc.)
- **restaurants.sql** – Restaurant master data (cuisine, rating, restaurant details)

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- SQLite
- Jupyter Notebook

---

## 🔄 Data Processing Steps
1. Loaded CSV, JSON, and SQL datasets using Pandas and SQLite.
2. Performed LEFT JOINs to merge:
   - `orders.csv` with `users.json` using `user_id`
   - Resulting dataset with `restaurants.sql` using `restaurant_id`
3. Created a final merged dataset:
   **final_food_delivery_dataset.csv**
4. Conducted exploratory and analytical queries on the final dataset.

---

## 📊 Analysis Performed
- Revenue analysis by city
- Gold vs Regular membership comparison
- Average order value analysis
- Cuisine-wise performance
- Rating-based revenue analysis
- Quarterly revenue trends

All analysis is performed using the **final merged dataset only**.

---

## 📁 Repository Structure

