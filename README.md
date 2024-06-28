# K-Means Clustering on Iris Dataset

This project demonstrates the use of K-Means clustering on the Iris dataset. The Iris dataset is a classic dataset in machine learning, often used for testing algorithms and models. In this notebook, we apply K-Means clustering to categorize the Iris data into different clusters based on petal length and width.

## Dataset

The Iris dataset consists of 150 samples from each of three species of Iris flowers (Iris setosa, Iris virginica, and Iris versicolor). Four features were measured from each sample: the lengths and the widths of the sepals and petals.

## Project Overview

1. **Data Loading and Preprocessing**
    - Load the Iris dataset
    - Normalize the data using MinMaxScaler
    - Remove unnecessary columns for clustering

2. **K-Means Clustering**
    - Apply K-Means clustering algorithm
    - Predict the cluster for each sample
    - Visualize the clusters

3. **Visualization**
    - Scatter plot of the clusters based on petal length and width
    - Elbow plot to determine the optimal number of clusters

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required libraries: `pandas`, `scikit-learn`, `matplotlib`

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/sarvesh-2109/K-means-Clustering
   ```
2. Install the required packages
   ```sh
   pip install pandas scikit-learn matplotlib
   ```

## Usage

1. Open the Jupyter Notebook
   ```sh
   jupyter notebook K_means.ipynb
   ```
2. Run all cells to see the clustering results and visualizations.

## Results

- **Scatter Plot**: Visual representation of the clusters based on petal length and width.
- **Elbow Plot**: Helps in determining the optimal number of clusters by plotting the sum of squared errors (SSE) against the number of clusters.

## License

Distributed under the MIT License. See `LICENSE` for more information.
