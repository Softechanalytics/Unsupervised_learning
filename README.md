# 🧠 Credit Card Customer Segmentation - Clustering Project
## 📌 Project Overview
This project leverages Unsupervised Learning (Clustering) to perform customer segmentation for AllLife Bank's credit card customers. 
The goal is to identify meaningful customer segments based on their behavior and interactions with the bank. 
This segmentation will assist the Marketing and Operations teams in personalizing campaigns and improving service delivery.

## 🎯 Objective
<ul>
<li>Identify different customer segments using clustering.</li>

<li>Understand what differentiates these segments.</li>

<li>Recommend strategies for targeted marketing and operational efficiency.</li>
</ul>

## 🧰 Tools & Technologies
<ul>
<li>Python</li>

<li>Pandas, NumPy</li>

<li>Matplotlib, Seaborn</li>

<li>Scikit-learn</li>

<li>Scipy
</ul>

## 🗂️ Dataset
The dataset contains information such as:

<ul>
<li>Credit Limit</li>

<li>Total number of credit cards</li>

<li>Frequency of contact with the bank (via online, call center, in-person)</li>

<li>Spending behaviors and interaction patterns</li>
</ul>
📄 Dataset file: Credit Card Customer Data.xlsx

## 🔍 Exploratory Data Analysis (EDA)
<ul>
<li>Performed univariate and bivariate analysis</li>

<li>Handled missing values and outliers</li>

<li>Visualized distributions and relationships using histograms, boxplots, and pairplots</li>
</ul>

##  📊 Clustering Techniques

### 1. K-Means Clustering
<ul>
<li>Used Elbow Method to determine optimal number of clusters</li>

<li>Analyzed clusters using Boxplots</li>
</ul>

### 2. Hierarchical Clustering
<ul>
<li>Tried different linkage methods (ward, complete, average)</li>

<li>Visualized Dendrogram</li>

<li>Evaluated using Cophenetic Coefficient</li>
</ul>
### 3. Evaluation Metrics
<ul>
<li>Compared models using Average Silhouette Score</li>

<li>Compared cluster quality and interpretability across both techniques</li>
</ul>

## 📈 Key Findings
<ul>
<li>Customers were segmented into X distinct clusters (update based on your result)</li>

<li>Each segment showed unique characteristics in terms of spending behavior, service usage, and contact frequency</li>

<li>Hierarchical Clustering performed better/worse compared to K-Means based on the silhouette score</li>
</ul>

## 💡 Recommendations
<ul>
<li>Segment 1: High spenders with frequent online interactions → Promote premium credit cards and digital-first services</li>

<li>Segment 2: Low interaction, low credit usage → Run awareness campaigns to boost engagement</li>

<li>Segment 3: Frequent call center users → Improve call support service experience</li>
</ul>

## 📁 Project Structure
lua
Copy
Edit

## 📦 Credit-Card-Customer-Segmentation
├── Credit Card Customer Data.xlsx
├── Unsupervised Learning Project.ipynb
├── README.md
└── output/
    ├── elbow_plot.png
    ├── dendrogram.png
    └── cluster_analysis.csv
## Additional Resources
[Data Source](https://github.com/Softechanalytics/SupervisedLearning/blob/main/Bank_Personal_Loan_Modelling.csv)

[Python Source code](https://github.com/Softechanalytics/SupervisedLearning/blob/main/AIML%20Project%202%20%20Supervised%20Learning%20by%20Chukwuemeka%20Isaac%20Anyakwu.ipynb)
    
## 👨‍💻 Author
Chukwuemeka Isaac Anyakwu
Unsupervised Learning Project for Great Learning

