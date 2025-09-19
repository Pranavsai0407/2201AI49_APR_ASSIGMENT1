# Assignment-1: Principal Component Analysis (PCA) on Iris Dataset

## Course Details
- **Course**: CS502 (Advanced Pattern Recognition)  
- **Name**: PADAMATI PRANAV SAI  
- **Roll No**: 2201AI49  

## Project Description
This assignment demonstrates the application of **Principal Component Analysis (PCA)** on the **Iris dataset**.  
The dataset contains 150 samples of three Iris species (Setosa, Versicolor, Virginica), each with 4 features:
- Sepal length
- Sepal width
- Petal length
- Petal width

PCA is applied to reduce the dataset from 4 dimensions to 2 dimensions (PC1 and PC2), allowing visualization while retaining most of the variance.

## Steps Performed
1. Import necessary Python libraries.  
2. Load the Iris dataset from scikit-learn.  
3. Standardize the data using `StandardScaler`.  
4. Apply PCA to reduce the dimensions to 2 components.  
5. Visualize the results with scatter plots.  
6. Plot explained variance to analyze how much information is retained.  

## Results
- **Explained Variance Ratio**:  
  - PC1: ~72%  
  - PC2: ~23%  
- Together, PC1 and PC2 retain ~95% of the variance.  
- The scatter plot shows clear separation of Setosa, while Versicolor and Virginica overlap slightly.  

## Files
- `pca_iris.ipynb` : Jupyter Notebook/Colab code implementation.  
- `report.tex` : LaTeX report source.  
- `report.pdf` : Final report (compiled).  
- `README.md` : This file.  

## How to Run
1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd <repo-folder>
