# SQL-Swiggy-Project-
End to end SQL data analytics project on food delivery data using data cleaning, star schema modeling, ETL, and business KPI analysis.

🍽️ Food Delivery Data Analytics Project (SQL)

**📌 Project Overview**
This project focuses on analyzing food delivery order data using SQL. The goal was to transform raw transactional data into a structured data warehouse and generate business insights.

**🧹 Step 1: Data Cleaning**
The raw dataset contained inconsistencies and duplicate records. I performed:

Data type validation using INFORMATION_SCHEMA

Null value checks

Blank string detection

Duplicate removal using ROW_NUMBER()

**🏗 Step 2: Data Modeling (Star Schema)**

I designed a star schema with one fact table and multiple dimension tables.

Fact Table

Fact_orders – Contains order-level transactional data

Dimension Tables

  - dim_date
  - dim_location
  - dim_restaurant
  - dim_category
  - dim_dish

🔄 Step 3: ETL Process

  - Extracted data from the raw table
  - Transformed date, location, and category attributes
  - Loaded distinct values into dimension tables
  - Linked fact and dimension tables using foreign keys

**📊 Step 4: Business Analysis (KPIs)**

Using SQL, I generated insights such as:

  - Total orders
    <img width="2018" height="384" alt="image" src="https://github.com/user-attachments/assets/f65196b8-b3b6-4020-9109-20719a0869ba" />

  - Total revenue
    <img width="2027" height="737" alt="image" src="https://github.com/user-attachments/assets/b8e732b4-ae10-47d4-933f-e6c125a054e7" />

  - Average dish price
    <img width="1991" height="448" alt="image" src="https://github.com/user-attachments/assets/29db1425-5edb-47e1-8409-f3323dcd83bb" />

  - Average rating
    <img width="2110" height="514" alt="image" src="https://github.com/user-attachments/assets/ddffd91f-8e83-4d80-b7d8-76c8c5aa4a15" />

    Time Based Trends
    
  - Monthly order trends
    <img width="1175" height="1031" alt="image" src="https://github.com/user-attachments/assets/48188784-5953-4dfc-8528-a9c6cbe21c7c" />
    <img width="901" height="1071" alt="image" src="https://github.com/user-attachments/assets/6fab4be3-484c-4729-9c43-faeb329c621b" />

  - Quarterly order trends
    <img width="665" height="868" alt="image" src="https://github.com/user-attachments/assets/826e6a2f-37fe-4fcd-848f-4f190ab36771" />

  - Yearly revenue analysis
    <img width="1354" height="887" alt="image" src="https://github.com/user-attachments/assets/a19205be-1cc5-4225-b666-e013808ce0f0" />

  - Weekday order distribution
    <img width="793" height="983" alt="image" src="https://github.com/user-attachments/assets/0de42d08-629b-4a9a-9ae4-ebd8df31fa5d" />

  - Top cities by order volume
   <img width="1113" height="1071" alt="image" src="https://github.com/user-attachments/assets/c9d3c660-2453-46bb-9095-b7962d0d1523" />

  - Revenue contribution by state
    <img width="818" height="1054" alt="image" src="https://github.com/user-attachments/assets/4f607c43-03bb-4afd-b70f-7fa67a07d094" />

  - Top 10 Restaurant by Order
    <img width="735" height="1048" alt="image" src="https://github.com/user-attachments/assets/7be03c5c-3ba2-4b1c-84d6-e6dbf53378cc" />

  - Top restaurants by revenue
    <img width="964" height="1065" alt="image" src="https://github.com/user-attachments/assets/fe586119-ab1f-4396-909a-296e9690d5f7" />

  - Most ordered dishes
    <img width="865" height="905" alt="image" src="https://github.com/user-attachments/assets/792cbbcb-87fc-46ad-adb4-0a8bb6c31a96" />
    <img width="829" height="1054" alt="image" src="https://github.com/user-attachments/assets/2629643a-b8e7-4fd8-b41b-93719fd7b957" />

  - Most Ordered Dish
      <img width="828" height="1054" alt="image" src="https://github.com/user-attachments/assets/a5743522-0492-4636-81f6-10a24d151556" />
      <img width="688" height="801" alt="image" src="https://github.com/user-attachments/assets/1d1fb57c-30c3-497b-8ebc-e87afab6b9b1" />

  - Customer Behavior
    <img width="977" height="978" alt="image" src="https://github.com/user-attachments/assets/d54d8cfc-56a5-4c65-a8c6-d18c87cbf637" />
    <img width="1056" height="1139" alt="image" src="https://github.com/user-attachments/assets/e4b26f57-9ea1-403d-b92b-49d520236abc" />

  - Spending distribution by price range
    <img width="1048" height="963" alt="image" src="https://github.com/user-attachments/assets/47e87412-862a-49ca-a37a-1123d7831cd5" />

  - Rating distribution
    <img width="689" height="739" alt="image" src="https://github.com/user-attachments/assets/ccef032a-4a0a-41aa-a98d-1ff18a749731" />

**🛠 Tools Used**
  - SQL Server
  - Data Cleaning
  - Data Modeling
  - ETL
  - Aggregations
  - Window Functions
