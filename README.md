# **📌 Wholesale-Customer-Segmentation-and-Spending-Behavior-Analysis-By-ML**  

## **📑 Table of Contents**  
1. [Overview](#overview)  
2. [Dataset](#dataset)  
3. [Project Workflow](#project-workflow)  
   - [Data Preprocessing](#1-data-preprocessing)  
   - [Exploratory Data Analysis (EDA)](#2-exploratory-data-analysis-eda)  
   - [K-Means Clustering](#3-k-means-clustering)  
   - [Logistic Regression](#4-logistic-regression)  
4. [Project Structure](#project-structure)  
5. [Installation and Usage](#installation-and-usage)  
6. [Results & Insights](#results--insights)  
7. [Next Steps](#next-steps)  
8. [Contributions](#contributions)  
9. [License](#license)  

---

## **📌 Overview**  
This project applies **Unsupervised Learning** techniques like **K-Means Clustering** and **Dimensionality Reduction** to analyze customer purchasing behavior in the **Wholesale Customers Dataset**. Additionally, **Logistic Regression** (in a separate file) is used to classify customers based on their characteristics.  

---

## **📊 Dataset**  
The dataset is sourced from the **UCI Machine Learning Repository**:  
🔗 [Wholesale Customers Dataset](https://archive.ics.uci.edu/dataset/292/wholesale+customers)  

### **🗂️ Features:**  
- **Channel**: Type of customer (Hotel/Restaurant/Café or Retailer).  
- **Region**: Geographic region of the customer.  
- **Fresh**: Annual spending on fresh products.  
- **Milk**: Annual spending on milk products.  
- **Grocery**: Annual spending on grocery items.  
- **Frozen**: Annual spending on frozen products.  
- **Detergents_Paper**: Annual spending on detergents and paper products.  
- **Delicatessen**: Annual spending on delicatessen items.  

---

## **📌 Project Workflow**  

### **1️⃣ Data Preprocessing**  
✔️ Handle missing values (if any).  
✔️ Detect and treat outliers using boxplots.  
✔️ Normalize the data for uniform scaling.  

### **2️⃣ Exploratory Data Analysis (EDA)**  
📊 Visualize the data using histograms, boxplots, and scatter plots.  
📌 Identify correlations between features.  

### **3️⃣ K-Means Clustering**  
🔹 Use the **Elbow Method** and **Silhouette Score** to determine the optimal number of clusters.  
🔹 Segment customers based on spending behavior.  
🔹 Interpret cluster characteristics and business implications.  

### **4️⃣ Logistic Regression** *(Separate File: `Logistic_Regression_Wholesale_Customers.ipynb`)*  
✔️ Use **Region or Channel** as the target variable.  
✔️ Train and evaluate a logistic regression model.  
✔️ Analyze accuracy, precision, recall, and F1-score.  

---

## **📂 Project Structure**  
```bash
📁 Wholesale-Customer-Segmentation-and-Spending-Behavior-Analysis-By-ML
│── 📁 data                  # Dataset folder  
│   ├── Wholesale customers data.csv   # Dataset file  
│── 📁 images                # Visualization images
│── 📊 Logistic_Regression_Wholesale_Customers.ipynb  # Logistic Regression Model  
│── 📊 K_Means_Clustering_Wholesale_Customers.ipynb   # K-Means Clustering Model  
│── 📄 README.md            # Project Documentation
├── 📦 requirements.txt                        # List of required Python libraries
└── 📜 LICENSE                                 # License for the repository
```

---

## **⚙️ Installation and Usage**  

### **🔹 Requirements**  
Ensure you have the following Python libraries installed:  
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### **🔹 Running the Project**  
1. **Clone the repository**  
```bash
git clone https://github.com/yourusername/Wholesale-Customer-Segmentation-and-Spending-Behavior-Analysis-By-ML
.git
cd Wholesale-Customer-Segmentation-and-Spending-Behavior-Analysis-By-ML

```
2. **Run the clustering script**  
```bash
jupyter notebook K_Means_Clustering_Wholesale_Customers.ipynb
```
3. **Run the logistic regression script**  
```bash
jupyter notebook Logistic_Regression_Wholesale_Customers.ipynb
```

---

## **📈 Results & Insights**  
📌 Identified distinct customer segments based on purchasing habits.  
📌 Businesses can use these insights for targeted marketing and inventory optimization.  
📌 Logistic regression provided a classification model to predict customer types.  

---

## **🚀 Next Steps**  
✔️ Experiment with **Hierarchical Clustering** for comparison.  
✔️ Explore **Deep Learning** models for advanced segmentation.  

---

## **🤝 Contributions**  
Feel free to **fork** this repository, **open issues**, and **submit pull requests** to improve the project!  

---

## **📜 License**  
This project is licensed under the MIT License.  

---
