# Data Mining Project - Text Mining

## Description
This project is a data mining analysis focused on **text mining** applied to Reuters articles. It includes steps for text data preprocessing, TF-IDF transformation, dimensionality reduction, and clustering techniques to identify patterns in text data.

## Project Structure
1. **Data Loading and Preprocessing**: Importing Reuters articles and cleaning the text data.
2. **Vectorization**: Transforming text into a TF-IDF weighted term matrix.
3. **Dimensionality Reduction**:
   - **PCA**: Reducing data to 3 dimensions for cluster visualization.
   - **NMF**: Non-negative Matrix Factorization to obtain feature vectors and cluster matrix.
4. **Clustering and Visualization**:
   - 3D visualization of clusters with adjustable viewing angles to examine cluster separation.
   - Cluster evaluation using metrics such as **purity score**, **entropy**, **Dunn index**, **Davies-Bouldin index**, and **Calinski-Harabasz index**.

## Installation
The following libraries are required to run the notebook:
- `numpy`
- `pandas`
- `nltk`
- `scikit-learn`
- `matplotlib`
- `seaborn`
  
Install them via `pip install -r requirements.txt` if a `requirements.txt` file is provided.

## Usage
1. **Download the Reuters Data**: Ensure you have the required data files (not included in this repository) and place them in the specified directory as shown in the code.
2. **Run the notebook cells** to reproduce the analysis and cluster visualizations.

## Results
Key findings include significant clusters within the Reuters dataset and the identification of the most frequent terms. The 3D visualization allows for observing the distribution of articles by main themes.

## Contact
For any questions, please contact [your email] or check my GitHub profile for similar projects.
