# Species Segmentation with Cluster Analysis (Iris Dataset)

## Project Overview
This project explores unsupervised learning on the **Iris dataset** using **K-Means clustering**. The Iris dataset contains 150 samples of iris flowers with 4 features: sepal length, sepal width, petal length, and petal width. The **Elbow Method** was applied to estimate the optimal number of clusters, and results were compared against the true species labels.

## Dataset
- **Features:** Sepal length, Sepal width, Petal length, Petal width  
- **Samples:** 150  
- **Classes:** Setosa, Versicolor, Virginica  

## Key Steps
- Data preprocessing and feature scaling  
- Implemented **K-Means clustering** with different values of K  
- Applied the **Elbow Method** to determine optimal clusters  
- Compared clustering results with true labels from the Iris dataset  
- Visualized clusters for both **sepal-based** and **petal-based** features  

## Tools and Libraries
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

## Results & Conclusion
- **Sepals alone are weak predictors** of iris species → clusters overlap heavily.  
- **Petal features give clear separation** between species.  
- The **Elbow Method suggested 2, 3, or 5 clusters**, but the true number is **3 species**.  
- **K-Means is effective when K is known in advance**, but unsupervised clustering without domain knowledge can be misleading.  
- This project highlights the **limitations of clustering** compared to classification when ground-truth labels are available.  

## Usage
1. Clone the repository:
   ```bash
   git clone <your-repo-url>
