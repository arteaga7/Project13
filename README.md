# Project13
This project analyzes the information of users in a gym (gender, location, group visits, age, lifetime, average additional charges, average class frequency, etc.) to train machine learning models to make some predictions and clustering.

**Objective:** To predict if users will cancel their subscription next month and to group customers with similar characteristics to design personalized strategies for each customer type.

## Overview
First, the exploratory data analysis (EDA) is performed to show the data in the non-cleaned datasets. Second, the data preprocessing is made, which consist of filling null values, dropping duplicates, verifying if data format is correct and processing the outliers. Third, to create data from the previously cleaned one. Fourth, to determine whether there is multiple collinearity in the data and any outliers that could pertur the training of the machine learning (ML) algorithms. Three different models will be built: **LogisticRegression** and **RandomForestClassifier** to predict if users will cancel their subscription next month; for clustering, **KMeans** to group customers with similar characteristics to design personalized strategies for each customer type. The performance of the first two algorithms is evaluated using the metrics 'accuracy', 'precision', 'recall' and using the 'silhouette value' for the 'K-means' algorithm.

Finally, conclusions are presented.

🛠️**Libraries used**: Pandas, Matplotlib, Seaborn, NumPy, SciPy, Scikit-learn.

The Jupyter Notebook is in scripts/project13.ipynb.

## 🚀 Installation
1. Clone this repository:
```
git clone https://github.com/arteaga7/Project13.git
```
2. Set virtual environment and install dependencies:
```
python3 -m venv env
source env/bin/activate
pip3 install -r requirements.txt
```
3. Run Jupyter Notebook in scripts/project13.ipynb.