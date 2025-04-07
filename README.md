# Supply-Chain-Analysis

This project involves analyzing the supply chain of a fashion and beauty startup. The analysis covers various stages of the supply chain, including product pricing, sales, inventory management, manufacturing, shipping, and defect rates. It leverages Python libraries for data manipulation, visualization, and machine learning to derive insights that help optimize the supply chain for better efficiency and profitability.

Project Overview
The primary objective of this analysis is to understand the performance of a startup's supply chain by analyzing various factors, such as product pricing, sales performance, manufacturing costs, shipping logistics, defect rates, and customer demographics. This is accomplished using data visualizations, machine learning models, and statistical analysis in Python.

Technologies Used 

This project utilizes the following technologies:

Python 3.x: The main programming language used for data analysis, modeling, and visualization.
Pandas: For data manipulation and cleaning.
NumPy: For numerical computations.
Matplotlib & Seaborn: For static data visualizations.
Plotly: For interactive visualizations.
Scikit-learn: For machine learning models and preprocessing.
Jupyter Notebooks: For developing and presenting the analysis in an interactive format.

Dataset Description

The dataset consists of multiple columns with information regarding various aspects of the startup's supply chain. Key columns include:
Product type
SKU
Price  
Availability  
Number of products sold 
Revenue generated
Customer demographics
Stock levels
Lead times
Order quantitieS
Location Lead time
Production volumes
Manufacturing lead
time Manufacturing
costs
Inspection results
Defect rates
Transportation modes
Routes       
Costs 

You can download the dataset from here : https://statso.io/supply-chain-analysis-case-study/

Analysis and Visualizations
1. Product Revenue vs Price
A scatter plot displays the relationship between the price of products and the revenue generated. The products are categorized by their type (e.g., skincare, cosmetics, etc.). This plot helps identify how different price points affect revenue generation, allowing for pricing strategy optimization.

2. Sales by Product Type
A pie chart is used to visualize the percentage of total sales contributed by each product type. For instance, it breaks down how much of the total sales come from categories like skincare, haircare, and cosmetics. This helps understand which product categories are the most popular and profitable.

3. Total Revenue by Shipping Carrier
A bar chart is used to display the total revenue generated by each shipping carrier. This visualization helps businesses assess which shipping carrier is the most profitable in terms of revenue. The comparison allows for optimization of logistics and partnerships with the best-performing carriers.

4. Shipping Costs Analysis
A bar chart that compares shipping costs across various carriers is shown. This helps identify the most cost-effective shipping methods and determine if shipping costs align with revenue generation, contributing to improved logistics strategy.

5. Defect Rates by Transportation Mode
Pie charts are used to display the defect rates associated with different transportation modes (e.g., air, sea, road). These charts provide insights into which shipping methods tend to result in more defects, helping improve quality control and logistics choices.


Clustering and Regression Analysis
1. KMeans Clustering
KMeans clustering groups products into clusters based on features such as price, revenue, stock levels, and order quantities. This segmentation allows businesses to tailor strategies for different product groups.

2. Regression Analysis
Linear Regression: Predicts revenue based on features such as price, stock levels, and order quantities.

Random Forest Regressor: A more advanced model to predict revenue, with a focus on improving accuracy by handling complex relationships in the data.

3. Model Evaluation
The models are evaluated based on Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared metrics. This evaluation helps assess how well the models predict future revenue.

