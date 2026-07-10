# Marketing Campaign Customer Segmentation & Cluster Analysis

## Business Scenario
In this project, I acted as a **Junior Data Analyst** for a Marketing Department. The company possessed two years of historical customer data but lacked an analytical framework to leverage it. 

The primary objective was to build an end-to-end data pipeline: from assessing data integrity and cleaning anomalies to identifying high-value customer segments, ultimately driving a data-driven communication and marketing strategy.

## 📊 Dataset Overview
The analysis was conducted on a **Marketing Campaign Dataset** containing demographic features and purchasing behavior across various product categories (Wines, Fruits, Meat, etc.) and channels (Web, Store, Catalog).

### Key Data Pipeline Steps:
1. **Data Audit & Cleaning:** Imputed missing values (e.g., `Income`) using median values and handled critical outliers (such as an anomalous income record of $666k and unrealistic birth years).
2. **Feature Engineering:** Created key behavioral metrics, including a composite **Total Spending** variable and family structure indicators (`Kidhome`, `Teenhome`).
3. **RFM Segmentation:** Built a traditional Recency, Frequency, and Monetary framework to evaluate baseline customer value.
4. **K-Means Clustering:** Applied Unsupervised Machine Learning to discover deep, multi-dimensional customer personas. The optimal number of clusters was determined using the **Elbow Method** and **Silhouette Score**.

##  Key Insights & Personas Identified
* **Cluster 0 (VIP / High-Value):** High income, heavy spenders on premium categories (Wines & Meat), frequent catalog and web buyers.
* **Cluster 1 (Loyal / Mid-Value):** Moderate income, consistent store and web buyers, highly responsive to milestone rewards.
* **Cluster 2 & 3 (At Risk / Low-Value):** Lower engagement, low monetary value, high concentration of households with kids/teens. Highly sensitive to urgent, discount-heavy reactivation campaigns.

## 🛠️ Marketing & Communication Strategy
Based on the clusters, I designed a tailored communication matrix:
* **VIPs:** Exclusive, appreciative, and VIP treatment (App push notifications, early access, no mass discounts).
* **Loyal:** Warm, engaging, milestone-focused rewards via standard newsletters.
* **At Risk:** Urgent, incentive-heavy win-back protocols via high-impact SMS and targeted remarketing ads.

## 💻 Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
