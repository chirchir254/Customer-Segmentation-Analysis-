# Customer Segmentation Analysis 

### 1. Project overview 
This report summarizes the process and findings of a customer segmentation analysis performed using a dataset from an e-commerce platform. The analysis employs the RFM (Recency, Frequency, Monetary) model to categorize customers into distinct segments based on their purchasing behavior.

### 2. Data Sources
The project utilizes an e-commerce dataset from Kaggle, containing customer purchase history, demographics, and behavioral data, providing a comprehensive foundation for effective customer segmentation analysis.

### 3. Tools
- python
  
### 4. Load Data & Exploratory Data Analysis (EDA)
The initial steps involved loading the dataset and performing basic exploratory data analysis (EDA) to understand its structure and identify any missing values.

### 5. Data Preprocessing
Data preprocessing steps included handling missing values, converting date columns to datetime format, and calculating RFM scores for each customer.

### 6. Customer Segmentation using K-Means Clustering
The processed data was then used to perform K-Means clustering to segment the customers.

### 7. Visualizing the Segments
The segmented data was visualized to understand the characteristics of each customer cluster.

![download](https://github.com/user-attachments/assets/64890a79-3a72-4e9f-a348-1b2a53808c34)

![download](https://github.com/user-attachments/assets/380dec3c-b611-4330-8730-f2d473ef7b44)

![download](https://github.com/user-attachments/assets/3194ebd2-0344-4aea-a195-738618da22bd)

### 8. Summary

- Cluster 0: Customers with low recency, frequency, and monetary value scores. These are occasional buyers likely to visit the platform only when they have a specific need.
- Cluster 1: Customers who make purchases often and have visited recently but have a low monetary value. These are frequent visitors who make small or few purchases each time.
- Cluster 2: High-frequency customers with high monetary value, indicating they spend a lot when shopping. This cluster likely includes bulk purchasers or those responsive to promotions.
- Cluster 3: New users with potential for long-term engagement. They have low monetary value and frequency but should be targeted with promotions to build brand loyalty.

This analysis helps in understanding the different customer segments and tailoring marketing strategies accordingly to enhance customer engagement and sales.

