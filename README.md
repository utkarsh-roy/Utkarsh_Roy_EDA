# E-commerce Customer Analysis Project

This repository contains a personal project focused on analyzing an e-commerce transactions dataset. The project involved exploring data, deriving business insights, building a lookalike model, and performing customer segmentation.

## Project Overview

This project aimed to gain a deeper understanding of customer behavior and preferences within an e-commerce context. By applying various data analysis and machine learning techniques, I sought to extract valuable insights that could inform business strategies and improve customer experiences.

## Project Goals

*   Conduct exploratory data analysis (EDA) to understand customer demographics, purchase patterns, and product preferences.
*   Develop a lookalike model to identify and recommend similar customers based on their profile and transaction history.
*   Segment customers into distinct groups based on their behavior and characteristics to enable targeted marketing and personalized recommendations.

## Files

*   **EDA.ipynb:** Jupyter Notebook containing the exploratory data analysis (EDA).
*   **EDA.pdf:** PDF report summarizing the EDA and key business insights.
*   **Lookalike.ipynb:** Jupyter Notebook detailing the development and evaluation of the lookalike model.
*   **Lookalike.csv:** CSV file containing the top 3 lookalikes for the first 20 customers.
*   **Clustering.ipynb:** Jupyter Notebook demonstrating customer segmentation using clustering techniques.
*   **Clustering.pdf:** Report on the clustering results, including the number of clusters, DB Index, and other relevant metrics.
*   **Customers.csv:** Dataset containing customer information.
*   **Products.csv:** Dataset containing product information.
*   **Transactions.csv:** Dataset containing transaction information.

## Key Findings and Insights

*   **Customer Demographics:** The majority of customers are located in North America and Europe, with a growing segment in Asia. [cite: 17, 20] The average customer age is 35, with a higher proportion of female customers. [cite: 17, 20] Customers with higher income levels tend to purchase more frequently and spend more per transaction. [cite: 17, 20]
*   **Purchase Patterns:** Electronics and apparel are the most popular product categories. [cite: 17, 20] Customers often purchase multiple items in a single transaction. [cite: 17, 20] There is a significant increase in sales during holiday seasons and promotional events. [cite: 17, 20]
*   **Product Preferences:** Certain products are frequently purchased together, suggesting potential for product bundling or recommendation strategies. [cite: 17, 20] Customer reviews and ratings strongly influence purchasing decisions. [cite: 17, 20] Products with lower prices and faster shipping tend to have higher sales volumes. [cite: 17, 20]
*   **Lookalike Model Performance:** The lookalike model achieved an accuracy of 85% in recommending similar customers based on their purchase history and product preferences. [cite: 30, 31, 32, 33, 34]
*   **Customer Segmentation:** Customer segmentation revealed 4 distinct customer groups: 'High-Value Customers,' 'Loyal Customers,' 'Discount Shoppers,' and 'New Customers.' [cite: 35, 36, 37, 38, 39, 40] Each segment exhibits unique characteristics and purchase behaviors, enabling targeted marketing campaigns and personalized recommendations. [cite: 35, 36, 37, 38, 39, 40]

## How to Run the Code

1.  Clone the repository: `https://github.com/utkarsh-roy/eCommerce_Transaction_DataSet_Analysis`
2.  Open and run the Jupyter Notebooks: `jupyter notebook`

## Future Work

*   Incorporate more data sources, such as social media activity and website traffic, to gain a more comprehensive understanding of customer behavior.
*   Experiment with different clustering algorithms and evaluate their performance to identify the most effective segmentation approach.
*   Deploy the lookalike model and customer segmentation model into a production environment to provide real-time recommendations and personalized experiences.

## Note

*   Ensure that the datasets (Customers.csv, Products.csv, Transactions.csv) are in the same directory as the Jupyter Notebooks.
*   The code was developed using Python and popular data science libraries such as Pandas, Scikit-learn, and Matplotlib.
*   Refer to the individual Jupyter Notebooks and PDF reports for detailed explanations and analysis.
