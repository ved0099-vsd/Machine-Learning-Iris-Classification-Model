# Machine-Learning-Iris-Classification-Model
An end-to-end Iris species classification project using Decision Trees and case studies in Python. Features incremental model implementations, data analysis of the Iris dataset, and tree structure visualization using Scikit-Learn

# 🌸 Iris Species Classification Using Decision Trees

An end-to-end machine learning project designed to classify flower species from the classic **Iris Dataset** using **Decision Tree Classifiers**. The project tracks the evolution of the pipeline through progressive case studies, culminating in a model visualization routine.

---

## 📊 Dataset Profile
The project utilizes the **Iris dataset** (`iris.xls`), which profiles three species of the Iris flower based on four biometric features:
* Sepal Length (cm)
* Sepal Width (cm)
* Petal Length (cm)
* Petal Width (cm)

**Target Labels:** `Iris-setosa`, `Iris-versicolor`, and `Iris-virginica`.

---

## 🗂️ Repository Directory Structure

The project tracks iterative implementations across various files:
* **`iris.xls`**: The structured worksheet containing the baseline training dataset.
* **`IrisCaseStudy1` to `IrisCaseStudy5`**: Progressive iterations exploring data loading, split strategies, clean metrics profiling, and model baseline adjustments.
* **`DecisionTreeClassifier_iris.py`**: The standardized pipeline implementing a pure `DecisionTreeClassifier` model using `scikit-learn`.
* **`DecisionTreeClassifier_iris_visualize.py`**: Extends the core script to export, render, and visually map out the generated decision tree boundaries and nodes.

---

## 🛠️ Pipeline Architecture

1. **Data Preparation:** Ingests the baseline Excel layout spreadsheet and extracts relevant descriptive features from target parameters.
2. **Train-Test Stratification:** Splits dataset variants into isolated sets for model evaluation and metrics checking.
3. **Model Construction:** Fits a `DecisionTreeClassifier` logic module over the multidimensional iris feature arrays.
4. **Tree Structure Visualization:** Plots graphical branch networks to clarify rules, split thresholds, and sample distributions.

---

## 🚀 Quick Start

### Prerequisites
Make sure you have Python 3.8+ installed along with the required libraries:
```bash
pip install pandas xlrd scikit-learn matplotlib
```
*(Note: `xlrd` is required by pandas to read `.xls` files)*

### Execution
To run the main classifier script or see the visual map tree:
```bash
python DecisionTreeClassifier_iris.py
python DecisionTreeClassifier_iris_visualize.py
```

---

## 🛠️ Core Toolchain & Frameworks

* **Scikit-Learn (`sklearn`):** Powers the core machine learning logic, including `DecisionTreeClassifier` engine optimization and matrix splitting tools.
* **Pandas:** Manages tabular matrix operations, handling the structural extraction of data fields from local storage files.
* **Matplotlib:** Renders the analytical graphics and rule engine branch plots for inspection.
* **Xlrd:** Underlying backend engine facilitating the direct processing of vintage `.xls` spreadsheets within Python data frames.

---

## ✍️ Author & Contributions

* **Author:** Vedant Dhamal
* **Contributions:** Open for extensions. Feel free to submit a Pull Request (PR) or open an Issue to introduce additional classification approaches (e.g., Random Forests or Support Vector Machines) to this case study tracker.
.
