# Customer Segmentation using K-Means Clustering

## Project Overview
This project focuses on customer segmentation using Machine Learning techniques to analyze customer purchasing behavior and identify distinct customer groups. The goal is to help businesses create targeted marketing strategies based on customer demographics, spending habits, and purchasing patterns.

The project includes:
- Data Cleaning and Exploration
- Descriptive Statistical Analysis
- Feature Engineering
- K-Means Clustering
- PCA Visualization
- Customer Segment Analysis
- Business Insights and Recommendations

---

## Objectives
- Understand customer purchasing behavior
- Perform Exploratory Data Analysis (EDA)
- Identify important customer characteristics
- Segment customers using K-Means Clustering
- Generate actionable business insights

---

## Dataset Information
The dataset contains customer demographic details, income, purchase history, campaign responses, and product spending information.

### Key Features
- Income
- Age
- Marital Status
- Product Spending
- Purchase Frequency
- Web and Store Purchases
- Campaign Responses

Dataset size:
- **Rows:** 2,205
- **Columns:** 39

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Workflow

### 1. Data Collection
Imported the customer marketing dataset for analysis.

### 2. Data Cleaning
- Checked missing values
- Removed unnecessary columns
- Handled outliers
- Verified data types

### 3. Exploratory Data Analysis (EDA)
Performed:
- Distribution analysis
- Correlation analysis
- Boxplots and histograms
- Customer spending analysis

### 4. Feature Engineering
Created new features such as:
- `Marital`
- `In_relationship`

### 5. Data Standardization
Applied `StandardScaler` to normalize features before clustering.

### 6. Principal Component Analysis (PCA)
Used PCA for dimensionality reduction and cluster visualization.

### 7. K-Means Clustering
Implemented K-Means clustering to group customers based on:
- Income
- Total Spending
- Relationship Status

### 8. Cluster Evaluation
Used:
- Elbow Method
- Silhouette Score

Optimal number of clusters identified: **4**

---

## Customer Segments Identified

### Cluster 0 – High Value Customers in Relationship
- High income
- High spending
- Married or together

### Cluster 1 – Low Value Single Customers
- Low income
- Low spending
- Mostly single

### Cluster 2 – High Value Single Customers
- High income
- High spending
- Single customers

### Cluster 3 – Low Value Customers in Relationship
- Low income
- Low spending
- Married or together

---

## Visualizations Included
- Histograms
- Boxplots
- Correlation Heatmaps
- Cluster Scatterplots
- Product Consumption Charts
- Cluster Distribution Charts

---

## Business Insights
- High-income customers spend more on premium products like wines and meat products.
- Customers with children tend to spend less overall.
- Relationship status influences purchasing behavior.
- Discount campaigns may work better for low-income customer groups.

---

## Recommendations
- Create personalized campaigns for high-value customers.
- Offer discounts and loyalty programs for low-value segments.
- Target premium products to high-income groups.
- Use relationship-based marketing strategies for family-oriented customers.

---

## Future Improvements
- Test additional clustering algorithms
- Build an interactive dashboard
- Analyze customer lifetime value
- Include gender and geographic information
- Study campaign response behavior in more detail

---

## Conclusion
This project successfully segmented customers into meaningful groups using K-Means Clustering. The analysis provides valuable insights into customer behavior and supports data-driven marketing strategies for improving customer engagement and business performance.

---

## Author
Sai Sa  
Aspiring Data Analyst | Python | Machine Learning | Data Analytics
