## Summary

This CSV file contains data about 200 customers at a mall. The dataset includes demographic and financial information, as well as a "Spending Score" for each customer. The columns are:

- **CustomerID**: Unique identifier for each customer (integer)
- **Gender**: Gender of the customer ("Male" or "Female")
- **Age**: Age of the customer (integer)
- **Annual Income (k$)**: Annual income in thousands of dollars (integer)
- **Spending Score (1-100)**: A score assigned by the mall based on customer behavior and spending (integer, 1 to 100)

## Details

### Columns & Data Types

| Column                 | Type     | Description                       |
|------------------------|----------|-----------------------------------|
| CustomerID             | Integer  | Unique customer ID                |
| Gender                 | String   | Male or Female                    |
| Age                    | Integer  | Age in years                      |
| Annual Income (k$)     | Integer  | Annual income in thousands ($000) |
| Spending Score (1-100) | Integer  | Score (1 = lowest, 100 = highest) |

### Value Ranges

- **CustomerID**: 1 to 200
- **Gender**: "Male" or "Female"
- **Age**: 18 to 70
- **Annual Income (k$)**: 15 to 137
- **Spending Score (1-100)**: 1 to 99

### Example Rows

| CustomerID | Gender | Age | Annual Income (k$) | Spending Score (1-100) |
|------------|--------|-----|--------------------|------------------------|
| 1          | Male   | 19  | 15                 | 39                     |
| 2          | Male   | 21  | 15                 | 81                     |
| 3          | Female | 20  | 16                 | 6                      |
| ...        | ...    | ... | ...                | ...                    |
| 200        | Male   | 30  | 137                | 83                     |

### Insights

- The dataset is commonly used for customer segmentation, clustering, and marketing analysis.
- "Spending Score" reflects how actively a customer spends at the mall.
- Age and Income are numerically distributed across a wide range.
- Both genders are represented.

### Potential Use Cases

- **Customer Segmentation**: Cluster customers based on spending habits, age, income, etc.
- **Targeted Marketing**: Identify groups for promotions based on demographic or spending patterns.
- **Data Visualization**: Plot age vs. income, income vs. spending score, etc.
