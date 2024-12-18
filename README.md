# Clustering Telecommunication Company Customers Using KMeans Algorithm

This project applies the **KMeans clustering algorithm** to group customers of a telecommunications company based on their behavior and characteristics. By segmenting customers into meaningful groups, the company can tailor services and marketing strategies to better meet customer needs.

---

## Dataset Description

The dataset contains information about customers, including:
- **Demographic Data**: Age, gender, marital status, income, etc.
- **Usage Statistics**: Peak minutes, off-peak minutes, SMS usage, voicemail usage, etc., across multiple months.
- **Churn Information**: Indicates whether the customer has left the company.

### **Excluded Variables**
The following variables were excluded from clustering:
1. `churn?`: Indicates whether the customer churned.
2. `Contract_date`: Date the customer signed the contract.
3. `Cust_ID`: Unique identifier for each customer.

---

## Objective

The goal of this project is to:
1. Use the KMeans algorithm to group customers into clusters based on their usage patterns and demographics.
2. Analyze the clusters to provide actionable insights for business strategies.

---

## Steps Involved

### **1. Data Preprocessing**
- Remove columns not relevant for clustering: `churn?`, `Contract_date`, `Cust_ID`.
- Handle missing values (drop or impute).
- Scale numeric features to ensure uniformity.

### **2. Clustering**
- Use the KMeans algorithm to group customers.
- Optimize the number of clusters using the **Elbow Method**.

### **3. Evaluation**
- Analyze cluster characteristics to identify patterns in customer behavior.
- Visualize the clusters using dimensionality reduction techniques like PCA or t-SNE.

---

## How to Run

### **1. Prerequisites**
- Python 3.7 or higher
- Jupyter Notebook
- Dependencies listed in `requirements.txt`

### **2. Steps**
1. Clone the repository:
   ```bash
   git clone https://github.com/shuhratkulboboev/Clustering-telecommunication-company-customer-using-K_means-algorithm.git
2. Navigate to the repository:
   ```bash
   cd Clustering-Telecommunication-Customer-KMeans
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
4. Run the Jupyter notebook:
   ```bash
   jupyter notebook notebook/clustering_kmeans.ipynb

