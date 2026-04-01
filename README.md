# Customer Segmentation using K-Means

A Machine Learning project that performs customer segmentation using K-Means clustering on a mall customer dataset.  
The goal is to group customers based on annual income, spending score, and age to help businesses identify target groups for marketing strategies.

---

## Project Overview

This project analyzes customer data to identify distinct segments using K-Means clustering.  
It follows a complete data analysis and unsupervised ML workflow:

- Data cleaning and preprocessing  
- Feature scaling  
- Applying K-Means clustering  
- Determining optimal number of clusters using Elbow Method and Silhouette Score  
- Visualization and interpretation of customer segments  

---

## Dataset Information

**Source:** Kaggle – Mall Customer Dataset  

**Features:**  

- CustomerID  
- Gender  
- Age  
- Annual Income (k$)  
- Spending Score (1-100)  

---

## Tools & Technology Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)  
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)  
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)  
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)  
![Matplotlib](https://img.shields.io/badge/Matplotlib-007D9C?style=flat&logo=matplotlib&logoColor=white)  
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)  
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)  

---

## Methodology

1. Data cleaning and preprocessing  
2. Feature scaling  
3. Applied K-Means clustering  
4. Determined optimal number of clusters using **Elbow Method** and **Silhouette Score**  
5. Visualized clusters and analyzed customer segments  

---

## Project Folder Structure

```bash
customer-segmentation-kmeans/
├── data/
│   └── mall_customers.csv
├── notebooks/
│   └── Customer_Segmentation_KMeans.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/hassan-ali786/customer-segmentation-kmeans.git
cd customer-segmentation-kmeans
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook:

```bash
jupyter notebook notebooks/Customer_Segmentation_KMeans.ipynb
```

4. Run all cells to see clustering results and visualizations.

---

## Future Improvements

- Add more customer features for enhanced segmentation  
- Integrate with a web dashboard to display segments interactively  
- Deploy as a small web application for business users  
- Experiment with other clustering algorithms like DBSCAN or Hierarchical Clustering  

---

## Author

Hassan Ali  
Data Scientist and Machine Learning Engineer  

GitHub: https://github.com/hassan-ali786
