# 🌸 Iris Flower Classification - CodSoft Internship (Task 3)

This project is submitted as part of the **CodSoft Data Science Internship**.

## 📌 Problem Statement

The Iris flower dataset consists of three species: **Setosa**, **Versicolor**, and **Virginica**.  
Each flower is described by four features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The goal is to build a machine learning model that can accurately **classify** a flower into its respective species based on these measurements.

---

## 📂 Dataset Used

- Source: [Kaggle – arshid/iris-flower-dataset](https://www.kaggle.com/datasets/arshid/iris-flower-dataset)
- Filename: `IRIS.csv`
- Total Rows: 150
- Features: 4 numerical inputs, 1 categorical target (`species`)

---

## 🧠 Algorithms Used

1. **Logistic Regression**
2. **Random Forest Classifier**

Both models were trained and tested using an **80-20 train-test split**.

---

## ⚙️ Steps Followed

1. Loaded dataset and dropped missing values
2. Encoded the categorical target labels
3. Scaled the features using StandardScaler
4. Split data into training and testing sets
5. Trained two ML models
6. Evaluated using Accuracy Score and Confusion Matrix
7. Visualized results using Seaborn heatmaps

---

## ✅ Results

| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | ✅ ~100% |
| Random Forest       | ✅ ~100% |

*Note: Due to the simplicity of the dataset, both models performed with very high accuracy.*

---

## 📊 Visualization

Confusion matrices were plotted using heatmaps to visualize prediction performance for both models.

---

## 📦 How to Run

1. Clone the repo or download the ZIP.
2. Open `iris_flower_classification` in Jupyter Notebook.
3. Run all cells step-by-step.
4. (Optional) Load the saved model.

## 🔖 Tags

#codsoft #datascience #internship #machinelearning
