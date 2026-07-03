# DecodeLabs_Task3

## Project Overview

This repository contains my **Task 3: Customer Segmentation Dashboard** completed as part of the **DecodeLabs Data Science Internship**.

The project applies **Unsupervised Machine Learning** techniques to segment customers based on their purchasing behavior. It uses **Principal Component Analysis (PCA)** for dimensionality reduction and **K-Means Clustering** to identify customer groups, followed by persona profiling and visualization.

---

## Repository Structure

```text
DecodeLabs_Task3/
│
├── DecodeLabsTask3.ipynb      # Jupyter Notebook containing the complete project
└── README.md                  # Project documentation
```

---

## Dataset

* **Dataset:** Mall Customers Dataset
* **Source:** https://raw.githubusercontent.com/dsrscientist/dataset1/master/mall_customers.csv
* **Fallback:** If the dataset cannot be downloaded, the notebook automatically generates a sample dataset for demonstration purposes.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## Features

* Automatic dataset loading
* Data preprocessing and cleaning
* Feature scaling
* Principal Component Analysis (PCA)
* Customer segmentation using K-Means Clustering
* Optimal cluster evaluation using Silhouette Score
* Customer persona profiling
* Visual dashboard for cluster analysis

---

## Project Workflow

### 1. Data Loading

* Loads the Mall Customers dataset.
* Generates a sample dataset if the download fails.

### 2. Data Preprocessing

* Handles missing values (if any).
* Selects relevant numerical features.
* Standardizes the data using **StandardScaler**.

### 3. Dimensionality Reduction

* Applies **Principal Component Analysis (PCA)**.
* Retains approximately **95% of the dataset variance** while reducing dimensionality.

### 4. Customer Segmentation

* Uses the **K-Means Clustering** algorithm.
* Evaluates clustering performance using the **Silhouette Score**.

### 5. Customer Profiling

* Groups customers into meaningful segments.
* Summarizes the characteristics of each customer cluster.

### 6. Visualization Dashboard

* Displays cluster distribution.
* Visualizes customers in PCA space.
* Helps interpret customer behavior and segmentation results.

---

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/MahnoorDataScientist/DecodeLabs_Task3.git
```

### 2. Open the project folder

```bash
cd DecodeLabs_Task3
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib scikit-learn
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open and run

```text
DecodeLabsTask3.ipynb
```

---

## Output

Running the notebook generates:

* Preprocessed customer dataset
* PCA-transformed features
* Customer clusters
* Silhouette Score evaluation
* Customer persona profiles
* Interactive visualizations for customer segmentation

---

## Learning Outcomes

Through this project, I learned how to:

* Perform customer segmentation using unsupervised learning
* Apply feature scaling before clustering
* Reduce dimensionality using PCA
* Build clustering models with K-Means
* Evaluate clustering quality using the Silhouette Score
* Interpret customer segments through visualization and profiling

---

## Author

**Mahnoor Ramzan**

**GitHub:** https://github.com/MahnoorDataScientist

---

## If you found this project helpful, consider giving it a star on GitHub!
