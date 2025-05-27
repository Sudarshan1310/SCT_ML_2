# SCT_ML_2
K-Means clustering on Mall Customers based on their purchase history
# 🛍️ Mall Customer Segmentation using K-Means Clustering

This project applies **K-Means Clustering** to group mall customers based on their **Annual Income** and **Spending Score**. The analysis helps businesses understand customer behavior for targeted marketing strategies.

---

## 📁 Dataset

- **File**: `Mall_Customers.csv`
- **Source**: Provided in the repository under `data/`
- **Attributes**:
  - `CustomerID` – Unique ID for each customer
  - `Gender` – Male/Female
  - `Age` – Age of the customer
  - `Annual Income (k$)` – Income in thousands
  - `Spending Score (1-100)` – Score assigned based on customer behavior

---

## 📊 Exploratory Data Analysis

The following visualizations are included:
- Gender distribution (`countplot`)
- Age distribution (`histplot`)
- Spending Score vs. Annual Income (`scatterplot`)
- Correlation heatmap

Visuals are saved in the `images/` folder.

---

## 🧠 Clustering Technique

- **Algorithm**: K-Means Clustering
- **Objective**: Group customers into clusters with similar behavior
- **Method**:
  - Used Annual Income and Spending Score
  - Determined the optimal number of clusters using the Elbow Method
  - Applied K-Means and visualized the results

---

## 🧪 How to Run

### 1. Clone the repository

bash git clone https://github.com/Sudarshan1310/SCT_ML_2.git
cd SCT_ML_2

### 2. Install dependencies

pip install -r requirements.txt

### 3. Run the analysis script

python src/kmeans_clustering.py

### 🗂️ Project Structure

mall-customer-segmentation/
├── data/
│   └── Mall_Customers.csv
├── src/
│   └── kmeans_clustering.py
├── images/
│   └── *.png (plots)
├── requirements.txt
├── README.md
└── .gitignore

### 📌 Future Improvements
Use PCA for dimensionality reduction

Build a web app using Streamlit

Compare K-Means with DBSCAN or Agglomerative Clustering

### 📜 License
This project is licensed under the MIT License. You’re free to use, modify, and distribute it.

### 🙌 Acknowledgements
Dataset used from a publicly available sample for educational purposes.


---

🔧 **To Use**: Copy this and paste it into the `README.md` file of your GitHub repository.

Let me know if you'd like a version with images embedded or a badge (e.g., GitHub stars, Python version, etc.).
