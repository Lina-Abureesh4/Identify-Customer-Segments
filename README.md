# 🎯 **Identify Customer Segments** - Unsupervised Learning with Demographic Data

This project leverages **unsupervised learning techniques** to segment the general population of Germany into distinct customer groups using real-world demographic data. The goal is to identify customer segments for a German mail-order company, providing insights to optimize marketing campaigns and target the most likely customers.

## 🗂️ **Project Overview**

In this project, we work with two key datasets:

- **General population demographics** (`Udacity_AZDIAS_Subset.csv`)
- **Existing customers’ demographics** (`Udacity_CUSTOMERS_Subset.csv`)

The goal is to clean, preprocess, and transform the general population data using **unsupervised learning methods**, particularly **K-Means Clustering** and **PCA** for dimensionality reduction. We aim to understand which demographic clusters are most likely to represent the customer base and how these insights can be applied to improve marketing efforts.

## 📊 **Datasets Used**

- `Udacity_AZDIAS_Subset.csv`: General population demographics (891,211 entries × 85 features)
- `Udacity_CUSTOMERS_Subset.csv`: Customer demographics (191,652 entries × 85 features)
- `Data_Dictionary.md`: Detailed metadata for each feature

> ⛔ *Due to privacy agreements with Arvato Bertelsmann, datasets are not publicly available.*

## 🧰 **Tools & Technologies**

- **Python 3**
- **Jupyter Notebook**
- **NumPy**, **Pandas**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**

## 🗂️ **Project Structure**

| Step                          | Description                                                                                           |
|-------------------------------|-------------------------------------------------------------------------------------------------------|
| 🔍 **Data Exploration & Cleaning**  | Investigated missing values, encoded unknowns, removed low-quality features, and handled categorical/ordinal/numerical discrepancies. |
| 🔄 **Feature Transformation**   | Applied **PCA** for dimensionality reduction, identifying key components that best explain population variance. |
| 🧠 **Clustering**               | Implemented **K-Means** to form clusters, determined optimal number using the elbow method, and analyzed the difference in cluster distribution between general population and customers. |

## 📁 **Files in This Repo**

- `📓 Identify_Customer_Segments.ipynb` – Main analysis notebook
- `🧾 Identify_Customer_Segments.html` – Rendered notebook in HTML
- `📘 Data_Dictionary.md` – Complete metadata on features

## 💭 **Reflections**

This project was a hands-on experience in handling real-world, untidy data and applying unsupervised learning methods. From cleaning massive datasets to interpreting clusters and PCA components, this task challenged my technical and analytical thinking. Understanding how data preprocessing impacts clustering results and how unsupervised learning can guide business decisions was a major takeaway.

## 🚫 **Disclaimer**

The data used in this project is **proprietary** and cannot be shared publicly. Only processed results, code, and metadata (such as the data dictionary) are available in this repository.

