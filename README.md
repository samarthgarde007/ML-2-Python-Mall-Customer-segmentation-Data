# Python-Mall-Customer-Segmentation-Data
# overview:
Typically, datasets used for this analysis contain customer data collected from a shopping mall. The goal is to segment customers based on their purchasing habits, demographic characteristics, or other relevant factors.
# Dataset:
The dataset used for this project is the Mall Customer Segmentation Data from Kaggle. It contains customer details such as gender, age, annual income, and spending score.
# Columns:
CustomerID: Unique ID for each customer. Gender: Gender of the customer (Male/Female). Age: Age of the customer. Annual Income (k$): Annual income of the customer in thousands of dollars. Spending Score (1-100): Score assigned to the customer based on spending behavior. Project Objectives Understand the basic customer patterns using exploratory data analysis (EDA). Use K-Means Clustering to segment customers into different groups. Visualize the clustered customer segments for deeper insights.
# Data Preprocessing:
Load and explore the dataset. Check for any missing or incorrect data. Normalize or scale the features where necessary. Exploratory Data Analysis (EDA):

Visualize the distribution of different features (age, gender, income, spending score). Use pair plots and histograms to understand data relationships. K-Means Clustering:

Determine the optimal number of clusters using the Elbow Method. Apply K-Means clustering to segment customers. Visualize the customer clusters in 2D space. Conclusions:

Analyze the characteristics of each cluster and provide insights. Dependencies To run this project, you'll need the following Python libraries:

pandas: For data manipulation and analysis. numpy: For numerical computations. matplotlib: For data visualization. seaborn: For advanced visualizations. sklearn: For K-Means clustering and other machine learning tools. You can install the dependencies using pip:

bash Copy code pip install pandas numpy matplotlib seaborn scikit-learn

Usage Clone this repository: bash Copy code git clone https://github.com/samarthgarde007/ML-2-Python-Mall-Customer-segmentation-Data/new/main

Navigate to the project directory: bash Copy code cd mall-customer-segmentation

Run the main Python file to execute the segmentation: bash Copy code python customer_segmentation.py

Alternatively, you can open and run the Jupyter notebook file to see detailed outputs and visualizations: bash Copy code jupyter notebook Mall_Customer_Segmentation.ipynb

Project Files Mall_Customer_Segmentation.ipynb: Jupyter notebook containing the full analysis and visualizations.

customer_segmentation.py: Python script for running the K-Means clustering algorithm.

Mall_Customers.csv: The dataset used for this project.

README.md: This file. Results

After running the K-Means clustering, customers are grouped into distinct segments based on their annual income and spending score. This segmentation allows businesses to target specific customer groups more effectively.
