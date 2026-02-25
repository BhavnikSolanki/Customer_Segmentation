# Assessment-1

# Customer Segmentation

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)

## 📌 Project Overview
This repository contains the code and dataset for a **Customer Segmentation** analysis (originally created for Assessment-1). The goal of this project is to group customers into distinct segments based on their purchasing behavior, demographics, or other key characteristics using unsupervised machine learning techniques. 

Customer segmentation helps businesses and marketing teams tailor their strategies, improve customer retention, and maximize revenue by understanding the distinct profiles of their customer base.

## 📂 Repository Contents
* **`project2.ipynb`**: The main Jupyter Notebook containing the end-to-end data analysis workflow. It includes data exploration, preprocessing, visualization, and the machine learning model used to segment the customers.
* **`new.csv`**: The dataset used for this analysis. It contains the raw customer records that are processed and clustered within the notebook.
* **`README.md`**: This documentation file.

## 🛠️ Technologies Used
* **Python 3.x**
* **Jupyter Notebook**
* **Pandas & NumPy** (Data manipulation and analysis)
* **Matplotlib & Seaborn** (Data visualization)
* **Scikit-Learn** (Machine Learning / Clustering algorithms)

## 🚀 Methodology
1.  **Data Loading & Cleaning**: Importing `new.csv` and handling any missing values, duplicates, or outliers.
2.  **Exploratory Data Analysis (EDA)**: Visualizing the distributions and relationships between different customer attributes to find underlying patterns.
3.  **Feature Scaling**: Standardizing the data to ensure all features contribute equally to the distance calculations in the clustering model.
4.  **Clustering / Segmentation**: Applying an unsupervised learning algorithm (such as K-Means Clustering) to partition the customers. Methods like the *Elbow Method* or *Silhouette Score* are used to determine the optimal number of clusters.
5.  **Insights & Evaluation**: Profiling each customer cluster to derive actionable business insights.

## 💻 Getting Started

### Prerequisites
To run the notebook locally, you will need Python installed along with the required libraries. You can install the dependencies using `pip`:

#### Clone this repository to your local machine:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
git clone [https://github.com/BhavnikSolanki/Customer_Segmentation.git](https://github.com/BhavnikSolanki/Customer_Segmentation.git)
```

####Navigate to the project directory:
```
cd Customer_Segmentation
```

####jupyter notebook
```
jupyter notebook
```

#### Citation
If you find the code is valuable, please use this citation.

#### **If you like this LLM Project do drop ⭐ to this repo**
#### Follow me on [![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bhavniksolanki/) &nbsp; [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/BhavnikSolanki/)
