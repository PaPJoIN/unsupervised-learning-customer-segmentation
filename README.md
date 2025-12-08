# Customer segmentation using K-Means Clustering
This project goal was to leverage clustering algorithms to group customers based on their purchasing behaviour and business value, thereby enabling targeted marketing, personalised offers, and improved customer experience.

## 🟩 Data
The data was provided by an E-commerce company with a global customer base spanning across 47 countries and 5 continents.
It contained 951,668 rows, each representing a product a customer ordered and contained details about the customer (location, product type, and loyalty member) and order (e.g. days to delivery, delivery date, order date, cost, quantity ordered, and profit), a total of 20 features.

## 🟩 Methodology
* Performed essential data cleaning, preprocessing and exploration.
* Conducted **feature engineering** to reduce the complexity of the data and create metrics which would help understand the nuance of the customer base, buying behaviour, preferences, and business value:
*       Customer Lifetime Value (CLV): Total revenue per customer
        Frequency: Number of orders per customer
        Average Unit Cost: Mean unit cost per customer
        Recency: Days since last purchase
        Age: Derived from date of birth
* Visualised and scaled the newly created features.
* Used the **Elbow method & Silhouette score** to select the optimal number of clusters.
* Performed **K-means & Agglomerative(Hierarchical) clustering** to cross-check model robustness & findings.
* Utilised dimentionality reduction techniques (**PCA, tSNE**) to generate intuitive output visualisations for both approaches.
* Summarised and reported the extracted insights.

## 🟩 Tools
* Python Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* Clustering Algorithms: K-Means, Agglomerative (Hierarchical) Clustering
* Dimensionality Reduction: PCA, t-SNE

## 🟩 Results and Findings
* Identified 6 distics customer segments based on the features used:
* When compared based on frequency, recency, CLV, and average unit cost we identified the
following patterns:


- Cluster 1 clearly stands out with the highest frequency and CLV, meaning they're the most
engaged and valuable customers.

- Cluster 0 has high recency and low frequency/CLV, likely
recent one-time buyers.
- Cluster 4 seems to pay the highest average unit cost, possibly
premium buyers but not necessarily frequent while Age distribution doesn’t differ too much
across clusters, thus it is not a strong differentiator.


Based on these insights, the marketing department can better tailor customer retention
schemes, marketing efforts and benefit.
