# Customer Segmentation using K-Means Clustering

## Description

The objective of this project is to perform customer segmentation using unsupervised machine learning techniques. The K-Means clustering algorithm is applied to group customers based on similarities in their features (x1 and x2). This helps in identifying distinct customer segments for analysis.

---

## Dataset

* **Source:** Clustering_Class.xlsx
* **Description of Data:**
  The dataset contains 8 customer records labeled A1 to A8. Each customer has two numerical features:

  * x1
  * x2

  These features represent measurable characteristics used to group similar customers together.

---

## Steps Performed

### 1. Data Cleaning

* Extracted relevant rows from the Excel file
* Renamed columns for clarity (CustomerID, x1, x2)
* Converted feature values to numeric format
* Checked and confirmed no missing values

---

### 2. Exploratory Data Analysis (EDA)

* Generated descriptive statistics (mean, min, max, etc.)
* Visualized customer distribution using scatter plots
* Analyzed feature distribution across customers

---

### 3. Visualization

* Scatter plot of customer data points
* Cluster visualization with centroids
* Elbow method graph for optimal K
* Silhouette score analysis
* Dendrogram for hierarchical clustering

---

### 4. Model Building

* Applied **StandardScaler** for feature normalization

* Used **K-Means Clustering** to segment customers

* Determined optimal clusters using:

  * Elbow Method
  * Silhouette Score

* Also applied **Hierarchical Clustering** for comparison

---

## Results

### Key Findings:

* Customers were grouped into 3 distinct clusters
* Each cluster represents a group with similar feature values
* K-Means and Hierarchical clustering produced similar results

### Metrics:

* Silhouette Score ≈ 0.56
* Indicates a reasonable cluster structure

---

## Tools Used

* Python
* Libraries:

  * pandas
  * numpy
  * matplotlib
  * seaborn
  * scikit-learn
  * scipy

---

## Conclusion

This project demonstrates how clustering techniques can be used to segment customers based on their characteristics. K-Means clustering effectively identified meaningful groups, which can be useful for targeted decision-making and analysis.

---

## Author

YS Ragul
