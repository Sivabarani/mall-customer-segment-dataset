# mall-customer-segment-dataset
This dataset contains details about 200 individuals who visited a mall, including their income and spending scores.

In this dataset, we cannot determine which variable should be predicted, as there is no clear target variable.

**Understanding Supervised Learning and Unsupervised Learning**
Unsupervised learning involves finding patterns in data that does not have labeled outcomes (i.e., no dependent variable). In this case, there is no target variable that explicitly indicates what you are trying to predict (like a label for a specific category or class). Instead, the goal is to discover natural groupings or patterns from the data itself. This type of analysis is useful for tasks like customer segmentation or clustering, where the goal is to group customers based on their similarities (e.g., spending habits, age, or income).

**Dataset Description:**

1. CustomerID: A unique identifier for each customer.
2. Genre: The gender of the customer (Male/Female).
3. Age: The age of the customer.
4. Annual Income (k$): Annual income of the customer in thousands of dollars.
5. Spending Score (1-100): A score assigned by the mall based on customer behavior and spending patterns.

**Objective:**
The goal of this analysis is to cluster customers based on their spending habits and other features like age and income. The dataset is ideal for customer segmentation, where we group individuals into segments with similar characteristics.

**Understanding Data Relationships:**
There is no dependent variable in this dataset, as all the features (CustomerID, Genre, Age, Annual Income, and Spending Score) are independent variables. Since there is no clear target to predict, this makes the problem suitable for unsupervised learning, specifically clustering algorithms like K-means.

