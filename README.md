# Mall Customers Clustering Project

This project applies K-means clustering to segment customers based on their spending and income characteristics. Using the Kaggle dataset 'Mall Customers,' the data is manipulated, visualized, and analyzed with Python libraries.

## Features and Techniques Used

1. **K-means Clustering**
   - Algorithm used to partition the dataset into meaningful clusters.

2. **Elbow Technique**
   - A method to determine the optimal number of clusters.

3. **MinMax Scaler**
   - Data normalization technique used to scale numerical features between 0 and 1.

## Dataset

The dataset `Mall_Customers.csv` contains the following columns:
- `CustomerID`: Unique identifier for customers.
- `Gender`: Customer's gender.
- `Age`: Customer's age.
- `Annual Income (k$)`: Customer's annual income in thousand dollars.
- `Spending Score (1-100)`: Score assigned to the customer based on their spending behavior and income.

## Libraries Used

- `pandas`: Data manipulation and analysis.
- `numpy`: Numerical computations.
- `matplotlib`: Data visualization.
- `seaborn`: Statistical data visualization.
- `sklearn`: Machine learning library for K-means and data preprocessing.

## Steps Implemented

1. **Loading and Exploring the Dataset**
   - Import the dataset using `pandas`.
   - Perform exploratory data analysis (EDA) to understand data distribution and relationships.

2. **Data Preprocessing**
   - Handle missing or inconsistent data (if any).
   - Scale features using `MinMaxScaler` to normalize data for clustering.

3. **Optimal Clusters Determination**
   - Use the Elbow Method to identify the best number of clusters by plotting the Within-Cluster-Sum of Squared Errors (WCSS).

4. **Applying K-means Clustering**
   - Cluster the data into groups based on annual income and spending score.
   - Assign cluster labels to each customer.

5. **Visualization**
   - Visualize clusters using scatter plots.
   - Interpret the characteristics of each cluster based on spending behavior and income.

## Results

- The dataset was successfully clustered into groups.
- Insights were derived about customer spending behavior and income patterns.

## Project Structure

```
Mall_Customers_Clustering/
├── data/
│   └── Mall_Customers.csv
├── notebooks/
│   └── mall_customers_clustering.ipynb
├── plots/
│   └── cluster_visualization.png
├── README.md
└── requirements.txt
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/mall-customers-clustering.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook to run the analysis:
   ```bash
   jupyter notebook notebooks/mall_customers_clustering.ipynb
   ```

## Dependencies

- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Acknowledgments

- Dataset from [Kaggle - Mall Customers](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python).

## Author

Sam Khair  
B.Tech Computer Science and Engineering  
Aspiring Data Scientist
