# supermarket-grocery-sales-retail-analytics
Unified Mentor project

This project analyzes and predicts product sales in different stores of a retail chain using the BigMart Sales Dataset. The goal is to identify key factors that influence sales and to build a predictive model for future performance using machine learning techniques.

📁 Dataset Description
The dataset contains information on sales of various products across multiple outlets. It includes features related to products, store types, and pricing.

Key Columns:
Item_Identifier: Unique ID for products
Item_Weight: Weight of the product
Item_Fat_Content: Low Fat / Regular
Item_Visibility: How visible the product is in the store
Item_Type: Category (e.g., Dairy, Snacks, etc.)
Item_MRP: Product price
Outlet_Identifier: Store ID
Outlet_Type: Type of the outlet (e.g., Supermarket Type1, Grocery Store)
Outlet_Size: Store size (Small/Medium/Large)
Item_Outlet_Sales: Target variable (sales value)

🧹 Project Workflow
1. Data Cleaning
Missing values handled using mean/mode imputation
Standardized inconsistent category values
Corrected Item_Fat_Content categories

2. Feature Engineering
Created Outlet_Years (how long the store has been running)
Extracted product category using ID prefixes
Applied Label Encoding for categorical features

3. Exploratory Data Analysis (EDA)
Analyzed sales trends across:
Product categories
Store types and sizes
City tiers
Visualized MRP vs Sales, Outlet impact, and Item Type influence

4. Model Building
Built a Linear Regression model to predict Item_Outlet_Sales
Evaluated performance using Root Mean Squared Error (RMSE)

📊 Visualizations Included
Histogram of Item MRP
Boxplot of Sales by Item Type
Bar chart of Sales by Outlet Type
Violin plot of Sales by Location Tier

🚀 Future Improvements
Use advanced models like Random Forest, XGBoost, or LightGBM
Tune hyperparameters using GridSearchCV
Deploy as a web app using Streamlit or Flask

🧠 Key Learnings
Real-world retail data preprocessing techniques
Importance of feature engineering in predictive modeling
Visual storytelling with Seaborn and Matplotlib
Building and evaluating regression



Here’s the image output showing EDA visualizations from the Supermart Grocery Sales dataset:
📊 Top-left: Distribution of Item MRP
📦 Top-right: Sales distribution by Item Type
🏬 Bottom-left: Average Sales by Outlet Type
🌍 Bottom-right: Sales spread by Outlet Location Tier





