# Linear Algebra with Applications
**BIS 231 — University of Washington Bothell**

A Python-based applied linear algebra course for interdisciplinary STEM majors. Lectures and homework are Jupyter notebooks. Students build machine learning models from scratch before using scikit-learn, so they understand what the library is doing under the hood.

---

## Getting Started

**Option 1 — Local (recommended)**
1. Install [Anaconda](https://www.anaconda.com/download)
2. Clone the repo: `git clone https://github.com/ajorgen1/Linear-Algebra-With-Applications.git`
3. Open any notebook in Jupyter or VS Code

**Option 2 — Cloud**
Upload notebooks to [Anaconda Cloud](https://anaconda.com/app/) and run them in the browser with no setup.

**Dependencies:** NumPy, pandas, matplotlib, scikit-learn, gensim (Lecture 2 only). All are included in a standard Anaconda installation.

---

## Repository Structure

```
notebooks/    Lecture and homework notebooks (see table below)
datasets/     CSV files used throughout the course
```

---

## Notebooks

### Lectures

| Notebook | Topics |
|----------|--------|
| Lecture 1 — Vectors & Matrices | Vectors, matrices, NumPy arrays, `.shape`, `.T` |
| Lecture 2 — Vector Operations | Addition, scalar multiplication, dot product, norm, unit vectors, cosine similarity, word embeddings (GloVe) |
| Lecture 3 — Exploratory Data Analysis | pandas workflow, indexing, column statistics as linear algebra, standardization, centroids, scatter plots |
| Lecture 4 — k-Means from Scratch | Lloyd's algorithm implemented step by step; k-means objective function |
| Lecture 5 — k-Means with Scikit-learn | `KMeans`, `StandardScaler`, PCA for visualization, elbow plots, cross-tabulation against ground truth |
| Lecture 7 — Matrix Algebra | Matrix multiplication, rotation matrices, images as matrices, iterated maps |
| Lecture 8 — Markov Processes | SIRD epidemic model, transition matrices, absorbing states, eigenvalues and convergence |
| Lecture 9 — Least Squares | Column space, matrix rank, inverse matrices, the least squares solution |
| Lecture 10 — Regression from Scratch | Linear regression, design matrix, SSR, RMSE, geometric interpretation of least squares |
| Lecture 11 — Regression with Scikit-learn | `LinearRegression`, `.predict()`, RMSE, R-squared, `sklearn.metrics` |
| Lecture 12 — Gradient Descent | Loss functions, partial derivatives, gradient vectors; logistic regression with `lbfgs` and `liblinear` solvers |

### Homework

Each homework mirrors the corresponding lecture. Students complete exercises and write code on the same datasets before submitting answers in Canvas.

| Notebook | Key Exercises |
|----------|---------------|
| HW 1 — Vectors & Matrices | Summation notation, NumPy array creation, `.shape` |
| HW 2 — Vector Operations | Dot product predictions, projections, cosine similarity, RMSE on a real model |
| HW 3 — Exploratory Data Analysis | Palmer Penguins dataset: missing values, standardization, centroids |
| HW 4 — k-Means from Scratch | Run Lloyd's algorithm by hand for 4 iterations on an 11-point dataset with k=3 |
| HW 5 — k-Means with Scikit-learn | Full pipeline on Palmer Penguins and College datasets; elbow plot; which universities cluster with UW? |
| HW 7 — Matrix Algebra | Matrix multiplication by hand, determinants, characteristic polynomial, eigenvalues |
| HW 8 — Systems of Equations | Column space, rank, inverse matrices, left-inverse |
| HW 9 — Least Squares | Least squares on the Wine dataset; correlation matrix from scratch |
| HW 10 — Regression from Scratch | Linear regression on the Swiss fertility dataset; SSR, RMS |
| HW 11 — Regression with Scikit-learn | sklearn pipeline on Swiss dataset; R-squared; when to use `.predict()` vs matrix multiplication |
| HW 12 — Gradient Descent | Logistic regression on Titanic; comparing solvers; when sklearn uses gradient descent vs. matrix algebra |

### Capstone Project

`Project_1_Unsupervised_Learning.ipynb` — Students select a real dataset, perform EDA, standardize, choose k via elbow plot, cluster with scikit-learn, reduce to 2D with PCA, and write a substantive interpretation of results. Full instructions are in the notebook.

---

## Datasets

| File | Used In |
|------|---------|
| `iris.csv` | Lectures 3, 5, 8 |
| `penguins.csv` | HW 3, HW 5 |
| `swiss.csv` | HW 10, HW 11 |
| `college.csv` | HW 5 |
| `wine.csv` | HW 9 |

The Titanic dataset is loaded directly from a public URL in HW 12.

---

## Author

Andrew D. Jorgenson — ajorgen1@gmail.com
