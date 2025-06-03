# Elevate_Lab_Tasks_6
INTERN AT ELEVATE LABS TASKS

# K-Nearest Neighbors (KNN) Classification

## 📌 Objective
Understand and implement the **K-Nearest Neighbors (KNN)** algorithm for classification problems using Python.

---

## 🧰 Tools & Libraries Used
- Python 3.x
- [Scikit-learn](https://scikit-learn.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- NumPy

---

## 📊 Dataset
We use the built-in **Iris dataset** from `scikit-learn`. It contains 150 samples with 4 features:
- Sepal length
- Sepal width
- Petal length
- Petal width

There are 3 classes:
- Setosa
- Versicolour
- Virginica

---

## 🔍 Steps Performed

### 1. **Load and Normalize Data**
- Loaded the Iris dataset.
- Standardized features using `StandardScaler`.

### 2. **Train-Test Split**
- Split the dataset into training (80%) and testing (20%) sets.

### 3. **Model Building**
- Used `KNeighborsClassifier` from `sklearn.neighbors`.
- Trained the model with `k=3` neighbors.

### 4. **Experimenting with K**
- Tested the model with K values from 1 to 20.
- Plotted accuracy vs K to find the optimal number of neighbors.

### 5. **Model Evaluation**
- Evaluated the model using:
  - Accuracy Score
  - Confusion Matrix

### 6. **Decision Boundary Visualization**
- Used only the first two features (sepal length & sepal width).
- Visualized the decision boundaries in 2D space using color maps.

---

## 📈 Output Examples

### 🔢 Accuracy Plot
A line plot of accuracy vs different K values to determine the best performing K.

### 🟦 Confusion Matrix
Graphical confusion matrix showing classification performance.

### 🌈 Decision Boundary
A 2D plot visualizing how the KNN model classifies different regions of feature space.

---  

## 📚 Concepts I Learn
- **Instance-Based Learning**
- **Euclidean Distance**
- **K Value Selection**
- **Feature Normalization**
- **Decision Boundary Visualization**


