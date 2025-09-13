# Customer Segmentation for Insurance Premium Analysis

This project applies **unsupervised machine learning (K-Means Clustering)** to segment insurance policyholders into risk groups. The goal is to analyze **profitability and risk** of each group to support **strategic decisions** in pricing and marketing.

---

## 🚀 Project Workflow
1. Data Cleaning & Feature Engineering  
   - Created features: claims frequency, average claim cost, customer lifetime value (CLV).  
2. Clustering  
   - Used **K-Means** with optimal clusters determined by the **Elbow Method** & **Silhouette Score**.  
3. Visualization  
   - Scatter plots and bar charts to compare clusters.  
4. Insights  
   - Identified profitable vs loss-making customer segments.

---

## 📊 Sample Results

### Elbow Method
<img width="642" height="585" alt="image" src="https://github.com/user-attachments/assets/7a8f284b-47e3-4ad3-840b-bf47a3939a84" />

### Silhouette Score
<img width="623" height="587" alt="image" src="https://github.com/user-attachments/assets/20b0bf26-da61-4dbe-a55b-68ff63f05091" />

### Cluster Segmentation
<img width="722" height="567" alt="image" src="https://github.com/user-attachments/assets/f2b16cad-5ee9-4b64-88de-cfc449f7a98d" />


---

## 🔑 Insights
- **Cluster 0**: Low claims, high premiums → **Most Profitable** 💰  
- **Cluster 1**: High claims, low CLV → **High Risk** ⚠️  
- **Cluster 2**: Balanced group → **Stable**  
- **Cluster 3**: Younger customers, small premiums → **Growth Potential** 📈  

---

## 🛠 Tech Stack
- Python, Pandas, NumPy  
- scikit-learn (KMeans, StandardScaler)  
- Matplotlib, Seaborn  

---

## 📂 Project Structure
customer_segmentation_insurance/
│── data/
│ └── insurance.csv
│── notebooks/
│ └── customer_segmentation.ipynb
│── README.md
