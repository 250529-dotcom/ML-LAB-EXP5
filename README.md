# Iris Flower Clustering using K-Means

## 📌 Project Description

This project uses **K-Means Clustering**, an unsupervised machine learning algorithm, to group different species of iris flowers based on their physical characteristics.

The Iris dataset contains measurements of sepal length, sepal width, petal length, and petal width.

## 🎯 Objectives

* Load the Iris dataset.
* Select numerical features for clustering.
* Apply K-Means clustering with 3 clusters.
* Add cluster labels to the dataset.
* Visualize the clusters using a scatter plot.
* Compare the obtained clusters with the actual species.

## 📂 Dataset

**File:** `Iriss.csv`

### Features

| Feature       | Description                 |
| ------------- | --------------------------- |
| SepalLengthCm | Sepal length in centimeters |
| SepalWidthCm  | Sepal width in centimeters  |
| PetalLengthCm | Petal length in centimeters |
| PetalWidthCm  | Petal width in centimeters  |
| Species       | Actual flower species       |

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## ⚙️ Algorithm

### K-Means Clustering

K-Means is an unsupervised machine learning algorithm that divides data into groups called clusters.

In this project:

* Number of clusters (`n_clusters`) = 3
* Numerical flower measurements are used as input.
* The `Species` column is excluded during clustering.
* Cluster labels are added as a new column named `Cluster`.

## 📊 Visualization

A scatter plot is created using:

* X-axis: Petal Length
* Y-axis: Petal Width
* Different colours: Different clusters

## 📈 Evaluation

The obtained cluster labels are compared with the actual species column using a cross-tabulation and clustering accuracy.

## 🚀 How to Run

1. Clone this repository.

2. Install the required libraries:

```bash
pip install pandas matplotlib scikit-learn
```

3. Place `Iriss.csv` in the project folder.

4. Open the Jupyter Notebook.

5. Run the code cells to perform clustering and visualize the results.

## 📁 Project Structure

```text
Iris-KMeans-Clustering/
│
├── Iriss.csv
├── iris_clustering.ipynb
└── README.md
```

## 👨‍💻 Author

AK

BTech Computer Science and AI Student

## 📜 License

This project is created for educational purposes.
