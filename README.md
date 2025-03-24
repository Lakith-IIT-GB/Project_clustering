# Intellihack_44Below_Task2



# Intellihack 44Below Customer Segmentation Project

## Overview
This project applies machine learning techniques to segment customers into three distinct groups: **Bargain Hunters, High Spenders, and Window Shoppers**. Using K-Means clustering with a silhouette score of 0.6279, we analyzed customer purchasing patterns, browsing behavior, and discount usage to enable targeted marketing strategies.

## Data Description
The dataset contains **999 customer records** with the following features:
- `total_purchases`: Number of purchases made
- `avg_cart_value`: Average shopping cart value
- `total_time_spent`: Time spent on the website
- `product_click`: Number of product interactions
- `discount_counts`: Number of discounts used
- `customer_id`: Unique customer identifier

## Methodology
- **Data Preprocessing:** Missing value imputation (KNN), feature scaling (StandardScaler)
- **Exploratory Data Analysis:** Feature distributions, correlation analysis, pairwise relationships
- **Clustering:** K-Means algorithm with optimal `k=3` (validated by Elbow & Silhouette methods)
- **Evaluation:** Final silhouette score of **0.6279**, confirming strong cluster separation

## Key Features
- Customer segmentation using **K-Means clustering**
- **Feature engineering** for customer behavior analysis
- **Visualization of customer groups** using PCA
- **Marketing strategy recommendations** for each customer segment

## File Structure
- `customer_behavior_analytics.csv` - Dataset for training and analysis
- `segmentation_analysis.ipynb` - Jupyter Notebook containing data processing, clustering, and visualization
- `44Below_Task2_Report.pdf` - Detailed analysis report

## Installation and Usage
### Requirements
- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

### Running the Project
1. Clone the repository:
   ```bash
   git clone <repository_url>

